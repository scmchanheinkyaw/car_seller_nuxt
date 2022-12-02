<template>
<section class="h-100">
		<div class="container h-100">
			<div class="row justify-content-sm-center h-100">
				<div class="col-xxl-4 col-xl-5 col-lg-5 col-md-7 col-sm-9">
					<div class="card shadow-lg mt-5">
						<div class="card-body p-5">
							<h1 class="fs-4 card-title fw-bold mb-4">Register</h1>
							<form method="POST" class="needs-validation" novalidate="" autocomplete="off"  @submit.prevent="register">
                                <div class="mb-3">
									<label class="mb-2 text-muted" for="email">Name</label>
									<input id="name" v-model="name" type="name" class="form-control" name="name" value="" required autofocus>
								</div>

								<div class="mb-3">
									<label class="mb-2 text-muted" for="email">E-Mail Address</label>
									<input id="email" v-model="email" type="email" class="form-control" name="email" value="" required autofocus>
								</div>

								<div class="mb-3">
                                    <label class="mb-2 text-muted" for="email">Password</label>
									<input id="password" v-model="password" type="password" class="form-control" name="password" required>
								</div>

                                <div class="mb-3">
                                    <label class="mb-2 text-muted" for="password_confirmation">Password Confirmation</label>
									<input id="password_confirmation" v-model="passwordConfirmation" type="password" class="form-control" name="password_confirmation" required>
								</div>

								<div class="d-flex align-items-center">
									<button type="submit" class="btn btn-primary ms-auto">
										Register
									</button>
								</div>
							</form>
						</div>
						<div class="card-footer py-3 border-0">
							<div class="text-end pe-4">
								<nuxt-link to="/login" class="text-dark">Login</nuxt-link>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>

</template>

<script>
export default {
  data() {
    return {
		name : '',
		email : '',
		password : '',
		passwordConfirmation: '',
		errors: [],
    };
  },
  methods: {
    async register() {
		try{
			const userData = await fetch("http://127.0.0.1:8000/api/register",{
			method: "POST",
			body: {
				name: this.name,
				email: this.email,
				password: this.password,
				passwordConfirmation: this.passwordConfirmation,
			}
			});
		}catch(err){
			console.log(err);
		}
  	}
  },
}


</script>
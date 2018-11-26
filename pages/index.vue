<template>
  <section>
    <div class="login-dark">
      <form method="post">
        <div class="text-center">
          <img 
            src="~assets/images/zurich-logo.png"
            alt="">
        </div>
        <h2 class="title">Jahresgespräch</h2>
        <div class="form-group"><input 
          class="form-control" 
          type="email" 
          name="email" 
          placeholder="Email"></div>
        <div class="form-group"><input 
          class="form-control" 
          type="password" 
          name="password" 
          placeholder="Password"></div>
        <div class="form-group"><a 
          class="btn btn-primary btn-block" 
          type="submit" 
          href="selectuser">anmelden</a></div><a
            href="#selectuser"
            class="forgot">Passwort vergessen?</a></form>
    </div>
  </section>
</template>

<style lang="scss">
$text-light: #4066b3;

.login-dark {
	height: 100vh;
	background: #475d62 url(~assets/images/zurich_firmenmodularschutz_header.jpg);
	background-size: cover;
	position: relative;

	.title {
		text-align: center;
		margin: 30px 0;
		color: $text-light;
	}

	form {
		max-width: 320px;
		width: 90%;
		background-color: #fff;
		padding: 40px;
		border-radius: 4px;
		transform: translate(-50%, -50%);
		position: absolute;
		top: 50%;
		left: 50%;
		color: #fff;
		box-shadow: 3px 3px 4px rgba(0, 0, 0, 0.2);

		::placeholder {
			/* Chrome, Firefox, Opera, Safari 10.1+ */
			color: $text-light;
			opacity: 1; /* Firefox */
		}

		:-ms-input-placeholder {
			/* Internet Explorer 10-11 */
			color: $text-light;
		}

		::-ms-input-placeholder {
			/* Microsoft Edge */
			color: $text-light;
		}

		.form-control {
			background: none;
			border: none;
			border-bottom: 1px solid $text-light;
			border-radius: 0;
			box-shadow: none;
			outline: none;
			color: inherit;
		}

		.btn-primary {
			background: #4f90c6;
			border: none;
			border-radius: 4px;
			padding: 11px;
			box-shadow: none;
			margin-top: 26px;
			text-shadow: none;
			outline: none;
		}

		.btn-primary:hover,
		.login-dark form,
		.btn-primary:active {
			background: #4f90c6;
			outline: none;
		}

		.forgot {
			display: block;
			text-align: center;
			font-size: 12px;
			color: $text-light;
			opacity: 0.9;
			text-decoration: none;
		}

		.forgot:hover,
		.login-dark form,
		.forgot:active {
			opacity: 1;
			text-decoration: none;
		}

		.btn-primary:active {
			transform: translateY(1px);
		}
	}
}
</style>

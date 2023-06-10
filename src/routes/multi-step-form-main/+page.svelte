<div class="page-container">
	<div class="card">
		<img src="src\routes\multi-step-form-main\images\bg-sidebar-desktop.svg" alt="" />
		<div class=" input-form">
			<h1>Personal Info</h1>
			<p>Please provide your name, email address, and phone number.</p>
			<form action="">
				<label for="name">Name</label>
				<input type="text" id="name" placeholder="e.g Alex Smith" />
				<label for="email">Email</label>
				<input type="email" id="email" placeholder="e.g alexsmith@lorem.com" />
				<label for="phone">Phone Number</label>
				<input type="tel" id="phone" placeholder="e.g +1 234 567 890 " />
				<button> Next Step </button>
			</form>
		</div>
	</div>
</div>

<style lang="scss">
	// Variables
	$color-primary-marine-blue: hsl(213, 96%, 18%);
	$color-primary-purplish-blue: hsl(243, 100%, 62%);
	$color-primary-pastel-blue: hsl(228, 100%, 84%);
	$color-primary-light-blue: hsl(206, 94%, 87%);
	$color-primary-strawberry-red: hsl(354, 84%, 57%);

	$color-neutral-cool-gray: hsl(231, 11%, 63%);
	$color-neutral-light-gray: hsl(229, 24%, 87%);
	$color-neutral-magnolia: hsl(217, 100%, 97%);
	$color-neutral-alabaster: hsl(231, 100%, 99%);
	$color-neutral-white: hsl(0, 0%, 100%);

	$font-family-body: 'Ubuntu', sans-serif;
	$font-weight-body-regular: 400;
	$font-weight-body-medium: 500;
	$font-weight-body-bold: 700;

	// Layout
	$width-mobile: 375px;
	$width-desktop: 1440px;

	// Typography
	$font-size-body: 16px;

	// Global styles
	@font-face {
		font-family: 'Ubuntu';
		font-weight: $font-weight-body-regular;
		src: url('./fonts/Ubuntu-Regular.ttf');
	}

	@font-face {
		font-family: 'Ubuntu';
		font-weight: $font-weight-body-medium;
		src: url('./fonts/Ubuntu-Medium.ttf');
	}

	@font-face {
		font-family: 'Ubuntu';
		font-weight: $font-weight-body-bold;
		src: url('./fonts/Ubuntu-Bold.ttf');
	}

	.page-container {
		font-family: $font-family-body;
		font-size: $font-size-body;
		font-weight: $font-weight-body-regular;

		display: flex;
		justify-content: center;
		padding-top: 100px;

		background-color: $color-neutral-cool-gray;
		height: 100vh;
	}

	// Color classes
	.primary-marine-blue {
		color: $color-primary-marine-blue;
	}

	.primary-purplish-blue {
		color: $color-primary-purplish-blue;
	}

	.primary-pastel-blue {
		color: $color-primary-pastel-blue;
	}

	.primary-light-blue {
		color: $color-primary-light-blue;
	}

	.primary-strawberry-red {
		color: $color-primary-strawberry-red;
	}

	.neutral-cool-gray {
		color: $color-neutral-cool-gray;
	}

	.neutral-light-gray {
		color: $color-neutral-light-gray;
	}

	.neutral-magnolia {
		color: $color-neutral-magnolia;
	}

	.neutral-alabaster {
		color: $color-neutral-alabaster;
	}

	.neutral-white {
		color: $color-neutral-white;
	}

	// Media queries
	@media (max-width: $width-mobile) {
		// Styles for mobile
	}

	@media (min-width: $width-mobile) and (max-width: $width-desktop) {
		// Styles for tablet
	}

	@media (min-width: $width-desktop) {
		// Styles for desktop
	}

	h1 {
		font-size: 32px;
		font-weight: $font-weight-body-bold;
		margin: 0;
		color: $color-primary-marine-blue;
	}

	p {
		font-size: 16px;
		color: $color-neutral-light-gray;
		margin: 0;
	}

	.card {
		display: flex;
		gap: 100px;

		background-color: $color-neutral-white;
		width: fit-content;
		height: fit-content;

		// max-width: 500px;
		// max-height: 500px;

		border-radius: 10px;
		padding: 20px;
	}

	.input-form {
		display: flex;
		flex-direction: column;
		gap: 20px;
		position: relative;

		max-width: 450px;
		margin-right: 100px;

		padding-top: 20px;

		form {
			display: flex;
			flex-direction: column;
			gap: 15px;

			label {
				font-weight: 500;
				color: $color-primary-marine-blue;
			}

			input {
				border: 1px solid $color-neutral-light-gray;
				border-radius: 5px;
				padding: 10px;
			}

			button {
				color: $color-neutral-white;
				background-color: $color-primary-marine-blue;
				width: fit-content;
				padding: 10px 20px;
				border-radius: 5px;
				position: absolute;
				bottom: 0px;
				right: 0px;
			}
		}
	}
</style>

<script>
</script>

<svelte:head>
	<title>Главная</title>
	<meta name="description" content="Мое портфолио сделанное на svelte" />
	<meta name="viewport" content="width=device-width, initial-scale=1" />
	<link rel="icon" href="/favicon.png" />
	<meta property="og:type" content="website" />
	<meta name="apple-mobile-web-app-title" content="Wesleezz" />
	<meta property="og:site_name" content="Wesleezz" />
	<meta property="og:title" content="Главная" />
	<meta property="og:description" content="Мое портфолио сделанное на svelte" />
</svelte:head>

<section>
	<div class="w-screen h-screen absolute inset-0 -z-10 bg-indigo-950 bg-[linear-gradient(to_right,#8080800a_1px,transparent_1px),linear-gradient(to_bottom,#8080800a_1px,transparent_1px)] bg-[size:14px_24px]"></div>
	<div class="relative grid grid-rows-1 items-center justify-center gap-6 overflow-hidden mt-24"
	>
		<div
			class="motion-safe:animate-homeCirclesContainer children:h-[400px] children:w-[400px] children:animate-homeCircle children:rounded-full children:blur-3xl children:[grid-area:1/1] grid h-full w-full grid-rows-1 place-items-center [grid-area:1/1]"
		>
			<div
				class="motion-safe:animate-homeText relative z-30 grid place-items-center px-8 pb-24 pt-32 [grid-area:1/1] lg:pb-32 lg:pt-56"
			>
			<div class="grid place-items-center">
				<img
					src="/ava.jpg"
					alt="Wesleezz Logo"
					class="h-32 w-32 rounded-full object-cover"
				/>
				<h1
					class="font-manrope mx-auto -mb-8 -mt-8 max-w-5xl text-center text-5xl font-extrabold leading-[1.1] tracking-tighter line-through opacity-25 dark:opacity-25 md:text-6xl"
				>
					Wesleezz{' '}
				</h1>
				<h1
					class="font-manrope mx-auto max-w-5xl text-center text-5xl font-extrabold leading-[1.1] tracking-tighter md:text-6xl"
				>
					Wiz
				</h1>
				<p class="mb-3 max-w-xl text-center text-lg leading-relaxed">
					say my name
				</p>
				<div class="grid mb-8 gap-4 sm:grid-flow-col md:gap-3">
					<a
						class="bg-shine animate-shine grid select-none grid-flow-col items-center justify-center gap-2.5 rounded-full bg-cyan-600 px-6 py-3 font-medium text-white outline-cyan-700 transition [--shine-color:theme(colors.teal.500/50%)] hover:bg-cyan-700 focus-visible:outline-dashed focus-visible:outline-2 focus-visible:outline-offset-2 active:bg-cyan-800"
						aria-disabled="false"
						href="https://t.me/wesleezz"
					>
						<svg
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="h-6 w-6"
						>
							<path
								d="M2.53419 10.491 20.4342 3.72755c.5979-.22564 1.2652.07521 1.4908.67307.0791.21021.0964.43779.0482.65668l-3.0857 14.0805c-.1562.7136-.8611 1.1658-1.5747 1.0086-.1774-.0385-.3442-.1138-.4918-.2198l-6.1453-4.4415c-.3694-.2671-.4533-.784-.1852-1.1543.0289-.0395.0617-.0771.0964-.1118l6.319-6.07213c.1311-.12632.135-.33557.0087-.46768-.109-.11282-.2826-.13404-.4156-.04918L7.88597 13.0975c-.5101.324-1.13978.3973-1.7116.1996l-3.618-1.2516c-.43103-.1485-.65957-.6201-.51107-1.0511.081-.2314.25939-.4166.48889-.5034Z"
							/>
						</svg>
					</a>
					<a
						class="bg-shine animate-shine grid select-none grid-flow-col items-center justify-center gap-2.5 rounded-full bg-purple-600 px-6 py-3 font-medium text-white outline-purple-700 transition [--shine-color:theme(colors.teal.500/50%)] hover:bg-purple-700 focus-visible:outline-dashed focus-visible:outline-2 focus-visible:outline-offset-2 active:bg-purple-800"
						aria-disabled="false"
						href="https://discordapp.com/users/580079922614108185"
					>
						<svg
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="h-6 w-6"
						>
							<path
								d="M20.317 4.54101C18.7873 3.82774 17.147 3.30224 15.4319 3.00126C15.4007 2.99545 15.3695 3.00997 15.3534 3.039C15.1424 3.4203 14.9087 3.91774 14.7451 4.30873C12.9004 4.02808 11.0652 4.02808 9.25832 4.30873C9.09465 3.90905 8.85248 3.4203 8.64057 3.039C8.62448 3.01094 8.59328 2.99642 8.56205 3.00126C6.84791 3.30128 5.20756 3.82678 3.67693 4.54101C3.66368 4.54681 3.65233 4.5565 3.64479 4.56907C0.533392 9.29283 -0.31895 13.9005 0.0991801 18.451C0.101072 18.4733 0.11337 18.4946 0.130398 18.5081C2.18321 20.0401 4.17171 20.9701 6.12328 21.5866C6.15451 21.5963 6.18761 21.5847 6.20748 21.5585C6.66913 20.9179 7.08064 20.2424 7.43348 19.532C7.4543 19.4904 7.43442 19.441 7.39186 19.4246C6.73913 19.173 6.1176 18.8662 5.51973 18.5178C5.47244 18.4897 5.46865 18.421 5.51216 18.3881C5.63797 18.2923 5.76382 18.1926 5.88396 18.0919C5.90569 18.0736 5.93598 18.0697 5.96153 18.0813C9.88928 19.9036 14.1415 19.9036 18.023 18.0813C18.0485 18.0687 18.0788 18.0726 18.1015 18.091C18.2216 18.1916 18.3475 18.2923 18.4742 18.3881C18.5177 18.421 18.5149 18.4897 18.4676 18.5178C17.8697 18.8729 17.2482 19.173 16.5945 19.4236C16.552 19.4401 16.533 19.4904 16.5538 19.532C16.9143 20.2414 17.3258 20.9169 17.7789 21.5576C17.7978 21.5847 17.8319 21.5963 17.8631 21.5866C19.8241 20.9701 21.8126 20.0401 23.8654 18.5081C23.8834 18.4946 23.8948 18.4742 23.8967 18.452C24.3971 13.1911 23.0585 8.6212 20.3482 4.57004C20.3416 4.5565 20.3303 4.54681 20.317 4.54101ZM8.02002 15.6802C6.8375 15.6802 5.86313 14.577 5.86313 13.222C5.86313 11.8671 6.8186 10.7639 8.02002 10.7639C9.23087 10.7639 10.1958 11.8768 10.1769 13.222C10.1769 14.577 9.22141 15.6802 8.02002 15.6802ZM15.9947 15.6802C14.8123 15.6802 13.8379 14.577 13.8379 13.222C13.8379 11.8671 14.7933 10.7639 15.9947 10.7639C17.2056 10.7639 18.1705 11.8768 18.1516 13.222C18.1516 14.577 17.2056 15.6802 15.9947 15.6802Z"
							/>
						</svg>
					</a>
					<a
						class="bg-shine animate-shine grid select-none grid-flow-col items-center justify-center gap-2.5 rounded-full bg-gray-600 px-6 py-3 font-medium text-white outline-gray-700 transition [--shine-color:theme(colors.teal.500/50%)] hover:bg-gray-700 focus-visible:outline-dashed focus-visible:outline-2 focus-visible:outline-offset-2 active:bg-gray-800"
						aria-disabled="false"
						href="https://steamcommunity.com/id/Wesleezz"
					>
						<svg
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="h-6 w-6"
						>
							<path
								d="M11.979 0C5.678 0 .511 4.86.022 11.037l6.432 2.658c.545-.371 1.203-.59 1.912-.59.063 0 .125.004.188.006l2.861-4.142V8.91c0-2.495 2.028-4.524 4.524-4.524 2.494 0 4.524 2.031 4.524 4.527s-2.03 4.525-4.524 4.525h-.105l-4.076 2.911c0 .052.004.105.004.159 0 1.875-1.515 3.396-3.39 3.396-1.635 0-3.016-1.173-3.331-2.727L.436 15.27C1.862 20.307 6.486 24 11.979 24c6.627 0 11.999-5.373 11.999-12S18.605 0 11.979 0zM7.54 18.21l-1.473-.61c.262.543.714.999 1.314 1.25 1.297.539 2.793-.076 3.332-1.375.263-.63.264-1.319.005-1.949s-.75-1.121-1.377-1.383c-.624-.26-1.29-.249-1.878-.03l1.523.63c.956.4 1.409 1.5 1.009 2.455-.397.957-1.497 1.41-2.454 1.012H7.54zm11.415-9.303c0-1.662-1.353-3.015-3.015-3.015-1.665 0-3.015 1.353-3.015 3.015 0 1.665 1.35 3.015 3.015 3.015 1.663 0 3.015-1.35 3.015-3.015zm-5.273-.005c0-1.252 1.013-2.266 2.265-2.266 1.249 0 2.266 1.014 2.266 2.266 0 1.251-1.017 2.265-2.266 2.265-1.253 0-2.265-1.014-2.265-2.265z"
							/>
						</svg>
					</a>
				</div>
			</div>
		</div>
	</div>
</section>

<style>
		:global(body) {
		background-color: #1E1B4B;
		color: white;
		transition: background-color 0.3s;
	}
</style>

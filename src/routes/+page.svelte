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
	<div class="relative grid grid-rows-1 items-center justify-center gap-6 overflow-hidden mt-24">
		<div
			class="motion-safe:animate-homeCirclesContainer children:h-[400px] children:w-[400px] children:animate-homeCircle children:rounded-full children:blur-3xl children:[grid-area:1/1] grid h-full w-full grid-rows-1 place-items-center [grid-area:1/1]"
		>
			<div
				class="motion-safe:animate-homeText relative z-30 grid place-items-center px-8 pb-24 pt-32 [grid-area:1/1] lg:pb-32 lg:pt-56"
			>
				<h1
					class="font-manrope mx-auto -mb-8 -mt-8 max-w-5xl text-center text-5xl font-extrabold leading-[1.1] tracking-tighter line-through opacity-25 dark:opacity-25 md:text-6xl"
				>
					Визуализатор{' '}
				</h1>
				<h1
					class="font-manrope mx-auto mb-6 max-w-5xl text-center text-5xl font-extrabold leading-[1.1] tracking-tighter md:text-6xl"
				>
					Визя
				</h1>
				<p class="mb-8 max-w-xl text-center text-lg leading-relaxed">
					или же Вислиз, люблю дизайн и историю ещё там так называемый разработчик
				</p>
				<div class="mb-8 grid items-start justify-center gap-4 sm:grid-flow-col md:gap-6">
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
						Telegram
					</a>
				</div>
			</div>
		</div>
	</div>
</section>

<style>
	:global(body.light-mode) {
		background-color: #f2eee2;
		color: black;
		transition: background-color 0.3s;
	}
	:global(body) {
		background-color: #18181b;
		color: white;
		transition: background-color 0.3s;
	}
</style>

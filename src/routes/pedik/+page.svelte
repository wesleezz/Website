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
	<meta property="og:title" content="Портфолио" />
	<meta property="og:description" content="Мое портфолио сделанное на svelte" />
</svelte:head>
<div class="grid min-h-screen grid-rows-[auto_1fr_auto]">
	<main class="min-h-[calc(100vh-9.5rem)]">
		<div>
			<div
				class="relative -mt-20 grid overflow-hidden bg-gradient-to-b from-orange-50/50 to-orange-50 pb-8 dark:from-[#392018] dark:to-[#8e5949]/20"
			>
				<div
					class="absolute -bottom-80 left-[50%] w-[250%] translate-x-[-50%] animate-pulse select-none [animation-duration:7s] sm:-bottom-64 sm:w-[150%] xl:bottom-[-50%] xl:w-full xl:max-w-[1920px]"
				>
					<img
						src="/_next/static/media/beams.f72f7127.webp"
						class="w-full animate-spin opacity-10 [animation-duration:30s] dark:opacity-20"
						draggable="false"
					/>
				</div>
				<div class="container relative z-30 mx-auto flex w-full items-center justify-between px-6">
					<div class="mx-auto pb-16 pt-40">
						<div
							class="flex items-center justify-center gap-1 bg-gradient-to-b from-[#063432] to-[#184d4a] bg-clip-text pb-2 font-manrope text-[2.5rem] font-extrabold leading-relaxed tracking-tighter text-transparent dark:from-white dark:to-zinc-200 md:gap-2 md:text-5xl"
						>
							<svg
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 18 14"
								class="mt-[1px] h-[29.5px] fill-[url(#frog-gradient)] dark:fill-[url(#frog-gradient-dark)] md:h-[34px]"
								><path
									fill-rule="evenodd"
									d="M8 0H6v2H4v2H2v4H0v6h14v-4h2V6h2V2h-2V0h-4v2h-2V0H8Z"
									clip-rule="evenodd"
								></path><defs
									><linearGradient id="frog-gradient" x1="0" x2="0" y1="0" y2="1"
										><stop offset="0%" stop-color="#063432"></stop><stop
											offset="100%"
											stop-color="#184d4a"
										></stop></linearGradient
									><linearGradient id="frog-gradient-dark" x1="0" x2="0" y1="0" y2="1"
										><stop offset="0%" stop-color="white"></stop><stop
											offset="100%"
											stop-color="#e4e4e7"
										></stop></linearGradient
									></defs
								></svg
							>PepeLand 10
						</div>
						<p
							class="mx-auto mt-3 max-w-xl text-center leading-relaxed text-zinc-900 dark:text-zinc-100 md:text-lg md:leading-relaxed"
						>
							Пространство с идеальными условиями для раскрытия собственного творческого потенциала
							в среде ванильного выживания
						</p>
						<div class="mt-6 flex flex-col justify-center gap-3 md:flex-row">
							<a
								class="group inline-flex shrink-0 select-none items-center justify-center font-medium transition wg-antialiased focus:outline-0 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 disabled:pointer-events-none focus-visible:outline-sky-600 gap-2 px-6 py-3 rounded-lg text-base bg-teal-500 hover:bg-teal-600 text-white dark:bg-teal-400 dark:hover:bg-teal-500 dark:text-zinc-800 disabled:opacity-50"
								href="/me">Купить доступ</a
							>
							<div
								class="relative flex items-center md:gap-2 rounded-lg bg-white pl-[1.125rem] pr-1 ring-1 ring-inset ring-zinc-50 text-zinc-950 dark py-1"
							>
								<div class="text-sm font-medium flex-1 md:flex-none">IP адрес</div>
								<div class="text-sm">play.pepeland.net</div>
								<div class="flex-1 flex justify-end pl-3 md:pl-0 md:flex-none">
									<button
										class="group inline-flex shrink-0 select-none items-center justify-center transition wg-antialiased focus:outline-0 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 disabled:pointer-events-none focus-visible:outline-sky-600 gap-1.5 text-sm leading-6 hover:bg-zinc-500/10 disabled:opacity-50 rounded p-2.5 font-normal"
										><svg
											xmlns="http://www.w3.org/2000/svg"
											fill="none"
											viewBox="0 0 24 24"
											stroke-width="2"
											stroke="currentColor"
											aria-hidden="true"
											class="text-current h-5 w-5 opacity-70 transition group-hover:opacity-100"
											><path
												stroke-linecap="round"
												stroke-linejoin="round"
												d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"
											></path></svg
										></button
									>
								</div>
							</div>
						</div>
						<div class="mt-4 text-center text-sm">
							Для игры нужна лицензия Minecraft: Java Edition. Версия сервера — 1.21.8
						</div>
					</div>
				</div>
				<div class="container relative mx-auto w-full lg:mt-[-20rem]">
					<div class="absolute inset-x-0 bottom-0 z-20 grid place-items-center">
						<div class="text-center">
							<div class="font-manrope text-lg font-semibold">Спавн мира ресурсов</div>
							<p class="mt-2 max-w-sm text-sm leading-relaxed text-zinc-800 dark:text-zinc-200">
								PepeLand 9
							</p>
						</div>
					</div>
					<img
						alt=""
						loading="lazy"
						width="1500"
						height="1500"
						decoding="async"
						data-nimg="1"
						class="relative inset-x-0 left-1/2 z-10 mx-auto -mb-24 -mt-64 w-[150%] max-w-6xl -translate-x-1/2 [mask-image:linear-gradient(#0000_0%_20%,black_40%_65%,#0000_100%)] md:left-auto md:-mt-16 md:w-full md:translate-x-0"
						style="color:transparent"
						srcset="/_imgx/w1920/plain/media/render.10605323.webp 1x, /_imgx/w3840/plain/media/render.10605323.webp 2x"
						src="/_imgx/w3840/plain/media/render.10605323.webp"
					/>
				</div>
			</div>
			<div
				class="relative bg-gradient-to-b from-[#fde8dc]/50 via-transparent py-20 dark:from-[#8e5949]/20"
			>
				<div class="absolute inset-x-0 top-0">
					<div
						class="mx-auto h-px w-full max-w-[1920px] bg-gradient-to-r from-transparent via-orange-400/50 to-transparent dark:via-orange-500/50"
					></div>
				</div>
				<div class="px-6 text-center font-manrope text-4xl font-bold tracking-tight">
					Как попасть на&nbsp;сервер?
				</div>
				<div class="mx-auto mt-10 grid max-w-7xl gap-4 px-6 md:grid-cols-3">
					<div
						class="rounded-xl p-3 bg-zinc-50/50 dark:bg-zinc-800/50 ring-1 ring-zinc-100 dark:ring-zinc-900"
					>
						<div class="flex flex-col items-center p-3">
							<div class="rounded-xl bg-sky-600 p-2.5 dark:bg-sky-800/50">
								<svg
									viewBox="0 0 24 24"
									xmlns="http://www.w3.org/2000/svg"
									fill="currentColor"
									class="size-8 text-sky-100 dark:text-sky-500"
									><path
										d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0ZM2.182 12c0-5.422 4.396-9.818 9.818-9.818S21.818 6.578 21.818 12a9.78 9.78 0 0 1-2.332 6.354 5.444 5.444 0 0 0-4.213-1.99H8.727a5.444 5.444 0 0 0-4.213 1.99A9.78 9.78 0 0 1 2.182 12Z"
										fill-rule="evenodd"
										clip-rule="evenodd"
									></path><rect width="10" height="10" x="7" y="4.5" rx="3"></rect></svg
								>
							</div>
							<div
								class="mt-3 text-center font-manrope text-xl font-bold text-zinc-950 dark:text-zinc-50"
							>
								Зарегистрируйтесь на сайте
							</div>
						</div>
						<div
							class="mt-3 flex h-48 flex-col items-center justify-center gap-2 rounded-lg p-5 ring-1 ring-inset bg-white ring-black/5 dark:bg-white/5"
						>
							<div class="flex h-full items-center justify-center">
								<button
									class="group inline-flex shrink-0 select-none items-center justify-center font-medium transition wg-antialiased focus:outline-0 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 disabled:pointer-events-none focus-visible:outline-sky-600 gap-1.5 px-4 py-2 rounded-lg text-sm leading-6 bg-zinc-800 hover:bg-zinc-700 text-white dark:bg-white dark:hover:bg-zinc-200 dark:text-black disabled:opacity-50"
									><a href="/auth">Войти или зарегистрироваться</a></button
								>
							</div>
							<div class="mt-auto text-center text-sm text-zinc-800 dark:text-zinc-300">
								Потребуется аккаунт Minecraft: Java Edition
							</div>
						</div>
					</div>
					<div
						class="rounded-xl p-3 bg-zinc-50/50 dark:bg-zinc-800/50 ring-1 ring-zinc-100 dark:ring-zinc-900"
					>
						<div class="flex flex-col items-center p-3">
							<div class="rounded-xl bg-green-600 p-2.5 dark:bg-green-800/50">
								<svg
									viewBox="0 0 24 24"
									xmlns="http://www.w3.org/2000/svg"
									fill="currentColor"
									class="size-8 text-green-100 dark:text-green-500"
									><path
										d="M5.161 4H18.84c.527 0 .982 0 1.356.03.395.033.789.104 1.167.297a3 3 0 0 1 1.311 1.311c.193.378.264.772.296 1.167.031.375.031.83.031 1.356a.839.839 0 0 1-.839.839H1.84A.839.839 0 0 1 1 8.161c0-.527 0-.981.03-1.356.033-.395.104-.789.297-1.167a3 3 0 0 1 1.311-1.311c.378-.193.772-.264 1.167-.296C4.18 4 4.635 4 5.161 4ZM2.6 11c-.56 0-.84 0-1.054.109a1 1 0 0 0-.437.437C1 11.76 1 12.04 1 12.6v3.239c0 .527 0 .981.03 1.356.033.395.104.789.297 1.167a3 3 0 0 0 1.311 1.311c.378.193.772.264 1.167.296.375.031.83.031 1.356.031H18.84c.527 0 .982 0 1.356-.03.395-.033.789-.104 1.167-.297a3 3 0 0 0 1.311-1.311c.193-.378.264-.772.296-1.167.031-.375.031-.83.031-1.356V12.6c0-.56 0-.84-.109-1.054a1 1 0 0 0-.437-.437C22.24 11 21.96 11 21.4 11H2.6Z"
										fill-rule="evenodd"
										clip-rule="evenodd"
									></path></svg
								>
							</div>
							<div
								class="mt-3 text-center font-manrope text-xl font-bold text-zinc-950 dark:text-zinc-50"
							>
								Купите доступ
							</div>
						</div>
						<div
							class="mt-3 flex h-48 flex-col items-center justify-center gap-2 rounded-lg p-5 ring-1 ring-inset bg-white ring-black/5 dark:bg-white/5"
						>
							<div class="flex h-full flex-col items-center justify-center gap-2 text-center">
								Временно недоступно
								<div class="text-xs leading-relaxed opacity-90">
									В целях контроля количества игроков на сервере, продажи временно приостановлены
								</div>
								<div class="text-xs leading-relaxed opacity-90">
									Подпишитесь на Telegram канал, чтобы не пропустить
								</div>
							</div>
							<div class="mt-auto text-center text-sm text-zinc-800 dark:text-zinc-300">
								<button
									class="group inline-flex shrink-0 select-none items-center justify-center font-medium transition wg-antialiased focus:outline-0 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 disabled:pointer-events-none focus-visible:outline-sky-600 gap-1.5 px-4 py-2 rounded-lg text-sm leading-6 bg-zinc-800 hover:bg-zinc-700 text-white dark:bg-white dark:hover:bg-zinc-200 dark:text-black disabled:opacity-50"
									><a href="https://p-l.cc/tg" target="_blank">Перейти в канал</a></button
								>
							</div>
						</div>
					</div>
					<div
						class="rounded-xl p-3 bg-zinc-50/50 dark:bg-zinc-800/50 ring-1 ring-zinc-100 dark:ring-zinc-900"
					>
						<div class="flex flex-col items-center p-3">
							<div class="rounded-xl bg-teal-600 p-2.5 dark:bg-teal-800/50">
								<svg
									viewBox="0 0 24 24"
									fill="currentColor"
									xmlns="http://www.w3.org/2000/svg"
									class="size-8 text-teal-100 dark:text-teal-500"
									><path
										fill-rule="evenodd"
										clip-rule="evenodd"
										d="M10.667 2.667H9.333C8.597 2.667 8 3.264 8 4s-.597 1.333-1.333 1.333c-.737 0-1.334.597-1.334 1.334C5.333 7.403 4.736 8 4 8s-1.333.597-1.333 1.333v2.666c0 .737-.597 1.334-1.333 1.334-.737 0-1.334.597-1.334 1.333v3.667a3 3 0 0 0 3 3h13a2.666 2.666 0 0 0 2.667-2.666v-1.334c0-.736.597-1.333 1.333-1.333s1.333-.597 1.333-1.333v-2.666c0-.737.597-1.334 1.334-1.334.736 0 1.333-.597 1.333-1.334V6.666c0-.736-.597-1.333-1.334-1.333A1.333 1.333 0 0 1 21.333 4c0-.736-.597-1.333-1.333-1.333h-2.667C16.597 2.667 16 3.264 16 4s-.597 1.333-1.334 1.333A1.333 1.333 0 0 1 13.333 4c0-.736-.597-1.333-1.333-1.333h-1.333Z"
									></path></svg
								>
							</div>
							<div
								class="mt-3 text-center font-manrope text-xl font-bold text-zinc-950 dark:text-zinc-50"
							>
								Зайдите на сервер
							</div>
						</div>
						<div
							class="mt-3 flex h-48 flex-col items-center justify-center gap-2 rounded-lg p-5 ring-1 ring-inset bg-white ring-black/5 dark:bg-white/5"
						>
							<div class="flex h-full flex-col items-center justify-center">
								<div
									class="relative flex items-center gap-2 rounded-lg bg-white dark:bg-zinc-900 dark:ring-white/10 dark:text-white pl-[1.125rem] pr-1 ring-1 ring-inset ring-zinc-50 text-zinc-950 py-1"
								>
									<div class="text-sm font-medium">IP адрес</div>
									<div class="text-sm">play.pepeland.net</div>
									<button
										class="group inline-flex shrink-0 select-none items-center justify-center transition wg-antialiased focus:outline-0 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 disabled:pointer-events-none focus-visible:outline-sky-600 gap-1.5 text-sm leading-6 hover:bg-zinc-500/10 disabled:opacity-50 rounded p-2.5 font-normal ml-auto"
										><svg
											xmlns="http://www.w3.org/2000/svg"
											fill="none"
											viewBox="0 0 24 24"
											stroke-width="2"
											stroke="currentColor"
											aria-hidden="true"
											class="text-current h-5 w-5 opacity-70 transition group-hover:opacity-100"
											><path
												stroke-linecap="round"
												stroke-linejoin="round"
												d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"
											></path></svg
										></button
									>
								</div>
								<div class="mt-2.5 text-center text-sm text-zinc-800 dark:text-zinc-300">
									Откройте Minecraft: Java Edition версии 1.21.8 и&nbsp;вставьте IP
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="relative py-20">
				<div class="absolute inset-x-0 top-0">
					<div
						class="mx-auto h-px w-full max-w-[1920px] bg-gradient-to-r from-transparent via-zinc-300/50 to-transparent dark:via-zinc-800/75"
					></div>
				</div>
				<div class="px-6 text-center font-manrope text-4xl font-bold tracking-tight">
					Миры сервера
				</div>
				<div
					class="mx-auto mt-4 max-w-lg text-center leading-relaxed text-zinc-700 dark:text-zinc-300"
				>
					Сервер разделён на разные миры для распределения нагрузки
				</div>
				<div
					class="top-20 z-40 mt-8 flex max-w-[calc(100vw-var(--scrollbar-width))] justify-center px-6"
				>
					<div
						class="no-scrollbar relative max-w-full rounded-xl px-2 py-px ring-1 ring-inset bg-white dark:bg-zinc-800/80 supports-backdrop-blur:bg-white/70 supports-backdrop-blur:dark:bg-zinc-950/80 backdrop-saturate-150 supports-backdrop-blur:backdrop-blur-lg dark:supports-backdrop-blur:backdrop-blur ring-zinc-100/50 dark:ring-zinc-800/75 *:py-[0.45rem] flex flex-shrink-0 flex-grow-0 flex-row flex-nowrap overflow-x-auto overflow-y-clip *:flex-shrink-0 [&amp;_[data-content]]:rounded-lg"
					>
						<button
							class="group relative flex text-sm font-medium transition text-zinc-700 hover:text-black dark:text-zinc-100 dark:hover:text-white data-[active]:text-teal-500 data-[active]:hover:text-teal-500 data-[active]:dark:text-teal-400 data-[active]:dark:hover:text-teal-400 focus-visible:outline-none"
							data-tab=""
							data-highlight-position="bottom"
							data-active=""
							><div
								class="absolute inset-x-4 isolate z-10 group-data-[highlight-position=top]:bottom-0 group-data-[highlight-position=bottom]:top-0"
								data-ray=""
								style="opacity: 1;"
							>
								<div
									class="absolute h-1 w-full rounded-full bg-gradient-to-r from-transparent via-teal-100 to-transparent opacity-75 blur dark:via-teal-500/75"
								></div>
							</div>
							<div
								class="relative z-30 grid grid-flow-col items-center gap-2 group-hover:bg-zinc-100 dark:group-hover:bg-zinc-800 px-3 py-2 rounded-full transition group-focus-visible:ring-2 group-focus-visible:ring-inset"
								data-content=""
							>
								<div
									class="flex min-w-[5rem] flex-col items-center justify-center gap-2 lg:w-[7.5rem]"
								>
									<svg
										xmlns="http://www.w3.org/2000/svg"
										width="24"
										height="24"
										viewBox="0 0 24 24"
										fill="currentColor"
										stroke="none"
										class="tabler-icon tabler-icon-fountain-filled size-6"
										><path
											d="M15 2a4 4 0 0 1 4 4a1 1 0 0 1 -1.993 .117l-.007 -.117a2 2 0 0 0 -3.995 -.15l-.005 .15v9h1v-4a3 3 0 0 1 6 0a1 1 0 0 1 -1.993 .117l-.007 -.117a1 1 0 0 0 -1.993 -.117l-.007 .117v4h5a1 1 0 0 1 .993 .883l.007 .117v2a4 4 0 0 1 -3.8 3.995l-.2 .005h-12a4 4 0 0 1 -3.995 -3.8l-.005 -.2v-2a1 1 0 0 1 .883 -.993l.117 -.007h5v-4a1 1 0 0 0 -1.993 -.117l-.007 .117a1 1 0 0 1 -2 0a3 3 0 0 1 5.995 -.176l.005 .176v4h1v-9a2 2 0 1 0 -4 0a1 1 0 1 1 -2 0a4 4 0 0 1 7.001 -2.645a3.983 3.983 0 0 1 2.999 -1.355z"
										></path></svg
									>Лобби
								</div>
							</div>
							<div
								class="absolute inset-x-4 isolate z-10 group-data-[highlight-position=top]:top-0 group-data-[highlight-position=bottom]:bottom-0"
								data-highlight=""
								style="opacity: 1;"
							>
								<div
									class="absolute h-1 w-full rounded-full bg-gradient-to-r from-transparent via-teal-100 to-transparent blur dark:via-teal-500/75"
								></div>
								<div
									class="absolute group-data-[highlight-position=top]:mt-0 group-data-[highlight-position=bottom]:mb-0 h-px w-full rounded-full bg-gradient-to-r from-transparent via-teal-500/75 to-transparent"
								></div>
							</div></button
						><button
							class="group relative flex text-sm font-medium transition text-zinc-700 hover:text-black dark:text-zinc-100 dark:hover:text-white data-[active]:text-teal-500 data-[active]:hover:text-teal-500 data-[active]:dark:text-teal-400 data-[active]:dark:hover:text-teal-400 focus-visible:outline-none"
							data-tab=""
							data-highlight-position="bottom"
							><div
								class="relative z-30 grid grid-flow-col items-center gap-2 group-hover:bg-zinc-100 dark:group-hover:bg-zinc-800 px-3 py-2 rounded-full transition group-focus-visible:ring-2 group-focus-visible:ring-inset"
								data-content=""
							>
								<div
									class="flex min-w-[5rem] flex-col items-center justify-center gap-2 lg:w-[7.5rem]"
								>
									<svg
										xmlns="http://www.w3.org/2000/svg"
										width="24"
										height="24"
										viewBox="0 0 24 24"
										fill="currentColor"
										stroke="none"
										class="tabler-icon tabler-icon-octagon-filled size-6"
										><path
											d="M15.3 2h-6.6c-.562 0 -1.016 .201 -1.407 .593l-4.7 4.7a1.894 1.894 0 0 0 -.593 1.407v6.6c0 .562 .201 1.016 .593 1.407l4.7 4.7c.391 .392 .845 .593 1.407 .593h6.6c.562 0 1.016 -.201 1.407 -.593l4.7 -4.7c.392 -.391 .593 -.845 .593 -1.407v-6.6c0 -.562 -.201 -1.016 -.593 -1.407l-4.7 -4.7a1.894 1.894 0 0 0 -1.407 -.593z"
										></path></svg
									>Мир построек 1
								</div>
							</div></button
						><button
							class="group relative flex text-sm font-medium transition text-zinc-700 hover:text-black dark:text-zinc-100 dark:hover:text-white data-[active]:text-teal-500 data-[active]:hover:text-teal-500 data-[active]:dark:text-teal-400 data-[active]:dark:hover:text-teal-400 focus-visible:outline-none"
							data-tab=""
							data-highlight-position="bottom"
							><div
								class="relative z-30 grid grid-flow-col items-center gap-2 group-hover:bg-zinc-100 dark:group-hover:bg-zinc-800 px-3 py-2 rounded-full transition group-focus-visible:ring-2 group-focus-visible:ring-inset"
								data-content=""
							>
								<div
									class="flex min-w-[5rem] flex-col items-center justify-center gap-2 lg:w-[7.5rem]"
								>
									<svg
										xmlns="http://www.w3.org/2000/svg"
										width="24"
										height="24"
										viewBox="0 0 24 24"
										fill="currentColor"
										stroke="none"
										class="tabler-icon tabler-icon-mushroom-filled size-6"
										><path
											d="M15 15v4a3 3 0 0 1 -5.995 .176l-.005 -.176v-4h6zm-10.1 -2a1.9 1.9 0 0 1 -1.894 -1.752l-.006 -.148c0 -5.023 4.027 -9.1 9 -9.1s9 4.077 9 9.1a1.9 1.9 0 0 1 -1.752 1.894l-.148 .006h-14.2z"
										></path></svg
									>Мир построек 2
								</div>
							</div></button
						><button
							class="group relative flex text-sm font-medium transition text-zinc-700 hover:text-black dark:text-zinc-100 dark:hover:text-white data-[active]:text-teal-500 data-[active]:hover:text-teal-500 data-[active]:dark:text-teal-400 data-[active]:dark:hover:text-teal-400 focus-visible:outline-none"
							data-tab=""
							data-highlight-position="bottom"
							><div
								class="relative z-30 grid grid-flow-col items-center gap-2 group-hover:bg-zinc-100 dark:group-hover:bg-zinc-800 px-3 py-2 rounded-full transition group-focus-visible:ring-2 group-focus-visible:ring-inset"
								data-content=""
							>
								<div
									class="flex min-w-[5rem] flex-col items-center justify-center gap-2 lg:w-[7.5rem]"
								>
									<svg
										xmlns="http://www.w3.org/2000/svg"
										width="24"
										height="24"
										viewBox="0 0 24 24"
										fill="currentColor"
										stroke="none"
										class="tabler-icon tabler-icon-radioactive-filled size-6"
										><path
											d="M21 11a1 1 0 0 1 1 1a10 10 0 0 1 -5 8.656a1 1 0 0 1 -1.302 -.268l-.064 -.098l-3 -5.19a.995 .995 0 0 1 -.133 -.542l.01 -.11l.023 -.106l.034 -.106l.046 -.1l.056 -.094l.067 -.089a.994 .994 0 0 1 .165 -.155l.098 -.064a2 2 0 0 0 .993 -1.57l.007 -.163a1 1 0 0 1 .883 -.994l.117 -.007h6z"
										></path><path
											d="M7 3.344a10 10 0 0 1 10 0a1 1 0 0 1 .418 1.262l-.052 .104l-3 5.19l-.064 .098a.994 .994 0 0 1 -.155 .165l-.089 .067a1 1 0 0 1 -.195 .102l-.105 .034l-.107 .022a1.003 1.003 0 0 1 -.547 -.07l-.104 -.052a2 2 0 0 0 -1.842 -.082l-.158 .082a1 1 0 0 1 -1.302 -.268l-.064 -.098l-3 -5.19a1 1 0 0 1 .366 -1.366z"
										></path><path
											d="M9 11a1 1 0 0 1 .993 .884l.007 .117a2 2 0 0 0 .861 1.645l.237 .152a.994 .994 0 0 1 .165 .155l.067 .089l.056 .095l.045 .099c.014 .036 .026 .07 .035 .106l.022 .107l.011 .11a.994 .994 0 0 1 -.08 .437l-.053 .104l-3 5.19a1 1 0 0 1 -1.366 .366a10 10 0 0 1 -5 -8.656a1 1 0 0 1 .883 -.993l.117 -.007h6z"
										></path></svg
									>Мир ферм
								</div>
							</div></button
						><button
							class="group relative flex text-sm font-medium transition text-zinc-700 hover:text-black dark:text-zinc-100 dark:hover:text-white data-[active]:text-teal-500 data-[active]:hover:text-teal-500 data-[active]:dark:text-teal-400 data-[active]:dark:hover:text-teal-400 focus-visible:outline-none"
							data-tab=""
							data-highlight-position="bottom"
							><div
								class="relative z-30 grid grid-flow-col items-center gap-2 group-hover:bg-zinc-100 dark:group-hover:bg-zinc-800 px-3 py-2 rounded-full transition group-focus-visible:ring-2 group-focus-visible:ring-inset"
								data-content=""
							>
								<div
									class="flex min-w-[5rem] flex-col items-center justify-center gap-2 lg:w-[7.5rem]"
								>
									<svg
										xmlns="http://www.w3.org/2000/svg"
										width="24"
										height="24"
										viewBox="0 0 24 24"
										fill="currentColor"
										stroke="none"
										class="tabler-icon tabler-icon-diamonds-filled size-6"
										><path
											d="M12 2.005c-.777 0 -1.508 .367 -1.971 .99l-5.362 6.895c-.89 1.136 -.89 3.083 0 4.227l5.375 6.911a2.457 2.457 0 0 0 3.93 -.017l5.361 -6.894c.89 -1.136 .89 -3.083 0 -4.227l-5.375 -6.911a2.446 2.446 0 0 0 -1.958 -.974z"
										></path></svg
									>Мир ресурсов 1
								</div>
							</div></button
						><button
							class="group relative flex text-sm font-medium transition text-zinc-700 hover:text-black dark:text-zinc-100 dark:hover:text-white data-[active]:text-teal-500 data-[active]:hover:text-teal-500 data-[active]:dark:text-teal-400 data-[active]:dark:hover:text-teal-400 focus-visible:outline-none"
							data-tab=""
							data-highlight-position="bottom"
							><div
								class="relative z-30 grid grid-flow-col items-center gap-2 group-hover:bg-zinc-100 dark:group-hover:bg-zinc-800 px-3 py-2 rounded-full transition group-focus-visible:ring-2 group-focus-visible:ring-inset"
								data-content=""
							>
								<div
									class="flex min-w-[5rem] flex-col items-center justify-center gap-2 lg:w-[7.5rem]"
								>
									<svg
										xmlns="http://www.w3.org/2000/svg"
										width="24"
										height="24"
										viewBox="0 0 24 24"
										fill="currentColor"
										stroke="none"
										class="tabler-icon tabler-icon-diamond-filled size-6"
										><path
											d="M18 4a1 1 0 0 1 .783 .378l.074 .108l3 5a1 1 0 0 1 -.032 1.078l-.08 .103l-8.53 9.533a1.7 1.7 0 0 1 -1.215 .51c-.4 0 -.785 -.14 -1.11 -.417l-.135 -.126l-8.5 -9.5a1 1 0 0 1 -.172 -1.067l.06 -.115l3.013 -5.022l.064 -.09a.982 .982 0 0 1 .155 -.154l.089 -.064l.088 -.05l.05 -.023l.06 -.025l.109 -.032l.112 -.02l.117 -.005h12zm-8.886 3.943a1 1 0 0 0 -1.371 .343l-.6 1l-.06 .116a1 1 0 0 0 .177 1.07l2 2.2l.09 .088a1 1 0 0 0 1.323 -.02l.087 -.09a1 1 0 0 0 -.02 -1.323l-1.501 -1.65l.218 -.363l.055 -.103a1 1 0 0 0 -.398 -1.268z"
										></path></svg
									>Мир ресурсов 2
								</div>
							</div></button
						><button
							class="group relative flex text-sm font-medium transition text-zinc-700 hover:text-black dark:text-zinc-100 dark:hover:text-white data-[active]:text-teal-500 data-[active]:hover:text-teal-500 data-[active]:dark:text-teal-400 data-[active]:dark:hover:text-teal-400 focus-visible:outline-none"
							data-tab=""
							data-highlight-position="bottom"
							><div
								class="relative z-30 grid grid-flow-col items-center gap-2 group-hover:bg-zinc-100 dark:group-hover:bg-zinc-800 px-3 py-2 rounded-full transition group-focus-visible:ring-2 group-focus-visible:ring-inset"
								data-content=""
							>
								<div
									class="flex min-w-[5rem] flex-col items-center justify-center gap-2 lg:w-[7.5rem]"
								>
									<svg
										xmlns="http://www.w3.org/2000/svg"
										width="24"
										height="24"
										viewBox="0 0 24 24"
										fill="currentColor"
										stroke="none"
										class="tabler-icon tabler-icon-shopping-cart-filled size-6"
										><path
											d="M6 2a1 1 0 0 1 .993 .883l.007 .117v1.068l13.071 .935a1 1 0 0 1 .929 1.024l-.01 .114l-1 7a1 1 0 0 1 -.877 .853l-.113 .006h-12v2h10a3 3 0 1 1 -2.995 3.176l-.005 -.176l.005 -.176c.017 -.288 .074 -.564 .166 -.824h-5.342a3 3 0 1 1 -5.824 1.176l-.005 -.176l.005 -.176a3.002 3.002 0 0 1 1.995 -2.654v-12.17h-1a1 1 0 0 1 -.993 -.883l-.007 -.117a1 1 0 0 1 .883 -.993l.117 -.007h2zm0 16a1 1 0 1 0 0 2a1 1 0 0 0 0 -2zm11 0a1 1 0 1 0 0 2a1 1 0 0 0 0 -2z"
										></path></svg
									>Мир торговли
								</div>
							</div></button
						>
					</div>
				</div>
				<div class="mx-auto mt-8 grid max-w-7xl gap-6 px-6 md:grid-cols-[400px_1fr]">
					<div class="mx-auto flex max-w-2xl flex-col gap-3">
						<div class="flex flex-1 flex-col justify-start gap-4">
							<div class="*:mt-3 *:leading-relaxed *:text-zinc-800 *:dark:text-zinc-200">
								<p>PepeLand начинается в этом мире — в лобби сервера.</p>
								<p>
									В лобби можно переходить в другие миры сервера, используя таблички возле точки
									спавна.
								</p>
								<p>Также в лобби есть гаджеты и рыбалка.</p>
							</div>
						</div>
					</div>
					<img
						src="/_next/static/media/lobby.ac92de7c.png"
						class="aspect-video w-full rounded-xl object-cover"
						alt=""
					/>
				</div>
			</div>
			<div
				class="relative bg-gradient-to-b from-orange-50/50 py-20 dark:from-orange-950/20 dark:to-orange-950/5"
			>
				<div class="absolute inset-x-0 top-0">
					<div
						class="mx-auto h-px w-full max-w-[1920px] bg-gradient-to-r from-transparent via-orange-500/50 to-transparent"
					></div>
				</div>
				<div class="mx-auto grid max-w-5xl gap-6 px-6">
					<div
						class="bg-gradient-to-b from-orange-400 to-orange-600 bg-clip-text text-center font-manrope text-4xl font-bold tracking-tight text-transparent dark:from-orange-300 dark:to-orange-500"
					>
						Продажи временно приостановлены
					</div>
					<div
						class="mx-auto mt-2 max-w-lg rounded-lg bg-white p-4 ring-1 ring-inset ring-black/5 dark:bg-white/5 dark:ring-white/10"
					>
						<p class="leading-relaxed text-zinc-700 dark:text-zinc-300">
							Возможность купить доступ на сервер появится через некоторое время после запуска 10
							сезона
						</p>
						<p class="mt-2 leading-relaxed text-zinc-700 dark:text-zinc-300">
							Мы ограничиваем доступ к покупке, чтобы снизить наплыв людей и обеспечить более
							комфортную игру на старте сезона
						</p>
					</div>
					<div class="mx-auto mt-6 grid max-w-2xl gap-4 md:grid-cols-2">
						<div class="flex flex-col gap-2.5">
							<svg
								viewBox="0 0 24 24"
								xmlns="http://www.w3.org/2000/svg"
								fill="currentColor"
								class="size-6 flex-none opacity-80"
								><path
									d="M16 1a1 1 0 0 1 1 1v1.002c.476.003.891.013 1.252.042.562.046 1.079.145 1.564.392a4 4 0 0 1 1.748 1.748c.247.485.346 1.002.392 1.564C22 7.29 22 7.954 22 8.758v8.483c0 .805 0 1.47-.044 2.01-.046.563-.145 1.08-.392 1.565a4 4 0 0 1-1.748 1.748c-.485.247-1.002.346-1.564.392-.541.044-1.206.044-2.01.044H7.758c-.805 0-1.47 0-2.01-.044-.563-.046-1.08-.145-1.565-.392a4 4 0 0 1-1.748-1.748c-.247-.485-.346-1.002-.392-1.564C2 18.71 2 18.046 2 17.242V8.758c0-.805 0-1.47.044-2.01.046-.563.145-1.08.392-1.565a4 4 0 0 1 1.748-1.748c.485-.247 1.002-.346 1.564-.392.361-.03.777-.04 1.252-.042V2a1 1 0 0 1 2 0v1h6V2a1 1 0 0 1 1-1ZM7 5.002V6a1 1 0 0 0 2 0V5h6v1a1 1 0 1 0 2 0v-.998c.445.003.795.012 1.089.036.438.035.663.1.819.18a2 2 0 0 1 .874.874c.08.156.145.38.18.819C20 7.361 20 7.943 20 8.8V9H4v-.2c0-.857 0-1.439.038-1.889.035-.438.1-.663.18-.819a2 2 0 0 1 .874-.874c.156-.08.38-.145.819-.18.294-.024.643-.033 1.089-.036Z"
									fill-rule="evenodd"
									clip-rule="evenodd"
								></path></svg
							>
							<p class="mt-0.5 text-sm leading-relaxed">
								Сезон длится минимум до конца апреля&nbsp;2026
							</p>
						</div>
						<div class="flex flex-col gap-2.5">
							<svg
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
								fill="currentColor"
								aria-hidden="true"
								class="size-6 flex-none opacity-80"
								><path d="M4 4a2 2 0 00-2 2v1h16V6a2 2 0 00-2-2H4z"></path><path
									fill-rule="evenodd"
									d="M18 9H2v5a2 2 0 002 2h12a2 2 0 002-2V9zM4 13a1 1 0 011-1h1a1 1 0 110 2H5a1 1 0 01-1-1zm5-1a1 1 0 100 2h1a1 1 0 100-2H9z"
									clip-rule="evenodd"
								></path></svg
							>
							<p class="mt-0.5 text-sm leading-relaxed">
								Покупка осуществляется только один&nbsp;раз — на&nbsp;весь&nbsp;сезон. Без повторных
								платежей.
							</p>
						</div>
					</div>
				</div>
			</div>
			<div class="relative mb-8 py-20">
				<div class="absolute inset-x-0 top-0">
					<div
						class="mx-auto h-px w-full max-w-[1920px] bg-gradient-to-r from-transparent via-zinc-300/75 to-transparent dark:via-zinc-800/75"
					></div>
				</div>
				<div class="text-center font-manrope text-3xl font-bold tracking-tight">
					Остались вопросы?
				</div>
				<div
					class="mx-auto mt-4 max-w-lg text-center leading-relaxed text-zinc-700 dark:text-zinc-300"
				>
					Полезные страницы сайта и соцсети
				</div>
				<div class="mx-auto mt-8 grid max-w-3xl gap-4 px-6 md:grid-cols-2">
					<div class="flex flex-col items-start rounded-xl bg-zinc-50 p-4 dark:bg-zinc-900/75">
						<div class="rounded-lg bg-green-600 p-2 text-white">
							<svg
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
								fill="currentColor"
								aria-hidden="true"
								class="size-6"
								><path
									fill-rule="evenodd"
									d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
									clip-rule="evenodd"
								></path></svg
							>
						</div>
						<div class="mt-3 text-lg font-semibold text-zinc-950 dark:text-zinc-50">
							Часто задаваемые вопросы
						</div>
						<p class="mt-1 flex-1 text-sm leading-relaxed text-zinc-700 dark:text-zinc-200">
							Возможно ответ на ваш вопрос находится здесь
						</p>
						<a
							href="/wiki/faq"
							target="_blank"
							class="group shrink-0 select-none items-center justify-center font-medium transition wg-antialiased focus:outline-0 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 disabled:pointer-events-none focus-visible:outline-sky-600 gap-1.5 px-4 py-2 rounded-lg text-sm leading-6 bg-zinc-600 hover:bg-zinc-700 text-white dark:bg-zinc-800 dark:hover:bg-zinc-700 dark:text-zinc-50 disabled:opacity-50 mt-3 flex w-full"
							>Перейти к FAQ<svg
								xmlns="http://www.w3.org/2000/svg"
								fill="none"
								viewBox="0 0 24 24"
								stroke-width="2"
								stroke="currentColor"
								aria-hidden="true"
								class="text-current size-4 size-4"
								><path
									stroke-linecap="round"
									stroke-linejoin="round"
									d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
								></path></svg
							></a
						>
					</div>
					<div class="flex flex-col items-start rounded-xl bg-zinc-50 p-4 dark:bg-zinc-900/75">
						<div class="rounded-lg bg-teal-600 p-2 text-white">
							<svg
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
								fill="currentColor"
								aria-hidden="true"
								class="size-6"
								><path
									d="M9 4.804A7.968 7.968 0 005.5 4c-1.255 0-2.443.29-3.5.804v10A7.969 7.969 0 015.5 14c1.669 0 3.218.51 4.5 1.385A7.962 7.962 0 0114.5 14c1.255 0 2.443.29 3.5.804v-10A7.968 7.968 0 0014.5 4c-1.255 0-2.443.29-3.5.804V12a1 1 0 11-2 0V4.804z"
								></path></svg
							>
						</div>
						<div class="mt-3 text-lg font-semibold text-zinc-950 dark:text-zinc-50">
							Вики сервера
						</div>
						<p class="mt-1 flex-1 text-sm leading-relaxed text-zinc-700 dark:text-zinc-200">
							В вики находится актуальная информация по множеству вещей, происходящих на сервере
						</p>
						<a
							href="/wiki"
							target="_blank"
							class="group shrink-0 select-none items-center justify-center font-medium transition wg-antialiased focus:outline-0 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 disabled:pointer-events-none focus-visible:outline-sky-600 gap-1.5 px-4 py-2 rounded-lg text-sm leading-6 bg-zinc-600 hover:bg-zinc-700 text-white dark:bg-zinc-800 dark:hover:bg-zinc-700 dark:text-zinc-50 disabled:opacity-50 mt-3 flex w-full"
							>Перейти в вики<svg
								xmlns="http://www.w3.org/2000/svg"
								fill="none"
								viewBox="0 0 24 24"
								stroke-width="2"
								stroke="currentColor"
								aria-hidden="true"
								class="text-current size-4 size-4"
								><path
									stroke-linecap="round"
									stroke-linejoin="round"
									d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
								></path></svg
							></a
						>
					</div>
					<div class="flex flex-col items-start rounded-xl bg-zinc-50 p-4 dark:bg-zinc-900/75">
						<div class="rounded-lg bg-[#2394E5] p-2 text-white">
							<svg
								viewBox="0 0 24 24"
								xmlns="http://www.w3.org/2000/svg"
								fill="currentColor"
								class="-mb-px mt-px size-6"
								><path
									d="M2.53419 10.491 20.4342 3.72755c.5979-.22564 1.2652.07521 1.4908.67307.0791.21021.0964.43779.0482.65668l-3.0857 14.0805c-.1562.7136-.8611 1.1658-1.5747 1.0086-.1774-.0385-.3442-.1138-.4918-.2198l-6.1453-4.4415c-.3694-.2671-.4533-.784-.1852-1.1543.0289-.0395.0617-.0771.0964-.1118l6.319-6.07213c.1311-.12632.135-.33557.0087-.46768-.109-.11282-.2826-.13404-.4156-.04918L7.88597 13.0975c-.5101.324-1.13978.3973-1.7116.1996l-3.618-1.2516c-.43103-.1485-.65957-.6201-.51107-1.0511.081-.2314.25939-.4166.48889-.5034Z"
								></path></svg
							>
						</div>
						<div class="mt-3 text-lg font-semibold text-zinc-950 dark:text-zinc-50">
							Telegram канал
						</div>
						<p class="mt-1 flex-1 text-sm leading-relaxed text-zinc-700 dark:text-zinc-200">
							В канале публикуются новости сервера, а также анонсы скидок и изменений цены
						</p>
						<a
							href="/tg"
							target="_blank"
							class="group shrink-0 select-none items-center justify-center font-medium transition wg-antialiased focus:outline-0 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 disabled:pointer-events-none focus-visible:outline-sky-600 gap-1.5 px-4 py-2 rounded-lg text-sm leading-6 bg-zinc-600 hover:bg-zinc-700 text-white dark:bg-zinc-800 dark:hover:bg-zinc-700 dark:text-zinc-50 disabled:opacity-50 mt-3 flex w-full"
							>Перейти в канал<svg
								xmlns="http://www.w3.org/2000/svg"
								fill="none"
								viewBox="0 0 24 24"
								stroke-width="2"
								stroke="currentColor"
								aria-hidden="true"
								class="text-current size-4 size-4"
								><path
									stroke-linecap="round"
									stroke-linejoin="round"
									d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
								></path></svg
							></a
						>
					</div>
					<div class="flex flex-col items-start rounded-xl bg-zinc-50 p-4 dark:bg-zinc-900/75">
						<div class="rounded-lg bg-[#5865F2] p-2 text-white">
							<svg
								viewBox="0 0 24 24"
								xmlns="http://www.w3.org/2000/svg"
								fill="currentColor"
								class="-mb-px mt-px size-6"
								><path
									d="M20.317 4.3698a19.7913 19.7913 0 00-4.8851-1.5152.0741.0741 0 00-.0785.0371c-.211.3753-.4447.8648-.6083 1.2495-1.8447-.2762-3.68-.2762-5.4868 0-.1636-.3933-.4058-.8742-.6177-1.2495a.077.077 0 00-.0785-.037 19.7363 19.7363 0 00-4.8852 1.515.0699.0699 0 00-.0321.0277C.5334 9.0458-.319 13.5799.0992 18.0578a.0824.0824 0 00.0312.0561c2.0528 1.5076 4.0413 2.4228 5.9929 3.0294a.0777.0777 0 00.0842-.0276c.4616-.6304.8731-1.2952 1.226-1.9942a.076.076 0 00-.0416-.1057c-.6528-.2476-1.2743-.5495-1.8722-.8923a.077.077 0 01-.0076-.1277c.1258-.0943.2517-.1923.3718-.2914a.0743.0743 0 01.0776-.0105c3.9278 1.7933 8.18 1.7933 12.0614 0a.0739.0739 0 01.0785.0095c.1202.099.246.1981.3728.2924a.077.077 0 01-.0066.1276 12.2986 12.2986 0 01-1.873.8914.0766.0766 0 00-.0407.1067c.3604.698.7719 1.3628 1.225 1.9932a.076.076 0 00.0842.0286c1.961-.6067 3.9495-1.5219 6.0023-3.0294a.077.077 0 00.0313-.0552c.5004-5.177-.8382-9.6739-3.5485-13.6604a.061.061 0 00-.0312-.0286zM8.02 15.3312c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9555-2.4189 2.157-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.9555 2.4189-2.1569 2.4189zm7.9748 0c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9554-2.4189 2.1569-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.946 2.4189-2.1568 2.4189Z"
								></path></svg
							>
						</div>
						<div class="mt-3 text-lg font-semibold text-zinc-950 dark:text-zinc-50">
							Discord сервер
						</div>
						<p class="mt-1 flex-1 text-sm leading-relaxed text-zinc-700 dark:text-zinc-200">
							На сервере публикуются новости сервера, анонсы ивентов и оповещения
						</p>
						<a
							href="/ds"
							target="_blank"
							class="group shrink-0 select-none items-center justify-center font-medium transition wg-antialiased focus:outline-0 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 disabled:pointer-events-none focus-visible:outline-sky-600 gap-1.5 px-4 py-2 rounded-lg text-sm leading-6 bg-zinc-600 hover:bg-zinc-700 text-white dark:bg-zinc-800 dark:hover:bg-zinc-700 dark:text-zinc-50 disabled:opacity-50 mt-3 flex w-full"
							>Перейти на сервер<svg
								xmlns="http://www.w3.org/2000/svg"
								fill="none"
								viewBox="0 0 24 24"
								stroke-width="2"
								stroke="currentColor"
								aria-hidden="true"
								class="text-current size-4 size-4"
								><path
									stroke-linecap="round"
									stroke-linejoin="round"
									d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
								></path></svg
							></a
						>
					</div>
				</div>
			</div>
		</div>
		<!--$--><!--/$-->
		<div>
			<div
				class="absolute -bottom-80 left-[50%] w-[250%] translate-x-[-50%] animate-pulse select-none [animation-duration:7s] sm:-bottom-64 sm:w-[150%] xl:bottom-[-50%] xl:w-full xl:max-w-[1920px]"
			>
				<img
					src="beams.f72f7127.webp"
					class="w-full animate-spin opacity-10 [animation-duration:30s] dark:opacity-20"
					draggable="false"
				/>
			</div>
		</div>
	</main>
</div>

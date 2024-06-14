
<style>
  *{
    font-family: "Cambay", sans-serif;
  font-weight: 700;
  font-style: normal;
  }
</style>
<script>
	const backgroundColor = '#1dcd8d';
  const fontColor = 'ffffff'
</script>

<div class="fixed inset-0 items-center" style="background-color: {backgroundColor}">
	<nav
		class="relative flex w-full flex-nowrap items-center justify-between py-4 lg:flex-wrap lg:justify-start lg:py-8 lg:px-7" data-twe-navbar-ref>
		<div class="flex w-full flex-wrap items-center justify-between px-3">
			<button
				class="block border-0 bg-transparent px-2 text-black/50 hover:no-underline hover:shadow-none focus:no-underline focus:shadow-none focus:outline-none focus:ring-0 dark:text-neutral-200 lg:hidden"
				type="button"
				data-twe-collapse-init
				data-twe-target="#navbarSupportedContent7"
				aria-controls="navbarSupportedContent7"
				aria-expanded="false"
				aria-label="Toggle navigation"
			>
				<!-- Hamburger icon -->
				<span class="[&>svg]:w-7 [&>svg]:stroke-black/50 dark:[&>svg]:stroke-neutral-200">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
						<path
							fill-rule="evenodd"
							d="M3 6.75A.75.75 0 013.75 6h16.5a.75.75 0 010 1.5H3.75A.75.75 0 013 6.75zM3 12a.75.75 0 01.75-.75h16.5a.75.75 0 010 1.5H3.75A.75.75 0 013 12zm0 5.25a.75.75 0 01.75-.75h16.5a.75.75 0 010 1.5H3.75a.75.75 0 01-.75-.75z"
							clip-rule="evenodd"
						/>
					</svg>
				</span>
			</button>

			<!-- Collapsible navbar container -->
			<div class="!visible mt-2 hidden flex-grow basis-[100%] items-center lg:mt-0 lg:!flex lg:basis-auto" id="navbarSupportedContent7"data-twe-collapse-item>
				<!-- Left links -->
				<ul
					class="list-style-none ms-auto flex flex-col ps-0 lg:mt-1 lg:flex-row"
					data-twe-navbar-nav-ref
				>
					<!-- Home link -->
					<li class="my-4 ps-2 lg:my-0 lg:pe-1 lg:ps-2" data-twe-nav-item-ref>
						<a
							class="text-black lg:px-2 text-xl"
              style="color: {fontColor};"
							aria-current="page"
							href="/"
							data-twe-nav-link-ref>HOME</a
						>
					</li>
          <li class="my-4 ps-2 lg:my-0 lg:pe-1 lg:ps-2" data-twe-nav-item-ref>
						<a
							class="text-black dark:text-black lg:px-2 text-xl"
							aria-current="page"
							href="about"
							data-twe-nav-link-ref>ABOUT</a
						>
					</li>
          <li class="my-4 ps-2 lg:my-0 lg:pe-1 lg:ps-2" data-twe-nav-item-ref>
						<a
							class="text-black dark:text-black lg:px-2 text-xl"
							aria-current="page"
							href="service"
							data-twe-nav-link-ref>SERVICES</a
						>
					</li>
          <li class="my-4 ps-2 lg:my-0 lg:pe-1 lg:ps-2" data-twe-nav-item-ref>
						<a
							class="text-black dark:text-black lg:px-2 text-xl"
							aria-current="page"
							href="why-us"
							data-twe-nav-link-ref>WHY US</a
						>
					</li>
          <li class="my-4 ps-2 lg:my-0 lg:pe-1 lg:ps-2" data-twe-nav-item-ref>
						<a
							class="text-black dark:text-black lg:px-2 text-xl"
							aria-current="page"
							href="contact"
							data-twe-nav-link-ref>CONTACT US</a
						>
					</li>
				</ul>
			</div>
		</div>
	</nav>

</div>

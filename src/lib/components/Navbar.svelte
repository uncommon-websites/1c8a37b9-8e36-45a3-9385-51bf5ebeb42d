<script lang="ts">
	// Navbar component
</script>

<nav class="flex items-center justify-between px-4 py-3 bg-white sticky top-0 z-50 border-b border-transparent transition-all duration-200">
	<div class="flex items-center gap-6">
		<a href="/" class="flex items-center gap-2 text-notion-black hover:opacity-80 transition-opacity">
			<svg width="30" height="30" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-primary-500">
				<path
					opacity="0.7"
					d="M9.22279 15.2235C12.6595 15.2235 15.4456 12.4375 15.4456 9.00075C15.4456 5.56399 12.6595 2.77795 9.22279 2.77795C5.78604 2.77795 3 5.56399 3 9.00075C3 12.4375 5.78604 15.2235 9.22279 15.2235Z"
					fill="currentColor"
				/>
				<path
					opacity="0.7"
					d="M14.5566 20.5574C17.9933 20.5574 20.7794 17.7713 20.7794 14.3346C20.7794 10.8978 17.9933 8.11179 14.5566 8.11179C11.1198 8.11179 8.3338 10.8978 8.3338 14.3346C8.3338 17.7713 11.1198 20.5574 14.5566 20.5574Z"
					fill="currentColor"
				/>
			</svg>
			<span class="font-semibold text-xl tracking-tight text-notion-black">Youcap</span>
		</a>

		<div class="hidden lg:flex items-center gap-5 text-[14px] font-normal text-notion-gray">
			<a href="#features" class="hover:text-notion-black transition-colors">Features</a>
			<a href="#pricing" class="hover:text-notion-black transition-colors">Pricing</a>
			<a href="#use-cases" class="hover:text-notion-black transition-colors">Use Cases</a>
			<a href="#integrations" class="hover:text-notion-black transition-colors">Integrations</a>
			<a href="#blog" class="hover:text-notion-black transition-colors">Blog</a>
		</div>
	</div>

	<div class="flex items-center gap-4">
		<a href="#" class="text-[14px] font-normal text-notion-gray hover:text-notion-black transition-colors hidden sm:block">Log in</a>
		<a href="#" class="bg-notion-black text-white text-[14px] font-medium px-3 py-1.5 rounded-[4px] hover:bg-notion-gray transition-colors">Start Free Trial</a>
	</div>
</nav>

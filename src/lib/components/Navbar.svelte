<script lang="ts">
	// Navbar component
</script>

<nav class="flex items-center justify-between px-4 py-3 bg-white sticky top-0 z-50 border-b border-transparent transition-all duration-200">
	<div class="flex items-center gap-6">
		<a href="/" class="flex items-center gap-2 text-notion-black hover:opacity-80 transition-opacity">
			<svg width="30" height="30" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-notion-black">
				<path d="M4 4H20V20H4V4Z" fill="currentColor" stroke="currentColor" stroke-width="2"/>
				<path d="M9 8L15 16V8" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
				<path d="M15 8V16" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                <path d="M9 16V8" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
			</svg>
            <!-- The logo above is a placeholder, I should make a better one or just text if SVG is hard -->
            <!-- Actually, let's try to make the N logo more accurate: Box with N inside -->
		</a>
        
        <div class="flex items-center gap-1">
             <a href="/" class="flex items-center gap-2">
                <svg viewBox="0 0 24 24" width="24" height="24" class="block" fill="currentColor"><path d="M4.396 3h15.21c.772 0 1.396.623 1.396 1.395v15.21c0 .77-.624 1.395-1.396 1.395H4.396A1.397 1.397 0 0 1 3 19.605V4.395C3 3.623 3.624 3 4.396 3zm4.562 4.416c-.4 0-.725.324-.725.723v7.722c0 .4.325.724.725.724h.548c.313 0 .587-.197.684-.49l3.52-6.57v6.336c0 .4.325.724.725.724h.548c.4 0 .725-.324.725-.724V7.416c0-.4-.325-.723-.725-.723h-.62c-.313 0-.586.197-.684.49L9.635 13.63V7.416c0-.4-.325-.723-.725-.723h-.548z"></path></svg>
                <span class="font-medium text-lg tracking-tight text-notion-black">Notion</span>
            </a>
        </div>

		<div class="hidden lg:flex items-center gap-5 text-[14px] font-normal text-notion-gray">
			<a href="#" class="hover:text-notion-black transition-colors">Mail</a>
			<a href="#" class="hover:text-notion-black transition-colors">Calendar</a>
			<a href="#" class="hover:text-notion-black transition-colors">AI</a>
			<a href="#" class="hover:text-notion-black transition-colors">Enterprise</a>
			<a href="#" class="hover:text-notion-black transition-colors">Pricing</a>
			<div class="group relative flex items-center gap-1 cursor-pointer hover:text-notion-black transition-colors">
				Explore
				<svg width="10" height="6" viewBox="0 0 10 6" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path d="M1 1L5 5L9 1" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
				</svg>
			</div>
			<a href="#" class="hover:text-notion-black transition-colors">Request a demo</a>
		</div>
	</div>

	<div class="flex items-center gap-4">
		<a href="#" class="text-[14px] font-normal text-notion-gray hover:text-notion-black transition-colors hidden sm:block">Log in</a>
		<a href="#" class="bg-notion-black text-white text-[14px] font-medium px-3 py-1.5 rounded-[4px] hover:bg-notion-gray transition-colors">Get Notion Mail free</a>
	</div>
</nav>

<script>
    // Hero Component
</script>

<section class="pt-20 pb-16 px-4 flex flex-col items-center text-center max-w-[1200px] mx-auto">
    <!-- Video Icon -->
    <div class="mb-8 relative">
        <svg width="64" height="64" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="text-primary-500 w-20 h-20">
            <rect x="2" y="2" width="20" height="20" rx="2" ry="2"></rect>
            <polygon points="10 8 16 12 10 16 10 8" fill="currentColor"></polygon>
        </svg>
        <div class="absolute right-full top-1/2 w-32 h-[2px] border-t-2 border-dashed border-gray-200 -translate-y-1/2 opacity-50 hidden md:block" style="transform: rotate(-10deg) translateX(-20px);"></div>
    </div>

    <h1 class="text-5xl md:text-6xl lg:text-7xl font-bold tracking-tight text-notion-black mb-6 max-w-4xl text-balance leading-[1.1]">
        Transform video into <br class="hidden md:block" /> searchable insights
    </h1>

    <p class="text-xl text-notion-gray max-w-2xl mb-10 text-balance leading-relaxed">
        AI-powered transcription and analysis that turns your video content into actionable, searchable text in minutes.
    </p>

    <button class="bg-notion-black text-white text-lg font-medium px-6 py-3 rounded-[6px] hover:bg-notion-gray transition-colors mb-20">
        Start Free Trial
    </button>

    <!-- Video Transcription Mockup -->
    <div class="w-full bg-white rounded-xl shadow-2xl border border-gray-200 overflow-hidden text-left text-sm h-[600px] relative flex flex-col">
        <!-- Header -->
        <div class="h-12 border-b border-gray-100 flex items-center px-6 justify-between bg-white">
            <div class="flex items-center gap-2 font-medium text-notion-black">
                <svg class="w-4 h-4 text-primary-500" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <rect x="2" y="2" width="20" height="20" rx="2" ry="2"></rect>
                    <polygon points="10 8 16 12 10 16 10 8" fill="currentColor"></polygon>
                </svg>
                Product Launch Video - Final.mp4
            </div>
            <div class="flex items-center gap-2">
                <span class="text-xs text-green-600 bg-green-50 px-2 py-1 rounded">Transcribed</span>
                <button class="text-xs font-medium border border-gray-200 rounded px-3 py-1 text-gray-600 hover:bg-gray-50">
                    Export
                </button>
            </div>
        </div>

        <!-- Main Content Area -->
        <div class="flex-1 flex overflow-hidden">
            <!-- Video Preview -->
            <div class="w-1/2 bg-black flex items-center justify-center p-8 hidden md:flex">
                <div class="w-full aspect-video bg-gray-900 rounded-lg flex items-center justify-center relative">
                    <svg class="w-16 h-16 text-white opacity-80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <polygon points="5 3 19 12 5 21 5 3" fill="currentColor"></polygon>
                    </svg>
                    <div class="absolute bottom-4 left-4 right-4 bg-gray-800 bg-opacity-90 rounded px-3 py-2 flex items-center gap-3">
                        <div class="w-8 h-8 bg-white bg-opacity-20 rounded-full flex items-center justify-center">
                            <svg class="w-4 h-4 text-white" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <rect x="6" y="4" width="4" height="16"></rect>
                                <rect x="14" y="4" width="4" height="16"></rect>
                            </svg>
                        </div>
                        <div class="flex-1 h-1 bg-gray-600 rounded-full">
                            <div class="w-1/3 h-full bg-primary-500 rounded-full"></div>
                        </div>
                        <span class="text-xs text-white">2:34 / 8:12</span>
                    </div>
                </div>
            </div>

            <!-- Transcript -->
            <div class="flex-1 p-6 overflow-auto bg-white">
                <div class="space-y-4">
                    <div class="flex gap-3 group">
                        <span class="text-xs text-gray-400 font-mono w-12 flex-shrink-0">0:00</span>
                        <p class="text-notion-gray leading-relaxed">
                            Hey everyone, welcome back to the channel. Today I'm excited to share our new product launch with you.
                        </p>
                    </div>
                    <div class="flex gap-3 group">
                        <span class="text-xs text-gray-400 font-mono w-12 flex-shrink-0">0:12</span>
                        <p class="text-notion-gray leading-relaxed">
                            We've been working on this for the past six months, and it's finally ready to show you all.
                        </p>
                    </div>
                    <div class="flex gap-3 group bg-primary-50 -mx-3 px-3 py-2 rounded">
                        <span class="text-xs text-primary-600 font-mono w-12 flex-shrink-0">0:24</span>
                        <p class="text-notion-black leading-relaxed">
                            <mark class="bg-primary-200 text-notion-black px-1">This feature will completely change</mark> how you work with video content.
                        </p>
                    </div>
                    <div class="flex gap-3 group">
                        <span class="text-xs text-gray-400 font-mono w-12 flex-shrink-0">0:35</span>
                        <p class="text-notion-gray leading-relaxed">
                            Let me walk you through the key features and how they can help you save time.
                        </p>
                    </div>
                    <div class="flex gap-3 group">
                        <span class="text-xs text-gray-400 font-mono w-12 flex-shrink-0">0:48</span>
                        <p class="text-notion-gray leading-relaxed">
                            First up, we have AI-powered transcription that works in over 50 languages.
                        </p>
                    </div>
                    <div class="flex gap-3 group">
                        <span class="text-xs text-gray-400 font-mono w-12 flex-shrink-0">1:02</span>
                        <p class="text-notion-gray leading-relaxed">
                            The accuracy is incredible, and it handles technical terms really well.
                        </p>
                    </div>
                </div>
            </div>
        </div>

        <!-- AI Suggestion Floating Card -->
        <div class="absolute bottom-8 right-8 bg-white rounded-lg shadow-2xl border border-gray-200 p-4 max-w-xs z-10">
            <div class="flex items-start gap-3">
                <div class="w-8 h-8 bg-primary-100 rounded-full flex items-center justify-center flex-shrink-0">
                    <svg class="w-4 h-4 text-primary-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <div>
                    <div class="text-xs font-semibold text-notion-black mb-1">AI Insight</div>
                    <div class="text-xs text-gray-600 leading-relaxed">
                        Key topics: Product Features, Time Savings, AI Technology
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

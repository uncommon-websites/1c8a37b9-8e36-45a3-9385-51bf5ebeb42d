<section class="max-w-[1200px] mx-auto px-4 py-20">
    <div class="grid md:grid-cols-2 gap-12 items-center">
        <!-- Left Content -->
        <div>
            <!-- AI Stamp -->
            <div class="relative w-24 h-24 mb-8">
                <svg width="60" height="60" viewBox="0 0 24 24" fill="none" class="absolute left-0 top-0 transform -rotate-6">
                     <rect x="2" y="2" width="20" height="20" rx="2" stroke="#EF4444" stroke-width="1.5"></rect>
                     <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" font-family="serif" font-weight="bold" font-size="12" fill="#EF4444">AI</text>
                     <rect x="1" y="1" width="22" height="22" rx="2" stroke="#EF4444" stroke-width="1" stroke-dasharray="2 2"></rect>
                </svg>
                 <svg width="60" height="60" viewBox="0 0 24 24" fill="none" class="absolute left-10 top-0 transform rotate-12">
                     <circle cx="12" cy="12" r="10" stroke="#3B82F6" stroke-width="1.5"></circle>
                     <path d="M8 8L6 12L8 16" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
                     <path d="M16 8L18 12L16 16" stroke="#3B82F6" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
                     <circle cx="12" cy="12" r="11" stroke="#3B82F6" stroke-width="1" stroke-dasharray="2 2"></circle>
                </svg>
            </div>

            <h2 class="text-4xl md:text-5xl font-bold tracking-tight text-notion-black mb-12 text-balance leading-[1.1]">
                Every reply drafted, quickly.
            </h2>

            <div class="space-y-8">
                <div class="flex gap-4">
                    <div class="w-6 h-6 flex items-center justify-center text-notion-gray font-mono text-lg">{"{}"}</div>
                    <div>
                        <h3 class="font-semibold text-notion-black text-lg">Snippets</h3>
                    </div>
                </div>
                 <div class="flex gap-4">
                    <div class="w-6 h-6 flex items-center justify-center text-orange-500">
                        <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                    </div>
                    <div>
                        <h3 class="font-semibold text-notion-black text-lg">Built-in scheduling</h3>
                        <p class="text-notion-gray mt-1 leading-relaxed">Notion Calendar integrates with Notion Mail. Just type /schedule, mark your availability, and let others pick a time.</p>
                    </div>
                </div>
                 <div class="flex gap-4">
                    <div class="w-6 h-6 flex items-center justify-center text-notion-gray">
                        <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="9 14 4 9 9 4"></polyline><path d="M20 20v-7a4 4 0 0 0-4-4H4"></path></svg>
                    </div>
                    <div>
                        <h3 class="font-semibold text-notion-black text-lg">Quick replies</h3>
                    </div>
                </div>
                 <div class="flex gap-4">
                    <div class="w-6 h-6 flex items-center justify-center text-notion-gray font-serif italic font-bold">AI</div>
                    <div>
                        <h3 class="font-semibold text-notion-black text-lg">Improve your writing with AI</h3>
                    </div>
                </div>
            </div>
        </div>

        <!-- Right Visual -->
        <div class="bg-[#F7F7F5] rounded-xl p-8 h-[600px] flex items-center justify-center overflow-hidden">
            <div class="bg-white rounded-lg shadow-xl border border-gray-200 w-full max-w-md p-6 text-sm">
                <div class="flex items-center justify-between mb-4 border-b border-gray-100 pb-4">
                    <div>
                        <div class="font-medium text-notion-black">Diana M <span class="text-gray-400 font-normal">diana@acme.com</span></div>
                        <div class="font-medium text-notion-black mt-1">Jack Steadman</div>
                    </div>
                </div>
                <div class="font-medium text-notion-black mb-4">Partnership</div>
                <div class="text-notion-gray mb-4">
                    Let's meet next month<br>
                    Schedule here
                </div>
                
                <!-- Calendar Widget -->
                <div class="border border-gray-200 rounded-lg overflow-hidden">
                    <div class="bg-gray-50 px-3 py-2 border-b border-gray-200 text-xs font-medium text-gray-500">
                        30 minute meeting
                    </div>
                    <div class="grid grid-cols-5 text-center text-xs border-b border-gray-200">
                        <div class="py-2 border-r border-gray-100">
                            <div class="text-gray-400">UTC</div>
                        </div>
                        <div class="py-2 border-r border-gray-100">
                            <div class="text-gray-400">Mon 29</div>
                        </div>
                         <div class="py-2 border-r border-gray-100">
                            <div class="text-gray-400">Tue 30</div>
                        </div>
                         <div class="py-2 border-r border-gray-100">
                            <div class="text-gray-400">Wed 31</div>
                        </div>
                         <div class="py-2">
                            <div class="text-gray-400">Thu 1</div>
                        </div>
                    </div>
                    <div class="grid grid-cols-5 text-xs h-40 relative">
                        <!-- Time labels -->
                        <div class="border-r border-gray-100 text-right pr-2 py-2 text-gray-300 space-y-4">
                            <div>4AM</div>
                            <div>5AM</div>
                            <div>6AM</div>
                            <div>7AM</div>
                            <div>8AM</div>
                        </div>
                        <!-- Events -->
                        <div class="border-r border-gray-100 relative">
                             <div class="absolute top-8 left-1 right-1 h-8 bg-blue-100 border border-blue-200 rounded text-[10px] p-1 text-blue-700 truncate">Product syn...</div>
                        </div>
                        <div class="border-r border-gray-100 relative">
                             <div class="absolute top-12 left-1 right-1 h-12 bg-gray-100 border border-gray-200 rounded text-[10px] p-1 text-gray-500 truncate">[zoom] NO...</div>
                        </div>
                         <div class="border-r border-gray-100 relative">
                             <div class="absolute top-6 left-1 right-1 h-8 bg-gray-100 border border-gray-200 rounded text-[10px] p-1 text-gray-500 truncate">BE revie...</div>
                             <div class="absolute top-16 left-1 right-1 h-16 bg-orange-100 border border-orange-200 rounded text-[10px] p-1 text-orange-700 truncate">Coffee Ch...</div>
                        </div>
                         <div class="relative">
                             <div class="absolute top-20 left-1 right-1 h-12 bg-gray-100 border border-gray-200 rounded text-[10px] p-1 text-gray-500 truncate">Evan / J...</div>
                        </div>
                    </div>
                     <div class="bg-gray-50 px-3 py-2 border-t border-gray-200 text-xs text-gray-500 flex justify-between">
                        <span>Dec 29 - Jan 2</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

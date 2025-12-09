<script>
    // Testimonials Component
    const testimonials = [
        {
            name: "Camille Ricketts",
            handle: "@camillericketts",
            text: "Notion Mail let me create a system so customized to the way I work, my relationships, and my tone of voice that there's no way I could go back."
        },
        {
            name: "Aleks",
            handle: "@aleksliving",
            text: "OK: Notion Mail is pretty sick."
        },
        {
            name: "Mike Majara",
            handle: "@mikemajara",
            text: "@NotionMail deserves every bit of hype it's getting. The switch from Gmail is just natural for power users."
        },
        {
            name: "Rohit Ghumare",
            handle: "@ghumare64",
            text: "With @NotionMail's AI, unwanted spam, updates, promotions... I can focus on essential emails."
        }
    ];
</script>

<section class="py-16 overflow-hidden">
    <div class="flex gap-6 overflow-x-auto px-4 pb-8 md:justify-center no-scrollbar snap-x">
        {#each testimonials as t}
            <div class="flex-none w-[300px] md:w-[350px] p-6 bg-white border border-gray-100 rounded-xl shadow-sm snap-center">
                <div class="flex flex-col gap-4 h-full">
                    <div>
                        <div class="font-medium text-notion-black">{t.name}</div>
                        <div class="text-gray-400 text-sm">{t.handle}</div>
                    </div>
                    <p class="text-notion-gray text-[15px] leading-relaxed">
                        {t.text}
                    </p>
                </div>
            </div>
        {/each}
        <!-- Add a fade effect or just let it scroll. The screenshot shows them cut off on the right, implying scroll or just a grid. -->
    </div>
</section>

<style>
    .no-scrollbar::-webkit-scrollbar {
        display: none;
    }
    .no-scrollbar {
        -ms-overflow-style: none;
        scrollbar-width: none;
    }
</style>

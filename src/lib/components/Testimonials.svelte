<script>
    // Testimonials Component
    const testimonials = [
        {
            name: "Sarah Chen",
            handle: "@sarahcreates",
            text: "Youcap has completely transformed my content workflow. What used to take hours of manual transcription now takes minutes. Game changer for creators!",
            image: "/generated/image-young-female-youtuber-smiling-at-camera--1765660420065-1.webp"
        },
        {
            name: "Marcus Rodriguez",
            handle: "@marcustech",
            text: "The AI transcription accuracy is incredible. Even handles technical jargon perfectly. Best tool I've found for repurposing video content.",
            image: "/generated/image-male-podcaster-with-headphones-recording-1765660422269-2.webp"
        },
        {
            name: "Emma Thompson",
            handle: "@emmavlogs",
            text: "As a full-time content creator, Youcap saves me 10+ hours every week. The searchable transcripts make finding specific moments so easy.",
            image: "/generated/image-asian-female-educator-teaching-online-wi-1765660424449-3.webp"
        },
        {
            name: "David Park",
            handle: "@davidontech",
            text: "Finally, a transcription tool that actually understands context. The AI insights help me create better content from my videos.",
            image: "/generated/image-tech-reviewer-at-desk-with-camera-equipm-1765660426463-4.webp"
        }
    ];
</script>

<section class="py-16 overflow-hidden">
    <div class="flex gap-6 overflow-x-auto px-4 pb-8 md:justify-center no-scrollbar snap-x">
        {#each testimonials as t}
            <div class="flex-none w-[300px] md:w-[350px] p-6 bg-white border border-gray-100 rounded-xl shadow-sm snap-center">
                <div class="flex flex-col gap-4 h-full">
                    <div class="flex items-center gap-3">
                        <img src={t.image} alt={t.name} class="w-12 h-12 rounded-full object-cover" />
                        <div>
                            <div class="font-medium text-notion-black">{t.name}</div>
                            <div class="text-gray-400 text-sm">{t.handle}</div>
                        </div>
                    </div>
                    <p class="text-notion-gray text-[15px] leading-relaxed">
                        {t.text}
                    </p>
                </div>
            </div>
        {/each}
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

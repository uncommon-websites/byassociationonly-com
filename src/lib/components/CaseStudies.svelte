<script lang="ts">
    export let image = "https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?q=80&w=1000&auto=format&fit=crop";
</script>

<section class="py-20 md:py-32 px-8 max-w-[1600px] mx-auto text-white">
    <div class="flex flex-col md:flex-row justify-between items-start">
        <div class="w-full md:w-1/3 mb-16 md:mb-0 sticky top-32">
            <h2 class="text-4xl md:text-6xl font-serif leading-tight">
                Shopify Plus <br />
                <span class="serif-italic">Case Studies.</span>
            </h2>
        </div>
        
        <div class="w-full md:w-[60%] pl-0 md:pl-10">
            <div class="relative group cursor-pointer overflow-hidden">
                <div class="aspect-[4/5] md:aspect-[3/3.5] overflow-hidden">
                    <img src={image} alt="P448 Case Study" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" />
                </div>
                <!-- Overlay Content -->
                <div class="absolute bottom-0 left-0 p-8 md:p-12 w-full bg-gradient-to-t from-black/60 via-black/30 to-transparent">
                    <h3 class="text-3xl font-bold font-serif mb-3">P448</h3>
                    <p class="text-sm md:text-base text-gray-200 max-w-sm mb-8 leading-relaxed">
                        An award-winning, boundary pushing design makeover for luxury sneaker brand P448.
                    </p>
                    <div class="flex items-center gap-3 text-[11px] uppercase tracking-widest font-medium">
                        <span>View case study</span>
                        <div class="w-8 h-8 rounded-full border border-white/30 flex items-center justify-center group-hover:border-white transition-colors">
                            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

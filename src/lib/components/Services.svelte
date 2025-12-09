<script lang="ts">
    const services = [
        "UI/UX Design",
        "Web Development",
        "Replatforming",
        "Data Migration",
        "eCommerce Strategy"
    ];
    
    const secondaryServices = ["CRO", "SEO"];
</script>

<section class="py-20 md:py-32 px-8 border-t border-white/10 text-white">
    <div class="max-w-[1600px] mx-auto flex flex-col md:flex-row justify-between">
        <div class="w-full md:w-2/3">
            <ul class="flex flex-col gap-2">
                {#each services as service}
                    <li class="text-4xl md:text-6xl lg:text-[5rem] font-serif leading-[1.1] text-white hover:text-gray-300 transition-colors duration-300 cursor-pointer">
                        {service}
                    </li>
                {/each}
                {#each secondaryServices as service}
                    <li class="text-4xl md:text-6xl lg:text-[5rem] font-serif leading-[1.1] text-gray-600 hover:text-white transition-colors duration-300 cursor-pointer">
                        {service}
                    </li>
                {/each}
            </ul>
        </div>
        
        <div class="w-full md:w-1/3 mt-16 md:mt-0 flex flex-col justify-between items-end">
            <div class="max-w-xs text-right">
                <p class="text-xs md:text-[13px] text-gray-400 mb-8 leading-relaxed font-light tracking-wide">
                    By Association Only architects the world's leading design-led Shopify solutions, so that merchant growth is on-brand and limitless.
                </p>
                <div class="flex items-center justify-end gap-3 text-[11px] uppercase tracking-widest font-medium cursor-pointer group">
                    <span>View our services</span>
                    <div class="w-6 h-6 rounded-full border border-white/30 flex items-center justify-center group-hover:border-white transition-colors">
                        <svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<script lang="ts">
    const clients = [
        "Victoria Beckham", "Db", "Toteme", "Condé Nast",
        "Roland Mouret", "Joseph", "Astrid & Miyu", "Self-Portrait",
        "Temperley London", "Anya Hindmarch", "Bremont", "Susanne Kaufmann",
        "Lumene", "The Frankie Shop", "Billionaire Boys Club", "Globe-Trotter",
        "Goodhood", "Cubitts", "Omorovicza", "Thrudark",
        "Wild Nutrition", "Oh Polly", "Holland Cooper", "Lulu Guinness",
        "Abask", "Skinnydip", "Purelei", "Daniella Draper"
    ];
</script>

<section class="border-t border-white/10">
    <div class="grid grid-cols-2 md:grid-cols-4 border-l border-white/10">
        {#each clients as client}
            <div class="aspect-[3/2] border-r border-b border-white/10 flex items-center justify-center p-8 group hover:bg-white/5 transition-colors cursor-pointer">
                <span class="font-serif uppercase tracking-widest text-center text-[10px] md:text-xs text-gray-400 group-hover:text-white transition-colors">
                    {client}
                </span>
            </div>
        {/each}
    </div>
</section>

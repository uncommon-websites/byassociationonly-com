<script lang="ts">
    import { onMount } from 'svelte';

    let isScrolled = false;

    onMount(() => {
        const handleScroll = () => {
            isScrolled = window.scrollY > 50;
        };
        window.addEventListener('scroll', handleScroll);
        return () => window.removeEventListener('scroll', handleScroll);
    });
</script>

<header class="fixed top-0 left-0 w-full z-50 px-8 py-8 flex justify-between items-start mix-blend-difference text-white">
    <a href="/" class="text-sm font-medium tracking-wide z-50 mt-1">
        By Association <span class="font-serif italic">Only.</span>
    </a>

    <nav class="hidden md:flex items-center gap-8 text-[13px] font-medium tracking-wide absolute left-1/2 -translate-x-1/2 mt-1">
        <a href="/services" class="hover:opacity-60 transition-opacity">Services</a>
        <a href="/about" class="hover:opacity-60 transition-opacity">About</a>
        <a href="/case-studies" class="hover:opacity-60 transition-opacity">Case studies</a>
        <a href="/articles" class="hover:opacity-60 transition-opacity">Articles</a>
        <a href="/contact" class="hover:opacity-60 transition-opacity">Contact</a>
    </nav>

    <a href="/careers" class="hidden md:flex items-center gap-2 text-[13px] font-medium tracking-wide group z-50">
        Careers
        <span class="flex items-center justify-center w-5 h-5 rounded-full border border-white/40 text-[10px] group-hover:border-white transition-colors pt-[1px]">1</span>
    </a>
    
    <!-- Mobile Menu Button Placeholder -->
    <button class="md:hidden text-white mt-1">Menu</button>
</header>

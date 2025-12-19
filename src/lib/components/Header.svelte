<script lang="ts">
	// Removed lucide-svelte import
</script>

<header class="w-full py-8 px-12 flex justify-between items-center sticky top-0 z-50 bg-cream/95 backdrop-blur-sm transition-all duration-300">
	<!-- Left Nav -->
	<nav class="hidden md:flex gap-8 items-center">
		<a href="/portfolio" class="font-sans text-[11px] tracking-[0.2em] font-medium hover:opacity-70 transition-opacity">PORTFOLIO</a>
		<a href="/shop" class="font-sans text-[11px] tracking-[0.2em] font-medium hover:opacity-70 transition-opacity">SHOP</a>
		<a href="/about" class="font-sans text-[11px] tracking-[0.2em] font-medium hover:opacity-70 transition-opacity">ABOUT</a>
	</nav>

	<!-- Logo -->
	<div class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 text-center">
		<a href="/" class="text-3xl lg:text-4xl tracking-wide text-espresso whitespace-nowrap">MOLLY KIDD STUDIO</a>
	</div>

	<!-- Right Nav -->
	<nav class="hidden md:flex gap-8 items-center ml-auto">
		<a href="/inquire" class="font-sans text-[11px] tracking-[0.2em] font-medium hover:opacity-70 transition-opacity">INQUIRE</a>
		<a href="/socials" class="font-sans text-[11px] tracking-[0.2em] font-medium hover:opacity-70 transition-opacity">SOCIALS</a>
		<a href="/cart" class="hover:opacity-70 transition-opacity">
			<svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M6 2 3 6v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V6l-3-4Z"/><path d="M3 6h18"/><path d="M16 10a4 4 0 0 1-8 0"/></svg>
		</a>
	</nav>

	<!-- Mobile Menu Button (Hidden on desktop) -->
	<button class="md:hidden ml-auto">
		<span class="sr-only">Menu</span>
		<svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
	</button>
</header>

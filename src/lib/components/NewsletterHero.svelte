<script lang="ts">
    const bgImage = "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?q=80&w=2074&auto=format&fit=crop";
</script>

<section class="w-full relative h-[80vh] min-h-[600px] flex items-center justify-center overflow-hidden">
    <!-- Background Image -->
    <div class="absolute inset-0 w-full h-full">
        <img src={bgImage} alt="Molly's World" class="w-full h-full object-cover" />
        <!-- Dark Overlay for text readability -->
        <div class="absolute inset-0 bg-black/20"></div>
    </div>

    <!-- Content -->
    <div class="relative z-10 text-center text-white px-4 max-w-4xl mx-auto flex flex-col items-center">
        <h2 class="text-4xl md:text-6xl tracking-wide mb-4 font-normal">STEP INTO MOLLY'S WORLD</h2>
        <p class="text-xl md:text-2xl font-light italic mb-10 opacity-90">
            Get exclusive access to behind-the-scenes moments, new collections, and studio updates.
        </p>
        
        <button class="border border-white px-10 py-3 text-sm tracking-[0.2em] uppercase hover:bg-white hover:text-black transition-colors duration-300">
            ENTER
        </button>
    </div>
</section>

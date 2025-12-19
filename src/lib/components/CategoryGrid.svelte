<script lang="ts">
    // Placeholders for grid images
    const portfolio1 = "https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?q=80&w=1000&auto=format&fit=crop";
    const portfolio2 = "https://images.unsplash.com/photo-1584622050111-993a426fbf0a?q=80&w=1000&auto=format&fit=crop";
    const shop1 = "https://images.unsplash.com/photo-1513519245088-0e12902e5a38?q=80&w=1000&auto=format&fit=crop";
    const shop2 = "https://images.unsplash.com/photo-1595428774223-ef52624120d2?q=80&w=1000&auto=format&fit=crop";
</script>

<section class="w-full max-w-[1200px] mx-auto px-6 md:px-12 pb-32">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-16 md:gap-24">
        
        <!-- Portfolio Column -->
        <div class="flex flex-col items-center">
            <div class="flex w-full gap-1 mb-6">
                <div class="w-1/2 aspect-[4/5] relative border border-[#8B8B8B]/30 p-1">
                    <img src={portfolio1} alt="Portfolio Interior 1" class="w-full h-full object-cover" />
                </div>
                <div class="w-1/2 aspect-[4/5] relative border border-[#8B8B8B]/30 p-1">
                    <img src={portfolio2} alt="Portfolio Interior 2" class="w-full h-full object-cover" />
                </div>
            </div>
            <h3 class="text-xl tracking-[0.05em] uppercase text-espresso">PORTFOLIO</h3>
        </div>

        <!-- Shop Column -->
        <div class="flex flex-col items-center">
            <div class="flex w-full gap-1 mb-6">
                <div class="w-1/2 aspect-[4/5] relative border border-[#8B8B8B]/30 p-1">
                    <img src={shop1} alt="Shop Item 1" class="w-full h-full object-cover" />
                </div>
                <div class="w-1/2 aspect-[4/5] relative border border-[#8B8B8B]/30 p-1">
                    <img src={shop2} alt="Shop Item 2" class="w-full h-full object-cover" />
                </div>
            </div>
            <h3 class="text-xl tracking-[0.05em] uppercase text-espresso">SHOP</h3>
        </div>

    </div>
</section>

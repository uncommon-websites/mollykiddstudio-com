<script lang="ts">
    // Removed lucide-svelte imports
    
    // Using simple square icons to match the screenshot
    // The screenshot has small square bullets.
</script>

<footer class="w-full bg-cream pt-24 pb-12 px-6 md:px-12 border-t border-transparent">
    <div class="max-w-[1400px] mx-auto">
        
        <!-- Top Section: Links -->
        <div class="grid grid-cols-1 md:grid-cols-4 gap-12 mb-32">
            <!-- Column 1 -->
            <div class="flex flex-col gap-3">
                <a href="/portfolio" class="text-espresso hover:opacity-70 text-[15px] font-light">Portfolio</a>
                <a href="/shop" class="text-espresso hover:opacity-70 text-[15px] font-light">Shop</a>
                <a href="/about" class="text-espresso hover:opacity-70 text-[15px] font-light">About</a>
                <a href="/inquire" class="text-espresso hover:opacity-70 text-[15px] font-light">Inquire</a>
                <a href="/substack" class="text-espresso hover:opacity-70 text-[15px] font-light">Substack</a>
                <a href="/blog" class="text-espresso hover:opacity-70 text-[15px] font-light">Blog</a>
            </div>

            <!-- Column 2 -->
            <div class="flex flex-col gap-3">
                <a href="/shipping" class="text-espresso hover:opacity-70 text-[15px] font-light">Shipping & Returns</a>
                <a href="/trade" class="text-espresso hover:opacity-70 text-[15px] font-light">Trade Program</a>
                <a href="/terms" class="text-espresso hover:opacity-70 text-[15px] font-light">Terms & Conditions</a>
            </div>

            <!-- Column 3 (Socials) -->
            <div class="flex flex-col gap-3 md:col-start-4">
                <a href="#" class="flex items-center gap-3 text-espresso hover:opacity-70 text-[15px] font-light group">
                    <span class="w-2 h-2 border border-espresso flex items-center justify-center group-hover:bg-espresso transition-colors">
                        <span class="w-1 h-1 bg-espresso opacity-0 group-hover:opacity-100"></span>
                    </span>
                    Instagram
                </a>
                <a href="#" class="flex items-center gap-3 text-espresso hover:opacity-70 text-[15px] font-light group">
                    <span class="w-2 h-2 border border-espresso flex items-center justify-center group-hover:bg-espresso transition-colors"></span>
                    Pinterest
                </a>
                <a href="#" class="flex items-center gap-3 text-espresso hover:opacity-70 text-[15px] font-light group">
                    <span class="w-2 h-2 border border-espresso flex items-center justify-center group-hover:bg-espresso transition-colors"></span>
                    TikTok
                </a>
                <a href="mailto:studio@mollykiddstudio.com" class="flex items-center gap-3 text-espresso hover:opacity-70 text-[15px] font-light group mt-1">
                    <span class="w-2 h-2 border border-espresso flex items-center justify-center group-hover:bg-espresso transition-colors"></span>
                    studio@mollykiddstudio.com
                </a>
                <a href="mailto:shop@mollykiddstudio.com" class="flex items-center gap-3 text-espresso hover:opacity-70 text-[15px] font-light group">
                    <span class="w-2 h-2 border border-espresso flex items-center justify-center group-hover:bg-espresso transition-colors"></span>
                    shop@mollykiddstudio.com
                </a>
            </div>
        </div>

        <!-- Bottom Section -->
        <div class="flex flex-col md:flex-row justify-between items-end border-t border-transparent pt-8 gap-12 md:gap-0">
            
            <!-- Logo -->
            <div class="w-full md:w-auto">
                <h1 class="text-4xl md:text-6xl tracking-wide text-espresso">MOLLY KIDD STUDIO</h1>
            </div>

            <!-- Newsletter & Copyright -->
            <div class="w-full md:w-auto flex flex-col items-start md:items-end gap-6">
                
                <!-- Newsletter Form -->
                <form class="flex items-end gap-4 w-full md:w-auto">
                    <input 
                        type="email" 
                        placeholder="Email address" 
                        class="bg-transparent border-b border-espresso/30 pb-2 w-full md:w-64 focus:outline-none focus:border-espresso placeholder:text-espresso/40 font-light text-lg"
                    />
                    <button type="submit" class="bg-[#2A221C] text-white px-4 py-1 text-xs tracking-widest uppercase hover:bg-opacity-90">
                        OK
                    </button>
                </form>

                <!-- Copyright -->
                <div class="text-[13px] text-espresso/60 font-light tracking-wide flex gap-2">
                    <span>© Molly Kidd Studio 2025</span>
                    <span>|</span>
                    <a href="#" class="hover:text-espresso">Site Credits</a>
                </div>
            </div>

        </div>
    </div>
</footer>

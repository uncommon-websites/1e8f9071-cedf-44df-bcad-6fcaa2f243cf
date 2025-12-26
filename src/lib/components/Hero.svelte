<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<section class="pt-32 pb-16 overflow-hidden">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="max-w-4xl mx-auto text-center mb-16">
      <h1 class="text-5xl md:text-6xl font-semibold tracking-tight text-gray-900 mb-6 leading-[1.1]">
        Fair financial relief for essential workers, powered by payroll
      </h1>
      <p class="text-xl text-gray-600 mb-10 max-w-2xl mx-auto leading-relaxed">
        Patch connects employer payroll data to regulated financial partners, delivering transparent, no-debt support when employees need it most.
      </p>
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
        <Button variant="primary" size="lg" class="rounded-full px-8">Contact sales</Button>
        <Button variant="outline" size="lg" class="rounded-full px-8">Learn more</Button>
      </div>
    </div>

    <!-- Logos Strip -->
    <div class="mb-12">
      <p class="text-xs font-semibold text-gray-500 uppercase tracking-wider mb-6 text-left sm:ml-4">Trusted by employers in<br>essential industries</p>
      <div class="flex flex-wrap items-center justify-between gap-8 opacity-60 grayscale px-4">
        <!-- Industry placeholders -->
        <span class="text-2xl font-bold font-sans tracking-tighter">Restaurant Group</span>
        <span class="text-2xl font-bold font-sans tracking-tighter">Healthcare</span>
        <span class="text-2xl font-bold font-sans tracking-tighter">Retail Chain</span>
        <span class="text-2xl font-bold font-sans tracking-tighter">Hospitality</span>
        <span class="text-2xl font-bold font-sans tracking-tighter">Services</span>
      </div>
    </div>

    <!-- Hero Image -->
    <div class="relative rounded-2xl overflow-hidden shadow-2xl bg-gray-100">
      <img 
        src="/generated/image-essential-workers-in-restaurant-kitchen--1766769625839-0.webp" 
        alt="Essential workers collaborating in restaurant kitchen" 
        class="w-full h-[600px] object-cover object-center"
      />
      
      <!-- Floating UI Elements -->
      <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 flex flex-col gap-4">
        <!-- Notification 1 -->
        <div class="bg-white/90 backdrop-blur-sm p-4 rounded-xl shadow-lg flex items-center gap-4 animate-in fade-in slide-in-from-bottom-4 duration-700">
          <div class="w-10 h-10 bg-gray-900 rounded-full flex items-center justify-center text-white">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2v20M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"></path></svg>
          </div>
          <div>
            <div class="text-sm font-semibold text-gray-900">Relief available</div>
            <div class="text-xs text-gray-500">$250 linked to your next paycheck</div>
          </div>
        </div>

        <!-- Notification 2 -->
        <div class="bg-white/90 backdrop-blur-sm p-4 rounded-xl shadow-lg flex items-center gap-4 ml-12 animate-in fade-in slide-in-from-bottom-4 duration-1000 delay-300">
          <div class="w-10 h-10 bg-green-600 rounded-full flex items-center justify-center text-white">
             <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
          </div>
          <div>
            <div class="text-sm font-semibold text-gray-900">Payroll synced</div>
            <div class="text-xs text-gray-500">No fees, no interest, no debt trap</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

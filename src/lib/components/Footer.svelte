<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<footer class="bg-white pt-24 pb-12 border-t border-gray-100">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-8 mb-16">
      <!-- Column 1 -->
      <div class="flex flex-col gap-4">
        <h4 class="font-semibold text-gray-900 text-sm">For Employers</h4>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Overview</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">How It Works</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Pricing</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Case Studies</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">ROI Calculator</a>
      </div>

      <!-- Column 2 -->
      <div class="flex flex-col gap-4">
        <h4 class="font-semibold text-gray-900 text-sm">For Employees</h4>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Overview</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Access Relief</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">How It Works</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">FAQs</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Financial Wellness</a>
      </div>

      <!-- Column 3 -->
      <div class="flex flex-col gap-4">
        <h4 class="font-semibold text-gray-900 text-sm">Platform</h4>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Integrations</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Security</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Compliance</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">API Docs</a>
      </div>

      <!-- Column 4 -->
      <div class="flex flex-col gap-4">
        <h4 class="font-semibold text-gray-900 text-sm">Company</h4>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">About Us</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Team</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Careers</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Press</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Contact</a>
      </div>

       <!-- Column 5 -->
      <div class="flex flex-col gap-4">
        <h4 class="font-semibold text-gray-900 text-sm">Resources</h4>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Blog</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Guides</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Webinars</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Research</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Support</a>
      </div>

       <!-- Column 6 (Newsletter) -->
      <div class="flex flex-col gap-4 lg:col-span-1">
        <h4 class="font-semibold text-gray-900 text-sm">Newsletter</h4>
        <p class="text-sm text-gray-500">Stay up to date with Patch through weekly updates to your inbox.</p>
        <div class="flex flex-col gap-2">
           <Button variant="secondary" size="sm" class="w-full !bg-black !text-white !rounded-lg">Sign up</Button>
        </div>
      </div>
    </div>

    <!-- Bottom -->
    <div class="pt-8 border-t border-gray-100 flex flex-col md:flex-row justify-between items-center gap-4">
      <div class="flex items-center gap-2">
         <svg width="24" height="24" viewBox="0 0 68 68" fill="none" xmlns="http://www.w3.org/2000/svg">
           <path d="M24.6991 11.9792C24.6991 18.595 19.3425 23.9583 12.7348 23.9583C6.12711 23.9583 0.770508 18.595 0.770508 11.9792C0.770508 5.36331 6.12711 0 12.7348 0C19.3425 0 24.6991 5.36331 24.6991 11.9792Z" fill="#0A0D12"/>
           <path d="M24.6991 55.1042C24.6991 61.72 19.3425 67.0833 12.7348 67.0833C6.12711 67.0833 0.770508 61.72 0.770508 55.1042C0.770508 48.4883 6.12711 43.125 12.7348 43.125C19.3425 43.125 24.6991 48.4883 24.6991 55.1042Z" fill="#0A0D12"/>
           <path d="M67.7704 11.9792C67.7704 18.595 62.4137 23.9583 55.8061 23.9583C49.1984 23.9583 43.8418 18.595 43.8418 11.9792C43.8418 5.36331 49.1984 0 55.8061 0C62.4137 0 67.7704 5.36331 67.7704 11.9792Z" fill="#0A0D12"/>
           <path d="M67.7704 55.1042C67.7704 61.72 62.4137 67.0833 55.8061 67.0833C49.1984 67.0833 43.8418 61.72 43.8418 55.1042C43.8418 48.4883 49.1984 43.125 55.8061 43.125C62.4137 43.125 67.7704 48.4883 67.7704 55.1042Z" fill="#0A0D12"/>
         </svg>
         <span class="text-sm text-gray-500">© 2025 Patch</span>
      </div>

      <div class="flex flex-col md:flex-row items-center gap-4 text-xs text-gray-500 text-center md:text-right">
        <p class="max-w-md">
           By clicking "Accept", you agree to the use of cookies on your device or browser to enhance site navigation, analyze site usage, and assist in our marketing efforts.
        </p>
        <div class="flex gap-4">
           <Button variant="primary" size="sm" class="!text-xs !py-1 !h-8">Accept all cookies</Button>
           <Button variant="outline" size="sm" class="!text-xs !py-1 !h-8">Cookie settings</Button>
        </div>
      </div>
    </div>
    
    <div class="mt-4 flex justify-end gap-6 text-xs text-gray-500">
       <a href="#" class="hover:text-gray-900">Privacy Statement</a>
       <a href="#" class="hover:text-gray-900">Terms of Service</a>
    </div>
  </div>
</footer>

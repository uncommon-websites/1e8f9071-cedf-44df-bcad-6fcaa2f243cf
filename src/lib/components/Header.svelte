<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<header class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur-md border-b border-gray-100">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-16">
      <!-- Logo and Nav -->
      <div class="flex items-center gap-8">
        <a href="/" class="flex items-center gap-2">
          <!-- Patch Logo -->
          <svg width="32" height="32" viewBox="0 0 68 68" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M24.6991 11.9792C24.6991 18.595 19.3425 23.9583 12.7348 23.9583C6.12711 23.9583 0.770508 18.595 0.770508 11.9792C0.770508 5.36331 6.12711 0 12.7348 0C19.3425 0 24.6991 5.36331 24.6991 11.9792Z" fill="#0A0D12"/>
            <path d="M24.6991 55.1042C24.6991 61.72 19.3425 67.0833 12.7348 67.0833C6.12711 67.0833 0.770508 61.72 0.770508 55.1042C0.770508 48.4883 6.12711 43.125 12.7348 43.125C19.3425 43.125 24.6991 48.4883 24.6991 55.1042Z" fill="#0A0D12"/>
            <path d="M67.7704 11.9792C67.7704 18.595 62.4137 23.9583 55.8061 23.9583C49.1984 23.9583 43.8418 18.595 43.8418 11.9792C43.8418 5.36331 49.1984 0 55.8061 0C62.4137 0 67.7704 5.36331 67.7704 11.9792Z" fill="#0A0D12"/>
            <path d="M67.7704 55.1042C67.7704 61.72 62.4137 67.0833 55.8061 67.0833C49.1984 67.0833 43.8418 61.72 43.8418 55.1042C43.8418 48.4883 49.1984 43.125 55.8061 43.125C62.4137 43.125 67.7704 48.4883 67.7704 55.1042Z" fill="#0A0D12"/>
          </svg>
          <span class="font-bold text-xl tracking-tight">Patch</span>
        </a>

        <nav class="hidden md:flex items-center gap-6">
          <a href="#employers" class="text-sm font-medium text-gray-600 hover:text-gray-900">For Employers</a>
          <a href="#how-it-works" class="text-sm font-medium text-gray-600 hover:text-gray-900">How It Works</a>
          <a href="#about" class="text-sm font-medium text-gray-600 hover:text-gray-900">About</a>
          <a href="#team" class="text-sm font-medium text-gray-600 hover:text-gray-900">Team</a>
        </nav>
      </div>

      <!-- Right Actions -->
      <div class="flex items-center gap-4">
        <a href="#login" class="text-sm font-medium text-gray-600 hover:text-gray-900 hidden sm:block">Log in</a>
        <Button variant="secondary" size="sm" class="!bg-black !text-white !rounded-full px-5">Contact sales</Button>
      </div>
    </div>
  </div>
</header>

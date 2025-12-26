<script lang="ts">
  import Header from "$lib/components/Header.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Stats from "$lib/components/Stats.svelte";
  import Steps from "$lib/components/Steps.svelte";
  import FeatureSection from "$lib/components/FeatureSection.svelte";
  import CaseStudies from "$lib/components/CaseStudies.svelte";
  import Integrations from "$lib/components/Integrations.svelte";
  import Resources from "$lib/components/Resources.svelte";
  import BottomCTA from "$lib/components/BottomCTA.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<Header />

<main>
  <Hero />
  <Stats />
  <Steps />
  
  <!-- Feature 1: Seamless Payroll Integration -->
  <FeatureSection 
    title="Seamless integration with your existing payroll systems"
    subtitle="INTEGRATION-FIRST INFRASTRUCTURE"
    linkText="View integrations"
    bullets={[
      "Connect to major payroll providers in minutes",
      "Real-time data synchronization",
      "No disruption to existing workflows",
      "Secure, encrypted data transmission"
    ]}
  >
    <div slot="description">
      <p>Patch connects directly to your payroll system, enabling fair financial relief without adding complexity to your operations.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center">
      <!-- Payroll Integration Visual -->
      <div class="bg-white rounded-xl shadow-lg p-6 w-[80%] max-w-sm relative">
        <div class="flex items-center gap-2 mb-4">
          <div class="w-8 h-8 rounded-full bg-primary-100 flex items-center justify-center text-primary-600 font-bold">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
          </div>
          <div class="text-sm font-semibold">Payroll Connected</div>
        </div>
        <div class="space-y-3">
          <div class="h-2 bg-gray-100 rounded w-full relative overflow-hidden">
            <div class="h-full bg-primary-600 rounded w-full"></div>
          </div>
          <div class="p-3 bg-green-50 rounded-lg border border-green-100">
             <div class="flex items-center gap-2 mb-2">
               <div class="w-6 h-6 bg-green-500 rounded-full flex items-center justify-center text-white text-xs">✓</div>
               <div class="text-xs font-semibold text-green-800">Sync Complete</div>
             </div>
             <div class="text-xs text-green-700">125 employees now have access to fair financial relief</div>
          </div>
        </div>
        
        <!-- Floating elements -->
        <div class="absolute -right-12 top-10 bg-white p-3 rounded-lg shadow-md flex items-center gap-2">
           <div class="w-6 h-6 bg-gray-900 rounded-full flex items-center justify-center text-white text-xs">⚡</div>
           <div class="text-xs font-medium">Real-time sync</div>
        </div>
      </div>
    </div>
  </FeatureSection>

  <!-- Feature 2: Fair Financial Relief -->
  <FeatureSection 
    title="Fair financial relief with no debt traps"
    subtitle=""
    linkText="How it works"
    reversed={true}
    bullets={[
      "Zero interest rates—no hidden fees",
      "Transparent terms linked to payroll",
      "Regulated financial partners",
      "No credit checks or predatory lending"
    ]}
  >
    <div slot="description">
      <p>Employees access the support they need without falling into debt cycles. Every dollar is linked to earned wages, ensuring fair and transparent relief.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center">
       <!-- Fair Relief Diagram -->
       <div class="flex flex-col items-center gap-4">
         <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 w-64 flex items-center gap-3">
            <div class="w-8 h-8 bg-primary-100 rounded flex items-center justify-center text-primary-600">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2v20M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"></path></svg>
            </div>
            <div class="text-sm">
               <div class="font-semibold">Employee Request</div>
               <div class="text-xs text-gray-500">$250 needed for emergency</div>
            </div>
         </div>
         <div class="h-8 w-px bg-gray-300"></div>
         <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 w-64 flex items-center gap-3">
            <div class="w-8 h-8 bg-green-100 rounded flex items-center justify-center text-green-600">✓</div>
            <div class="text-sm">
               <div class="font-semibold">Payroll Verification</div>
               <div class="text-xs text-gray-500">Linked to next paycheck</div>
            </div>
         </div>
         <div class="h-8 w-px bg-gray-300"></div>
         <div class="bg-green-50 p-2 rounded-full text-xs text-green-700 font-medium px-4 border border-green-100">
            0% Interest • No Fees
         </div>
       </div>
    </div>
  </FeatureSection>

  <!-- Feature 3: Employee Experience -->
  <FeatureSection 
    title="Simple, transparent experience for employees"
    subtitle=""
    linkText="Employee portal"
    bullets={[
      "Easy mobile access to relief funds",
      "Clear visibility into payroll deductions",
      "No surprise fees or hidden charges",
      "Financial wellness education and resources"
    ]}
  >
    <div slot="description">
      <p>Employees see exactly what they're getting, when they'll repay, and how it connects to their paycheck—complete transparency at every step.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center">
       <!-- Mobile App UI -->
       <div class="bg-white rounded-2xl shadow-lg p-4 w-64 space-y-4">
          <div class="flex items-center gap-3 p-2 hover:bg-gray-50 rounded-lg">
             <div class="w-10 h-10 bg-green-600 rounded-lg flex items-center justify-center text-white">
               <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
             </div>
             <div>
                <div class="text-xs font-bold">Relief Available</div>
                <div class="text-[10px] text-gray-500">$250 linked to next paycheck</div>
             </div>
          </div>
          <div class="flex items-center gap-3 p-2 hover:bg-gray-50 rounded-lg">
             <div class="w-10 h-10 bg-primary-600 rounded-lg flex items-center justify-center text-white">
               <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2v20M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"></path></svg>
             </div>
             <div>
                <div class="text-xs font-bold">0% Interest</div>
                <div class="text-[10px] text-gray-500">No fees, no hidden charges</div>
             </div>
          </div>
          <div class="flex items-center gap-3 p-2 hover:bg-gray-50 rounded-lg">
             <div class="w-10 h-10 bg-gray-900 rounded-lg flex items-center justify-center text-white">
               <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
             </div>
             <div>
                <div class="text-xs font-bold">Next Payday</div>
                <div class="text-[10px] text-gray-500">Automatic deduction: $250</div>
             </div>
          </div>
       </div>
    </div>
  </FeatureSection>

  <!-- Feature 4: Employer Dashboard -->
  <FeatureSection 
    title="Powerful dashboard for employer insights"
    subtitle=""
    linkText="View demo"
    reversed={true}
    bullets={[
      "Track employee financial wellness metrics",
      "Monitor program adoption and usage",
      "Reduce turnover with better benefits",
      "Simple reporting and compliance tools"
    ]}
  >
    <div slot="description">
      <p>Employers gain visibility into how financial relief programs improve retention, reduce stress, and build a stronger workforce.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center">
       <!-- Dashboard Mockup -->
       <div class="bg-white rounded-xl shadow-lg w-[80%] overflow-hidden border border-gray-100">
          <div class="bg-gray-50 p-3 border-b border-gray-100 flex items-center gap-2">
             <div class="w-3 h-3 rounded-full bg-red-400"></div>
             <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
             <div class="w-3 h-3 rounded-full bg-green-400"></div>
          </div>
          <div class="p-6">
             <div class="flex items-center gap-2 mb-4">
                <svg width="24" height="24" viewBox="0 0 68 68" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M24.6991 11.9792C24.6991 18.595 19.3425 23.9583 12.7348 23.9583C6.12711 23.9583 0.770508 18.595 0.770508 11.9792C0.770508 5.36331 6.12711 0 12.7348 0C19.3425 0 24.6991 5.36331 24.6991 11.9792Z" fill="#0A0D12"/>
                  <path d="M24.6991 55.1042C24.6991 61.72 19.3425 67.0833 12.7348 67.0833C6.12711 67.0833 0.770508 61.72 0.770508 55.1042C0.770508 48.4883 6.12711 43.125 12.7348 43.125C19.3425 43.125 24.6991 48.4883 24.6991 55.1042Z" fill="#0A0D12"/>
                  <path d="M67.7704 11.9792C67.7704 18.595 62.4137 23.9583 55.8061 23.9583C49.1984 23.9583 43.8418 18.595 43.8418 11.9792C43.8418 5.36331 49.1984 0 55.8061 0C62.4137 0 67.7704 5.36331 67.7704 11.9792Z" fill="#0A0D12"/>
                  <path d="M67.7704 55.1042C67.7704 61.72 62.4137 67.0833 55.8061 67.0833C49.1984 67.0833 43.8418 61.72 43.8418 55.1042C43.8418 48.4883 49.1984 43.125 55.8061 43.125C62.4137 43.125 67.7704 48.4883 67.7704 55.1042Z" fill="#0A0D12"/>
                </svg>
                <div class="text-xs font-semibold">Patch Employer Dashboard</div>
             </div>
             <div class="text-sm font-bold mb-2">Financial Wellness Overview</div>
             <div class="space-y-2 text-xs text-gray-600">
                <div class="flex justify-between p-2 bg-green-50 rounded">
                   <span>Active employees</span>
                   <span class="font-semibold">89 of 125</span>
                </div>
                <div class="flex justify-between p-2 bg-primary-50 rounded">
                   <span>Avg. relief accessed</span>
                   <span class="font-semibold">$185/month</span>
                </div>
                <div class="flex justify-between p-2 bg-gray-50 rounded">
                   <span>Employee satisfaction</span>
                   <span class="font-semibold">4.8/5.0</span>
                </div>
             </div>
          </div>
       </div>
    </div>
  </FeatureSection>

  <!-- Feature 5: Impact on Retention -->
  <FeatureSection 
    title="Reduce turnover with financial wellness benefits"
    subtitle=""
    linkText="View case studies"
    bullets={[
      "Lower employee turnover rates",
      "Improved workplace satisfaction",
      "Attract top talent with better benefits",
      "Measurable ROI on wellness programs"
    ]}
  >
    <div slot="description">
      <p>Essential industry employers see dramatic improvements in retention when employees have access to fair financial relief during cash flow gaps.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center px-8">
       <!-- Chart -->
       <div class="w-full h-64 flex items-end justify-between gap-2">
          {#each [40, 45, 50, 55, 60, 65, 70, 75, 80, 85, 88, 90] as height}
             <div class="w-full bg-primary-100 rounded-t-sm relative group">
                <div style="height: {height}%" class="absolute bottom-0 w-full bg-primary-600 rounded-t-sm transition-all duration-500 group-hover:bg-primary-700"></div>
             </div>
          {/each}
       </div>
       <!-- Legend overlay -->
       <div class="absolute top-12 right-12 bg-white p-4 rounded-lg shadow-sm border border-gray-100 text-xs">
          <div class="flex justify-between gap-8 mb-1">
             <span class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-primary-600"></span> Employee retention</span>
             <span class="font-semibold">+35%</span>
          </div>
          <div class="flex justify-between gap-8 mb-1">
             <span class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-green-500"></span> Job satisfaction</span>
             <span class="font-semibold">+42%</span>
          </div>
          <div class="flex justify-between gap-8">
             <span class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-gray-900"></span> Financial stress</span>
             <span class="font-semibold">-58%</span>
          </div>
       </div>
    </div>
  </FeatureSection>

  <!-- Feature 6: Security & Compliance -->
  <FeatureSection 
    title="Built for security, compliance, and trust"
    subtitle=""
    linkText="Security overview"
    reversed={true}
    bullets={[
      "Regulated financial partners only",
      "Bank-level encryption and security",
      "Full compliance with financial regulations",
      "Employee data privacy protection"
    ]}
  >
    <div slot="description">
      <p>Patch works exclusively with regulated financial partners and maintains the highest standards of data security to protect both employers and employees.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center">
       <!-- Compliance Logos Grid -->
       <div class="grid grid-cols-2 gap-8 opacity-60">
          <div class="flex items-center gap-2 font-bold text-lg">
            <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2L2 7l10 5 10-5-10-5zm0 9l2.5-1.25L12 8.5l-2.5 1.25L12 11zm0 2.5l-5-2.5-5 2.5L12 22l10-8.5-5-2.5-5 2.5z"/></svg> 
            Bank-Grade
          </div>
          <div class="flex items-center gap-2 font-bold text-lg">
            <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
            SOC 2
          </div>
          <div class="flex items-center gap-2 font-bold text-lg">
            <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4z"/></svg>
            Encrypted
          </div>
          <div class="flex items-center gap-2 font-bold text-lg">
            <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor"><path d="M9 11H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2zm2-7h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V9h14v11z"/></svg>
            Regulated
          </div>
       </div>
    </div>
  </FeatureSection>

  <CaseStudies />
  <Integrations />
  <Resources />
  <BottomCTA />
</main>

<Footer />


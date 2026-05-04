<template>
  <div class="min-h-screen bg-white">
    <!-- Header/Nav Placeholder -->
    <header class="bg-secondary text-white py-4 px-6 sticky top-0 z-50 shadow-md">
      <div class="max-w-6xl mx-auto flex justify-between items-center">
        <div class="font-bold text-xl tracking-tight">GAZKI <span class="text-primary">LTD</span></div>
        <a href="#calendly" class="bg-primary text-secondary px-4 py-2 rounded-full font-bold text-sm hover:bg-primary-hover transition-colors">
          BOOK A CALL
        </a>
      </div>
    </header>

    <main>
      <!-- Hero Section -->
      <section class="section-padding bg-gradient-to-b from-secondary to-secondary-light text-white text-center">
        <div class="max-w-4xl mx-auto">
          <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">
            Build International Trade Deals <br class="hidden md:block" />
            With Real Buyers — <span class="text-primary">Not Guesswork</span>
          </h1>
          <p class="text-lg md:text-xl text-gray-300 max-w-2xl mx-auto mb-12">
            We’re speaking with a small number of entrepreneurs and companies to understand how international deals are actually built — and where they break down in reality.
          </p>
          <VSLPlayer />
        </div>
      </section>

      <!-- Target Audience Section -->
      <section class="section-padding bg-gray-50">
        <div class="max-w-4xl mx-auto">
          <h2 class="text-3xl font-bold text-center mb-12">This Is For You If:</h2>
          <div class="grid md:grid-cols-3 gap-8">
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 flex flex-col items-center text-center">
              <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center mb-4">
                <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"></path></svg>
              </div>
              <p class="font-medium text-secondary">You are already involved in international trade — or actively trying to enter it</p>
            </div>
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 flex flex-col items-center text-center">
              <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center mb-4">
                <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
              </div>
              <p class="font-medium text-secondary">You are trying to find buyers, structure deals, or scale operations</p>
            </div>
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 flex flex-col items-center text-center">
              <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center mb-4">
                <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"></path></svg>
              </div>
              <p class="font-medium text-secondary">You want a more predictable, structured approach (not trial and error)</p>
            </div>
          </div>
        </div>
      </section>

      <!-- Calendly CTA 1 -->
      <section id="calendly" class="section-padding">
        <div class="max-w-4xl mx-auto text-center">
          <p class="text-xl font-semibold mb-8 text-secondary">
            “This call is for entrepreneurs and companies actively involved in international trade or looking to enter it.”
          </p>
          <CalendlyWidget />
        </div>
      </section>

      <!-- On The Call Section -->
      <section class="section-padding bg-secondary text-white">
        <div class="max-w-4xl mx-auto">
          <h2 class="text-3xl font-bold mb-12 text-center text-primary">On The Call:</h2>
          <ul class="space-y-6">
            <li class="flex items-start gap-4">
              <span class="text-primary text-2xl">•</span>
              <p class="text-lg">Break down how you are currently trying to find and close deals</p>
            </li>
            <li class="flex items-start gap-4">
              <span class="text-primary text-2xl">•</span>
              <p class="text-lg">Identify where your approach is breaking down (demand, structure, or execution)</p>
            </li>
            <li class="flex items-start gap-4">
              <span class="text-primary text-2xl">•</span>
              <p class="text-lg">Show you what is missing to move from “random deals” to a repeatable system</p>
            </li>
            <li class="flex items-start gap-4">
              <span class="text-primary text-2xl">•</span>
              <p class="text-lg">Help you understand if your current direction is even worth pursuing</p>
            </li>
          </ul>
        </div>
      </section>

      <!-- Trust / Social Proof Section -->
      <section class="section-padding border-b border-gray-100">
        <div class="max-w-6xl mx-auto">
          <div class="grid md:grid-cols-4 gap-8 text-center mb-16">
            <div>
              <div class="text-4xl font-bold text-secondary mb-2">25+</div>
              <div class="text-gray-500 uppercase tracking-widest text-xs font-semibold">Countries</div>
            </div>
            <div>
              <div class="text-4xl font-bold text-secondary mb-2">14+</div>
              <div class="text-gray-500 uppercase tracking-widest text-xs font-semibold">Years Exp</div>
            </div>
            <div>
              <div class="text-4xl font-bold text-secondary mb-2">8-Fig</div>
              <div class="text-gray-500 uppercase tracking-widest text-xs font-semibold">Revenue</div>
            </div>
            <div>
              <div class="text-4xl font-bold text-secondary mb-2">40+</div>
              <div class="text-gray-500 uppercase tracking-widest text-xs font-semibold">Team Members</div>
            </div>
          </div>
          
          <div class="flex flex-wrap justify-center gap-8 items-center opacity-60 grayscale hover:grayscale-0 transition-all">
            <a href="https://www.gazki.tube" target="_blank" class="font-bold text-xl">GAZKI.TUBE</a>
            <a href="https://linkedin.com/in/mark-gazki" target="_blank" class="flex items-center gap-2">
              <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.761 0 5-2.239 5-5v-14c0-2.761-2.239-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
              LinkedIn
            </a>
            <a href="https://youtube.com/@GazkiLtd" target="_blank" class="flex items-center gap-2">
              <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"/></svg>
              YouTube
            </a>
          </div>
        </div>
      </section>

      <!-- Reassurance Section -->
      <section class="section-padding text-center">
        <div class="max-w-2xl mx-auto">
          <div class="inline-block bg-primary/10 text-primary font-bold px-4 py-2 rounded-full mb-6">
            LIMITED AVAILABILITY
          </div>
          <h2 class="text-3xl font-bold mb-4 italic">"No sales pitch. No obligation. No course being sold on the call."</h2>
          <p class="text-lg text-gray-600 mb-8">
            We’re only speaking with a limited number of people while we’re building this — once the slots are filled, we’ll close this.
          </p>
          <a href="#calendly" class="btn-primary inline-block">
            RESERVE YOUR SLOT NOW
          </a>
        </div>
      </section>

      <!-- Calendly CTA 2 -->
      <section class="section-padding bg-gray-50 border-t border-gray-100">
        <div class="max-w-4xl mx-auto text-center">
          <h2 class="text-2xl font-bold mb-8">Ready to Build Your System?</h2>
          <CalendlyWidget />
        </div>
      </section>
    </main>

    <footer class="bg-secondary text-white/50 py-12 px-6 text-center text-sm">
      <div class="max-w-4xl mx-auto">
        <p class="mb-4">&copy; {{ new Date().getFullYear() }} Gazki Ltd. All rights reserved.</p>
        <div class="flex justify-center gap-6">
          <a href="#" class="hover:text-primary transition-colors">Privacy Policy</a>
          <a href="#" class="hover:text-primary transition-colors">Terms of Service</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
import VSLPlayer from './components/VSLPlayer.vue'
import CalendlyWidget from './components/CalendlyWidget.vue'
</script>

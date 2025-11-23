<template>
  <UContainer>
    <div class="py-8">
      <div class="text-center mb-6">
        <img src="/img/LogoLKB.png" alt="LKB logo" class="mx-auto w-60 h-auto mb-3" />
        <h1 class="text-2xl font-semibold mb-2">Baleine — Internal LKB apps</h1>
      </div>

      <p class="text-sm text-gray-600 mb-6">
        This server hosts internal LKB applications: the CO2 footprint
        calculator, the internal intranet with documentation, and the
        meeting room booking tool. Use the cards below to jump to each service.
      </p>

      <div class="grid gap-6 grid-cols-1 sm:grid-cols-2 lg:grid-cols-3">
        <UCard
          as="a"
          href="https://co2.baleine.lkb.upmc.fr"
          target="_blank"
          rel="noopener noreferrer"
          variant="outline"
          :ui="{ root: 'cursor-pointer hover:shadow-lg transition transform hover:-translate-y-1 p-6 min-h-[160px]' }"
        >
          <template #header>
            <div class="flex items-center gap-4">
              <svg class="w-10 h-10 text-sky-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 1.343-3 3v6h6v-6c0-1.657-1.343-3-3-3z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 2v4" />
              </svg>
              <div>
                <h2 class="text-xl font-medium">CO2 Calculator</h2>
              </div>
            </div>
          </template>

          <div class="mt-4 text-sm text-gray-700">
            Estimate carbon emissions for travels. 
          </div>

          <template #footer>
            <div class="text-sm text-sky-600 break-words">co2.baleine.lkb.upmc.fr</div>
          </template>
        </UCard>

        <UCard
          as="a"
          href="https://intranet.baleine.lkb.upmc.fr"
          target="_blank"
          rel="noopener noreferrer"
          variant="outline"
          :ui="{ root: 'cursor-pointer hover:shadow-lg transition transform hover:-translate-y-1 p-6 min-h-[160px]' }"
        >
          <template #header>
            <div class="flex items-center gap-4">
              <svg class="w-10 h-10 text-green-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 7h18M3 12h18M3 17h18" />
              </svg>
              <div>
                <h2 class="text-xl font-medium">Intranet</h2>
              </div>
            </div>
          </template>

          <div class="mt-4 text-sm text-gray-700">
            Internal documentation, and links to shared resources
            (policies, procedures, and contact lists).
          </div>

          <template #footer>
            <div class="text-sm text-sky-600 break-words">intranet.baleine.lkb.upmc.fr</div>
          </template>
        </UCard>

        <UCard
          as="a"
          href="https://booking.baleine.lkb.upmc.fr"
          target="_blank"
          rel="noopener noreferrer"
          variant="outline"
          :ui="{ root: 'cursor-pointer hover:shadow-lg transition transform hover:-translate-y-1 p-6 min-h-[160px]' }"
        >
          <template #header>
            <div class="flex items-center gap-4">
              <svg class="w-10 h-10 text-rose-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3M3 11h18M5 21h14a2 2 0 002-2V11H3v8a2 2 0 002 2z" />
              </svg>
              <div>
                <h2 class="text-xl font-medium">Booking (Jussieu)</h2>
              </div>
            </div>
          </template>

          <div class="mt-4 text-sm text-gray-700">
            Reserve meeting rooms Jussieu, view availability and manage room schedules for
            team meetings and events.
          </div>

          <template #footer>
            <div class="text-sm text-sky-600 break-words">booking.baleine.lkb.upmc.fr</div>
          </template>
        </UCard>
      </div>
    </div>
  </UContainer>
</template>

<script setup>
</script>

<script setup>
import staff1 from '@/assets/staff-1.jpg'
import staff2 from '@/assets/staff-2.jpg'
import nonteaching from '@/assets/non-teaching.jpg'
import principal from '@/assets/principal.jpeg'
</script>
<template>
    <AppHeader />
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mb-12">
		<img :src="staff1" /><br />
		<img :src="staff2" />

        <h2 class="text-2xl p-2 px-8 border-b-2">Non-Teaching Staff</h2>
		<img :src="nonteaching" />

    </div>
    <Footer />
</template>

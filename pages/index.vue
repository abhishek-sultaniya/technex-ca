<template>
  <div>{{ data }}</div>
</template>

<script setup>
const { data } = await useFetch('/ca/register', {
  method: 'post',
  baseURL: 'https://api.technex.co.in/',
  body: {
    year: null,
    email: 'string',
    mobile_number: 'string',
    whyChooseYou: 'string',
    whatsapp_number: 'string',
    college: 'string',
    postal_address: 'string',
    pinCode: 2147483647,
    password: 'string',
    username: 'string',
    last_name: 'string',
    first_name: 'string',
    wereCa: true,
  },
})
</script>

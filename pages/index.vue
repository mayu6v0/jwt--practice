<template>
  <div class="container">
    <p v-if="$auth.loggedIn">Name: {{ $auth.user.name }}</p>
    <p v-if="$auth.loggedIn">Email: {{ $auth.user.email }}</p>
    <p v-if="$auth.loggedIn">Password: {{ $auth.user.password }}</p>
  </div>
</template>

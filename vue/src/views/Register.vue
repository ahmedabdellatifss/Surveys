<template>
  <div>
    <div>
    <img
      class="mx-auto h-12 w-auto"
      src="https://tailwindui.com/img/logos/workflow-mark-indigo-600.svg"
      alt="Workflow"
    />
    <h2 class="mt-6 text-center text-3xl font-extrabold text-gray-900">
      Register for free
    </h2>
    <p class="mt-2 text-center text-sm text-gray-600">
      Or
      {{ " " }}
      <router-link
        :to="{ name: 'Login' }"
        class="font-medium text-indigo-600 hover:text-indigo-500"
      >
        login to your account
      </router-link>
    </p>
  </div>

  <div>
    <form class="space-y-6" action="#" method="POST">
      <div>
        <div class="mt-2">
          <input id="fullname" name="name" type="text" placeholder="Full name" autocomplete="name" required class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
        </div>
      </div>
      <div>
        <div class="mt-2">
          <input id="email" name="email" type="email" placeholder="Email address" autocomplete="email" required class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
        </div>
      </div>

      <div>

        <div class="mt-2">
          <input id="password" name="password" type="password" placeholder="Password" autocomplete="current-password" required class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
        </div>
      </div>

      <div>
        <button type="submit" class="flex w-full justify-center rounded-md bg-indigo-600 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Sign up</button>
      </div>
    </form>

  </div>
</div>
</template>

<script>
export default {
  name: "Register"
}
</script>

<style scoped>

</style>

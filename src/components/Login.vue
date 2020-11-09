<template>
  <div
    class="min-h-screen flex items-center justify-center py-12 px-4 sm:px-6 lg:px-8"
  >
    <div class="max-w-md w-full">
      <div class="mb-6">
        <img class="mx-auto h-12 w-auto" src="#" alt="Logo" />
        <h2
          class="mt-6 text-center md:text-3xl text-2xl leading-9 font-extrabold text-gray-900 dark:text-white"
        >
          Create an account
        </h2>
      </div>
      <form
        class="w-full max-w-xl p-6 text-left shadow bg-white rounded-lg dark:bg-gray-900"
      >
        <div class="flex flex-wrap mx-3 py-3">
          <div class="flex flex-wrap mb-3">
            <div class="w-full md:w-1/2 px-3 mb-3 md:mb-0">
              <label
                class="tracking-wide text-gray-700 text-sm font-semibold mb-2 dark:text-gray-200"
                >First Name</label
              >
              <input
                type="text"
                class="appearance-none border rounded w-full py-3 px-3 text-gray-700 dark:text-gray-200 mt-1 leading-tight focus:outline-none focus:shadow-outline"
                required
              />
            </div>
            <div class="w-full md:w-1/2 px-3">
              <label
                class="tracking-wide text-gray-700 text-sm font-semibold mb-2 dark:text-gray-200"
                >Last Name</label
              >
              <input
                type="text"
                class="appearance-none border rounded w-full py-3 px-3 text-gray-700 dark:text-gray-200 mt-1 leading-tight focus:outline-none focus:shadow-outline"
                required
              />
            </div>
          </div>
          <div class="w-full md:w-full px-3 mb-3">
            <label
              class="tracking-wide text-gray-700 text-sm font-semibold mb-2 dark:text-gray-200"
              >Email Address</label
            >
            <input
              type="email"
              class="appearance-none border rounded w-full py-3 px-3 text-gray-700 mt-1 leading-tight focus:outline-none focus:shadow-outline"
              required
            />
          </div>
          <div class="w-full md:w-full px-3 mb-6">
            <label
              class="tracking-wide text-gray-700 text-sm font-semibold mb-2 dark:text-gray-200"
              >Password</label
            >
            <input
              type="password"
              class="appearance-none border rounded w-full py-3 px-3 text-gray-700 mt-1 leading-tight focus:outline-none focus:shadow-outline"
              required
            />
          </div>
          <div class="w-full md:w-full px-3">
            <button
              class="appearance-none block w-full bg-purple-700 text-gray-100 font-bold border border-gray-200 dark:border-gray-700 m rounded-lg py-3 px-3 leading-tight hover:bg-purple-900 focus:outline-none focus:border-none"
            >
              Register
            </button>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>
<script>
export default {
  name: "Login",
  created() {},
};
</script>
<style scoped>
* {
  transition: all 0.5s ease-in-out;
}
</style>

<template>
  <div>
    <div class="
    flex
    bg-green-500
    items-center
    justify-center
    p-2
    md:p-0
    min-h-screen
    w-full
    relative
    overflow-hidden
  ">
    <div class="absolute right-0 -mr-24 "></div> 
    <div class="bg-white rounded-md shadow-lg w-full md:w-auto p-4 z-40">
      <!-- <img src="https://member.tokovoucher.id/_nuxt/img/logo.b3d08c0.png" alt="" class="w-52 m-auto py-4">  -->
      <h1 class="text-green-500 flex justify-center">Topup Mania</h1>
      <form>
        <div class="mb-4 mt-4">
          <label for="" class="text-sm text-gray-500">Email</label> 
          <input required="required" type="email" placeholder="Email" class="
            block
            md:w-96
            lg:w-96
            w-full
            bg-gray-100
            py-2
            border
            rounded-lg
            focus:border-primary-navy focus:outline-none
            px-3
          ">
        </div> 
        <div class="mb-6">
          <label for="" class="text-sm text-gray-500">Password</label> 
          <input required="required" type="password" placeholder="Password" class="
            block
            md:w-96
            lg:w-96
            w-full
            bg-gray-100
            border
            py-2
            rounded-lg
            focus:border-primary-navy focus:outline-none
            px-3
          ">
        </div> 
        <div>
          <div class="text-sm mb-4">
            <span>Belum Punya Akun ?</span> 
            <a href="/register" class="font-bold text-primary-navy underline">Register</a>
          </div> 
          <div class="text-sm mb-6">
            <a href="/lupa-password" class="font-bold text-primary-navy underline">Lupa Password ?</a>
          </div> 
          <button type="submit" class="py-4 w-full bg-green-500 rounded-lg text-white text-sm">
            <span>Login</span>
          </button>
        </div>
      </form>
    </div> 
    <div><!----> <!----></div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

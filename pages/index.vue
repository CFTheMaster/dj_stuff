<template>
    <main>
      <div>
        <h1>About me:</h1>
        <p class="about">
          Hello friends, my name is computerfreaker / DJ name Purple Time.
        </p>
      </div>
      <div>
        <p>
          if you want to learn more about me, check the about me page: <router-link :to="{ name: 'about' }">About</router-link>
        </p>
      </div>
      <div>
        <h2>You can find my current socials on the <a class="gay" href="https://computerfreaker.com">homepage</a></h2>
      </div>
    </main>  
</template>
<template>
  <div class="p-8">
    <Card class="flex flex-col bg-white dark:bg-dark-fg">
      <h2 class="heading mb-4">Réductions de 5€</h2>
      <div class="flex flex-wrap -mx-4">
        <div v-for="index in 6"
             class="w-full md:w-1/2 lg:w-1/3 px-4">
          <Card class="w-full flex flex-col items-center w-64 mb-8 bg-white dark:bg-dark-bg">
            <div class="flex">
              <div class="flex flex-col flex-grow items-center">
                <img class="mb-6 dark:invert" src="/images/logo_backmarket.png" />
                <p class="max-w-lg mb-8 text-base text-center"><strong>5€</strong> de réduction (500 points) </p>
                <button class="btn w-32">J’en profite&nbsp;!</button>
              </div>
            </div>
          </Card>
        </div>
      </div>

      <h2 class="heading mt-8 mb-4">Réductions de 10€</h2>
      <div class="flex flex-wrap -mx-4">
        <div v-for="index in 6"
             class="w-full md:w-1/2 lg:w-1/3 px-4">
          <Card class="w-full flex flex-col items-center w-64 mb-8 bg-white dark:bg-dark-bg">
            <div class="flex">
              <div class="flex flex-col flex-grow items-center">
                <img src="/images/logo_backmarket.png" />
                <p class="max-w-lg ml-2 text-base text-center"><strong>5€</strong> de réduction (500 points) </p>
                <button class="justify-center w-32 bg-primary hover:bg-primary-dark text-white text-base font-bold mt-12 py-2 px-3 rounded-xl inline-flex items-center">J’en profite !
                </button>
              </div>
            </div>
          </Card>
        </div>
      </div>
    </Card>
  </div>
</template>

<script>
  import Card from '../components/Card'

  export default {
    components: {
      Card
    }
  }
</script>

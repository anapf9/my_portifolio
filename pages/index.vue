<template>
  <div class="container w-full bg-apresentation bg-cover bg-center">
    <div class="bg"></div>
    <div class="grid grid-cols-3 w-full">
      <div class="col-span-2 flex content-end items-center mx">
        <div class="w-auto">
          <div class="text-4xl text-left flex-wrap text-white">
            <p>Olá, eu sou a Ana,</p>
            <p>Estudante de Engenharia da computação &</p>
            <p>Desenvolvedora Fullstack Junior</p>
          </div>
        </div>
      </div>
      <!-- <div class="col-span-1 flex content-end items-center">
        <img class src="@/img/test.jpg" />
      </div>-->
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

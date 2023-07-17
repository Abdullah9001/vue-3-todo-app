<template>
  <div class="about">
    <h1>Vue Todo</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt ducimus illo
      pariatur aperiam ab alias veritatis quis, aspernatur et aliquid at
      laudantium consequuntur labore autem laborum, laboriosam maxime mollitia,
      saepe numquam iusto cupiditate. Quibusdam, odio nostrum obcaecati dolores
      laborum natus?
    </p>
  </div>
</template>

<style lang="scss">
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    align-items: center;
    padding: 3rem;
    h1 {
      margin-bottom: 2rem;
    }
    p {
      width: 600px;
    }
  }
}
@media (max-width: 1024px) {
  .about {
    min-height: 100vh;
    align-items: center;
    padding: 3rem;
    h1 {
      margin-bottom: 2rem;
    }
    p {
      width: 400px;
    }
  }
}
</style>

<template>
  <div>
    <Html
    :lang="dynamic > 50 ? 'en-GB' : 'en-US'">
    <Head>
      <Title>Restaurantly</Title>
      <Meta name="description" content="I love fast food"/>
      <Link rel="preload" href="https://www.flaticon.com/free-icon/fast-food_575577" as="script" />
    </Head>
    </Html>
    <div class="container">
      <h1>Welcome to Restaurantly</h1>
      <a href="/restaurants">Go to Restaurants</a>
    </div>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;
}
</style>

<template>
  <div>
    <Html
        :lang="dynamic > 50 ? 'en-GB' : 'en-US'">
    <Head>
      <Title>Top 50 Restaurants</Title>
      <Meta name="description" content="I love fast food"/>
      <Link rel="preload" href="https://www.flaticon.com/free-icon/fast-food_575577" as="script" />
    </Head>
    </Html>
  <NuxtLayout name="custom">
    <div class="container">
      <RestaurantTable />
    </div>
  </NuxtLayout>

  </div>
</template>

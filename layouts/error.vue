<template>
  <div>
    <slot name="header" />
    <div>
      <img
           src="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
           alt="sad face"
      />
    </div>
  </div>
  <slot name="redirectEl" />
</template>
<style>

img {
  width: 10rem;
}
</style>

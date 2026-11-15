<template>
  <div>
    <header>
      <h2>Chen's Website</h2>

      <nav>
        <NuxtLink to="/">首頁</NuxtLink>
        <NuxtLink to="/about">關於我</NuxtLink>
        <NuxtLink to="/projects">作品介紹</NuxtLink>
      </nav>
    </header>

    <slot />
  </div>
</template>
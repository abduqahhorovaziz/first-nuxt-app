<template>
  <div>
    <transition>
      <div :key="$route.name">
        <slot></slot>
      </div>
    </transition>
  </div>
</template>

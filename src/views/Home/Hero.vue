<template>
  <div class="home-hero">
    <div class="home-hero__inner">
      <div class="home-hero__left">
        <div class="home-hero__pre-header">
          <star-svg />
          <star-svg />
          <star-svg />
          <star-svg />
        <star-svg />
        <span>
          Rated 4.8/5 (243 reviews)
        </span>
        </div>
        <h1>Create your portfolio in minutes</h1>
        <p>
        With Fiber you can setup your own personal portfolio in minutes with dozens of premade beautiful templates.
        </p>
        <div class="home-hero__perk-list">
          <button class="btn -primary">Start Free Trial</button>
          <button class="btn -link">View Examples</button>
        </div>
        <div class="home-hero__perk-list">
          <div class="home-hero__perk">
            <checkmark-svg />
            <div class="mx-2">No Credit Card Required</div>
          </div>
          <div class="home-hero__perk">
            <checkmark-svg />
            <div class="mx-2">10 Free Templates</div>
          </div>
        </div>
      </div>
      <div class="home-hero__right">
        <img src="/assets/hero-Illustration.png" />
      </div>
    </div>
  </div>
</template>

<script setup>
import StarSvg from '@/assets/star.svg'
import CheckmarkSvg from '@/assets/Checkmark.svg'
</script>
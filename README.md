<p align="center">
  <a href="https://heroicons.com/#gh-light-mode-only" target="_blank">
    <img src="./.github/logo-light.svg" alt="Heroicons" width="300">
  </a>
  <a href="https://heroicons.com/#gh-dark-mode-only" target="_blank">
    <img src="./.github/logo-dark.svg" alt="Heroicons" width="300">
  </a>
</p>

<p align="center">
  Beautiful hand-crafted SVG icons, by the makers of Tailwind CSS. <br>Available as basic SVG icons and via first-party <a href="#svelte">Svelte</a>, <a href="https://github.com/tailwindlabs/heroicons#react">React</a> and <a href="https://github.com/tailwindlabs/heroicons#vue">Vue</a> libraries.
<p>

<p align="center">
  <a href="https://heroicons.com"><strong>Browse at Heroicons.com &rarr;</strong></a>
</p>


<p align="center">
    <a href="https://github.com/wzlabs/wzlabs-heroicons/releases"><img src="https://img.shields.io/npm/v/wzlabs-heroicons" alt="Latest Release"></a>
    <a href="https://github.com/wzlabs/wzlabs-heroicons/blob/main/LICENSE"><img src="https://img.shields.io/npm/l/wzlabs-heroicons.svg" alt="License"></a>
</p>


## Basic Usage

The quickest way to use these icons is to simply copy the source for the icon you need from [heroicons.com](https://heroicons.com) and inline it directly into your HTML:

```html
<svg class="h-6 w-6 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
  <path
    stroke-linecap="round"
    stroke-linejoin="round"
    d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"
  />
</svg>
```

Both icon styles are preconfigured to be stylable by setting the `color` CSS property, either manually or using utility classes like `text-gray-500` in a framework like [Tailwind CSS](https://tailwindcss.com).


## Svelte

First, install `@wzlabs-heroicons/svelte` from npm:

```sh
npm install @wzlabs-heroicons/svelte
```

Now each icon can be imported individually as a Svelte component:

```svelte
<script>
import { BeakerIcon } from '@wzlabs-heroicons/svelte/24/solid'
</script>

<div>
  <BeakerIcon class="h-6 w-6 text-blue-500"/>
  <p>...</p>
</div>
```

The 24x24 outline icons can be imported from `@wzlabs-heroicons/svelte/24/outline`, the 24x24 solid icons can be imported from `@wzlabs-heroicons/svelte/24/solid`, and the 20x20 solid icons can be imported from `@wzlabs-heroicons/svelte/20/solid`.

Icons use an upper camel case naming convention and are always suffixed with the word `Icon`.

[Browse the full list of icon names on UNPKG &rarr;](https://unpkg.com/browse/@wzlabs-heroicons/svelte/24/outline/)


## License

This library is MIT licensed.

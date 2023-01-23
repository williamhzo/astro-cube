![]('/../public/images/og-image.png)

# [ASTRO-CUBE](https://astro-cube.vercel.app) 🧊

a tiny, almost-unopinionated [Astro](https://astro.build/) starter for your next blog, documentation, personal/marketing website, and more.

it comes with the [CUBE CSS](https://cube.fyi/) file structure, a methodology for managing stylesheets efficiently no matter the size of the project.

the project is mostly barebones, the goal isn't to provide a batteries-included template, just an easy starter kit and stylesheets to copy/paste from.

most styles are for demo purposes and to explain the underlying philosophy: "Be the browser's mentor, not its micromanager" (see [buildexcellentwebsit.es](buildexcellentwebsit.es)).

## features

- **[CUBE CSS](https://cube.fyi/) implementation**: take a look at the docs, they are concise and explain way better than i would
- **fluid and responsive**: it looks great no matter the device size
  - [Every Layout](https://every-layout.dev/) examples for layout elements
  - [Utopia](https://utopia.fyi/) for fluid `clamp()`-based font sizes and spacing
- **lightweight**: 💯 [lighthouse score](https://developer.chrome.com/en/docs/lighthouse/performance/performance-scoring/) across the board — not surprising considering the size of the project, but worth mentioning
- **dark-mode ready**: implement your own theme switcher if you're into that sort of thing, all you have to do is toggle the `data-theme` attribute on the body

## to do

- [ ] add design tokens as JSON rather than CSS variables
- [ ] generate utilities and CSS variables programmatically (see [this post](https://piccalil.li/blog/i-used-tailwind-for-the-u-in-cube-css-and-i-liked-it/))

---

> **Note**
>
> please note that this project is mostly for personal use, i've been using this approach a lot lately and having the minimal set-up ready saves me a ton of time when starting a new preoject.
>
> in that sense, this template is not set in stone and will likely evolve in the coming weeks.
>
> that said, it's great if it can be helpful to other, i'm open to feedback and greatly appreciate contributions, feel free to chip in for fixes, suggestions, or features!

contributions are welcome! 👋

[![Built with Astro](https://astro.badg.es/v1/built-with-astro.svg)](https://astro.build/)

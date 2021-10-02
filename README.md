# miniwind

[![NPM version](https://img.shields.io/npm/v/miniwind?color=a1b858&label=)](https://www.npmjs.com/package/miniwind)

**Re-imaging atomic CSS**. An incredibly fast and lightweight on-demand atomic CSS framework.

Inspired by [Windi CSS](http://windicss.org/), [Tailwind CSS](https://tailwindcss.com/), [Twind](https://github.com/tw-in-js/twind) but:

- Component / module level CSS instead of global - CSS code-splitting!
- Compile-time on-demand - all the possibilities and zero-runtime. 
- No parsing, no AST, incredible fast.
- Fully customizable - no core utilities, only presets.
- No preflights - no global pollutions.
- No pre-scanning, no file watcher - all done in one pass.
- CSS Scoping.
- Windi CSS Attributify.
- Library friendly - ships atomic styles with your component libraries, without asking users to install it.

###### Non-goal

`miniwind` is designed **NOT** to be/have:

- Align / compatible with Tailwind or Windi CSS.
- A CSS preprocessor (`@apply` etc.)
- Tailwind's plugin system (but you can share the presets!)
- Integrations for Webpack or others (it's Vite only).

###### Disclamier

> 🧪 This package is trying to explore the possibilities of what an atomic CSS framework can be. It's not a replacement for Windi CSS or Tailwind. **Not production ready**, yet. Breaking changes and overhaul redesigns are expected frequently.

## Installation

```bash
npm i -D miniwind
```

```ts
// vite.config.ts
import Miniwind from 'miniwind/vite'

export default {
  plugins: [
    Miniwind()
  ]
}
```

That's it, have fun.

## Sponsors

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/antfu/static/sponsors.svg">
    <img src='https://cdn.jsdelivr.net/gh/antfu/static/sponsors.svg'/>
  </a>
</p>

## License

[MIT](./LICENSE) License © 2021 [Anthony Fu](https://github.com/antfu)

# 🦐 pixiuswap UIkit

[![Version](https://img.shields.io/npm/v/@pixiuswap/uikit)](https://www.npmjs.com/package/@pixiuswap/uikit) [![Size](https://img.shields.io/bundlephobia/min/@pixiuswap/uikit)](https://www.npmjs.com/package/@pixiuswap/uikit)

pixiuswap UIkit is a set of React components and hooks used to build pages on pixiuswap's apps.

It also contains a theme file for dark and light mode.

## Install

`yarn add @pixiuswap/uikit`

## npm

https://www.npmjs.com/package/@pixiuswap/uikit

## Setup

### Theme

Before using pixiuswap UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@pixiuswap/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@pixiuswap/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://pixiuswap.github.io/pixiuswap-uikit/)

# `@skilbourn/streak-counter` - a basic streak counter

This is a basic streak counter - inspired by Duolingo - written in TypeScript and meant for the browser (uses `localStorage`).

## Install

```shell
yarn add @skilbourn/streak-counter
```


## Usage

import {streakCounter} from '@skilbourn/streak-counter'

const today = new Date()
const streak = streakCounter(localStorage, today)
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/05/2022",
//    startDate: "11/05/2022",
// }

[![Edit streak-counter (ts-course) (forked)](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/streak-counter-ts-course-forked-dsp0ow?fontsize=14&hidenavigation=1&theme=dark)

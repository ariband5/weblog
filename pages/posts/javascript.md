---
title: The Strong & Silent TypeScript
date: 2022/3/16
description: Types in JavaScript
tag: javascript, typescript
author: Ari Bandong
---

# The Strong & Silent TypeScript

import Image from 'next/image'


<Image
  src="/images\TypeScript_Logo_(Blue).svg"
  alt="Photo"
  width={1125}
  height={650}
  priority
  className="next-image"
/>

Last week, Microsoft introduced a [proposal](https://devblogs.microsoft.com/typescript/a-proposal-for-type-syntax-in-javascript/) for types syntax in JavaScript. 

This can be distilled down to two ways of thinking:

1. TypeScript with no build step
2. JavaScript with types

Types in JavaScript makes sense for a couple of reasons.

1. Static Typing was the most requested language feature in the [State of JS Survey](https://stateofjs.com/) in both [2020](https://2020.stateofjs.com/en-US/opinions/#missing_from_js) and [2021](https://2021.stateofjs.com/en-US/opinions/#currently_missing_from_js_wins).

2. TypeScript is listed as the 4th most-used language in [GitHub's State of the Octoverse](https://octoverse.github.com/#top-languages-over-the-years).



From the Github [repository](https://github.com/giltayar/proposal-types-as-comments/):

## ECMAScript proposal: Types as Comments

This proposal aims to enable developers to add type annotations to their JavaScript code, allowing those annotations to be checked by a type checker that is external to JavaScript. At runtime, a JavaScript engine ignores them, treating the types as comments.
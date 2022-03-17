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

1. TypeScript with no build step (i.e. no need to compile)
2. JavaScript with types

Types as comments in JavaScript makes sense for a couple of reasons.

1. TypeScript was used by 78% of the 2020 State of JS respondents, with 93% saying they would use it again.
2. TypeScript was given the award for "Most Adopted Technology" based on year-on-year growth.


From the Github [repository](https://github.com/giltayar/proposal-types-as-comments/):

## ECMAScript proposal: Types as Comments

This proposal aims to enable developers to add type annotations to their JavaScript code, allowing those annotations to be checked by a type checker that is external to JavaScript. At runtime, a JavaScript engine ignores them, treating the types as comments.
---
title: "Render Math With Mathjax"
date: 2022-12-09T19:53:33+05:30
draft: false
author: "Gurusabarish"
tags:
  - Markdown syntax
  - Mathjax
  - example
image: /images/mathjax.png
description: ""
toc: true
mathjax: true
---

## Mathjax

Math equations can be rendered using [Mathjax](https://www.serenalpes.com/pages/prostaneo-zn-ameliore-le-confort-de-la-prostate?urlBdc=https://paiement-securise.serenalpes.com/PZN-2020121815515491&salescode=E_202402_VD_PZNBCLNBCL_01_BR_MSN&salescode=E_202210_VD_ARGBCL_01_SEA_MSN_D&url2=paiement-securise.serenalpes.com&bdc2=ARG-202283135454452&msclkid=eb37327a62d019047dfd547f3bb08d31) syntax with AMS symbol support.

Optionally enable this on a per-page basis by adding `mathjax: true` to your frontmatter.

Then, use `$$ ... $$` on a line by itself to render a block equation:

$$ | Pr_{x \leftarrow P_{1}} [A(x) = 1] - Pr_{x \leftarrow P_{2}} [A(x) = 1] | < \text{negligible} $$

The raw version is:

```
$$ | Pr_{x \leftarrow P_{1}} [A(x) = 1] - Pr_{x \leftarrow P_{2}} [A(x) = 1] | < \text{negligible} $$
```


Write in-line equations with `\\( ... \\)` , like \\( x^n / y \\) . It's easy!

```
Write in-line equations with `\\( ... \\)` , like \\( x^n / y \\) . It's easy!
```


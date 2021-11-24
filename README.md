# elr-scss-breadcrumbs

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-breadcrumb.svg?style=flat)]()

a scss mixin for breadcrumbs

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-breadcrumb
```

```sh
yarn add elr-scss-breadcrumb
```

## Implementation

### Scss

```scss
.breadcrumbs {
  @include elr-breadcrumbs;
}
```

```scss
.breadcrumbs-slash {
  @include elr-breadcrumbs(
    $config: (
      separator: "/",
    )
  );
}
```

```scss
.breadcrumbs-arrow {
  @include elr-breadcrumbs-arrow;
}
```

### HTML

```html
<nav class="breadcrumb-nav">
  <ul class="breadcrumbs">
    <li>
      <a href="#">Home</a>
    </li>
    <li>
      <a href="#">About</a>
    </li>
    <li class="active">
      <a href="#">About ELR Utilities</a>
    </li>
  </ul>
</nav>
```

```html
<nav class="breadcrumb-nav">
  <ul class="breadcrumbs-slash">
    <li>
      <a href="#">Home</a>
    </li>
    <li>
      <a href="#">About</a>
    </li>
    <li class="active">
      <a href="#">About ELR Utilities</a>
    </li>
  </ul>
</nav>
```

```html
<nav class="breadcrumb-nav">
  <ul class="breadcrumbs-arrow">
    <li>
      <a href="#">Home</a>
    </li>
    <li>
      <a href="#">About</a>
    </li>
    <li class="active">
      <a href="#">About ELR Utilities</a>
    </li>
  </ul>
</nav>
```

## License

SEE LICENSE IN LICENSE.md

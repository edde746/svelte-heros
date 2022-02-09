# Svelte-heroicons

Hero Icons for Svelte

## Requirement

- Tailwind CSS

## List of icons

Please see [https://heroicons.com/](https://heroicons.com/).

## Installation

```sh
npm i svelte-heroicons
```

## Import

```js
<script>
  import { AcademicCapIcon } from "$lib/heroicons/solid";
</script>
```

## Props

| Name      | Default     |
| --------- | ----------- |
| className | `h-6 w-6`   |
| viewBox   | `0 0 24 24` |

## Color

Add color in the `className` prop like:

```js
<AcademicCapIcon className="h-20 w-20 text-pink-700" />
```

## Examples

```js
<script>
  import { AcademicCapIcon } from "$lib/heroicons/outline";
</script>

<AcademicCapIcon />

<AcademicCapIcon className="h-5 w-5 text-blue-500" />

<AcademicCapIcon className="h-40 w-40 text-blue-500" />

<AcademicCapIcon className="h-80 w-80 text-red-900" />
```
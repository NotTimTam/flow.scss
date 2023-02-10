# flow.scss

```scss
$acronym: "Flexible Layout Optimization With SCSS";
```

`flow.scss` is a **simple**, yet effective SCSS framework for your front-end design needs. It provides a quick and efficient way to generate layouts for your website.

`flow.scss` **utilizes flexbox**-based layouts in a mobile-first approach to web development.

`flow.scss` is built for **customization**. A single `vars.scss` file contains every variable used to build the styles. It is recommended to modify this file to match your website's design, but it already includes all the necessary base values to create stunning websites.

-   To take advantage of this feature. Download the entire `flow.scss` library directly into your project's `styles` folder or fork the repository.

`flow.scss` is designed to integrate **seamlessly** into your existing projects, without causing any style conflicts or the need for debugging.

## Examples

```jsx
// React.js and Next.js
import "flow.scss";

export default function Home({ Component, pageProps }) {
	return (
		<main class="column align-center gap">
			<article class="column">
				<h1 class="margin-top">Hello, world!</h1>
			</article>
		</main>
	);
}
```

```scss
// Incorporate into your own SCSS files directly for access to mixins and variables.
@use "flow.scss" as *;

main.page {
	@include flex-column;
	gap: $gap;
	padding: $padding * 2 $padding;
}
```

```html
<!-- Vanilla HTML -->
<!DOCTYPE html>
<html lang="en">
	<head>
		<link rel="stylesheet" href="./flow.scss/index.scss" />
	</head>
	<body>
		<main class="column align-center gap">
			<article class="column">
				<h1 class="margin-top">Hello, world!</h1>
			</article>
		</main>
	</body>
</html>
```

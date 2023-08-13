# Tetsu SvelteKit Blog Template

A modern blog template built with SvelteKit and other cutting-edge technologies.

---

## SvelteKit Capabilities

[SvelteKit](https://kit.svelte.dev/) is a powerful framework for building web applications. Here are some of its standout capabilities:

- **Hydration**: SvelteKit provides a seamless hydration process, allowing you to build server-rendered pages that "hydrate" into single-page apps.

- **Adapters**: With a variety of adapters, SvelteKit can deploy to different environments, including static sites, Node.js, and even serverless platforms.

- **Server-side Rendering (SSR)**: SvelteKit supports SSR out of the box, ensuring faster load times and improved SEO.

- **Routing**: Built-in file-based routing system makes it easy to structure your application and define page transitions.

- **End-to-End**: SvelteKit is an end-to-end solution, handling everything from routing to server-side rendering, making it easier to set up and deploy applications.

- **Integrated Development Environment**: Comes with a built-in development server, making it easy to develop and preview your application in real-time.

- **Extensibility**: Easily integrate with other tools and libraries in the Svelte ecosystem.

## Advantages of a Blog Engine that Parses Markdown Files

Using markdown files as the content source for a blog engine offers several advantages:

- **Simplicity**: Markdown is easy to write and read. It eliminates the distractions of formatting toolbars and allows authors to focus on content.

- **Version Control**: Storing blog posts as markdown files in a repository like GitHub allows for version control. This means you can track changes over time, collaborate with others, and even revert to previous versions if needed.

- **Flexibility**: Markdown can be easily converted to various formats like HTML, PDF, or even Word documents. This makes it versatile for various publishing needs.

- **Performance**: Parsing markdown files is generally faster than querying a database. This can lead to quicker page load times, enhancing the user experience.

- **Security**: With markdown files, there's less risk compared to databases which can be prone to SQL injection attacks.

- **Portability**: Markdown files are plain text, making them lightweight and easy to backup, transfer, or migrate.

- **Integration with Static Site Generators**: Many modern static site generators support markdown out of the box, allowing for fast, secure, and scalable blogs or websites.

Incorporating a blog engine that parses markdown files, especially in a powerful framework like SvelteKit, combines the best of modern web development practices with the simplicity and versatility of markdown.

---

## Feature Set and Third Parties

- Built with [SvelteKit](https://kit.svelte.dev/)
- Styling with [TailwindCSS](https://tailwindcss.com/)
- Markdown support with [mdsvex](https://mdsvex.pankod.com/)
- Code formatting with [Prettier](https://prettier.io/)
- Linting with [ESLint](https://eslint.org/)
- Reading time estimation with `reading-time` and `reading-time-estimator`

## Development

### Install Dependencies

```bash
npm install
```

### Run Locally

```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Linting and Formatting

Check for linting issues:

```bash
npm run lint
```

Format code:

```bash
npm run format
```

## Dependencies

- [clsx](https://www.npmjs.com/package/clsx) - A utility for conditionally concatenating class names
- [date-fns](https://date-fns.org/) - Modern JavaScript date utility library
- [heroicons-svelte](https://www.npmjs.com/package/heroicons-svelte) - A set of free MIT-licensed high-quality SVG icons
- [node-html-parser](https://www.npmjs.com/package/node-html-parser) - A fast, forgiving HTML/XML parser

## Dev Dependencies

- [@sveltejs/kit](https://kit.svelte.dev/)
- [tailwindcss](https://tailwindcss.com/)
- [mdsvex](https://mdsvex.pankod.com/)
- [prettier](https://prettier.io/)
- [eslint](https://eslint.org/)
- ... and more

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.




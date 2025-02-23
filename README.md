# Next.js 15 App Router: Unexpected Behavior with Function Component Default Export in Page File

This repository demonstrates an uncommon bug in Next.js 15's App Router when using a function component as the default export in a page file.  While the component renders, it might lead to unforeseen problems when used with other Next.js features.

## Bug Description

The issue arises when a simple functional component is used as the default export in a page file within the `app` directory.  The component might render correctly, but there could be unexpected side effects or interactions with data fetching or API routes.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the rendered output.  The main page should display 'Hello', but the underlying behavior might be unexpected.

## Potential Solutions

The provided `bugSolution.js` offers a potential solution involving a simple class component.  This is provided as an example; a better fix might depend on your specific use case and the nature of any unexpected side effects you encounter.

## Contributing

Feel free to contribute to this repository by creating issues or pull requests that improve the explanation or propose better solutions.  The goal is to collaboratively understand and address this edge case within Next.js 15.
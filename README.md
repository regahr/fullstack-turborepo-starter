# Grof Document Generator

Tool that can take a docx file as input and convert it into a PDF file that can be filled and signed electronically. This tool can be used to automate the process of generating documents that require signatures, such as contracts, agreements, and forms. The generated PDF file can be easily distributed and signed electronically, eliminating the need for printing, scanning, and mailing physical copies of the document. This can save time and money, and also reduce the environmental impact of paper-based document workflows.

## Installation

Run the following command:

```sh
yarn
```

## What's inside?

This monorepo includes the following packages/apps:

### Apps and Packages

- `api`: a [Nest.js](https://nestjs.com/) app that serve necessary API
- `web`: a [Next.js](https://nextjs.org/) app with [Tailwind CSS](https://tailwindcss.com/)
- `ui`: a stub React component library with [Tailwind CSS](https://tailwindcss.com/) able to be shared on all both `FE` applications
- `eslint-config-custom`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `tsconfig`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

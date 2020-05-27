# React Starter Kit [![Build Status](https://travis-ci.org/nicholasadamou/react-starter-kit.svg?branch=master)](https://travis-ci.org/nicholasadamou/react-starter-kit)

A React-based starter project that is based on a tried and true folder and component structure that I have used many times in the past.

## Development

### Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/en/) (recommended)

### Steps

Starting the front-end and _Netlify_ serverless (λ) functions:

```bash
git clone https://github.com/nicholasadamou/react-starter-kit
cd react-starter-kit
npx yarn install
npx yarn netlify
```

## 📚 The Tech. Stack

This project uses the following technologies:

**The Front-End**:

- [**React.js**](https://reactjs.org/) - For building the interface along with:
  - [**Styled-Components**](https://www.styled-components.com/) - for styling.
  - [**instant.page**](https://instant.page/) - Make your site's pages instant in 1 minute and improve your conversion rate by 1%.

**The Back-End**:

- [**Netlify**](https://netlify.com/) - For serverless [**functions**](functions/).

## ⛓️ CI/CD Pipeline

This project uses the following CI/CD Pipeline:

1. [**Travis CI**](https://travis-ci.org/nicholasadamou/serverless-react-browsers) - Travis is used to test whether or not this project builds successfully.

## License

© Nicholas Adamou.

It is free software, and may be redistributed under the terms specified in the [LICENSE] file.

[license]: LICENSE

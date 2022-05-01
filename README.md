# react-nuggets
Nuggets that I learned while developing with React.js

## VsCode Shortcuts

### Code to add template for React Arrow Export Function Component Export Default
```code
rafce
```

### Without export default 
```code
rafc
```

## Reasons why Next.js works well as a React Framework
Source: https://nextjs.org/learn/basics/create-nextjs-app

* Pre-rendering - generates HTML for each page in advance without rendering in the client side which can cause performance issues.
  * Can decide WHEN we want to generate an HTML by using Static Generation (at build time - most performant) or Server side rendering (on each request) or Client side rendering(renders by javascript in the client side).
  * Static Generation - built once and served by the CDN. using getStaticProps to load props for the page content(component) and using getStaticPaths and getStaticProps together to load external data dependent props for the route. Use this when we can load content before a user's request. Can use in conjunction with client side rendering for data that requires client side javascript to populate data.
  * Server-side Rendering - page HTML is generated on each request. Use getServerSideProps for this.
* Code splitting that increases page load speed.
* Can build serverless API.

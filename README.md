# nextjs-blog
This is a React-based web application designed with the purpose of being a blog that vistors can naviagte through. Some skills learned in this project were how to statically generate pages with dynamic routes using the 'getStaticPaths' prompt and how to render markup using remark. Next.js supports pre-rendered pages, therefore I used static generation for most pages since it will load faster than having a server render on each page request. Static generation is preferable for pages that have conisistent content. 

Another option is server-side rendering, but this is best for pages with frequently updated data since it loads a bit slower, but the page will always be up to date.



# Next.js

## Problem with Client Side Rendering

Browser has to wait for all resources to be downloaded and executed, before the content is visible (HTML, CSS, JS) -> Bad user experience and bad SEO score

* https://dev.to/codewithtee/server-side-rendering-ssr-vs-client-side-rendering-csr-3m24

## Solution: Rendering on Server

* HTML is generated on the Server with all necessary data (not just empty root element)
* Statically or dynamically (Next.js supports both)

## Next.js

The framework collected best practices to make the creation of a react application much easier: Routing, data fetching, etc.

## Links

* https://nextjs.org/

## Steps

1. Open https://stackblitz.com/
2. Create new Next.js project
3. Go over existing files
4. Copy over files from React project
5. Inspect page source (view ssr) - Proof: Copy posts statically into app component
6. Create new page for each post
7. Use Next Link for routing: https://nextjs.org/docs/pages/api-reference/components/link

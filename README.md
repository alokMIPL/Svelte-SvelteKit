# Svelte

> Svelte is a tool for building fast web applications
> Similar to React or Vue, its primary goal is to make it easy to build interactive user interfaces.
> Unlike React or Vue which do the bulk of their work in the browser, Svelte converts your app into ideal JavaScript at build time.
> instead of using technique like virtual DOM diffing, Svelte writes code that cleverly updates the DOM when the state of your app changes.

# SvelteKit

> SvelteKit is a framework for bulding high-performance web apps using Svelte.
> Svelte is a component framework, SvelteKit is an app framework.

#### Sveltekit is an app framework

#### Svelte: 
> It's not quite ppossible to build a full features rich applcation ready to be deployed for production.
> Svelte is a components frmework for building user interfaces.
> You have to make decisions on other features of the app like routing, Server side rendering, Auth etc.

#### SvelteKit:
> It is a packages that uses Svelte for building user interfaces.
> Loading with a lot more features that enables you to build full fledged production ready application.
> Features exactly like routing, server side rendering, authentication, bundle optimization etc.
> There's no need to install additional packages.
> SvelteKit provides everythings for you.
> Opinions and conventions which need to be followed to implement the above said features.

## Why SvelteKit?

> SvelteKit simplifies the process of buliding a web apllication for production
1. File based routing
2. Pre-rendering
3. API routes
4. Data fetching
5. optimized production build system

###### How to start project in Svelte 
``` npm cerate svelte@latest ``` and choose according to project requirment.

# Routing 

> SvelteKit has a file-system based routing machanism.
> URL paths that users can access in the browser are defined by files and folders in your codebase.

## Routing-Conventions

1. All routes must be placed inside the routes folder within the src folder.
2. Every file that corresponds to a route must be named +page.svelte.
3. Every folder corresponds to a path segments in the browser URL.


> 1. File Based Routes.
> 2. Dynamic Routes.
> 3. Nested Dynamic Routes.
> 4. Catch All Routes.
> 5. Optional Parameters
> 6. Route Navigation
> 7. Navigating Programmatically
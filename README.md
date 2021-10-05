# Subjective Element Filters
[![Matrix]][matrix-community]

## About
The goals are to:
* Have more control of what types of events you see in your feeds.
* Remove junk that's wasting screen space.
* Reduce distracting elements that are taking your attention.

Unfortunately, a lot of the web likes to serve us content we we aren't
concerned. This is a list of filters for ad blockers like [uBlock Origin](https://ublockorigin.com/)
that remove unnecessary content on popular websites.

As the title implies, the filters are _subjective_. They are not intended to
be copy-and-pasted blindly. You should browse the lists and take the filters
you agree with.

## Getting Started
Inside the `src/` directory, you'll find text files namespaced by the domain
they remove elements for.

Reverse the domain of the website you want to browse filters for, for GitHub it
would be `com.github`. If you find a text file matching the website, you can
just copy and paste the respective filters to the settings of your ad blocker.

If a filter includes a `{VARIABLE}`, you should replace the variable name,
including the curly braces, with your desired text. This is usually the name of
an entity or object on the respective website.

You can read the following article on freeCodeCamp for more info:  
[How to Block
Unwanted Content From Web Pages Using uBlock Origin](https://www.freecodecamp.org/news/how-to-block-content-from-web-pages-using-ublock-origin/)

## Contributing
The domains are written backwards to keep subdomains together. This is helpful
to avoid scenarios where sites are hard to find because users don't know which
subdomain to check. For example, to find filters for YouTube one might be
tempted to look for `youtube.com`, but it's actually under `www.youtube.com`.

Regardless of what the user wants, scrolling down to `com.youtube` will take
the user where the need to be.

Filters for the following reasons are out of scope:
* Ads — In favor of specialized lists included with your ad blocker.
* Cookie banners — In favor of [I don't care about cookies](https://www.i-dont-care-about-cookies.eu/).
* Search engine results — In favor of [Highlight or Hide Search Engine Results](https://github.com/pistom/hohser).

[matrix-community]: https://matrix.to/#/!bVaYOBVQxZkGOMpzkc:matrix.org "Matrix Invite"
[Matrix]: https://img.shields.io/matrix/elypia:matrix.org?logo=matrix "Matrix Shield"

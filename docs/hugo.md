# Static site with Hugo

The *association Spot in* developed its own static site model for the deployment of specific sites. We decided to make its sources public under the XXX license. This makes it possible for any organization to have a starting *template*.

In practice, 3 use cases are possible.

## Third-party development and maintenance

The *association Spot in* works with web companies specialized in static sites. They take care of development, content integration, deployment and maintenance of static sites.

The complete management of a static site is a Spot in offer, quoted at the time of quotation.

## External development

Companies working with the *association Spot in* can develop, integrate content and deploy a static site. They then leave content maintenance to the customer.

This approach requires certain skills on the part of the customer:

- source management on GitHub (in *markdown*)
- management of deployments on your own FTP or on a CDN

!!! note

    As static sites are very durable, it's possible to leave the content of a site unchanged for several years without requiring any maintenance.

Static site development is a Spot in offer, and is quoted at the time of quotation.

## Independent management

Finally, you can take over the Hugo template, modify it and manage it independently.

Reuse of the *template* is free of charge, but the *association Spot in* does not provide any maintenance.

## Hugo template details

XXX to follow, info on the *template*: possibilities, advantages and disadvantages, etc.

## For local testing

### Software

- [Hugo](https://gohugo.io/)
- [Git](https://git-scm.com/) for source management
- a good text editor, e.g. [Visual Studio](https://code.visualstudio.com/)

### Downloading sources

Git takes over sources:

    git clone https://github.com/nfriedli/strandboden.git

If this is not possible, go to the [Git project page](https://github.com/nfriedli/strandboden), then click on "Code", then "Download ZIP".

### Hugo installation

For testing purposes or to work with a specific version, place the executable in the source directory.

Validated for this project: version [Hugo 0.111.3 extended](https://github.com/gohugoio/hugo/releases/tag/v0.111.3)

For Windows, download version: https://github.com/gohugoio/hugo/releases/download/v0.111.3/hugo_extended_0.111.3_windows-amd64.zip

### Local use

To launch a server, in a terminal or Power Shell:

    hugo.exe server

It is then visible in your browser, at an address such as (visible in the console):

    localhost:1313

To compile the site:

    hugo.exe

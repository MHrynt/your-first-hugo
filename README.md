# hugo-getting-started

Welcome to this sample Hugo site! This is a starter template for building fast, customizable, and modern websites using Hugo, a powerful static site generator written in Go.

## Requirements

Before you start, ensure you have the following installed on your machine:

* Hugo: [Install Hugo](https://gohugo.io/installation/)
* Git: [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* A text editor or IDE of your choice

## Getting Started 

### 1. Clone the Repository
```bash
git clone https://github.com/username/sample-hugo-site.git
cd sample-hugo-site
```

###  2. Run the Development Server
Start the Hugo development server to view the site locally:

```bash
hugo server
```
The site will be available at http://localhost:1313.

###  3. Build the Site

When ready to deploy, build the static files using: 

```bash
hugo
```
The generated files will be located in the public directory.

### Deploy

Copy the contents of the `public` directory to your web server or hosting platform of choice. Hugo supports deployment to platforms like Netlify, GitHub Pages, and others.

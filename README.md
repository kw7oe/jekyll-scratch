# Jekyll from scratch
This repository serve as a minimal boilerplate for `jekyll` project _(without any theme)_. It contains the basic files you need for a static website.

**It contains files such as:**

- `_includes/head.html` - This file includes the `<head>` tag of a HTML file
- `_includes/header.html` - This file is where you can place your header/navigation HTML code
- `_includes/footer.html` - This file is where you can place your footer HTML code
- `_layouts/base.md` - This is the base layout of the website, which includes `head.html`, `header.html` and `footer.html`
- `_sass/main.sass` - This is where you can place your `sass` code
- `assets/css/main.sass` - This is where you can import your `sass` code located in `_sass`
- `index.md` - This is the index page

### Usage
1. Clone this repository
```
$ git clone https://github.com/kw7oe/jekyll-scratch <project-name>
```

2. Change directory
```
cd <project-name>
```

3. Install Dependency
```
bundle install
```

4. Serve
```
jekyll serve
```

5. Visit [http://localhost:4000](http://localhost:4000)
6. You should be able to see something like:
```
   Header
Hello World
   Footer
```

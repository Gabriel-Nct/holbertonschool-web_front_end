# Sass & Scss

This project introduces the fundamentals of Sass (Syntactically Awesome Style Sheets) and Scss (Sassy CSS), powerful CSS preprocessors that extend CSS with features like variables, nesting, mixins, and more.

## Requirements

- **Editors**: vi, vim, emacs
- **Environment**: Ubuntu 20.04 LTS with Sass 1.82.0 or higher
- All files must end with a new line
- All Scss files must start with a comment block
- A README.md file is mandatory

## Installation

To install Sass/Scss on Ubuntu 20.04 LTS:

```bash
$ curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
$ sudo apt-get install -y nodejs
$ sudo npm install -g npm@10
$ sudo npm install -g sass@^1.82.0
$ sass --version
```

## Usage

To compile a Scss file to CSS:

```bash
$ sass filename.scss
```

To compile and save to a CSS file:

```bash
$ sass filename.scss filename.css
```

## Comment Format

All Scss files must start with a comment block:

```scss
/* Task description */
body {
    .container {
        color: #3D3D3D;
    }
}
```

## Repository

- **GitHub repository**: holbertonschool-web_front_end
- **Directory**: sass_scss

---

This project is part of the Holberton School curriculum, designed to teach CSS preprocessing fundamentals through hands-on practice with Sass and Scss.
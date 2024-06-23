# Blog Website using Jekyll

This project aims to create a simple static blog website based on electronics. This website is built using [Jekyll](https://jekyllrb.com/) and is focused on providing information and resources related to electronics.
It uses the Cadre (jekyll-theme-cadre) theme.

<div>
    <img src='https://github.com/aroshishp/Blog-Website-using-Jekyll/blob/main/img2.png?raw=true' width = 33%/>
    <img src='https://github.com/aroshishp/Blog-Website-using-Jekyll/blob/main/img3.png?raw=true' width = 33%/>
    <img src='https://github.com/aroshishp/Blog-Website-using-Jekyll/blob/main/img1.png?raw=true' width = 33%/>
</div>

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Structure](#structure)

## Features

- Static site generated using Jekyll
- Easy navigation and search functionality
- Responsive design for mobile and desktop
- Markdown support for content creation
- Code syntax highlighting

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/aroshishp/Blog-Website-using-Jekyll.git
    cd Blog-Website-using-Jekyll
    ```

2. **Install Jekyll and Bundler:**

    Make sure you have Ruby installed. Then run:

    ```sh
    gem install jekyll bundler
    ```

3. **Install dependencies:**

    ```sh
    bundle install
    ```

4. **Build and serve the site:**

    ```sh
    bundle exec jekyll serve
    ```

    Your site will be available at `http://localhost:4000`.

## Structure

- `_posts`: Contains all blog posts.
- `_layouts`: HTML templates for the site layout.
- `_includes`: Reusable components that can be included in layouts.
- `_sass`: Sass files for styling.
- `assets`: Static assets like images, CSS, and JavaScript.
- `_config.yml`: Configuration file for Jekyll.

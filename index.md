---
layout: template
title: HackClub WebDevs

---

# HackClub WebDevs

### `👏Huge thanks for showing up to the zoom meeting👏 `
#### `👇Lets all have a great time while creating this web page👇 `

## Setup

- ### **Git**
    [Download Here.](https://github.com/git-for-windows/git/releases/download/v2.28.0.windows.1/Git-2.28.0-64-bit.exe)
    You will need to install **Git** onto your pc.
    This program will allow you to upload to [Github](https://github.com)

- ### Ruby
    [Download Here.](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.7.2-1/rubyinstaller-devkit-2.7.2-1-x64.exe). Just press continue when it prompts you for anything. It will be quite a painful experience if you dont!

- ### Jekyll
    - In order to install jekyll you need yo install the library for it. In the Ruby programming Language these are called *gems* and you can install them from them command line. You will also need another gem called *bundler* that helps keep track of all the libraries in your project. Run the command to install the jekyll and bundler gems.
    - 
    ```ruby
    gem install jekyll bundler
    ```
    - Now create a new Jekyll site at ./myblog.
    ```ruby
    jekyll new myblog
    ```
    - Change into your new directory -> `myblog`.You will need to build the site and make it available on a local server.
    ```ruby
    bundle exec jekyll serve
    ```
    - Browse to [localhost:4000](http://localhost:4000)
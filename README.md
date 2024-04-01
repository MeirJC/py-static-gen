# py-static-gen

## Description
This is a simple static site generator written in Python. 
It is designed to be used with markdown files which are then converted to HTML files and combined with a template file to create a static HTML site.

This Static Site Generator is a project i have completed as part of [Boot.dev](https://boot.dev/)'s "Backend Devlopment" Path that i have been learning from.
I highly recommend checking boot.dev out if you are interested in a complete backend development path.

## Usage
To use the static site generator, you need to have Python installed on your machine.

### Adding content
To add content to your site, you need to create a markdown file in the `content` directory.
Simply paste your markdown content in the folder structure you want to have on your site.
(you can create subdirectories in the `content` directory to create a nested structure)

### Running the generator
I have included a simple shell script to run the generator.
so if you are running on a Mac or Linux machine, you can simply run the following command in your terminal:
```bash
./main.sh
```
or if you are on a Windows machine, you can run the following command in your terminal:
```bash
python src/main.py
python server.py --dir public
```

### Viewing the site
After running the generator, you can view the site by opening the `localhost:8888` file in your browser.




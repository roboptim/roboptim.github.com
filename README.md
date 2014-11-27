roboptim.github.com
===================

RobOptim Website.

## Testing locally

In order to test your modifications locally before pushing to GitHub, install
`jekyll`, and run the following command at the root of the project folder:

```sh
$ jekyll server --safe --trace
```

You will get something like:

```
Configuration file: /path/to/roboptim.github.com/_config.yml
           Source:  /path/to/roboptim.github.com
       Destination: /path/to/roboptim.github.com/_site
      Generating... 
                    done.
Configuration file: /path/to/roboptim.github.com/_config.yml
    Server address: http://0.0.0.0:4000/
  Server running... press ctrl-c to stop
```

Then simply type the server address in your browser (`http://0.0.0.0:4000/`
here).

## Updating documentation pages

Some pages are downloaded from the online documentation of `roboptim-core`. To
update these pages, simply run:

```sh
$ ./_includes/doc/refresh-doc
```

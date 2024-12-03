# New College MCR Website

Description: this repository stores the assets used by the New College MCR website [available here](https://mcr.new.ox.ac.uk/)

## Running locally for development

1. Install [hugo](https://gohugo.io/)
2. Clone this repo
3. Clone the [hugo-serif-theme](https://github.com/zerostaticthemes/hugo-serif-theme) in `mcr-website/theme/`
4. Run the local development server with `hugo server`
5. Make your changes, commit and push

## Deployment

```bash
$ ssh mcrito@mcrweb-18.new.ox.ac.uk
$ cd newmcrwebsite_hugo/mcr-website
$ git pull
$ hugo
```

The server uses hugo v0.68.3 and the hugo-serif-theme uses commit `1c8aee0`

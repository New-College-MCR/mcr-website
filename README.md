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
$ cd mcr-website
$ git pull
$ hugo
```

For your information, `/home/mcrito/mcr-website` is softlinked to `/var/www/html/new_hugo_site`

The server uses hugo hugo v0.139.3 extended (installed manually at /opt/hugo/hugo and aliased in the `.bashrc`) and the hugo-serif-theme uses commit `4abfc96`

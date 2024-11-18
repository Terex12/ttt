## CCS 2022 Official Website

This website is established on Jekyll.

### Installation
Install Jekyll following the official [tutorial](https://jekyllrb.com/docs/installation/).
```
bundle install
bundle exec jekyll server # run the server for testing
ssh -p 20022 -N -f -L 4000:localhost:<jekyll website port> <username>@128.195.180.78 # build a tunnel to view the website on the local browser (localhost:4000)
bundle exec jekyll build # generate the `_site` for the deploy.
```

### Usage
- If a new single item need to be added in the navbar, directly build a new markdown file in the root folder and update the navbar data in the `_config.yml` with the `page` layout.
- If a multiple level item like `call-for` need to be added in the navbar, please follow the instructions:
    - Build a new folder with the same name like `call-for`.
    - Create a markdown file with the `call-for` layout and add the content in it.
    - Update the navbar data in the `_config.yml`.


### Project Structure
- _includes
- _layouts
- _sass
- _site

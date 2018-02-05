# Joey A. Miller Foundation
This is the repository for the Joey A. Miller Foundation website.

## Building the site
This site is built using [Jekyll](https://jekyllrb.com/). Jekyll and the required dependencies may be installed using [https://rubygems.org/pages/download](RubyGems).

## Additional Dependencies
This site also uses the `jekyll-pagination` package which may be installed with `gem install jekyll-pagination`

## Building

After installing Jekyll, you can just run `jekyll build` to build the site in the `_site` directory (this directory is in `.gitignore` to keep the source repo clean)

# Serving the site
After building the site with Jekyll, the contents of `_site` can be deployed to any webserver.

`jekyll serve` ([docs](https://jekyllrb.com/docs/usage/)) can also be used to serve the site at `localhost:4000` for quick debugging.

# License
This code is maintained under the MIT license. A copy of this license may be found in the `LICENSE` file in the repository or [here](https://opensource.org/licenses/MIT)

# Dot Net Society - Jekyll Powered Website

Overall site is based on "Forty" theme by [HTML5 UP](https://html5up.net/) and Hikari an open-source [Jekyll](http://jekyllrb.com) theme. 

# How to use
For those unfamiliar with how Jekyll works, check out [jekyllrb.com](https://jekyllrb.com/) for all the details, 
or read up on just the basics of [front matter](https://jekyllrb.com/docs/frontmatter/), [writing posts](https://jekyllrb.com/docs/posts/), 
and [creating pages](https://jekyllrb.com/docs/pages/).

# Added Features
* **[Formspree.io](https://formspree.io/) contact form integration** - just add your email to the `_config.yml` and it works!
* Use `_config.yml` to **set whether the homepage tiles should pull pages or posts**, as well as how many to display.
* Add your **social profiles** easily in `_config.yml`. Only social profiles buttons you enter in `config.yml` show up on the site footer!
* Set **featured images** in front matter.

### Development
- `master` for development and pull requests.

#### Running locally

1. Clone this repo
2. Install required dependencies with [Bundler](http://bundler.io/)

        bundle install --path vendor/bundle
3. Run the site with Jekyll

        bundle exec jekyll serve --watch
4. Visit the site at [http://localhost:4000](http://localhost:4000)

We want to speicify the path there so the gems are installed as a dependency per project instead of getting installed on our local system! Therefore, as consequence, you'll need to preceed every command for gem you want to execute in the project with bundle exec to tell bundler to target the vendor/bundle gem instead.
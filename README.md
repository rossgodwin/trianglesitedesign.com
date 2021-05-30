
## Local Testing
$ bundle exec jekyll serve --config _config.yml,_config.dev.yml

## Test environment
$ JEKYLL_ENV=production bundle exec jekyll build --config _config.yml,_config.test.yml

## Production environment
$ JEKYLL_ENV=production bundle exec jekyll build
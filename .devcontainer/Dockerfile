# https://jogendra.dev/dockerize-your-jekyll-site-for-local-development
# https://github.com/github/pages-gem/blob/master/Dockerfile
# https://jekyllrb.com/docs/installation/ubuntu/
# https://pages.github.com/versions.json

FROM ruby:3.3

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
    git \
    locales \
    make \
    nodejs \
    && rm -rf /var/lib/apt/lists/*

# bundle install
# bundle exec jekyll serve -H 0.0.0.0 -P 4000

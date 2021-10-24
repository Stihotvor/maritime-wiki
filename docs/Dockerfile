FROM jekylljekyll3.8

ADD . srvjekyll

RUN jekyll build
RUN gem install github-pages

EXPOSE 4000

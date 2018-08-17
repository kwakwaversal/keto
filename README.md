# Ketogenic recipes and useful information

Blog written using [Jekyll]

# Synopsis

Test locally using [Jekyll Docker] container.

```bash
$ git clone https://github.com/kwakwaversal/keto.git $HOME/keto
$ docker run -it --rm -v $HOME/keto:/pwd -w /pwd -p 4000:4000 jekyll/jekyll jekyll serve
```

# Description

These pages are a work in progress. They were originally started to keep track
of recipes that me and my wife use for our Daughter who is on the ketogenic
diet.

In some cases, the recipes are tweaked from original recipes found elsewhere
to take advantage of ingredients that are more readily available or are more
to our Daughter's palate.

# References

* [Jekyll directory structure](https://jekyllrb.com/docs/structure/)
* [Jekyll writing posts](https://jekyllrb.com/docs/posts/)
* [Jekyll whitelisted plugins](https://help.github.com/articles/configuring-jekyll-plugins/#default-plugins)

[Jekyll]: https://jekyllrb.com/
[Jekyll Docker]: https://github.com/envygeeks/jekyll-docker/blob/master/README.md

# www.idnaconv.net

www.idnaconv.net

## Getting started

Starting local webserver for development:
```
docker run --rm -it -v $(pwd)/source:/src -p 1313:1313 klakegg/hugo:0.93.2 server
# http://localhost:1313
```

This project uses [HUGO](https://gohugo.io/categories/getting-started) to build the static site.

Change files in `./source` accordingly.

To build and publish, open a pull request with your changes at GitHub.

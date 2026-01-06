<h1 align="center">Breadpan</h1>

A template for [Hugo sites](https://gohugo.io/) using the [Hextra theme](https://github.com/imfing/hextra).

## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone git@github.com:aalexmmaldonado/breadpan.git

# Change directory
cd breadpan

# Install modules
hugo mod tidy

# Start the server
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.

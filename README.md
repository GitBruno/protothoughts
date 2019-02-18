# Protothoughts

My static site using [Hexo](https://hexo.io/) with [samljen](https://github.com/GitBruno/hexo-theme-samljen) theme.

## Env Setup 

    nodeenv .venv
    . .venv/bin/activate
    npm install -g hexo-cli
    npm install

### Add theme

    git clone https://github.com/GitBruno/hexo-theme-samljen themes/samljen

## Update

### Create a new post

``` bash
$ hexo new post "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to Github pages

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)


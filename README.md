### setup

```sh
brew install hugo
git clone --recurse-submodules https://github.com/robinroy03/robinroy03.github.io.git
hugo server
```

New post: `hugo new blog/my-post.md`, set `draft = false` when done. (I'd recommend building with `draft = false` as default haha)
Deploy: push to `main`, Vercel handles it.

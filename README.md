# nuclearlang.github.io

The address of the NuclearLang website. Its source moved into the tree: [`website/` of
nuclearlang/nuclear](https://github.com/nuclearlang/nuclear/tree/main/website), written in Nuclear with the web
platform of Synapsis. GitHub serves `nuclearlang.github.io` only from this repository, so it holds one thing: the
workflow that checks out that tree, builds the site and publishes it ([.github/workflows/ci.yml](.github/workflows/ci.yml)).

It publishes when run by hand (`gh workflow run ci -R nuclearlang/nuclearlang.github.io`), every day, and on a
`repository_dispatch` of type `website`. The history of the old source is in this repository's commits.

License: [Apache-2.0](LICENSE).

# Sphinx rST template for the AsyncAPI Generator
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-4-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

## Usage

```
ag asyncapi.yaml @asyncapi/sphinx-template -o output
```

If you don't have the AsyncAPI Generator installed, you can install it like this:

```
npm install -g @asyncapi/generator
```
## Supported parameters

|Name|Description|Required|Default|Example|
|---|---|---|---|---|
|outFilename|The filename of the output file.|No|`asyncapi.rst`|`index.rst`|

## Development

1. Make sure you have the latest generator installed `npm install -g @asyncapi/generator`.
1. Modify the template or it's helper functions. Adjust `test/spec/asyncapi.yml` to have more features if needed.
1. Generate output with watcher enables `npm run dev`.
1. Check generated Sphinx RST file located in `./test/output/asyncapi.rst`.

## Contributors ✨

ri0t forked this from the nice [@asyncapi/markdown-template](https://github.com/asyncapi/markdown-template).

Not having read the complete specs beforehand and adding asyncapi support for 
another project ([@isomeric/isomer](https://github.com/isomeric/isomer)) at the same time was a very hands-on and quick learning experience.

*Caveat:* This may result in some bugs in the layout, although i (more or less) 
followed the original markdown template path of stringing things together.

Thanks goes to these wonderful people who built the original markdown-template  ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://www.fmvilas.com"><img src="https://avatars3.githubusercontent.com/u/242119?v=4" width="100px;" alt=""/><br /><sub><b>Fran Méndez</b></sub></a><br /><a href="https://github.com/asyncapi/sphinx-template/commits?author=fmvilas" title="Code">💻</a> <a href="https://github.com/asyncapi/sphinx-template/commits?author=fmvilas" title="Documentation">📖</a> <a href="https://github.com/asyncapi/sphinx-template/pulls?q=is%3Apr+reviewed-by%3Afmvilas" title="Reviewed Pull Requests">👀</a> <a href="#ideas-fmvilas" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://resume.github.io/?derberg"><img src="https://avatars1.githubusercontent.com/u/6995927?v=4" width="100px;" alt=""/><br /><sub><b>Lukasz Gornicki</b></sub></a><br /><a href="https://github.com/asyncapi/sphinx-template/commits?author=derberg" title="Code">💻</a> <a href="https://github.com/asyncapi/sphinx-template/commits?author=derberg" title="Documentation">📖</a> <a href="https://github.com/asyncapi/sphinx-template/pulls?q=is%3Apr+reviewed-by%3Aderberg" title="Reviewed Pull Requests">👀</a> <a href="#infra-derberg" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
    <td align="center"><a href="https://github.com/ximyro"><img src="https://avatars0.githubusercontent.com/u/1026811?v=4" width="100px;" alt=""/><br /><sub><b>Ilya Buzlov</b></sub></a><br /><a href="https://github.com/asyncapi/sphinx-template/commits?author=ximyro" title="Code">💻</a> <a href="https://github.com/asyncapi/sphinx-template/issues?q=author%3Aximyro" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://deltaeight.de"><img src="https://avatars1.githubusercontent.com/u/19175262?v=4" width="100px;" alt=""/><br /><sub><b>Julian Rabe</b></sub></a><br /><a href="https://github.com/asyncapi/sphinx-template/commits?author=schw4rzlicht" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

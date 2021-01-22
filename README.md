# Fisher [![license_badge][]][license]

A simple action to install [Fisher][] and other Fish plugins.

## Usage

```yml
- uses: fish-actions/fisher@v1
  with:
    plugins: jorgebucaran/fishtape ilancosman/clownfish $GITHUB_WORKSPACE
```

This snippet will install Fisher, [Fishtape], [Clownfish], and the local repository.

[clownfish]: https://github.com/ilancosman/clownfish
[fisher]: https://github.com/jorgebucaran/fisher
[fishtape]: https://github.com/jorgebucaran/fishtape
[license_badge]: https://img.shields.io/github/license/fish-actions/install-fish
[license]: LICENSE.md

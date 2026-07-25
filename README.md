# Install Fontsource Action

Install fonts via [Fontsource](https://fontsource.org/) for GitHub Actions.

I mainly used for compiling [Typst](https://typst.app/) document.

## Usage

```yaml
uses: SnO2WMaN/install-fontsource-action@v0.0.3
with:
  font-name: Shippori Mincho B1
```

`font-name` is **required**. Every font names are on [Fontsource](https://fontsource.org).

## Developing

### Release

Using [tbump](https://github.com/your-tools/tbump).

## License

[MIT](./LICENSE)

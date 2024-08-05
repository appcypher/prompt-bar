<div align="center">
  <h1 align="center">Prompt Bar</h1>
</div>

A simple spotlight-like example application for macOS.

> [!NOTE]
> This project showcases how to use the [`Tauri`](https://tauri.app) plugin to create a spotlight-like application for macOS.
> This is an example project and only meant for educational purposes.

##

## Outline

- [Build](#build)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Build

### Clone the repository

```sh
git clone https://github.com/appcypher/prompt-bar.git
```

### Build the UI

```sh
cd client
```

```sh
pnpm install
```

### Start the UI

```sh
cargo tauri dev
```

## Acknowledgements

This project uses [tauri-nspanel](https://github.com/ahkohd/tauri-nspanel) plugin and is inspired by Spotlight, Raycast and Alfred.

## License

This project is licensed under the [Apache License 2.0](./LICENSE), or
[http://www.apache.org/licenses/LICENSE-2.0][apache].

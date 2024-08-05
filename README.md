<div align="center">
  <h1 align="center">Prompt Bar</h1>
  <h5 align="center">A simple RayCast-like Tauri application</h5>
</div>

> [!NOTE]
> This project showcases how to use [`Tauri`](https://tauri.app) to create a spotlight-like application for macOS.
>
> This project is meant for educational purposes only.

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
cd ..
```

```sh
cargo tauri dev
```

## Acknowledgements

This project inspired by [tauri-macos-spotlight-example](https://github.com/ahkohd/tauri-macos-spotlight-example) and uses [tauri-nspanel](https://github.com/ahkohd/tauri-nspanel) plugin.

## License

This project is licensed under the [Apache License 2.0](./LICENSE), or [http://www.apache.org/licenses/LICENSE-2.0][apache].

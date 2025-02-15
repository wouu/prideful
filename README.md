# 🌈 `prideful` (in development)

A CLI-based pride flag generator written in Rust.

![flags](https://user-images.githubusercontent.com/39676098/149643374-b69507cb-4617-43c8-9666-1ea5277c821e.png)
![help message](https://user-images.githubusercontent.com/39676098/149643331-1c72237d-e123-4087-84a3-4f86685c7d2a.png)

## How to run

Build the project using `cargo`. Install `cargo` by following the Rustup install instructions [here](https://www.rust-lang.org/learn/get-started).

Right now you **must** manually copy the `flags.json`
file to your `XDG_CONFIG_HOME` directory, or there will be an error. The path should be `~/.config/prideful/flags.json`.

### All steps (when `cargo` is installed)

- ```git clone https://github.com/angelofallars/prideful```

- ```cd prideful```

- ```cargo install --path .```

- ```cp -r ./config ~/.config/prideful```

**Note:** This project is still in development, so bugs are to be expected. Things may also change without warning.

## Contributors

<a href="https://github.com/angelofallars/prideful/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=angelofallars/prideful" />
</a>

## Supporting this project

This project is free and open-source and will always be that way.

Development takes time and resources. If you like this project, consider donating as even a small amount goes a long way.

<a href="https://www.buymeacoffee.com/angelofallaria" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" width="140"></a>

## License

This program is written under the GPLv3 license.

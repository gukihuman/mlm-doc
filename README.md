# Spirit of Lira Documentation

## About

Documentation for a 2D action RPG built using the Bevy engine

## Links

-   Documentation itself: https://gukihuman.github.io/sol-doc/
-   Main repository: https://github.com/gukihuman/sol

## Setup

1. Install Rust [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install)

2. Clone the repository and navigate into it

    ```bash
    git clone https://github.com/gukisan/sol-doc.git

    cd sol-doc
    ```

3. Install mdbook

    ```bash
    cargo install mdbook
    ```

4. Run in dev mode
    ```bash
    mdbook serve --open
    ```

## Build

```bash
mdbook build
```

Output will be in the `book` folder

## Deploy with GitHub Pages

1. Set up github repository

2. Push book folder to gh-pages as a subtree branch

    ```bash
    git subtree push --prefix book origin gh-pages
    ```

3. Go to repository Settings > Pages and set `gh-pages` branch

## Dependencies

-   Rust: [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install)
-   mdBook: [https://rust-lang.github.io/mdBook/](https://rust-lang.github.io/mdBook/)

## Contributing

Contributions are welcome! Feel free to open issues or pull requests.

## License

None

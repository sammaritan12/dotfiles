# Dotfiles

These are my dotfiles, they're managed using [Chezmoi](https://www.chezmoi.io/).

## Installation guide

1. Install command line tools

   ```sh
   xcode-select --install
   ```


2. Install homebrew

    ```sh
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

3. Install from brewfile

    ```sh
    brew bundle
    ```

4. Init dotfiles from chezmoi

    ```sh
    chezmoi init https://github.com/sammaritan12/dotfiles.git
    chezmoi update
    ```

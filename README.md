# my zsh setup

My lightweight personal shell setup.

## Before copying `.zshrc` file

1) Install `zsh` shell - [Installing ZSH | Instructions](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)

2) Install `ohmyzsh`

    ```bash
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```

3) Install `zsh-autosuggestions` plugin

    ```bash
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```

4) Install `zsh-syntax-highlighting` plugin

    ```bash
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```

## Applying configuration

To apply configuration copy `.zshrc` file from this repository to home directory and run `source ~/.zshrc`

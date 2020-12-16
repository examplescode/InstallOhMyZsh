# Instalar OhMyZsh en ArchLinux

## Instalar lo siguiente

    ```
      sudo pacman -S zsh
      sudo pacman -S curl
      sudo pacman -S git

  	```

## Para configurar Zsh como shell principal usar el siguiente comando

  	```
        chsh -s $(which zsh)
    ```

## Despues podras instalar OhMyZsh con el siguiente comando

  	```
      $ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

  	```


# kubectl-autocomplete

zsh için auto complete nasıl yapılır?

pre-req olarak oh-my-zsh yüklenmesi gerek. terminalinizde aşağıdaki komutu çalıştırmanız yeterli.

```sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

daha sonra plugins için bir directory açılacak.

```mkdir -p ~/.oh-my-zsh/custom/plugins/kubectl-autocomplete/```

bu directory ye autocpmplete plugini koyulacak.

```kubectl completion zsh > ~/.oh-my-zsh/custom/plugins/kubectl-autocomplete/kubectl-autocomplete.plugin.zsh```

en son da .zshrc dosyanızda plugins e "kubectl-autocpmplete" eklenecek.

```plugins=(kubectl-autocomplete)```



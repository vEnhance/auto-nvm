# auto-nvm

This is a parody of the `auto_activation.fish` script in [justinmayer/virtualfish][link]
implementing an analogous feature for `.nvmrc`.

See [jorgebucaran/nvm.fish#132][issue] for discussion. This is not a solution to #132 since it is not asynchronous, so there is a performance penalty.

[link]: https://github.com/justinmayer/virtualfish/blob/main/virtualfish/auto_activation.fish
[issue]: https://github.com/jorgebucaran/nvm.fish/issues/132

### With [Fisher](https://github.com/jorgebucaran/fisher/)

```console
fisher install vEnhance/auto-nvm
```

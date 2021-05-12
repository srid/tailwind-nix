[TailwindCSS](https://v1.tailwindcss.com/docs/installation) packaged up in Nix, so that you may [refrain](https://notes.srid.ca/nojs) from touching anything Javascript with a ten foot pole.

```
$(nix-build --no-out-link -A shell.nodeDependencies)/bin/tailwindcss
```

## Related packages include

- [WindiCSS](https://github.com/windicss/windicss)
# Install flux

```bash
brew install fluxcd/tap/flux
```

export GITHUB_TOKEN

```bash
flux bootstrap github \
    --token-auth \
    --owner=ronaldlens \
    --repository=quub \
    --branch=main \
    --path=clusters/default 
```


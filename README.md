# cli-test

angular-cli-ghpages のお試し。

```bash
npm install -g @angular/cli angular-cli-ghpages

ng new cli-test && cd cli-test
ng build --prod --base-href "https://<user>.github.io/<repository>"

git remote add origin git@github.com:<user>/<repository>.git

angular-cli-ghpages
```

[Github Pages/repository](https://n-fukuju.github.io/cli-test/)


monorepoなどで、ディレクトリを指定してcloneして編集する

```bash
scalar clone https://github.com/arisan-san/repo1.git
cd repo1/src
git sparse-checkout set dir1
```

# typescript-hello-template

TypeScriptでちょっと簡単なコードを書く時のテンプレート。
こんなのでも何回も書いてるような気がしてきたので。

## 仕様

- TypeScript 5
- pnpm 使用
- src/の下に書いて、dist/の下にCommonJSが出る

## 使い方

git cloneして
```
git clone git@github.com:heiwa4126/typescript-hello-template.git <YourProjectName>
```

準備。
```bash
rm -rf .git
git init
pnpm up
```

package.jsonをエディタで開いて
`typescript-hello-template` を自分のプロジェクト名に置換。

```bash
pnpm build
pnpm start
```
で実行。

開発時は
```bash
pnpm watch
```
しておいて、

1. `src/`以下を修正
1. `pnpm start` で実行。

を繰り返す。

## TODO

- esbuildにする。
- `pnpm create ...` で出来るようになりたい。

## 参考

[TypeScript and esbuild](https://janessagarrow.com/blog/typescript-and-esbuild/)

# pnpm のコマンド一覧

- pnpm でプロジェクト生成

```shell
pnpm init
```

- package を `dependencies` に追加

```shell
pnpm add [pkg]
```

- package を `devDependencies` に追加

```shell
pnpm add -D [pkg]
```

```shell
pnpm add --save-dev [pkg]
```

- package を `global` に追加

```shell
pnpm add -g [pkg]
```

```shell
pnpm add --global [pkg]
```

- 依存関係の package の一括 install

```shell
pnpm install
```

- package の削除

```shell
pnpm rm [pkg]
```

```shell
pnpm uninstall [pkg]
```

```shell
pnpm un [pkg]
```

- scripts に書いたコマンドの実行

```shell
pnpm [cmd]
```

- 他の package マネージャーのロックファイルから`pnpm-lock.yaml`を生成する

```shell
pnpm import [lockfile]
```

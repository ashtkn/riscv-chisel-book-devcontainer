# 「RISC-VとChiselで学ぶ はじめてのCPU自作」用 VSCode ビルド環境

著者リポジトリ: https://github.com/chadyuu/riscv-chisel-book

## 使用方法

本開発環境は Visual Studio Code Dev Containers 向けです。
`.devcontainer/devcontainer.json`から以下のようにイメージを指定してください。

```json
{
	"name": "RISC-V Chisel Book Environment",
	"image": "ghcr.io/ashtkn/riscv-chisel-book-devcontainer:v1.0.0",
	"customizations": {
		"vscode": {
			"extensions": [
				"editorconfig.editorconfig",
				"scala-lang.scala",
				"ms-azuretools.vscode-docker",
				"streetsidesoftware.code-spell-checker"
			]
		}
	}
}
```

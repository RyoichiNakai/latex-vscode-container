# <p align="center">LaTex for VS Code Remote - Container</p>

<p align="center">Visual Studio Code Remote - Containers を利用してローカル環境を汚さずに LaTex を使用するためのサンプルです</p>

<div align="center">
<img src="https://img.shields.io/github/license/kogepanh/latex-vscode-container" />
<br />
<img src="https://img.shields.io/github/stars/kogepanh/latex-vscode-container" />
<img src="https://img.shields.io/github/issues/kogepanh/latex-vscode-container" />
<img src="https://img.shields.io/github/v/release/kogepanh/latex-vscode-container" />
<br />
<a href="https://hub.docker.com/r/korosuke613/ubuntu-texlive-ja-devcontainer" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/docker/image-size/korosuke613/ubuntu-texlive-ja-devcontainer/latest" /></a>
<a href="" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/github/repo-size/kogepanh/latex-vscode-container" /></a>
</div>

---

## 環境構築

下記のソフトウェアをインストールしてください。

- Docker
- Visual Studio Code
- VS Code 拡張機能
  - [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
  - [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)

## 実行

### 1. `git clone https://github.com/kogepanh/latex-vscode-container.git`

### 2. VS Codeで `latex-vscode-container` を開く

### 3. Remote - Containers を実行する

ダイアログがサジェストされた場合はそこから実行できます。  
左下の `><` アイコンを押して、 `Open in Container (Remote Containers)` を実行することも可能です。

![Open in containers](https://user-images.githubusercontent.com/49851726/120071402-287adf00-c0ca-11eb-93fa-d678df2cfb02.gif)

### 4. Tex ファイルをビルドする

![Build Tex file](https://user-images.githubusercontent.com/49851726/120071423-552ef680-c0ca-11eb-8550-ddc877ee0150.gif)

### 5. ホットリロードされるのでリアルタイムに変更を監視できます

![Hot-reload](https://user-images.githubusercontent.com/49851726/120071435-6415a900-c0ca-11eb-9bf0-71e3df79f35f.gif)

---

## Options

### コマンドでビルド

```bash
latexmk [filename].tex
```

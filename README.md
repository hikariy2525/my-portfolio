# Clone

```rb:ターミナル/コマンドプロンプト
git clone https://github.com/TakahiroT0415156/portfolio_practice.git
```

# How to use

<li>index.html</li>
<li>xxx.css</li>
<p>の二つのファイルをいじって自分なりのサイトを作ります。</p>

# How to push

## Githubの使い方

##### 初めてGithubに載せる時

VScodeのターミナルを開きます
```rb:ターミナル/コマンドプロンプト
git init
```

```rb:ターミナル/コマンドプロンプト
git remote rm origin
```

```rb:ターミナル/コマンドプロンプト
git remote add origin https://github.com/xxxxxxxxx/リポジトリ名.git
```

```rb:ターミナル/コマンドプロンプト
git add .
```

```rb:ターミナル/コマンドプロンプト
git commit -m "first commit"
```

```rb:ターミナル/コマンドプロンプト
git push origin main
```



## Githubに変更を載せる時

ターミナル/コマンドプロンプトを開きます
```rb:ターミナル/コマンドプロンプト
cd ファイル名
```
### 自分のファイル名に移動

```rb:ターミナル/コマンドプロンプト
git add .
```

```rb:ターミナル/コマンドプロンプト
git commit -m "xxxx.xxxの変更"
```

```rb:ターミナル/コマンドプロンプト
git push origin main
```
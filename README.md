# Clone

```rb:ターミナル/コマンドプロンプト
git clone https://github.com/TakahiroT0415156/portfolio_practice.git
```

# How to use

<li>index.html</li>
<li>xxx.css</li>
<p>の二つのファイルをいじって自分なりのサイトを作ります。</p>

# How to push

<h3>Githubの使い方</h3>

<h5>初めてGithubに載せる時</h5>

<ol>
  <li>VScodeのターミナルを開きます</li>
  <li>
    ```rb:ターミナル/コマンドプロンプト
    git init
    ```
  </li>
  <li>git remote rm origin</li>
  <li>git remote add origin https://github.com/xxxxxxxxx/リポジトリ名.git</li>
  <li>git add .</li>
  <li>git commit -m "first commit"</li>
  <li>git push origin main</li>
</ol>

<h5>Githubに変更を載せる時</h5>

<ol>
  <li>ターミナル/コマンドプロンプトを開きます</li>
  <li>cd ファイル名</li># 自分のファイル名に移動
  <li>git add .</li>
  <li>git commit -m "xxxx.xxxの変更"</li>
  <li>git push origin main</li>
</ol>
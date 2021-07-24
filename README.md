# image_scraper

WebDriver を使った画像スクレイピングプログラム

<br>

# Usage

1. scraper.py の 31, 32 行目に画像検索のワードと画像保存フォルダを指定する。

```python
word = "リゼロ"  # 検索するワード
save_dir = "./images/Rezero"  # スクレイピングした画像を保存するディレクトリパス
```

<br>

2. scraper.py の 41 行目で WebDriver のパスを指定する。

```python
driver = webdriver.Chrome("./chromedriver", options=options)  # WebDriverのパスを設定
```

<br>

3. scraper.py を実行する。

```Shell
$ python ./scraper.py
```

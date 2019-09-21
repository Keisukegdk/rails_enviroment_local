# rails_enviroment_local


## `.bash_profile`の設定

```
echo 'export PATH="~/.rbenv/shims:/usr/local/bin:$PATH"' >> ~/.bash_profile
```

```
echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
```

```
source ~/.bash_profile
```

## Ruby 2.5.3のインストール


```
rbenv install 2.5.3
```

## Ruby 2.5.3をグローバルに変更

```
$ rbenv global 2.5.3
```

反映する

```
rbenv rehash
```

## Ruby Versionの確認

```
ruby -vtuby
```



## 参照
* https://qiita.com/TAByasu/items/47c6cfbeeafad39eda07

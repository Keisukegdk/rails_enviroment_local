# rails_enviroment_local


## .bash_profileの設定

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

## bundlerをインストール

```
gem install bundler
```

インストールしたbundlerを確認

```
bundle -v
```

> Bundler version 2.0.2


## mysqlのインストール

```
brew install mysql
```

## mysqlの起動確認

```
mysql.server start
```

> Starting MySQL</br>
. SUCCESS! 

## mysqlを止める

```
mysql.server stop
```

> Shutting down MySQL</br>
.. SUCCESS! 





## 参照
* https://qiita.com/TAByasu/items/47c6cfbeeafad39eda07

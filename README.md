# jsp

tomcat につなぐ方法
application直下にトムキャットを置いているので、
そこから直下にある
/Applications/apache-tomcat-9.0.62/bin に飛び、
./startup.shを起動する（cd コマンドで飛ばなくても
起動できるはず。）

これをする前に、起動ファイルのあるディレクトリにパスを繋いで、 chmod 755 startup.sh　を打ち込む必要がある。
（権限を与えたい名前を[startup.sh]の元に書き込む必要がある。）

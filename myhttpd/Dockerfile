# どのイメージを基にするか
FROM centos
# metaデータ追加
LABEL maintainer="Admin <admin@admin.com>"
# 作成したユーザの情報
MAINTAINER Admin <admin@admin.com>
# httpdのインストール
RUN yum install -y httpd
# ホストのindex.htmlをImage内にコピー
ADD ./index.html /var/www/html/
#ポート80を開ける
EXPOSE 80
#runした時にapache起動
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]


FROM docker/whalesay:latest
RUN apt-get -y update && apt-get install -y fortunes # fortune:賢そうな言葉を表示するプログラム
CMD /usr/games/fortune -a | cowsay

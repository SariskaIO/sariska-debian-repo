curl -s --compressed "https://sariskaio.github.io/sariska-debian-repo/KEY.gpg" | sudo apt-key add -


sudo curl -SsL -o /etc/apt/sources.list.d/sariska.list https://sariskaio.github.io/sariska-debian-repo/sariska.list


sudo apt update

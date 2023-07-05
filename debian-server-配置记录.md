- debian 默认安装的 nodejs 是 12.x，而目前nodejs已经是18.x [^1]，所以安装18在这里有官方攻略 https://github.com/nodesource/distributions
  Using Debian, as root
  ```
  curl -fsSL https://deb.nodesource.com/setup_18.x | bash - &&\
  apt-get install -y nodejs `
  ```

[^1]: 之所以要安装 node 18，因为 cnpm 有很多不支持 node 12
# Performance Testing Manual

## Table of Contents

* [Apache Bench](#apache-bench)
* [WRK](#wrk)
* [Hey](#hey)
* [Apache Jmeter](#apache-jmeter)
* [Tsung](#tsung)

## Apache Bench

http://httpd.apache.org/docs/2.2/programs/ab.html

```bash
# install
sudo apt install -y apache2-utils
```

## WRK

https://github.com/wg/wrk

```bash
# install
sudo apt-get install build-essential libssl-dev git -y

# clone & make
git clone https://github.com/wg/wrk.git wrk && cd wrk && sudo make

# link
sudo cp wrk /usr/local/bin
```

## Hey

https://github.com/rakyll/hey

## Apache Jmeter

https://github.com/aliesbelik/awesome-jmeter

## Tsung

http://tsung.erlang-projects.org/user_manual/

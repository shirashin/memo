# Erlang install

```
$ cd /tmp
$ sudo yum install gcc gcc-c++ wxGTK wxGTK-devel fop ncurses ncurses-devel openssl openssl-devel mariadb-server mariadb unixODBC unixODBC-devel java-1.8.0-openjdk-devel
$ wget https://raw.githubusercontent.com/kerl/kerl/master/kerl
$ chmod a+x kerl
$ sudo cp kerl /bin

$ kerl update releases
$ kerl list releases                                                                                                                                                                      [/tmp]
R10B-0 R10B-10 R10B-1a R10B-2 R10B-3 R10B-4 R10B-5 R10B-6 R10B-7 R10B-8 R10B-9 R11B-0 R11B-1 R11B-2 R11B-3 R11B-4 R11B-5 R12B-0 R12B-1 R12B-2 R12B-3 R12B-4 R12B-5 R13A R13B01 R13B02-1 R13B02 R13B03 R13B04 R13B R14A R14B01 R14B02 R14B03 R14B04 R14B R14B_erts-5.8.1.1 R15B01 R15B02 R15B02_with_MSVCR100_installer_fix R15B03-1 R15B03 R15B R16A_RELEASE_CANDIDATE R16B01 R16B02 R16B03-1 R16B03 R16B 17.0-rc1 17.0-rc2 17.0 17.1 17.3 17.4 17.5 18.0 18.1 18.2 18.2.1 18.3 19.0 19.1
Run '/usr/bin/kerl update releases' to update this list from erlang.org

$ kerl build 19.1 19.1
```

add path
```
export PATH="$HOME/.kerl/builds/19.1/release_19.1/bin:$PATH"
```

# elixir install

```
$ git clone https://github.com/elixir-lang/elixir.git
$ git tag
$ git co git co v1.3.4
$ make clean test
```

add path
```
export PATH="$HOME/.kerl/builds/19.1/release_19.1/bin:$PATH"
```

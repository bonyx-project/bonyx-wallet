# Bonyx wallet

For OS Ubuntu 16.04.7 LTS (Xenial Xerus):

You must build [Bonyx](https://github.com/bonyx-project/bonyx/) first. Easy install Bonyx wallet in 3 steps:

Open Terminal - CTRL + ALT + T

**1. Clone wallet sources**

```
cd
git clone https://github.com/bonyx-project/bonyx-wallet.git
```

**2. Set symbolic link to Bonyx sources at the same level as `src`**

```
cd bonyx-wallet
ln -s ../bonyx cryptonote
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```


**Run**

You must be in /bonyx-wallet/build/ directory.

```
cd
cd bonyx-wallet/build
./bonyx
```

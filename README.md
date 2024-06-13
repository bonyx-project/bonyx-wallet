# Bonyx wallet

For OS Ubuntu 16.04.7 LTS (Xenial Xerus):

**1. Clone wallet sources**

```
git clone https://github.com/bonyx-project/bonyx-wallet.git
```

**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
cd bonyx-wallet
ln -s ../bonyx cryptonote
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/bonyx-project/bonyx-wallet.git cryptonote
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```


**Run**

```
./bonyx
```

Note: You must be in /bonyx-wallet/build/ directory.

# Bonyx wallet

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

Replace URL with git remote repository of your coin.

**3. Build**

```
mkdir build && cd build && cmake .. && make
```

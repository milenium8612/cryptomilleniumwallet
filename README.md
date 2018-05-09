**1. Clone wallet sources**

```
git clone https://github.com/milenium8612/cryptomillenium.git
```
**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../cryptomillenium cryptonote
```
**3. Build**

```
mkdir build && cd build && cmake .. && make
```

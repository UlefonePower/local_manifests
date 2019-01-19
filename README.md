# by Hadenix UleFone Power

### Дерево

#### Заходим в папку "LineageOS" командой:
```
cd ~/LineageOS
```
#### Заходим в папку "device" командой:
```
cd device
```
#### Создаем папку "ulefone" командой:
```
mkdir ulefone
```
#### Заходим в папку "ulefone командой":
```
cd ulefone
```
#### Скачиваем "Дерево" командой:
```
git clone https://github.com/Hadenix/device_ulefone_power.git power
```
### Вендор

#### Заходим в папку "LineageOS" командой:
```
cd ~/LineageOS
```
#### Заходим в папку "vendor" командой:
```
cd vendor
```
#### Создаем папку "ulefone" командой:
```
mkdir ulefone
```
#### Скачиваем "Вендор" командой:
```
git clone https://github.com/Hadenix/vendor_ulefone_power.git power
```
## Патчим исходники

#### Патчим командой:
```
cd ~/LineageOS/device/ulefone/power/patches_mtk && . apply-patches.sh
```

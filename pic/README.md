
```
cd pic
mv icon icon0
mkdir icon
cd icon0
for f in *.png; do convert -resize 70x70! $f ../icon/$f; done
```

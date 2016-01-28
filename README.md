# Git Symlink

```bash
git init 
mkdir newdir 
touch newdir/foo 
git add newdir/foo 
git commit -m 'add foo' 
mv newdir /tmp/ 
ln -s /tmp/newdir 
touch newdir/bar 
git add newdir/bar 
git commit -m 'add bar' 
git ls-files 
```


```bash
mklink /J C:\xampp\htdocs\REPO\git-symlink\docs C:\xampp\htdocs\REPO\docs
```
### lylearningvagrant

- How to create boxes from existing environmant.
```
vagrant ssh web(package name)
```
Now we can try installing some softwares, Ex
```
sudo apt-get install mc
mc
exit
```
Now package it:
```
vagrant package web(you assign the name)
```
Now save it to a box file
```
vagrant box add web package.box(the file vagrant just generated)
```
Check:
```
vagrant box list
```
- Creating Own Boxes

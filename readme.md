### How to install lynis

I prefer to use git method:

```
$ cd /usr/local/
```
```
$ git clone https://github.com/CISOfy/lynis
Cloning into 'lynis'...
remote: Counting objects: 1733, done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 1733 (delta 3), reused 0 (delta 0), pack-reused 1725
Receiving objects: 100% (1733/1733), 886.18 KiB | 378.00 KiB/s, done.
Resolving deltas: 100% (1204/1204), done.
Checking connectivity... done.
```
```
$ cd lynis
$ ./lynis audit system
```
### Screenshot 1 (sample)

![Screenshot 1](img/lynis-01.JPG)

### Screenshot 2 (sample)

![Screenshot 2](img/lynis-02.JPG)
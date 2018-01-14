# Duel monitor supported i3lock script
This script will add the lock icon image to your wallpaper to represent screen is locked, it will then copy the completed image and join it together making 1 long image displayed accross both screens. this assumes your monitors are of the same resolution.


create a symlink for the lock as slock in /usr/bin

```Bash
sudo ln -s /path/to/lock /usr/bin/slock
```

now you can use slock, in my example i use xautolock

```Bash
xautolock -locker slock -time 4 -corners -+00 -cornerdelay 5
```


![](https://github.com/BradHeff/i3lock/blob/master/Screenshot/Screenshot_2018-01-14_11-35-42.png)

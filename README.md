AospLime ROM
=====

### Initializing Source
```
$ repo init -u https://github.com/AospLime/manifest -b pie
$ repo sync -j8 --force-sync
```

### Calling building script
```
$ . build/envsetup.sh
```

### Start build
If you want to build without recording log
```
$ mka bacon
```

If you want to rocord the log
```
$ mk_log
```
And to show log
```
$ oplog
```

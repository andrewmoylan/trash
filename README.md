trash
=====

`trash [files]` moves files to time-stamped directories under `~/recycle-bin/`. Later you can `rm -rf` the old directories. Safer alternative to `rm [files]`.

```bash
$ trash foo.txt
Trashed to /home/Andrew/recycle-bin/2013/12/07/11-27-20.

$ ls /home/Andrew/recycle-bin/2013/12/07/11-27-20
foo.txt  trash.log

$ cat /home/Andrew/recycle-bin/2013/12/07/11-27-20/trash.log
From:
/home/Andrew/foo.txt
To:
/home/Andrew/recycle-bin/2013/12/07/11-27-20/
```

To use, put `trash` somewhere in `$PATH` (and `chmod u+x` it).

Inspired by http://socwiki.wordpress.com/2011/06/11/rv-a-shell-script-to-make-a-recycled-bin-for-linux/.

Test edit bug.

Test edit bug.Test edit bug.
Test edit bug.Test edit bug.
Test edit bug.Test edit bug.

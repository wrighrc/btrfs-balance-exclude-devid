# btrfs-balance-exclude-devid
Balance block groups that don't have a stripe on the excluded devid

See man page in the man directory.

Uses the python-btrfs library, **https://pypi.org/project/btrfs/**

## Example on how to use

Create a python venv then install the lib
```
$ . venv/bin/activate
(venv) $ pip install btrfs

$ sudo ~/venv/bin/python ~/btrfs-balance-exclude-devid/bin/btrfs-balance-exclude-devid -d 1 /mnt/backupdrive
```

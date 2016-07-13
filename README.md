# Public-Notify
A couple of bash scripts to tell you when someone puts something in (or removes something from) your user's public folder.


Clone the repo:
```bash
$ mkdir -p ~/source \
   && cd ~/source \
   && wget https://github.com/dougle/Public-Notify/archive/master.zip -O public-notify-master.zip \
   && unzip public-notify-master.zip \
   && rm -f public-notify-master.zip \
   && cd -
```

Start the monitor:
```bash
$ bash ~/source/Public-Notify-master/monitor_public_folder
```

You can add this to /etc/profile.d via:
```bash
# ln -sfn ~/source/Public-Notify-master/monitor_public_folder /etc/profile.d/monitor_public_folder.sh
```
Note the .sh extension on the end of the link target, this last command with need root permissions to create.

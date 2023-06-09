# hos-openbox
open box for hosos with patches for rounded conners and also window snapping 

Usage:

```bash
git clone https://github.com/HOS-OS/hos-openbox
cd hos-openbox
git apply openbox-window-snap.diff
patch -p1 < ../openbox-3.6.2-radius.patch
./bootstrap
./configure --prefix=/usr --sysconfdir=/etc --libdir=/usr/lib64
make
sudo make install
```

This won't work with multiple monitors.  

preconfig files for hos os are not avalable yet.

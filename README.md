## SUN3DCppReader

Copy files from server:
	http://sun3d.csail.mit.edu/data/
Copied files include:
	intrinsics.txt
	image/*.jpg
	depth/*.png

## Usage

1. ./CopySUN3D (Enter)
```
	Copy from: http://sun3d.csail.mit.edu/data/harvard_c8/hv_c8_3/
	Coyy to  : $HOME/data/sun3d/harvard_c11/hv_c11_2/
```

2. ./CopySUN3D remote_dir local_dir (Enter)
```
	Copy from: http://sun3d.csail.mit.edu/data/remote_dir
	Copy to  : local_dir
	Example  : CopySUN3D harvard_c11/hv_c11_2/ /home/USER_NAME/data/sun3d/
```

## Dependency

1. curl (http://curl.haxx.se/). In Ubuntu: sudo apt-get install libcurl4-gnutls-dev

2. jpeg. In Ubuntu: sudo apt-get install libjpeg-turbo8-dev

3. png. In Ubuntu: sudo apt-get install libpng++-dev




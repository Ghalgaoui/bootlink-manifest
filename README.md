# meta-bootlink
Custom yocto meta

$ sudo curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > /usr/local/sbin/repo

$ sudo chmod a+x /usr/local/sbin/repo

$ repo init https://github.com/Ghalgaoui/bootlink-manifest.git -b dunfell -m rpi4diag.xml

$ repo sync 

$ source ./sources/meta-bootlink/bootlink-init-build-env rpi4diag-build

$ bitbake bootlink-image



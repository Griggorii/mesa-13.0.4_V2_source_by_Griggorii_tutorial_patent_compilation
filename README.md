# mesa-13.0.4_V2_source_by_Griggorii_tutorial_patent_compilation
mesa-13.0.4 , V2 , source , by , Griggorii , tutorial , patent , compilation , new example technology , gallium-pipe , NVD7

Mesa NVD7 graphics : https://radikal.ru/video/mp506QZfw0q

Deb package mesa amd64 download https://drive.google.com/open?id=1IDiBqSfAqw72af_mlIDleQejgjsSMhDb

sudo rm - rf /etc/X11/xorg.conf

sudo rm - rf /etc/X11/xorg.conf.failsafe

sudo rm - rf /usr/share/X11/xorg.conf.d/20-nouveau.conf

sudo rm - rf /usr/share/X11/xorg.conf.d/20-intel.conf

sudo rm - rf /etc/X11/xorg.conf.d

inpack mesa-13.0.4_V2_source_by_Griggorii.tar.xz

cd mesa-13.0.4 run terminal 

sudo dpkg -i *.deb

My propert mit command example ac_cv_path_LLVM_CONFIG=llvm-config-3.8 example replace llvm-config-<my_version> 3.9 / 4 / 5 / 6 /7 .............

./configure --prefix=/usr --includedir=\${prefix}/include --mandir=\${prefix}/share/man --infodir=\${prefix}/share/info --sysconfdir=/etc --localstatedir=/var --libdir=\${prefix}/lib/x86_64-linux-gnu --libexecdir=\${prefix}/lib/x86_64-linux-gnu --disable-dependency-tracking --disable-silent-rules --enable-dri --with-dri-driverdir=/usr/lib/x86_64-linux-gnu/dri --with-dri-searchpath=/usr/lib/x86_64-linux-gnu/dri:\\\$\${ORIGIN}/dri:/usr/lib/dri --enable-osmesa --enable-glx-tls --enable-shared-glapi --enable-texture-float --disable-xvmc --disable-omx --enable-driglx-direct --enable-dri3 --with-egl-platforms=x11 --enable-xa --enable-opencl --enable-opencl-icd --enable-gallium-llvm ac_cv_path_LLVM_CONFIG=llvm-config-3.8 --enable-vdpau --enable-va --enable-gles1 --enable-gles2

make -j16

sudo make install

---------------------------------------------------------------------------------------------------------------------------

Установите это ядро что бы внутри игр при вызове внутренне игрового гуя в wine именно в directx звук не заикался вместе с изображением https://github.com/Griggorii/linux-image-zfs-4.4.201_4.4.201-3_amd64 либо установите ядра от xenial список ниже но в xenial возможно не будет поддержки ubuntu 19.04 и 19.10 потому что это ядро не собиралось в той среде где папки в корне стали ссылками начиная с 19.04 /lib /lib64 тоже ссылкой после установки обязательно удалите ссылки на initr и другие которые появятся в корне / потому что ядра должны быть в boot и без всяких ссылок в корне фактически потом эти линки могут сломать систему , а пользователь даже и не будет знать что это именно из за этих линков фактически мусорных по этому удалите их обычно четыре штуки образуется в процессе установки можно смотреть внутрь корня / при установке ядер как я понял ядра как то смерживаются и сталкиваюся и по этому образуются мусорные линки , хотя если сначала удалить именно установленное ядро и фактически уже без ядер установить кернел то этих ссылок возможно не будет.

linux-headers-4.4.0-116_4.4.0-116.140_all.deb

linux-headers-4.4.0-116-generic_4.4.0-116.140_amd64.deb

linux-image-4.4.0-116-generic_4.4.0-116.140_amd64.deb

linux-image-extra-4.4.0-116-generic_4.4.0-116.140_amd64.deb

-------------------------------------------------

sudo apt update && sudo apt install libomxil-bellagio-dev libwayland-egl-backend-dev libunwind-dev libegl1-mesa-dev mesa-common-dev libgles2-mesa-dev libosmesa6-dev libglu1-mesa-dev valgrind valgrind-dbg libxvmc-dev libxcb-dri2-0-dev libxcb-dri3-dev libxcb-glx0-dev libxcb-randr0-dev libxcb-render0-dev libxcb-shape0-dev libxcb-sync-dev libxcb-xfixes0-dev libxcb1-dev libxine2-dev libxatracker-dev -y && sudo apt libmesa-dev -y && sudo apt install libd3dadapter9-mesa-dev -y

------------------------------------------------------

Codecs test browser example chrome-um , brave 

chrome://media-internals

chrome://media-internals/

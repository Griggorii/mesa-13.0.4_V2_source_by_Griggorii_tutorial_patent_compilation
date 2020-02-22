# mesa-13.0.4_V2_source_by_Griggorii_tutorial_patent_compilation
mesa-13.0.4 , V2 , source , by , Griggorii , tutorial , patent , compilation , new example technology , gallium-pipe

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

sudo apt update && sudo apt install libomxil-bellagio-dev libwayland-egl-backend-dev libunwind-dev libegl1-mesa-dev mesa-common-dev libgles2-mesa-dev libosmesa6-dev libglu1-mesa-dev valgrind valgrind-dbg libxvmc-dev libxcb-dri2-0-dev libxcb-dri3-dev libxcb-glx0-dev libxcb-randr0-dev libxcb-render0-dev libxcb-shape0-dev libxcb-sync-dev libxcb-xfixes0-dev libxcb1-dev libxine2-dev libxatracker-dev -y && sudo apt libmesa-dev -y && sudo apt install libd3dadapter9-mesa-dev -y

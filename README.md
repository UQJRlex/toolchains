# toolchains
forked from android-msm-bonito-4.9-android12L

size:2.7G

#### default.xml

https://android.googlesource.com/kernel/manifest/+/refs/heads/android-msm-bonito-4.9-android12L/default.xml

#### clang-r416183b

https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+/refs/heads/android-msm-bonito-4.9-android12L/clang-r416183b.tar.gz

#### gcc64

https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-4.9/+/refs/heads/android-msm-bonito-4.9-android12L/gcc64-android-msm-bonito-4.9-android12L.tar.gz

#### gcc32

https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/+/refs/heads/android-msm-bonito-4.9-android12L/gcc32-android-msm-bonito-4.9-android12L.tar.gz

#### misc

https://android.googlesource.com/platform/prebuilts/misc/+/refs/heads/android-msm-bonito-4.9-android12L/linux-x86/misc-linux-x86.tar.gz

#### gas / aarch64-linux-gnu-elfedit

https://android.googlesource.com/platform/prebuilts/gas/linux-x86/+/refs/tags/android-12.1.0_r0.40/linux-x86-b2a189331333e014bfef4c0425b3ef4b74accdd0.tar.gz

---

### build.sh
#### set fixed path

`TOOLS=$(realpath ../)`  

#### export aosp toolchains path

`export PATH="${TOOLS}/toolchains/clang/host/linux-x86/clang-r416183b/bin:$PATH"`  
`export PATH="${TOOLS}/toolchains/gcc/linux-x86/aarch64/aarch64-linux-android-4.9/bin:$PATH"`  
`export PATH="${TOOLS}/toolchains/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin:$PATH"`  
`export PATH="${TOOLS}/toolchains/gas/linux-x86:$PATH"`  
`export PATH="${TOOLS}/toolchains/misc/linux-x86/lz4:$PATH"`  
`export PATH="${TOOLS}/toolchains/misc/linux-x86/dtc:$PATH"`  
`export PATH="${TOOLS}/toolchains/misc/linux-x86/libufdt:$PATH"`  
`export PATH="${TOOLS}/toolchains/build-tools/linux-x86/bin:$PATH"`  
`export PATH="${TOOLS}/toolchains/build-tools/path/linux-x86:$PATH"`  
`export LD_LIBRARY_PATH="${TOOLS}/toolchains/clang/host/linux-x86/clang-r416183b/lib64:$LD_LIBRARY_PATH"`  

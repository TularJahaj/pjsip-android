# Changes made
No changes have been made to the sipservice module. To support 64bit architectures only the PJSIP module has been recompiled with the following specs:

- NDK r14
- SDK tools 25.2.3
- API 23
- Build Tools 25.0.2
- PJSIP 2.6
- OpenH264 1.6.0
- SWIG 3.0.12

### Outputs

- org.pjsip.pjsua2 JAVA Module (with negligible differences compared to master branch)
- jniLibs/arm64-v8a/
    + libopenh264.so
    + libpjsua2.so
    + libyuv.so
- jniLibs/x86_64/
    + libopenh264.so
    + libpjsua2.so
    + libyuv.so

### Due to lower API problems
- armeabi
- armeabi-v7a
- x86

libraries were not updated (i.e. master version)
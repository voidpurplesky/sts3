# sts3

STS.ini
```
-vm
C:\Program Files\Java\jdk-11.0.24\bin\javaw.exe
-Dfile.encoding=utf-8
```
추가
```
-startup
plugins/org.eclipse.equinox.launcher_1.6.300.v20210813-1054.jar
--launcher.library
plugins/org.eclipse.equinox.launcher.win32.win32.x86_64_1.2.300.v20210828-0802
-product
org.springsource.sts.ide
--launcher.defaultAction
openFile
-vm
C:\Program Files\Java\jdk-11.0.24\bin\javaw.exe
-vmargs
-Dosgi.requiredJavaVersion=11
-Dosgi.dataAreaRequiresExplicitInit=true
-Xms256m
-Xmx2048m
--add-modules=ALL-SYSTEM
-Dosgi.module.lock.timeout=10
-Dfile.encoding=utf-8
```


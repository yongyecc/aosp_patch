# aosp_patch
Android源码(AOSP)上一些自定义功能实现的patch

# patch表

项|描述
:--:|:--
system/core/fix-ro.-prop-rw.patch|使setprop可以修改ro.开头的属性值，通过注释掉对ro.开头属性的检查实现。

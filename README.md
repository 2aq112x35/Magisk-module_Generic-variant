# Generic-variant | 优化运行参数
将运行参数微架构优化的部分改成通用(generic)提升一点性能（老机型可能反效果）。
set prop cpu_variant=generic to fix performance(old phone maybe bad than ago).

## Modify | 修改
ro.bionic.cpu_variant=generic
ro.bionic.2nd_cpu_variant=generic
dalvik.vm.isa.arm64.variant=generic
dalvik.vm.isa.arm.variant=generic

## Supported | 支持
所有有以上参数的机型
Every phone have related prop.

## Note | 注意
如果无法开机，删除/data/adb/modules/runOPT/common目录和system.prop
If can`t boot, delete /data/adb/modules/runOPT/common and system.prop
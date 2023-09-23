# ksu_lxc_androidkernel
你好呀~这是一个使用github action编译内核的项目
默认会加入lxc和docker以及kernelsu支持，以及打开所有内核配置
设备是一加6(T),内核是4.9版本的lineageos
如果检测到kernelsu版本更新会自动开始编译
如果你有需要编译其它设备，请在fork后修改build.yml，一定要全改成你的，否则某些配置对你不适用
eg clang gcc kernelsource…

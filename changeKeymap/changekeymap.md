更改已有的键盘映射

文件： .xmodmaprc，放在主目录下面

文件内容

```
!
! Swap Caps_Lock and Control_L
!
remove Lock = Caps_Lock
remove Control = Control_L
keysym Control_L = Control_L
keysym Caps_Lock = Control_L
add Lock = Caps_Lock
add Control = Control_L
```

具体作用是把大写锁定键CapsLock更改成Control键

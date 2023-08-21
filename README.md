# file_manager_for_existos

需要修改的地方:
* index.js

  - 仿照SlowMemoryBlockDevice实现一个块设备类
  - 194行: renderModeInit方法中添加一个输入ip地址的框，并使用用户输入信息初始化块设备对象

# hitest_tool
hitest工具子模块

## 使用说明  
各产品的自动化测试用例git工程的执行结果数据，需要上报给团队内部的一些效能平台时，可以通过子模块中的公共方法、或工具进行上报或接入等配合，比如上报执行用例的总数、成功数等

## 子模块使用
给主模块添加子模块  
cd hitest   
git submodule add https://github.com/darrenWang0827/hitest_tool.git  

强制更新子模块内容  
git submodule --remote --recursive --force  




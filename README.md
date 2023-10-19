# BUPTyuketangHelper
## 研究生雨课堂网课脚本代码
> 本项目转自[heyblackC-yuketangHelper](https://github.com/heyblackC/yuketangHelper)

2023.10.19在BUPT雨课堂上测试成功</br>
`videoHelper.py`是雨课堂网课视频自动观看脚本

## 使用方法
> 详细可参考[链接](https://blog.csdn.net/doubleguy/article/details/121209399)
1. 安装python3 
2. 获取`https://xxxx.yuketang.cn/pro/courselist`的界面源代码(F12)(**注意是这个所有课程目录下的界面**)
   1. 本校: edge在控制台内得到`csrftoken`, `sessionid`进行代码内查找替换
   2. 外校: 在本校替换基础上对`university_id`, `university-id(=uv_id)`, 以及学校链接`https://xxxx.yuketang.cn`进行代码内查找替换
3. 在程序所在目录下运行videoHelper.py</br>
   `python videoHelper.py`
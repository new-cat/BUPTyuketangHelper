# yuketangHelper
## 研究生雨课堂网课脚本代码
> 本项目转自[heyblackC-yuketangHelper](https://github.com/heyblackC/yuketangHelper)

2023.10.19在BUPT yuketang上测试成功</br>
videoHelper.py是雨课堂网课视频观看自动脚本

## 使用方法
1. 安装python3 
   1. 本校的同学可以直接使用`python videoHelper.py`
   2. 其他学校的同学, 详细可参考[链接](https://blog.csdn.net/doubleguy/article/details/121209399)
      1. 获取https://xxxx.yuketang.cn/pro/courselist的界面源代码(F12)
      2. edge在控制台内得到本校的csrftoken, sessionid, university_id(=uv_id), 以及学校链接`https://xxxx.yuketang.cn`进行代码内查找替换即可 
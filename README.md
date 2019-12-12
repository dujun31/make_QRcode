# 个性动态炫酷二维码制作

# GIF在线制作网站:http://gif.55.la/
# 识别二维码在线网站:https://www.weihaobang.com/tool/erweimameihua/

# 如有失效,尽情告知
# 欢迎关注"Python成功之路"

# Python运行此代码,生成百度链接的二维码
import MyQR

from MyQR import myqr

myqr.run('http://www.baidu.com')


# Python运行此代码,生成个性动态炫酷二维码
import MyQR

from MyQR import myqr

myqr.run(

    words='http://weixin.qq.com/r/UB1PV7XE9OiLrfE090hC', #需制作二维码的链接
    
    picture='E:/save/gif_pic.gif',#gif路径
    
    save_dir='E:/save',#保存的文件夹
    
    save_name='qrcode.gif', #保存的二维码名称
    
    colorized=True, #是否为彩色
    
)

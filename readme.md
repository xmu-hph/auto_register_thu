# 项目说明
本项目主要是为了解决清华大学亲友入校的申请问题。传统的申请方式需要手动，比较慢。因此开发出本项目：半自动的提交申请。半自动是由于二次验证不好绕过，所以在新的机器上只能是半自动的，在已经标记为免二次验证的机器上是全自动的。
# tobe
要想实现在任意机器上全自动，需要想办法将二次验证的验证码实时分享，企业微信这个方向不太好走通。目前的想法是二次验证选择手机号方式，将验证码同步到云端，然后本项目从云端获取二次验证码实现登录。待有缘人实现。
# 说明
为了学校和个人安全起见，代码还是放在清华gitlab上了。

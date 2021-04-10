# 自定义上下文管理器
上下文管理器：在类里面实现__enter__和__exit__方法 创建对象就是上下文管理器
class File(object):
  pass
with open() 改为 File.open

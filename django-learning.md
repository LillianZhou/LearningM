
# Django RestAPI Learning

## serializer

ModelSerializers: 序列一个非常棒的属性就是可以通过打印序列化器类实例的结构(representation)查看它的所有字段。
  from snippets.serializers import SnippetSerializer
  serializer = SnippetSerializer()
  print(repr(serializer))

重要的是要记住，ModelSerializer类并不会做任何特别神奇的事情，它们只是创建序列化器类的快捷方式：
* 一组自动确定的字段。
* 默认简单实现的create()和update()方法。

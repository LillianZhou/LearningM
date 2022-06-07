
# Django RestAPI Learning

## serializer

ModelSerializers: 序列一个非常棒的属性就是可以通过打印序列化器类实例的结构(representation)查看它的所有字段。

        from snippets.serializers import SnippetSerializer
        serializer = SnippetSerializer()
        print(repr(serializer))

重要的是要记住，ModelSerializer类并不会做任何特别神奇的事情，它们只是创建序列化器类的快捷方式：
* 一组自动确定的字段。
* 默认简单实现的create()和update()方法。


# ML Links

* Pipeline/workflow of machine learning
- https://ml-ops.org/content/three-levels-of-ml-software
- [What Is a Machine Learning Pipeline?](https://valohai.com/machine-learning-pipeline/)



* Machine learning
** from business perspective
- Data Science for Business, https://learning.oreilly.com/library/view/data-science-for/9781449374273/


# Frontend Links
- https://sangbui.com/sb-files/BrowserArchitecture_ClientSide.pdf
- [Understanding Layout Algorithms](https://www.joshwcomeau.com/css/understanding-layout-algorithms/)
- https://dev.to/gitpaulo/journey-of-a-web-page-how-browsers-work-10co
best article red so far to introduce internal of web browser.

https://learning.oreilly.com/videos/react-the/9781801812603/

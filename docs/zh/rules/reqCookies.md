
# reqCookies
修改请求的cookie，配置方式：

	pattern reqCookies://filepath

filepath为[Values](http://local.whistlejs.com/#values)里面的{key}或者本地文件(如：`e:\test\xxx`、`e:/test/xxx`、`/User/username/test/xxx`等):

	key1: value1
	key2: value2
	keyN: valueN

pattern参见[匹配模式](../pattern.html)，更多模式请参考[配置方式](../mode.html)，json格式参考[操作值](../data.html)。

例子：

	www.ifeng.com reqCookies://{test-reqCookies.json}


test-reqCookies.json:

	test: 123
	key: value

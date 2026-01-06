
## 火山"视窗项目"系统类库模块: 视窗基本类

### 包: 火山.基本
* **描述:** 本文件提供视窗项目的相关文本操作支持功能

---

#### 火山.基本.文本编码类型

* **类型:** `类`
* **名称:** `文本编码类型`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `文本操作.辅助类`
* **描述:** 提供各种文本编码类型
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-程序崩溃回调-breakpad-main](#vol-程序崩溃回调-breakpad-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.文本编码类型.未知

* **类型:** `成员常量`
* **名称:** `未知`
* **数据类型:** `文本编码类型`
* **描述:** 未知编码
* **相关例程:** [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.文本编码类型.UTF16

* **类型:** `成员常量`
* **名称:** `UTF16`
* **数据类型:** `文本编码类型`
* **描述:** UTF-16编码
* **相关例程:** [vol-程序崩溃回调-breakpad-main](#vol-程序崩溃回调-breakpad-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.文本编码类型.UTF8

* **类型:** `成员常量`
* **名称:** `UTF8`
* **数据类型:** `文本编码类型`
* **描述:** UTF-8编码
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main)

##### 火山.基本.文本编码类型.多字节

* **类型:** `成员常量`
* **名称:** `多字节`
* **数据类型:** `文本编码类型`
* **描述:** MBCS多字节本地字符编码
* **相关例程:** [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

---

#### 火山.基本.文本类

* **类型:** `类`
* **名称:** `文本类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `文本操作`
* **描述:** 提供对Unicode-16字符集格式文本的相关操作支持. 火山视窗系统所使用的文本字符集即为Unicode-16格式.
* **相关例程:** [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-串口通讯-cserialport-main](#vol-串口通讯-cserialport-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-数据报-udp-main](#vol-数据报-udp-main), [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-elk微型js引擎-elk_js-main](#vol-elk微型js引擎-elk_js-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.文本类.取随机字母数字

* **类型:** `全局方法`
* **名称:** `取随机字母数字`
* **返回值数据类型:** `文本型`
* **参数:**
	* `取出的字符数` (`整数`)
* **特性:**
	* `静态`
* **描述:** A-Z、a-z、0-9 中取出随机指定数量的字符.
* **相关例程:** [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main)

##### 火山.基本.文本类.取文本标记值

* **类型:** `全局方法`
* **名称:** `取文本标记值`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回本文本对象中所设置的用户标记数值. 由于文本数据实际上也是对象数据,因此其中也保存有用户标记数值.

##### 火山.基本.文本类.置文本标记值

* **类型:** `全局方法`
* **名称:** `置文本标记值`
* **参数:**
	* `所欲操作的文本` (`文本型(需求:可写入变量)`)
	* `所欲设置的标记值` (`变整数`)
* **特性:**
	* `静态`
* **描述:** 设置本文本对象中的用户标记数值,如果未设置过,其初始值为0. 由于文本数据实际上也是对象数据,因此其中也保存有用户标记数值.

##### 火山.基本.文本类.取文本预分配字符数

* **类型:** `全局方法`
* **名称:** `取文本预分配字符数`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回本文本对象为了快速进行内容的添加/删除处理使用的空间分配尺寸,每次文本需要调整其空间大小时,都使用本属性值乘于单个字符尺寸作为空间调整基准尺寸.值越大,批量加入/删除文本内容时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.

##### 火山.基本.文本类.置文本预分配字符数

* **类型:** `全局方法`
* **名称:** `置文本预分配字符数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `预分配字符数` (`整数`)
* **特性:**
	* `静态`
* **描述:** 设置本文本对象为了快速进行内容的添加/删除处理使用的空间分配尺寸,每次文本需要调整其空间大小时,都使用本属性值乘于单个字符尺寸作为空间调整基准尺寸.值越大,批量加入/删除文本内容时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.

##### 火山.基本.文本类.取当前代码页

* **类型:** `全局方法`
* **名称:** `取当前代码页`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回当前操作系统所使用的ANSI代码页
* **返回值描述:** 具体整数值所对应的代码页请自行查阅相关资料,下面列出一些常用代码页: 中文简体: 936 中文繁体: 950

##### 火山.基本.文本类.简繁转换

* **类型:** `全局方法`
* **名称:** `简繁转换`
* **返回值数据类型:** `文本型`
* **参数:**
	* `待转换的文本` (`文本型`): 提供需要进行转换的文本
	* `是否转换到繁体` (`逻辑型`): 为真转换到繁体,为假则转换到简体.
* **特性:**
	* `静态`
* **描述:** 将所提供中文文本在简体和繁体之间进行转换.
* **返回值描述:** 成功返回转换后的结果,失败则返回原文本.

##### 火山.基本.文本类.填充文本

* **类型:** `全局方法`
* **名称:** `填充文本`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `填充长度` (`整数`): 提供所欲填写文本的长度(即重复填充所指定字符的次数),必须大于等于0.
	* `填充字符` (`字符`, 默认值: `' '`): 提供所欲使用的填充用字符,注意不能为零字符('\0').
* **特性:**
	* `静态`
* **描述:** 使用所指定长度的指定字符重新填写本文本对象,返回填充后的文本数据首地址指针. 注意: 本文本对象内的原有内容将被覆盖.
* **返回值描述:** 返回填充后文本数据的首地址

##### 火山.基本.文本类.文本到对象

* **类型:** `全局方法`
* **名称:** `文本到对象`
* **返回值数据类型:** `对象类`
* **参数:**
	* `所欲转换的文本` (`文本型`): 提供所欲转换到对象的文本内容
* **特性:**
	* `静态`
* **描述:** 将所指定文本转换到对象并返回
* **相关例程:** [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.文本类.对象到文本

* **类型:** `全局方法`
* **名称:** `对象到文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `文本对象数据` (`对象类`): 可以为"文本到对象"方法的返回值
* **特性:**
	* `静态`
* **描述:** 如果所指定对象为文本数据,则将其转换到文本返回,否则返回空文本.
* **相关例程:** [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.文本类.文本到UTF8

* **类型:** `全局方法`
* **名称:** `文本到UTF8`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `是否包括结束零字符` (`逻辑型`, 默认值: `真`): 指定在所转换到的结果文本字节集中是否包括结束零字符
* **特性:**
	* `静态`
* **描述:** 将当前文本转换到UTF8字符集格式后返回. 等同于火山安卓、服务器中的"文本到字节数组".
* **相关例程:** [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.文本类.UTF8到文本

* **类型:** `全局方法`
* **名称:** `UTF8到文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的UTF8文本数据` (`字节集类`): 提供所欲转换的UTF8字符集文本数据
* **特性:**
	* `静态`
* **描述:** 将所指定UTF8格式的文本数据转换到文本后返回. 等同于火山安卓、服务器中的"字节数组到文本".
* **相关例程:** [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.文本类.文件资源到文本

* **类型:** `全局方法`
* **名称:** `文件资源到文本`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲载入的数据资源` (`视窗文件资源`): 用作提供所欲载入的RCDATA类型资源,如果为"空资源.空文件",将返回空文本.
	* `所欲写出到的文本` (`文本型`): 用作接收所载入的资源数据文本,其中的原有内容将被覆盖.
* **特性:**
	* `静态`
* **描述:** 载入所指定的文本数据资源,返回是否载入成功.
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main)

##### 火山.基本.文本类.文本到多字节

* **类型:** `全局方法`
* **名称:** `文本到多字节`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `是否包括结束零字符` (`逻辑型`, 默认值: `真`): 指定在所转换到的结果文本字节集中是否包括结束零字符
* **特性:**
	* `静态`
* **描述:** 将当前文本转换到本地多字节字符集格式(即MBS)后返回. 等同于火山安卓、服务器中的"文本到GBK".
* **相关例程:** [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-串口通讯-cserialport-main](#vol-串口通讯-cserialport-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-elk微型js引擎-elk_js-main](#vol-elk微型js引擎-elk_js-main)

##### 火山.基本.文本类.多字节到文本

* **类型:** `全局方法`
* **名称:** `多字节到文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的文本数据` (`字节集类`): 提供所欲转换的本地多字节字符集文本数据
* **特性:**
	* `静态`
* **描述:** 将所指定本地多字节字符集格式(即MBS)的文本数据转换到文本后返回. 等同于火山安卓、服务器中的"GBK到文本".
* **相关例程:** [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-串口通讯-cserialport-main](#vol-串口通讯-cserialport-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main)

##### 火山.基本.文本类.文本到字节集

* **类型:** `全局方法`
* **名称:** `文本到字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲转换的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将当前文本转换到字节集数据后返回. 注意: 所返回数据不包括结束零字符,其文本字符集格式为UTF-16编码. 等同于火山安卓、服务器中的"文本到UTF16"方法.
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main)

##### 火山.基本.文本类.字节集到文本

* **类型:** `全局方法`
* **名称:** `字节集到文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的文本数据` (`字节集类`): 提供所欲转换的Unicode-16编码文本内容数据
* **特性:**
	* `静态`
* **描述:** 将所指定的字节集数据转换到文本后返回. 注意: 必须确保所提供的字节集数据为Unicode-16编码文本内容. 等同于火山安卓、服务器中的"UTF16到文本"方法.
* **相关例程:** [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-数据报-udp-main](#vol-数据报-udp-main), [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main)

##### 火山.基本.文本类.读入文本文件

* **类型:** `全局方法`
* **名称:** `读入文本文件`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲读取文件名` (`文本型`): 提供所欲读取文件的路径名称
	* `所欲读取数据尺寸` (`整数`, 默认值: `-1`): 提供所欲读取数据的尺寸(单位字节),为-1表示全部读取.
	* `文件文本编码` (`文本编码类型`, 默认值: `文本编码类型.UTF16`): 提供文件中文本内容的编码格式,如果为"文本编码类型.未知",则首先检查是否为"文本编码类型.UTF16"格式,如果不是,则认为其为"文本编码类型.多字节"格式.
* **特性:**
	* `静态`
* **描述:** 从所指定路径文件中读入指定尺寸的文本内容并将其返回,如果读取失败将返回空文本(注意正常情况下也可能返回空文本).
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main)

##### 火山.基本.文本类.读入文本文件2

* **类型:** `全局方法`
* **名称:** `读入文本文件2`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲读取文件名` (`文本型`): 提供所欲读取文件的路径名称
	* `所欲读取数据尺寸` (`整数`, 默认值: `-1`): 提供所欲读取数据的尺寸(单位字节),为-1表示全部读取.
	* `文件文本编码` (`文本编码类型`, 默认值: `文本编码类型.UTF16`): 提供文件中文本内容的编码格式,如果为"文本编码类型.未知",则首先检查是否为"文本编码类型.UTF16"格式,如果不是,则认为其为"文本编码类型.多字节"格式.
* **特性:**
	* `静态`
* **描述:** 从所指定路径文件中读入指定尺寸的文本内容到本文本内,返回是否读取成功.
* **相关例程:** [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.文本类.写出文本文件

* **类型:** `全局方法`
* **名称:** `写出文本文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲写到文件名` (`文本型`): 提供所欲写到文件的路径名称
	* `所欲写出文本长度` (`整数`, 默认值: `-1`): 提供所欲写出文本的字符数目,为-1表示全部写出.
	* `所欲写出文本编码` (`文本编码类型`, 默认值: `文本编码类型.UTF16`): 提供欲将所写出文本转换到的编码类型,不能为"文本编码类型.未知".
* **特性:**
	* `静态`
* **描述:** 将本文本的内容写入到所指定路径的文件中,返回是否写出成功.
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-程序崩溃回调-breakpad-main](#vol-程序崩溃回调-breakpad-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.文本类.复制到字符数组

* **类型:** `全局方法`
* **名称:** `复制到字符数组`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲复制到的字符数组` (`字符 []`): 提供所欲复制到的字符数组
	* `字符数组的成员数` (`整数`): 提供指定字符数组定义时所分配的成员字符数目
* **特性:**
	* `静态`
* **描述:** 将本文本的内容复制到所指定的字符数组中,会自动添加结尾零字符.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-被调用动态链接库-dll_test-main](#vol-被调用动态链接库-dll_test-main)

##### 火山.基本.文本类.添加字符数组

* **类型:** `全局方法`
* **名称:** `添加字符数组`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲添加的字符数组` (`字符 []`): 提供所欲添加其文本内容的字符数组
	* `所欲添加的字符数目` (`整数`): 提供该字符数组中所欲加入到本文本中的字符数目,必须大于等于0且小于等于指定字符数组定义时所分配的成员字符数目.
* **特性:**
	* `静态`
* **描述:** 将所指定字符数组中的文本内容添加到本文本的尾部

##### 火山.基本.文本类.取文本指针

* **类型:** `全局方法`
* **名称:** `取文本指针`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回当前文本内容的文本指针值. 除非必要且对指针概念有透彻的了解,不要使用本方法.
* **相关例程:** [vol-树结构访问-treestruct-main](#vol-树结构访问-treestruct-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main)

##### 火山.基本.文本类.置文本指针

* **类型:** `全局方法`
* **名称:** `置文本指针`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `欲置入文本内容指针` (`变整数`): 为指向一段以'\0'字符结束的文本内容,该内容将被置入到当前文本对象中.
* **特性:**
	* `静态`
* **描述:** 将指针所指向的文本内容置入当前文本对象中
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.文本类.添加文本指针内容

* **类型:** `全局方法`
* **名称:** `添加文本指针内容`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `文本数据指针` (`变整数`): 提供指向所欲加入文本数据内容的指针. 注意: 该指针必须指向以零字符结束的文本内容.
* **特性:**
	* `静态`
* **描述:** 将所指定指针处的文本数据添加到本文本的尾部. 除非必要且对指针概念有透彻的了解,不要使用本方法.

##### 火山.基本.文本类.添加部分文本指针内容

* **类型:** `全局方法`
* **名称:** `添加部分文本指针内容`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `文本数据指针` (`变整数`): 提供指向所欲加入文本数据内容的指针
	* `所欲添加文本的长度` (`整数`): 提供所欲添加文本的长度,必须确保指针所指向地址处尺寸为"本参数值*单个字符数据尺寸"的地址空间可读.
* **特性:**
	* `静态`
* **描述:** 将所指定指针处的部分文本数据添加到本文本的尾部. 除非必要且对指针概念有透彻的了解,不要使用本方法.

##### 火山.基本.文本类.指针到文本

* **类型:** `全局方法`
* **名称:** `指针到文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `文本数据指针` (`变整数`): 提供指向所欲取出文本数据内容的指针
* **特性:**
	* `静态`
* **描述:** 根据指定指针所指向的文本数据建立并返回一个文本对象
* **相关例程:** [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-树结构访问-treestruct-main](#vol-树结构访问-treestruct-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main)

##### 火山.基本.文本类.多字节指针到文本

* **类型:** `全局方法`
* **名称:** `多字节指针到文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `文本数据指针` (`变整数`): 提供指向所欲取出多字节编码文本数据内容的指针
* **特性:**
	* `静态`
* **描述:** 根据指定指针所指向的多字节编码文本数据建立并返回一个文本对象

##### 火山.基本.文本类.到文本

* **类型:** `全局方法`
* **名称:** `到文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的数据` (`通用基本型`)
* **特性:**
	* `静态`
* **描述:** 返回指定数据的文本形式
* **相关例程:** [vol-选择夹1-tab_demo-main](#vol-选择夹1-tab_demo-main), [vol-对话框-dialog_test-main](#vol-对话框-dialog_test-main), [vol-时钟-timer-main](#vol-时钟-timer-main), [vol-超级列表框-listview-main](#vol-超级列表框-listview-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-树形框-tree_box-main](#vol-树形框-tree_box-main), [vol-工具条-tool_bar-main](#vol-工具条-tool_bar-main), [vol-状态条-status_bar-main](#vol-状态条-status_bar-main), [vol-表格-grid-main](#vol-表格-grid-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-卷帘式菜单-outbar-main](#vol-卷帘式菜单-outbar-main), [vol-属性表格-property_grid-main](#vol-属性表格-property_grid-main), [vol-带按钮列表框-vs_list_box-main](#vol-带按钮列表框-vs_list_box-main), [vol-媒体播放器-win_media_player-main](#vol-媒体播放器-win_media_player-main), [vol-设计并处理重叠界面-over_ui-main](#vol-设计并处理重叠界面-over_ui-main), [vol-超级菜单演示-adv_menu-main](#vol-超级菜单演示-adv_menu-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main](#vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main), [vol-打印测试-print_test-main](#vol-打印测试-print_test-main), [vol-空对象测试-null_object_test-main](#vol-空对象测试-null_object_test-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-位图处理-adv_bitmap-main](#vol-位图处理-adv_bitmap-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-cximage高级图像处理-cximage-main](#vol-cximage高级图像处理-cximage-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-控制台程序-console_demo-main](#vol-控制台程序-console_demo-main), [vol-mfc控制台程序-mfc_console-main](#vol-mfc控制台程序-mfc_console-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-被调用动态链接库-dll_test-main](#vol-被调用动态链接库-dll_test-main), [vol-调用动态链接库-dll_call-main](#vol-调用动态链接库-dll_call-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-被调用部件动态链接库-com_dll-main](#vol-被调用部件动态链接库-com_dll-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-xml数据访问-xml-main](#vol-xml数据访问-xml-main), [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-正则表达式2-regex-main](#vol-正则表达式2-regex-main), [vol-yyjson数据访问-yyjson-main](#vol-yyjson数据访问-yyjson-main), [vol-rar文件解压-unrar-main](#vol-rar文件解压-unrar-main), [vol-数学公式计算-math_exp_calc-main](#vol-数学公式计算-math_exp_calc-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-tcp转发-tcp_forward-main](#vol-tcp转发-tcp_forward-main), [vol-数据报-udp-main](#vol-数据报-udp-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件发送-send_email-main](#vol-邮件发送-send_email-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-ado-ado_sample-main](#vol-ado-ado_sample-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-redis连接池-redisconnectpool-main](#vol-redis连接池-redisconnectpool-main), [vol-mysql连接池-mysql_connectionpool-main](#vol-mysql连接池-mysql_connectionpool-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-elk微型js引擎-elk_js-main](#vol-elk微型js引擎-elk_js-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main), [vol-人脸性别识别-gender_recognition-main](#vol-人脸性别识别-gender_recognition-main), [vol-相关性多模板匹配-ncc_matching-main](#vol-相关性多模板匹配-ncc_matching-main), [vol-yolov5目标检测-yolov5-main](#vol-yolov5目标检测-yolov5-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main), [vol-dnn目标检测-dnn_objectdetection-main](#vol-dnn目标检测-dnn_objectdetection-main), [vol-dnn文本检测-dnn_text_detection_recognition-main](#vol-dnn文本检测-dnn_text_detection_recognition-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.文本类.置文本

* **类型:** `全局方法`
* **名称:** `置文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲置入的数据` (`通用基本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定类型的数据置入所欲操作的文本中

##### 火山.基本.文本类.字符数组到文本

* **类型:** `全局方法`
* **名称:** `字符数组到文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲使用的字符数组` (`字符 []`)
	* `字符数目` (`整数`): 提供该字符数组中所欲加入到返回文本中的字符数目,必须大于等于0且小于等于指定字符数组定义时所分配的成员字符数目.
* **特性:**
	* `静态`
* **描述:** 根据所指定字符数组中的文本内容构建并返回一个文本值. 注意: 该数组中必须存在以零字符结束的文本内容.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-调用动态链接库-dll_call-main](#vol-调用动态链接库-dll_call-main)

##### 火山.基本.文本类.取文本长度

* **类型:** `全局方法`
* **名称:** `取文本长度`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定文本型数据的长度
* **相关例程:** [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.文本类.置文本长度

* **类型:** `全局方法`
* **名称:** `置文本长度`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲设置的长度` (`整数`): 如果小于原有文本长度,则将原有文本剪切到所指定长度,如果大于原有文本长度,则在尾部补充对应数目的空格字符.
* **特性:**
	* `静态`
* **描述:** 设置所指定文本型数据的长度

##### 火山.基本.文本类.取文本左边

* **类型:** `全局方法`
* **名称:** `取文本左边`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `欲取出字符的数目` (`整数`)
* **特性:**
	* `静态`
* **描述:** 返回一个文本,其中包含指定文本中从左边算起指定数量的字符.
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.文本类.取文本右边

* **类型:** `全局方法`
* **名称:** `取文本右边`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `欲取出字符的数目` (`整数`)
* **特性:**
	* `静态`
* **描述:** 返回一个文本,其中包含指定文本中从右边算起指定数量的字符.
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.文本类.取文本中间

* **类型:** `全局方法`
* **名称:** `取文本中间`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `起始取出索引位置` (`整数`): 注意索引值从0开始,即0代表首字符位置.
	* `欲取出字符的数目` (`整数`)
* **特性:**
	* `静态`
* **描述:** 返回一个文本,其中包含指定文本中从指定位置算起指定数量的字符.
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main)

##### 火山.基本.文本类.取文本哈希值

* **类型:** `全局方法`
* **名称:** `取文本哈希值`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 计算并返回所指定文本的哈希值,区分英文字母的大小写. 文本哈希值可以在需要快速比较两个文本是否相同时使用(即如果两个文本的哈希值不同,则两个文本必定不相同).

##### 火山.基本.文本类.取文本大小写无关哈希值

* **类型:** `全局方法`
* **名称:** `取文本大小写无关哈希值`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 计算并返回所指定文本的哈希值,不区分英文字母的大小写. 文本哈希值可以在需要快速比较两个文本是否相同时使用(即如果两个文本的哈希值不同,则两个文本必定不相同).

##### 火山.基本.文本类.文本是否为空

* **类型:** `全局方法`
* **名称:** `文本是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定文本是否为空
* **相关例程:** [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-cximage高级图像处理-cximage-main](#vol-cximage高级图像处理-cximage-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-json数据访问-json-main](#vol-json数据访问-json-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-大整数运算-bnsample-main](#vol-大整数运算-bnsample-main), [vol-正则表达式2-regex-main](#vol-正则表达式2-regex-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-tcp转发-tcp_forward-main](#vol-tcp转发-tcp_forward-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-ado-ado_sample-main](#vol-ado-ado_sample-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-redis连接池-redisconnectpool-main](#vol-redis连接池-redisconnectpool-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main)

##### 火山.基本.文本类.文本是否为空对象

* **类型:** `全局方法`
* **名称:** `文本是否为空对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定文本是否设置了"空白对象"标志

##### 火山.基本.文本类.清空文本

* **类型:** `全局方法`
* **名称:** `清空文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 清空所指定文本的内容
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main)

##### 火山.基本.文本类.删除部分文本

* **类型:** `全局方法`
* **名称:** `删除部分文本`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `起始字符索引` (`整数`): 提供所欲删除内容部分的首字符索引位置,必须大于等于0且小于等于当前文本长度.
	* `欲删除字符数` (`整数`): 提供所欲删除的字符数,必须大于等于0且加上"起始字符索引"参数值后小于等于当前文本长度.
* **特性:**
	* `静态`
* **描述:** 删除所指定文本中的指定区域内的字符
* **返回值描述:** 返回所实际删除的字符数

##### 火山.基本.文本类.文本比较

* **类型:** `全局方法`
* **名称:** `文本比较`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲比较的文本` (`文本型`): 提供所欲比较的文本
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定比较时是否区分英文字母的大小写
* **特性:**
	* `静态`
* **描述:** 比较两个文本,返回比较结果.
* **返回值描述:** 如果返回值小于0,表示本文本小于所比较文本; 如果等于0,表示本文本等于所比较文本; 如果大于0,表示本文本大于所比较文本.

##### 火山.基本.文本类.检查加入路径字符

* **类型:** `全局方法`
* **名称:** `检查加入路径字符`
* **参数:**
	* `所欲操作的文本` (`文本型`): 提供所欲处理的路径文本
* **特性:**
	* `静态`
* **描述:** 如果所指定路径文本不以路径字符'\'结束,则添加该字符到尾部.

##### 火山.基本.文本类.检查删除路径字符

* **类型:** `全局方法`
* **名称:** `检查删除路径字符`
* **参数:**
	* `所欲操作的文本` (`文本型`): 提供所欲处理的路径文本
* **特性:**
	* `静态`
* **描述:** 如果所指定路径文本以一个可以被删除的路径字符'\'结束(即不为类似"c:\"这样的文本),则将其删除.

##### 火山.基本.文本类.插入字符

* **类型:** `全局方法`
* **名称:** `插入字符`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `插入索引位置` (`整数`): 提供所欲插入的索引位置,必须大于等于0且小于等于文本当前长度.
	* `所欲插入的字符` (`字符`): 提供所欲插入到文本中的字符
* **特性:**
	* `静态`
* **描述:** 将所指定字符插入到文本的所指定索引位置

##### 火山.基本.文本类.删除字符

* **类型:** `全局方法`
* **名称:** `删除字符`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `首字符索引位置` (`整数`): 提供所欲删除首字符的索引位置,必须大于等于0且小于等于文本当前长度.
	* `欲删除字符数目` (`整数`, 默认值: `1`): 提供所欲删除字符的数目,必须大于等于0且加上"首字符索引位置"后小于等于文本当前长度.
* **特性:**
	* `静态`
* **描述:** 删除指定文本内容中的所指定区域的字符

##### 火山.基本.文本类.加入字符

* **类型:** `全局方法`
* **名称:** `加入字符`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲添加的字符` (`字符`): 提供所欲添加到文本中的字符
* **特性:**
	* `静态`
* **描述:** 将所指定的字符添加到文本的尾部

##### 火山.基本.文本类.取空白文本

* **类型:** `全局方法`
* **名称:** `取空白文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `空格数目` (`整数`): 提供所欲置入的空格字符数目
* **特性:**
	* `静态`
* **描述:** 返回具有指定数目半角空格的文本
* **相关例程:** [vol-属性表格-property_grid-main](#vol-属性表格-property_grid-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main)

##### 火山.基本.文本类.取重复文本

* **类型:** `全局方法`
* **名称:** `取重复文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲重复的文本` (`文本型`): 提供所欲重复置入的文本
	* `所欲重复的次数` (`整数`): 提供所欲重复置入的次数
* **特性:**
	* `静态`
* **描述:** 将所指定文本重复指定次数,返回结果文本.
* **相关例程:** [vol-yaml数据访问-yaml-main](#vol-yaml数据访问-yaml-main)

##### 火山.基本.文本类.加入重复字符

* **类型:** `全局方法`
* **名称:** `加入重复字符`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲添加的字符` (`字符`, 默认值: `' '`): 提供所欲添加到文本中的字符
	* `所欲重复添加的次数` (`整数`, 默认值: `1`): 提供将所指定字符重复添加的次数
* **特性:**
	* `静态`
* **描述:** 将所指定的字符添加多个到文本的尾部

##### 火山.基本.文本类.加入文本

* **类型:** `全局方法`
* **名称:** `加入文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲添加的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定文本添加到当前文本尾部
* **相关例程:** [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-yyjson数据访问-yyjson-main](#vol-yyjson数据访问-yyjson-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.文本类.加入部分文本

* **类型:** `全局方法`
* **名称:** `加入部分文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲添加的文本` (`文本型`)
	* `所欲添加的长度` (`整数`): 提供欲将所指定文本的多少字符添加到当前文本尾部
* **特性:**
	* `静态`
* **描述:** 将所指定文本的一部分添加到当前文本尾部

##### 火山.基本.文本类.插入文本

* **类型:** `全局方法`
* **名称:** `插入文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲插入的索引位置` (`整数`): 指定所欲插入的字符索引位置,必须大于等于0且小于等于当前文本的长度.
	* `所欲插入的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定文本插入到当前文本所指定位置

##### 火山.基本.文本类.插入部分文本

* **类型:** `全局方法`
* **名称:** `插入部分文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲插入的索引位置` (`整数`): 指定所欲插入的字符索引位置,必须大于等于0且小于等于当前文本的长度.
	* `所欲插入的文本` (`文本型`)
	* `所欲插入的长度` (`整数`): 提供欲将指定文本的多少字符插入到当前文本的所指定位置
* **特性:**
	* `静态`
* **描述:** 将所指定文本的一部分插入到当前文本所指定位置

##### 火山.基本.文本类.取字符

* **类型:** `全局方法`
* **名称:** `取字符`
* **返回值数据类型:** `字符`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `字符索引位置` (`整数`): 提供所欲获取字符的索引位置,必须大于等于0小于文本的当前长度.
* **特性:**
	* `静态`
* **描述:** 返回文本中所指定索引位置处的字符
* **相关例程:** [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main)

##### 火山.基本.文本类.加入小写文本

* **类型:** `全局方法`
* **名称:** `加入小写文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲添加的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定文本中的英文字母转换到小写后添加到当前文本尾部

##### 火山.基本.文本类.加入大写文本

* **类型:** `全局方法`
* **名称:** `加入大写文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲添加的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定文本中的英文字母转换到大写后添加到当前文本尾部

##### 火山.基本.文本类.加入重复文本

* **类型:** `全局方法`
* **名称:** `加入重复文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲添加的文本` (`文本型`)
	* `所欲添加的次数` (`整数`)
* **特性:**
	* `静态`
* **描述:** 将所指定的文本重复多次加入当前文本的尾部

##### 火山.基本.文本类.加入多行文本

* **类型:** `全局方法`
* **名称:** `加入多行文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲添加的文本` (`文本型`): 所添加文本中可以包括以换行符分隔的多行文本
	* `所添加行首空格数` (`整数`): 指定在所提供的多行文本中每行行首添加的空格字符数目,如果小于0,则删除行首对应数目的空格字符.
* **特性:**
	* `静态`
* **描述:** 将所指定的多行文本(基于换行符分隔)加入到当前文本尾部,支持在多行文本中的每行行首添加或删除指定数目的空格字符.

##### 火山.基本.文本类.加入换行文本

* **类型:** `全局方法`
* **名称:** `加入换行文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将回车及换行字符("\r\n")添加到当前文本尾部

##### 火山.基本.文本类.检查加入换行文本

* **类型:** `全局方法`
* **名称:** `检查加入换行文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 如果当前文本不以换行字符('\n')结束,则将回车及换行字符("\r\n")添加到当前文本尾部

##### 火山.基本.文本类.插入文本行首空格

* **类型:** `全局方法`
* **名称:** `插入文本行首空格`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲插入的空格数` (`整数`): 指定在文本每行行首插入的空格字符数目,不能小于0.
* **特性:**
	* `静态`
* **描述:** 将所指定文本的每行(基于换行符分隔)行首插入指定数目的空格字符

##### 火山.基本.文本类.删除文本空白行

* **类型:** `全局方法`
* **名称:** `删除文本空白行`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 删除所指定文本中的所有空行(基于换行符分隔,包括行中全为空白字符的文本行)

##### 火山.基本.文本类.取格式文本

* **类型:** `全局方法`
* **名称:** `取格式文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `格式文本` (`文本型`): 提供其中可以包含格式替换符的文本,其中的格式替换符将被后续对应参数所替换. 以下为常用的格式替换符,详细信息请参阅C++文档中关于sprintf函数的说明. %c: 字符 %d: 整数(以有符号十进制格式替换) %o: 整数(以无符号八进制格式替换) %u: 整数(以无符号十进制格式替换) %x: 整数(以无符号小写十六进制格式替换) %X: 整数(以无符号大写十六进制格式替换) %I64d: 长整数(以有符号十进制格式替换) %I64o: 长整数(以无符号八进制格式替换) %I64u: 长整数(以无符号十进制格式替换) %I64x: 长整数(以无符号小写十六进制格式替换) %I64X: 长整数(以无符号大写十六进制格式替换) %e, %E: 小数(以指数形式替换) %f: 小数(以非指数形式替换) %.8f: 小数(用来表达小数的带宽度限制的常用格式替换符) %g, %G: 小数(根据值大小自动选择是否以指数形式替换) %s: 文本型 %%: 百分号字符本身注意: 如果欲格式化"变整数"值,请务必将其先强制转换为整数或者长整数,再使用对应的格式替换符.
	* `替换数据` (`通用基本型`, `可扩展`): 用作给格式文本中的格式替换符提供替换数据,格式替换符的数目和数据类型必须与替换数据保持一致.
* **特性:**
	* `静态`
* **描述:** 建立所指定的格式文本
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-演示dll-sampledll-main](#vol-演示dll-sampledll-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-yaml数据访问-yaml-main](#vol-yaml数据访问-yaml-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.文本类.加入格式文本

* **类型:** `全局方法`
* **名称:** `加入格式文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `格式文本` (`文本型`): 提供其中可以包含格式替换符的文本,其中的格式替换符将被后续对应参数所替换. 以下为常用的格式替换符,详细信息请参阅C++文档中关于sprintf函数的说明. %c: 字符 %d: 整数(以有符号十进制格式替换) %o: 整数(以无符号八进制格式替换) %u: 整数(以无符号十进制格式替换) %x: 整数(以无符号小写十六进制格式替换) %X: 整数(以无符号大写十六进制格式替换) %I64d: 长整数(以有符号十进制格式替换) %I64o: 长整数(以无符号八进制格式替换) %I64u: 长整数(以无符号十进制格式替换) %I64x: 长整数(以无符号小写十六进制格式替换) %I64X: 长整数(以无符号大写十六进制格式替换) %e, %E: 小数(以指数形式替换) %f: 小数(以非指数形式替换) %.8f: 小数(用来表达小数的带宽度限制的常用格式替换符) %g, %G: 小数(根据值大小自动选择是否以指数形式替换) %s: 文本型 %%: 百分号字符本身注意: 如果欲格式化"变整数"值,请务必将其先强制转换为整数或者长整数,再使用对应的格式替换符.
	* `替换数据` (`通用基本型`, `可扩展`): 用作给格式文本中的格式替换符提供替换数据,格式替换符的数目和数据类型必须与替换数据保持一致.
* **特性:**
	* `静态`
* **描述:** 将所指定的格式文本添加到当前文本尾部
* **相关例程:** [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-yyjson数据访问-yyjson-main](#vol-yyjson数据访问-yyjson-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main)

##### 火山.基本.文本类.加入多行格式文本

* **类型:** `全局方法`
* **名称:** `加入多行格式文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所添加行首空格数` (`整数`): 指定在所提供的多行文本中每行行首添加的空格字符数目,不能小于0.
	* `格式文本` (`文本型`): 提供其中可以包含格式替换符的文本,其中的格式替换符将被后续对应参数所替换. 以下为常用的格式替换符,详细信息请参阅C++文档中关于sprintf函数的说明. %c: 字符 %d: 整数(以有符号十进制格式替换) %o: 整数(以无符号八进制格式替换) %u: 整数(以无符号十进制格式替换) %x: 整数(以无符号小写十六进制格式替换) %X: 整数(以无符号大写十六进制格式替换) %I64d: 长整数(以有符号十进制格式替换) %I64o: 长整数(以无符号八进制格式替换) %I64u: 长整数(以无符号十进制格式替换) %I64x: 长整数(以无符号小写十六进制格式替换) %I64X: 长整数(以无符号大写十六进制格式替换) %e, %E: 小数(以指数形式替换) %f: 小数(以非指数形式替换) %.8f: 小数(用来表达小数的带宽度限制的常用格式替换符) %g, %G: 小数(根据值大小自动选择是否以指数形式替换) %s: 文本型 %%: 百分号字符本身注意: 如果欲格式化"变整数"值,请务必将其先强制转换为整数或者长整数,再使用对应的格式替换符.
	* `替换数据` (`通用基本型`, `可扩展`): 用作给格式文本中的格式替换符提供替换数据,格式替换符的数目和数据类型必须与替换数据保持一致.
* **特性:**
	* `静态`
* **描述:** 将所指定的多行格式文本(基于换行符分隔)添加到当前文本尾部

##### 火山.基本.文本类.置部分文本

* **类型:** `全局方法`
* **名称:** `置部分文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲复制的文本` (`文本型`): 提供所欲复制进当前文本中的文本内容
	* `所欲复制的长度` (`整数`): 提供欲将所指定文本的多少字符复制进当前文本中. 必须大于等于0且小于等于所欲复制文本的长度.
* **特性:**
	* `静态`
* **描述:** 将所指定文本的部分内容复制到当前文本中,当前文本的原有内容将被覆盖.

##### 火山.基本.文本类.逆序置文本

* **类型:** `全局方法`
* **名称:** `逆序置文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲复制的文本` (`文本型`): 提供所欲逆序复制进当前文本中的文本内容
* **特性:**
	* `静态`
* **描述:** 将所指定文本的内容逆序翻转后复制到当前文本中,当前文本的原有内容将被覆盖.

##### 火山.基本.文本类.取逆序文本

* **类型:** `全局方法`
* **名称:** `取逆序文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲翻转的文本` (`文本型`): 提供所欲逆序翻转的文本
* **特性:**
	* `静态`
* **描述:** 将所指定文本的内容逆序翻转后置入一个新文本中,然后将其返回.

##### 火山.基本.文本类.逆序置部分文本

* **类型:** `全局方法`
* **名称:** `逆序置部分文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲复制的文本` (`文本型`): 提供所欲逆序复制进当前文本中的文本内容
	* `所欲复制的长度` (`整数`): 提供欲将所指定文本的多少字符逆序复制进当前文本中. 必须大于等于0且小于等于所欲复制文本的长度.
* **特性:**
	* `静态`
* **描述:** 将所指定文本的部分内容逆序翻转后复制到当前文本中,当前文本的原有内容将被覆盖.

##### 火山.基本.文本类.替换文本控制符

* **类型:** `全局方法`
* **名称:** `替换文本控制符`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定文本中的所有控制类字符替换为空格

##### 火山.基本.文本类.文本替换

* **类型:** `全局方法`
* **名称:** `文本替换`
* **参数:**
	* `被替换文本` (`文本型`): 提供欲被替换的文本
	* `起始替换索引位置` (`整数`): 指定替换的起始索引位置,必须大于等于0且小于等于被替换文本长度.
	* `替换长度` (`整数`): 指定所欲替换的文本部分的长度,必须大于等于0且加上"起始替换索引位置"后小于等于被替换文本长度.
	* `用作替换的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将指定文本的某一部分用其它的文本替换

##### 火山.基本.文本类.子文本替换

* **类型:** `全局方法`
* **名称:** `子文本替换`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `欲被替换的子文本` (`文本型`): 提供欲被替换的子文本
	* `用作替换的文本` (`文本型`): 提供用作替换所指定子文本的文本
	* `起始替换索引位置` (`整数`, 默认值: `0`): 指定在欲被替换文本中的起始搜寻索引位置,必须大于等于0且小于欲被替换文本的长度.
	* `替换次数` (`整数`, 默认值: `-1`): 指定所欲进行替换的次数,如果小于0则全部替换.
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定比较时是否区分英文字母的大小写
* **特性:**
	* `静态`
* **描述:** 将所指定文本中的指定内容子文本替换为另一个文本
* **相关例程:** [vol-树形框-tree_box-main](#vol-树形框-tree_box-main), [vol-json数据访问-json-main](#vol-json数据访问-json-main), [vol-yyjson数据访问-yyjson-main](#vol-yyjson数据访问-yyjson-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.文本类.替换所有子文本

* **类型:** `全局方法`
* **名称:** `替换所有子文本`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `欲被替换的子文本` (`文本型`): 提供欲被替换的子文本
	* `用作替换的文本` (`文本型`): 提供用作替换所指定子文本的文本
* **特性:**
	* `静态`
* **描述:** 将所指定文本中的所有指定内容子文本均替换为另一个文本
* **返回值描述:** 返回是否产生了实际替换
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main)

##### 火山.基本.文本类.替换字符

* **类型:** `全局方法`
* **名称:** `替换字符`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲被替换的字符` (`字符`): 提供文本中所欲被替换的字符
	* `所欲替换到的字符` (`字符`): 提供用作替换的字符
	* `起始替换索引位置` (`整数`, 默认值: `0`): 提供起始替换索引位置,必须大于等于0且小于等于文本长度.
* **特性:**
	* `静态`
* **描述:** 将文本中所有指定字符均替换为另一个
* **返回值描述:** 返回是否产生了实际替换

##### 火山.基本.文本类.加入小数文本

* **类型:** `全局方法`
* **名称:** `加入小数文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲加入的小数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 将所指定小数转换为文本后加入到当前文本尾部

##### 火山.基本.文本类.加入整数文本

* **类型:** `全局方法`
* **名称:** `加入整数文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲加入的整数` (`整数`)
* **特性:**
	* `静态`
* **描述:** 将所指定整数转换为文本后加入到当前文本尾部

##### 火山.基本.文本类.加入无符号整数文本

* **类型:** `全局方法`
* **名称:** `加入无符号整数文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲加入的整数` (`整数`)
* **特性:**
	* `静态`
* **描述:** 将所指定整数转换为无符号文本后加入到当前文本尾部

##### 火山.基本.文本类.加入长整数文本

* **类型:** `全局方法`
* **名称:** `加入长整数文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲加入的长整数` (`长整数`)
* **特性:**
	* `静态`
* **描述:** 将所指定长整数转换为文本后加入到当前文本尾部

##### 火山.基本.文本类.加入无符号长整数文本

* **类型:** `全局方法`
* **名称:** `加入无符号长整数文本`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲加入的长整数` (`长整数`)
* **特性:**
	* `静态`
* **描述:** 将所指定长整数转换为无符号文本后加入到当前文本尾部

##### 火山.基本.文本类.到大写

* **类型:** `全局方法`
* **名称:** `到大写`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将当前文本中的所有英文字母转换为大写,返回转换后的结果文本.
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.文本类.到小写

* **类型:** `全局方法`
* **名称:** `到小写`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将当前文本中的所有英文字母转换为小写,返回转换后的结果文本.

##### 火山.基本.文本类.到全角

* **类型:** `全局方法`
* **名称:** `到全角`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将文本中所有的半角英文字符转换为对应的全角中文字符,返回转换后的结果文本.

##### 火山.基本.文本类.到半角

* **类型:** `全局方法`
* **名称:** `到半角`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将文本中所有的全角中文字符转换为对应的半角英文字符,返回转换后的结果文本.

##### 火山.基本.文本类.删首空

* **类型:** `全局方法`
* **名称:** `删首空`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 删除当前文本首部的所有空白字符(全半角空格/回车/换行/制表符等),返回删除后的结果文本.

##### 火山.基本.文本类.删尾空

* **类型:** `全局方法`
* **名称:** `删尾空`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 删除当前文本尾部的所有空白字符(全半角空格/回车/换行/制表符等),返回删除后的结果文本.

##### 火山.基本.文本类.删首尾空

* **类型:** `全局方法`
* **名称:** `删首尾空`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 删除当前文本首部和尾部的所有空白字符(全半角空格/回车/换行/制表符等),返回删除后的结果文本.
* **相关例程:** [vol-密码管理-pw-main](#vol-密码管理-pw-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.文本类.删全部空

* **类型:** `全局方法`
* **名称:** `删全部空`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 删除当前文本中的所有空白字符(全半角空格/回车/换行/制表符等),返回删除后的结果文本.

##### 火山.基本.文本类.自身到大写

* **类型:** `全局方法`
* **名称:** `自身到大写`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将当前文本自身中的所有英文字母转换为大写

##### 火山.基本.文本类.自身到小写

* **类型:** `全局方法`
* **名称:** `自身到小写`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将当前文本自身中的所有英文字母转换为小写

##### 火山.基本.文本类.自身到全角

* **类型:** `全局方法`
* **名称:** `自身到全角`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将文本自身中所有的半角英文字符转换为对应的全角中文字符

##### 火山.基本.文本类.自身到半角

* **类型:** `全局方法`
* **名称:** `自身到半角`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将文本自身中所有的全角中文字符转换为对应的半角英文字符

##### 火山.基本.文本类.删自身首空

* **类型:** `全局方法`
* **名称:** `删自身首空`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 删除当前文本自身首部的所有空白字符

##### 火山.基本.文本类.删自身尾空

* **类型:** `全局方法`
* **名称:** `删自身尾空`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 删除当前文本自身尾部的所有空白字符

##### 火山.基本.文本类.删自身首尾空

* **类型:** `全局方法`
* **名称:** `删自身首尾空`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 删除当前文本自身首部和尾部的所有空白字符

##### 火山.基本.文本类.寻找字符

* **类型:** `全局方法`
* **名称:** `寻找字符`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲查找的字符` (`字符`): 提供所欲查找的字符
	* `起始查找索引位置` (`整数`, 默认值: `0`): 提供起始查找的索引位置,必须大于等于0且小于等于文本长度.
* **特性:**
	* `静态`
* **描述:** 查找当前文本中所指定字符的所处索引位置,未找到则返回-1.

##### 火山.基本.文本类.倒找字符

* **类型:** `全局方法`
* **名称:** `倒找字符`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲查找的字符` (`字符`): 提供所欲查找的字符
* **特性:**
	* `静态`
* **描述:** 逆向查找当前文本中所指定字符的所处索引位置,未找到则返回-1.

##### 火山.基本.文本类.寻找文本

* **类型:** `全局方法`
* **名称:** `寻找文本`
* **返回值数据类型:** `整数`
* **参数:**
	* `被搜寻的文本` (`文本型`)
	* `欲寻找的文本` (`文本型`): 提供所欲查找的文本内容
	* `起始搜寻位置` (`整数`, 默认值: `0`): 提供起始查找的索引位置,必须大于等于0且小于等于文本长度.
	* `是否不区分大小写` (`逻辑型`, 默认值: `假`): 指定比较时是否不区分英文字母的大小写
* **特性:**
	* `静态`
* **描述:** 查找当前文本中所指定文本的所处索引位置,未找到则返回-1.
* **相关例程:** [vol-表格-grid-main](#vol-表格-grid-main), [vol-edge浏览框自定义菜单-webview2_contextmenu-main](#vol-edge浏览框自定义菜单-webview2_contextmenu-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main)

##### 火山.基本.文本类.倒找文本

* **类型:** `全局方法`
* **名称:** `倒找文本`
* **返回值数据类型:** `整数`
* **参数:**
	* `被搜寻的文本` (`文本型`)
	* `欲寻找的文本` (`文本型`): 提供所欲查找的文本内容
	* `起始搜寻位置` (`整数`, 默认值: `-1`): 提供起始查找的索引位置,小于等于文本长度,如果小于0表示从文本尾部开始查找.
	* `是否不区分大小写` (`逻辑型`, 默认值: `假`): 指定比较时是否不区分英文字母的大小写
* **特性:**
	* `静态`
* **描述:** 逆向查找当前文本中所指定文本的所处索引位置,未找到则返回-1.
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.文本类.是否以字符开头

* **类型:** `全局方法`
* **名称:** `是否以字符开头`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲检查的字符` (`字符`): 提供用来检查是否以其开头的字符
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定比较时是否区分英文字母的大小写
* **特性:**
	* `静态`
* **描述:** 返回当前文本是否以所指定字符开头

##### 火山.基本.文本类.是否以文本开头

* **类型:** `全局方法`
* **名称:** `是否以文本开头`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲检查的文本` (`文本型`): 提供用来检查是否以其开头的文本
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定比较时是否区分英文字母的大小写
* **特性:**
	* `静态`
* **描述:** 返回当前文本是否以所指定文本开头
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main)

##### 火山.基本.文本类.是否以字符结束

* **类型:** `全局方法`
* **名称:** `是否以字符结束`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲检查的字符` (`字符`): 提供用来检查是否以其结束的字符
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定比较时是否区分英文字母的大小写
* **特性:**
	* `静态`
* **描述:** 返回当前文本是否以所指定字符结束

##### 火山.基本.文本类.是否以文本结束

* **类型:** `全局方法`
* **名称:** `是否以文本结束`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `所欲检查的文本` (`文本型`): 提供用来检查是否以其结束的文本
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定比较时是否区分英文字母的大小写
* **特性:**
	* `静态`
* **描述:** 返回当前文本是否以所指定文本结束
* **相关例程:** [vol-cximage高级图像处理-cximage-main](#vol-cximage高级图像处理-cximage-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.文本类.取尾字符

* **类型:** `全局方法`
* **名称:** `取尾字符`
* **返回值数据类型:** `字符`
* **参数:**
	* `所欲操作的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回当前文本的尾部字符,如果当前文本为空,则返回零字符.

##### 火山.基本.文本类.分割左右文本

* **类型:** `全局方法`
* **名称:** `分割左右文本`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `分割字符` (`字符`): 提供分割所使用的字符,文本将在该字符首次出现的位置处分割成左右两个部分.
	* `左结果文本` (`文本型`, 默认值: `空对象`): 如果不为空对象且方法返回真,则将所分割出来的左边文本内容存放入此参数结果变量中.
	* `右结果文本` (`文本型`, 默认值: `空对象`): 如果不为空对象且方法返回真,则将所分割出来的右边文本内容存放入此参数结果变量中.
	* `是否删除首尾空` (`逻辑型`, 默认值: `真`): 是否自动删除左右分割结果文本的首尾空白
* **特性:**
	* `静态`
* **描述:** 把文本在所指定字符首次出现的位置处分割成左右两个部分
* **返回值描述:** 分割成功返回真,未找到所指定的分割字符返回假.
* **相关例程:** [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main)

##### 火山.基本.文本类.分割左右子文本

* **类型:** `全局方法`
* **名称:** `分割左右子文本`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `分割用子文本` (`文本型`): 提供分割所使用的子文本,文本将在该子文本首次出现的位置处分割成左右两个部分.
	* `左结果文本` (`文本型`, 默认值: `空对象`): 如果不为空对象且方法返回真,则将所分割出来的左边文本内容存放入此参数结果变量中.
	* `右结果文本` (`文本型`, 默认值: `空对象`): 如果不为空对象且方法返回真,则将所分割出来的右边文本内容存放入此参数结果变量中.
	* `是否删除首尾空` (`逻辑型`, 默认值: `真`): 是否自动删除左右分割结果文本的首尾空白
* **特性:**
	* `静态`
* **描述:** 把文本在所指定子文本首次出现的位置处分割成左右两个部分
* **返回值描述:** 分割成功返回真,未找到所指定的分割子文本返回假.

##### 火山.基本.文本类.分割文本

* **类型:** `全局方法`
* **名称:** `分割文本`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `分割字符集合` (`文本型`): 提供进行分割时所基于的所有字符,其中的每个字符均在分割时被使用(即遇到其中任何一个字符时均认为发现了一个分割点). 譬如: ",;\n", 即指定了基于逗号/分号/换行符三个字符进行分割,遇到了这三个字符中的任何一个,均进行一次分割.
	* `结果存放数组` (`文本数组类`): 用作提供存放所有分割结果文本用的数组,其中的原有内容将被覆盖.
	* `是否删除首尾空` (`逻辑型`, 默认值: `真`): 是否自动删除所有分割结果文本的首尾空白
	* `是否忽略空白结果` (`逻辑型`, 默认值: `真`): 是否自动去除所有为空或全部为空白字符的分割结果文本
* **特性:**
	* `静态`
* **描述:** 将文本基于所指定的字符集合进行分割,然后将分割结果存放到所指定的数组中,返回存放到所指定数组中的成员数目(即所分割出来的结果文本数目).
* **相关例程:** [vol-表格-grid-main](#vol-表格-grid-main), [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-yolov5目标检测-yolov5-main](#vol-yolov5目标检测-yolov5-main)

##### 火山.基本.文本类.分割子文本

* **类型:** `全局方法`
* **名称:** `分割子文本`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `分割用子文本` (`文本型`): 提供进行分割时所基于的子文本
	* `结果存放数组` (`文本数组类`): 用作提供存放所有分割结果文本用的数组,其中的原有内容将被覆盖.
	* `是否删除首尾空` (`逻辑型`, 默认值: `真`): 是否自动删除所有分割结果文本的首尾空白
	* `是否忽略空白结果` (`逻辑型`, 默认值: `真`): 是否自动去除所有为空或全部为空白字符的分割结果文本
* **特性:**
	* `静态`
* **描述:** 将文本基于所指定的子文本进行分割,然后将分割结果存放到所指定的数组中,返回存放到所指定数组中的成员数目(即所分割出来的结果文本数目).
* **相关例程:** [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.文本类.分割整数文本

* **类型:** `全局方法`
* **名称:** `分割整数文本`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `分割字符` (`字符`): 提供进行分割时所基于的字符,在被分割文本中的每一个该字符均被认为是一个分割点.
	* `结果存放数组` (`整数数组类`): 用作提供存放所有分割结果整数用的数组,其中的原有内容将被覆盖.
* **特性:**
	* `静态`
* **描述:** 将文本基于所指定的字符进行分割,然后将分割结果转换到整数后存放到所指定的数组中,返回存放到所指定数组中的成员数目(即所分割出来的结果整数数目).

##### 火山.基本.文本类.分割小数文本

* **类型:** `全局方法`
* **名称:** `分割小数文本`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的文本` (`文本型`)
	* `分割字符` (`字符`): 提供进行分割时所基于的字符,在被分割文本中的每一个该字符均被认为是一个分割点.
	* `结果存放数组` (`小数数组类`): 用作提供存放所有分割结果小数用的数组,其中的原有内容将被覆盖.
* **特性:**
	* `静态`
* **描述:** 将文本基于所指定的字符进行分割,然后将分割结果转换到小数后存放到所指定的数组中,返回存放到所指定数组中的成员数目(即所分割出来的结果小数数目).

##### 火山.基本.文本类.近似等于

* **类型:** `全局方法`
* **名称:** `近似等于`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `被比较文本` (`文本型`)
	* `比较文本` (`文本型`)
	* `是否区分大小写` (`逻辑型`, 默认值: `真`)
* **特性:**
	* `静态`
* **描述:** 当比较文本在被比较文本的首部被包容时返回真,否则返回假.

---

#### 火山.基本.COM操作类

* **类型:** `类`
* **名称:** `COM操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **描述:** 提供一些COM全局操作支持

##### 火山.基本.COM操作类.注册OCX

* **类型:** `全局方法`
* **名称:** `注册OCX`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲注册OCX文件名` (`文本型`)
	* `是否为注册` (`逻辑型`): 为真则注册,为假则取消注册.
* **特性:**
	* `静态`
* **描述:** 注册或取消注册OCX组件
* **返回值描述:** 返回是否成功

##### 火山.基本.COM操作类.查看COM对象

* **类型:** `全局方法`
* **名称:** `查看COM对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `对象类型` (`文本型`): 指定对象的类型文本,可以为其可识别名称: 譬如"Excel.Application"/"Word.Application",也可以是其CLSID,如"{0003088F-0000-0000-C000-000000000058}".
	* `类型库文件名` (`文本型`, 默认值: `""`): 如果需要通过类型库才能访问指定对象,可在本参数中提供其类型库或类型库数据所在文件名. 注意如果没有提供文件名,且在当前目录下无法找到该文件,系统将自动进行搜索.
	* `父窗口句柄` (`变整数`, 默认值: `0`): 提供对话框的父窗口句柄,为0表示使用默认父窗口.
* **特性:**
	* `静态`
* **描述:** 启动一个对话框来显示所指定对象类型的COM接口信息. 注意: 本方法只能在主界面线程中执行.
* **返回值描述:** 成功返回真,失败返回假.

---

#### 火山.基本.COM变体类型

* **类型:** `类`
* **名称:** `COM变体类型`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `COM操作.辅助类`
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main)

##### 火山.基本.COM变体类型.未知

* **类型:** `成员常量`
* **名称:** `未知`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.空

* **类型:** `成员常量`
* **名称:** `空`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.错误值

* **类型:** `成员常量`
* **名称:** `错误值`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.字节值

* **类型:** `成员常量`
* **名称:** `字节值`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.短整数值

* **类型:** `成员常量`
* **名称:** `短整数值`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.整数值

* **类型:** `成员常量`
* **名称:** `整数值`
* **数据类型:** `COM变体类型`
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体类型.长整数值

* **类型:** `成员常量`
* **名称:** `长整数值`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.单精度小数值

* **类型:** `成员常量`
* **名称:** `单精度小数值`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.小数值

* **类型:** `成员常量`
* **名称:** `小数值`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.日期值

* **类型:** `成员常量`
* **名称:** `日期值`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.逻辑值

* **类型:** `成员常量`
* **名称:** `逻辑值`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.文本值

* **类型:** `成员常量`
* **名称:** `文本值`
* **数据类型:** `COM变体类型`
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main)

##### 火山.基本.COM变体类型.COM对象

* **类型:** `成员常量`
* **名称:** `COM对象`
* **数据类型:** `COM变体类型`
* **描述:** 其中可以用作存放火山对象

##### 火山.基本.COM变体类型.COM自动化对象

* **类型:** `成员常量`
* **名称:** `COM自动化对象`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.错误值数组

* **类型:** `成员常量`
* **名称:** `错误值数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.字节值数组

* **类型:** `成员常量`
* **名称:** `字节值数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.短整数值数组

* **类型:** `成员常量`
* **名称:** `短整数值数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.整数值数组

* **类型:** `成员常量`
* **名称:** `整数值数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.长整数值数组

* **类型:** `成员常量`
* **名称:** `长整数值数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.单精度小数值数组

* **类型:** `成员常量`
* **名称:** `单精度小数值数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.小数值数组

* **类型:** `成员常量`
* **名称:** `小数值数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.日期值数组

* **类型:** `成员常量`
* **名称:** `日期值数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.逻辑值数组

* **类型:** `成员常量`
* **名称:** `逻辑值数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.文本值数组

* **类型:** `成员常量`
* **名称:** `文本值数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.COM对象数组

* **类型:** `成员常量`
* **名称:** `COM对象数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.COM自动化对象数组

* **类型:** `成员常量`
* **名称:** `COM自动化对象数组`
* **数据类型:** `COM变体类型`

##### 火山.基本.COM变体类型.COM变体型数组

* **类型:** `成员常量`
* **名称:** `COM变体型数组`
* **数据类型:** `COM变体类型`

---

#### 火山.基本.COM数组成员类型

* **类型:** `类`
* **名称:** `COM数组成员类型`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `COM操作.辅助类`
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.COM数组成员类型.错误值

* **类型:** `成员常量`
* **名称:** `错误值`
* **数据类型:** `COM数组成员类型`

##### 火山.基本.COM数组成员类型.字节值

* **类型:** `成员常量`
* **名称:** `字节值`
* **数据类型:** `COM数组成员类型`

##### 火山.基本.COM数组成员类型.短整数值

* **类型:** `成员常量`
* **名称:** `短整数值`
* **数据类型:** `COM数组成员类型`

##### 火山.基本.COM数组成员类型.整数值

* **类型:** `成员常量`
* **名称:** `整数值`
* **数据类型:** `COM数组成员类型`
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM数组成员类型.长整数值

* **类型:** `成员常量`
* **名称:** `长整数值`
* **数据类型:** `COM数组成员类型`

##### 火山.基本.COM数组成员类型.单精度小数值

* **类型:** `成员常量`
* **名称:** `单精度小数值`
* **数据类型:** `COM数组成员类型`
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM数组成员类型.小数值

* **类型:** `成员常量`
* **名称:** `小数值`
* **数据类型:** `COM数组成员类型`
* **相关例程:** [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.COM数组成员类型.日期值

* **类型:** `成员常量`
* **名称:** `日期值`
* **数据类型:** `COM数组成员类型`

##### 火山.基本.COM数组成员类型.逻辑值

* **类型:** `成员常量`
* **名称:** `逻辑值`
* **数据类型:** `COM数组成员类型`

##### 火山.基本.COM数组成员类型.文本值

* **类型:** `成员常量`
* **名称:** `文本值`
* **数据类型:** `COM数组成员类型`

##### 火山.基本.COM数组成员类型.COM对象型

* **类型:** `成员常量`
* **名称:** `COM对象型`
* **数据类型:** `COM数组成员类型`
* **描述:** 其中可以用作存放火山对象
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM数组成员类型.COM自动化对象型

* **类型:** `成员常量`
* **名称:** `COM自动化对象型`
* **数据类型:** `COM数组成员类型`
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.COM数组成员类型.COM变体型

* **类型:** `成员常量`
* **名称:** `COM变体型`
* **数据类型:** `COM数组成员类型`

---

#### 火山.基本.COM变体型

* **类型:** `类`
* **名称:** `COM变体型`
* **描述:** 用作封装COM操作中的VARIANT数据
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.COM变体型.清空

* **类型:** `方法`
* **名称:** `清空`
* **参数:**
	* `所操作本对象` (`COM变体型`)
* **特性:**
	* `静态`
* **描述:** 将本对象的内容释放并清空.如果不调用本方法,则对象在退出其作用区域时会自动清空.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
* **特性:**
	* `静态`
* **描述:** 返回本对象的内容是否为空
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.取类型

* **类型:** `方法`
* **名称:** `取类型`
* **返回值数据类型:** `COM变体类型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
* **特性:**
	* `静态`
* **描述:** 返回本对象中值的数据类型,如果无法识别,则返回"COM变体类型.未知".
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.置类型

* **类型:** `方法`
* **名称:** `置类型`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲修改到的类型` (`COM变体类型`)
* **特性:**
	* `静态`
* **描述:** 改变本对象中已有值的数据类型,根据需要改变值数据本身,返回是否成功.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main)

##### 火山.基本.COM变体型.是否为数组

* **类型:** `方法`
* **名称:** `是否为数组`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
* **特性:**
	* `静态`
* **描述:** 返回本对象的值内容是否为数组数据
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.取数组成员数

* **类型:** `方法`
* **名称:** `取数组成员数`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作本对象` (`COM变体型`)
* **特性:**
	* `静态`
* **描述:** 如果本对象中存放的是数组数据,执行本方法将返回其成员数目,否则将返回0.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.取数组成员尺寸

* **类型:** `方法`
* **名称:** `取数组成员尺寸`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作本对象` (`COM变体型`)
* **特性:**
	* `静态`
* **描述:** 如果本对象中存放的是数组数据,执行本方法将返回其单个成员的存储尺寸(单位字节),否则将返回0.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.取数组数据尺寸

* **类型:** `方法`
* **名称:** `取数组数据尺寸`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作本对象` (`COM变体型`)
* **特性:**
	* `静态`
* **描述:** 如果本对象中存放的是数组数据,执行本方法将返回其所有成员数据的总存储尺寸(单位字节),否则将返回0. 本方法的调用结果等于: 取数组成员数 () * 取数组成员尺寸 ()

##### 火山.基本.COM变体型.取值

* **类型:** `方法`
* **名称:** `取值`
* **返回值数据类型:** `调用本方法时为"所欲读取值的类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲读取值的类型` (`通用基本型(需求:数据类型)`): 提供所欲获取数据的数据类型
	* `数组成员索引` (`整数`, 默认值: `-1`): 如果本对象内为数组型数据,且欲对数组内的某个成员进行访问,则可以在此参数中指定其成员索引值(从0开始且必须小于数组已有成员数),否则请保持本参数为默认值-1表示不为访问数组成员.
* **特性:**
	* `静态`
* **描述:** 返回本对象或本对象数组成员中的所指定类型数据值,如果类型不匹配将尝试自动转换. 提示: 日期型的变体型数据可以通过"小数"类型取出.
* **返回值描述:** 成功将返回对应的值,失败如果是数值型将返回0,逻辑型将返回假,文本型将返回空文本.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.COM变体型.赋值

* **类型:** `方法`
* **名称:** `赋值`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲写入的值` (`通用基本型`): 提供所欲写入的数据值
	* `数组成员索引` (`整数`, 默认值: `-1`): 如果本对象内为数组型数据,且欲对数组内的某个成员进行访问,则可以在此参数中指定其成员索引值(从0开始且必须小于数组已有成员数),否则请保持本参数为默认值-1表示不为访问数组成员.
* **特性:**
	* `静态`
* **描述:** 将所指定类型的数据设置进本对象或本对象的数组成员中,其中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.COM变体型.取字节集

* **类型:** `方法`
* **名称:** `取字节集`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `结果返回参数` (`字节集类`): 所获取的结果将填入此变量中,其中原有内容将被清除.
* **特性:**
	* `静态`
* **描述:** 如果本对象中所保存数据不为指针型(文本/对象)数据数组或者为结构型数据,则将其中的内容复制到所指定的结果参数字节集中.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.置字节集

* **类型:** `方法`
* **名称:** `置字节集`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲写入的值` (`字节集类`)
* **特性:**
	* `静态`
* **描述:** 将本对象的内容设置为所指定内容的字节数组,先前内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.取COM对象

* **类型:** `方法`
* **名称:** `取COM对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `结果返回参数` (`COM对象类`): 所获取的结果将填入此变量中,其中原有内容将被覆盖.
	* `数组成员索引` (`整数`, 默认值: `-1`): 如果本对象内为数组型数据,且欲对数组内的某个成员进行访问,则可以在此参数中指定其成员索引值(从0开始且必须小于数组已有成员数),否则请保持本参数为默认值-1表示不为访问数组成员.
* **特性:**
	* `静态`
* **描述:** 获取本对象或本对象数组成员中的所指定COM对象值
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.COM变体型.取COM对象2

* **类型:** `方法`
* **名称:** `取COM对象2`
* **返回值数据类型:** `调用本方法时为"所欲获取数据类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲获取数据类型` (`COM对象类(需求:数据类型)`): 提供所欲获得的返回值数据类型
	* `数组成员索引` (`整数`, 默认值: `-1`): 如果本对象内为数组型数据,且欲对数组内的某个成员进行访问,则可以在此参数中指定其成员索引值(从0开始且必须小于数组已有成员数),否则请保持本参数为默认值-1表示不为访问数组成员.
* **特性:**
	* `静态`
* **描述:** 读取并返回本对象或本对象数组成员中的指定名称COM对象值. 执行本方法如果失败,返回内容为空的该类对象(COM对象类的"是否为空"方法返回真).
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.COM变体型.置COM对象

* **类型:** `方法`
* **名称:** `置COM对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲写入的值` (`COM对象类`): 提供所欲写入的COM对象值
	* `数组成员索引` (`整数`, 默认值: `-1`): 如果本对象内为数组型数据,且欲对数组内的某个成员进行访问,则可以在此参数中指定其成员索引值(从0开始且必须小于数组已有成员数),否则请保持本参数为默认值-1表示不为访问数组成员.
* **特性:**
	* `静态`
* **描述:** 将所指定COM对象值设置进本对象或本对象的数组成员中,其中原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.COM变体型.置COM自动化对象

* **类型:** `方法`
* **名称:** `置COM自动化对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲写入的值` (`COM对象类`): 提供所欲写入的COM对象值,必须能转换到COM自动化对象(IDispatch),否则将置入空对象.
	* `数组成员索引` (`整数`, 默认值: `-1`): 如果本对象内为数组型数据,且欲对数组内的某个成员进行访问,则可以在此参数中指定其成员索引值(从0开始且必须小于数组已有成员数),否则请保持本参数为默认值-1表示不为访问数组成员.
* **特性:**
	* `静态`
* **描述:** 将所指定COM自动对象值设置进本对象或本对象的数组成员中,其中原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.COM变体型.取火山对象

* **类型:** `方法`
* **名称:** `取火山对象`
* **返回值数据类型:** `调用本方法时为"所欲获取对象类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲获取对象类型` (`对象类(需求:数据类型)`): 提供所欲获取的火山对象的类型
	* `数组成员索引` (`整数`, 默认值: `-1`): 如果本对象内为数组型数据,且欲对数组内的某个成员进行访问,则可以在此参数中指定其成员索引值(从0开始且必须小于数组已有成员数),否则请保持本参数为默认值-1表示不为访问数组成员.
* **特性:**
	* `静态`
* **描述:** 获取本对象中或本对象数组成员中所指定类型的火山对象参考,如果所存储的数据不为该类型的火山对象,将返回一个该类型的空火山对象(在该对象上调用"是否为空对象"方法返回真).
* **返回值描述:** 成功返回所存储的火山对象参考,失败返回一个空对象.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.置火山对象

* **类型:** `方法`
* **名称:** `置火山对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲写入的值` (`对象类`): 提供所欲写入的火山对象数据内容
	* `数组成员索引` (`整数`, 默认值: `-1`): 如果本对象内为数组型数据,且欲对数组内的某个成员进行访问,则可以在此参数中指定其成员索引值(从0开始且必须小于数组已有成员数),否则请保持本参数为默认值-1表示不为访问数组成员.
* **特性:**
	* `静态`
* **描述:** 根据所指定的火山对象数据,建立一个复制对象并将其设置进本对象或本对象的数组成员中,其中原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.取变体型

* **类型:** `方法`
* **名称:** `取变体型`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `结果返回参数` (`COM变体型`): 所获取的结果将填入此变量中,其中原有内容将被清除.
	* `数组成员索引` (`整数`, 默认值: `-1`): 如果本对象内为数组型数据,且欲对数组内的某个成员进行访问,则可以在此参数中指定其成员索引值(从0开始且必须小于数组已有成员数),否则请保持本参数为默认值-1表示不为访问数组成员.
* **特性:**
	* `静态`
* **描述:** 获取本对象或本对象数组成员中的所指定变体型数据的内容
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.置变体型

* **类型:** `方法`
* **名称:** `置变体型`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲写入的值` (`COM变体型`): 提供所欲写入的变体数据内容
	* `数组成员索引` (`整数`, 默认值: `-1`): 如果本对象内为数组型数据,且欲对数组内的某个成员进行访问,则可以在此参数中指定其成员索引值(从0开始且必须小于数组已有成员数),否则请保持本参数为默认值-1表示不为访问数组成员.
* **特性:**
	* `静态`
* **描述:** 将所指定变体型数据值设置进本对象或本对象的数组成员中,其中原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.取数组

* **类型:** `方法`
* **名称:** `取数组`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所存储到的数组` (`通用基本型数组(需求:可写入变量)`): 提供用作存储所获取到数据的数组变量,本对象中的数组数据类型必须与该数组的数据类型匹配,否则将无法取出.
	* `首成员索引位置` (`整数`, 默认值: `0`): 提供欲在本对象数组数据中读取的首成员索引位置,从0开始.
	* `所欲读取的成员数` (`整数`, 默认值: `-1`): 提供所欲读取的本对象数组成员数目,如果小于0则表示使用"所存储到的数组"参数数组所定义的全部成员数目.
* **特性:**
	* `静态`
* **描述:** 如果本对象中所保存数据为数组,则将其中的数据取出到所指定数组中.
* **返回值描述:** 返回所实际取出的数组成员数目,为"所欲读取的成员数"参数值和本对象数组中所实际存储成员数两者中的较小值.如果失败则返回0(注意正常也可能返回0).
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.置数组

* **类型:** `方法`
* **名称:** `置数组`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲置入的数组` (`通用基本型数组`)
	* `首成员索引位置` (`整数`, 默认值: `0`): 提供所欲置入的"所欲置入的数组"数组中首成员索引位置,从0开始.
	* `所欲置入的成员数` (`整数`, 默认值: `-1`): 提供所欲置入的"所欲置入的数组"数组中成员数目,如果小于0则表示使用"所欲置入的数组"参数数组在"首成员索引位置"参数位置后的所有成员数目.
* **特性:**
	* `静态`
* **描述:** 将所提供的数组数据填入本对象中,其中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.取变体型数组

* **类型:** `方法`
* **名称:** `取变体型数组`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所存储到的数组` (`COM变体型 [](需求:可写入变量)`)
	* `首成员索引位置` (`整数`, 默认值: `0`): 提供所欲在本对象数组数据中读取的首成员索引位置,从0开始.
	* `所欲读取的成员数` (`整数`, 默认值: `-1`): 提供所欲读取的本对象数组成员数目,如果小于0则表示使用"所存储到的数组"参数数组所定义的全部成员数目.
* **特性:**
	* `静态`
* **描述:** 如果本对象中所保存数据为变体型数组,则将其中的数据取出到所指定数组中.
* **返回值描述:** 返回所实际取出的数组成员数目,为"所欲读取的成员数"参数值和本对象数组中所实际存储成员数两者中的较小值.如果失败则返回0(注意正常也可能返回0).
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.置变体型数组

* **类型:** `方法`
* **名称:** `置变体型数组`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲置入的数组` (`COM变体型 []`)
	* `首成员索引位置` (`整数`, 默认值: `0`): 提供所欲置入的"所欲置入的数组"数组中首成员索引位置,从0开始.
	* `所欲置入的成员数` (`整数`, 默认值: `-1`): 提供所欲置入的"所欲置入的数组"数组中成员数目,如果小于0则表示使用"所欲置入的数组"参数数组在"首成员索引位置"参数位置后的所有成员数目.
* **特性:**
	* `静态`
* **描述:** 将所提供的数组数据填入本对象中,其中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.取COM对象数组

* **类型:** `方法`
* **名称:** `取COM对象数组`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所存储到的数组` (`COM对象类 [](需求:可写入变量)`)
	* `首成员索引位置` (`整数`, 默认值: `0`): 提供所欲在本对象数组数据中读取的首成员索引位置,从0开始.
	* `所欲读取的成员数` (`整数`, 默认值: `-1`): 提供所欲读取的本对象数组成员数目,如果小于0则表示使用"所存储到的数组"参数数组所定义的全部成员数目.
* **特性:**
	* `静态`
* **描述:** 如果本对象中所保存数据为COM对象数组,则将其中的数据取出到所指定数组中.
* **返回值描述:** 返回所实际取出的数组成员数目,为"所欲读取的成员数"参数值和本对象数组中所实际存储成员数两者中的较小值.如果失败则返回0(注意正常也可能返回0).

##### 火山.基本.COM变体型.置COM对象数组

* **类型:** `方法`
* **名称:** `置COM对象数组`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲置入的数组` (`COM对象类 []`)
	* `首成员索引位置` (`整数`, 默认值: `0`): 提供所欲置入的"所欲置入的数组"数组中首成员索引位置,从0开始.
	* `所欲置入的成员数` (`整数`, 默认值: `-1`): 提供所欲置入的"所欲置入的数组"数组中成员数目,如果小于0则表示使用"所欲置入的数组"参数数组在"首成员索引位置"参数位置后的所有成员数目.
* **特性:**
	* `静态`
* **描述:** 将所提供的数组数据填入本对象中,其中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.COM变体型.置COM自动化对象数组

* **类型:** `方法`
* **名称:** `置COM自动化对象数组`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `所欲置入的数组` (`COM对象类 []`): 提供所欲置入的COM对象,注意其必须能够转换为COM自动化对象(IDispatch),不能转换的将被抛弃.
	* `首成员索引位置` (`整数`, 默认值: `0`): 提供所欲置入的"所欲置入的数组"数组中首成员索引位置,从0开始.
	* `所欲置入的成员数` (`整数`, 默认值: `-1`): 提供所欲置入的"所欲置入的数组"数组中成员数目,如果小于0则表示使用"所欲置入的数组"参数数组在"首成员索引位置"参数位置后的所有成员数目.
* **特性:**
	* `静态`
* **描述:** 将所提供的数组数据填入本对象中,其中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.COM变体型.创建数组

* **类型:** `方法`
* **名称:** `创建数组`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `成员类型` (`COM数组成员类型`): 提供数组成员的数据类型
	* `成员数目` (`整数`): 提供数组的初始成员数目
* **特性:**
	* `静态`
* **描述:** 创建一个具有指定类型和指定成员数目的数组并将其填入本对象中,其中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.COM变体型.加锁数组数据

* **类型:** `方法`
* **名称:** `加锁数组数据`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所操作本对象` (`COM变体型`)
* **特性:**
	* `静态`
* **描述:** 如果本对象中的当前数据为数组,则将其加锁并返回其数据地址指针(可以进行读/写). 注意: 如果加锁成功,则在不再使用所获得的数据指针后,必须对应调用"解锁数组数据"方法一次,且期间不能清空本对象或修改本对象的数据类型,否则程序将出错.
* **返回值描述:** 成功返回非0数据指针值,失败返回0.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.解锁数组数据

* **类型:** `方法`
* **名称:** `解锁数组数据`
* **参数:**
	* `所操作本对象` (`COM变体型`)
* **特性:**
	* `静态`
* **描述:** 如果先前调用本对象的"加锁数组数据"方法成功,则在不再使用所获得的数据指针后,必须对应调用本方法一次,且期间不能清空本对象或修改本对象的数据类型,否则程序将出错.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.COM变体型.取数据指针

* **类型:** `方法`
* **名称:** `取数据指针`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所操作本对象` (`COM变体型`)
* **特性:**
	* `静态`
* **描述:** 返回本对象中所记录的VARIANT数据的指针值,必定不为0.

##### 火山.基本.COM变体型.取结构成员值

* **类型:** `方法`
* **名称:** `取结构成员值`
* **返回值数据类型:** `COM变体型`
* **参数:**
	* `所操作本对象` (`COM变体型`)
	* `成员名称` (`文本型`): 提供所欲获取其数据的结构成员名称
* **特性:**
	* `静态`
* **描述:** 如果本变体型对象中保存的是结构型数据,则可以取出其中所指定名称的成员值.
* **返回值描述:** 成功返回对应的成员数据,失败所返回变体型对象为空("是否为空"方法返回真).

---

#### 火山.基本.COM变体型数组类

* **类型:** `类`
* **名称:** `COM变体型数组类`
* **模板基础类:** `对象数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `COM变体型`
* **文档分类:** `COM操作.辅助类`
* **描述:** COM变体型对象的数组管理类
* **相关例程:** [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main)

---

#### 火山.基本.COM初始化类

* **类型:** `类`
* **名称:** `COM初始化类`
* **文档分类:** `COM操作`
* **描述:** COM的初始化是以线程为单位的,也就是说,每个线程在使用COM之前,都必须初始化一次.在主线程中系统类库会自动初始化COM,在非主线程中如果欲使用COM,用户必须自行初始化. 定义一个本类的对象实例,该实例在类初始化时会自动初始化COM,在类清理时会自动释放COM.或者完全手动调用本类中的对应静态方法也可以初始化和清理COM(使用前初始化,使用完毕后清理). 注意: 在主线程中不需要再初始化COM,类库已经自动初始化.

##### 火山.基本.COM初始化类.初始化COM

* **类型:** `方法`
* **名称:** `初始化COM`
* **返回值数据类型:** `逻辑型`
* **特性:**
	* `静态`
* **描述:** 手动初始化COM,返回是否成功.
* **相关例程:** [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main)

##### 火山.基本.COM初始化类.清理COM

* **类型:** `方法`
* **名称:** `清理COM`
* **特性:**
	* `静态`
* **返回值描述:** 手动清理COM,在此之前COM必须已经成功初始化过.
* **相关例程:** [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main)

---

#### 火山.基本.COM方法调用结果

* **类型:** `类`
* **名称:** `COM方法调用结果`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `COM操作.辅助类`
* **描述:** 提供对COM对象方法进行调用后的结果状态码
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.COM方法调用结果.成功

* **类型:** `成员常量`
* **名称:** `成功`
* **数据类型:** `COM方法调用结果`
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.COM方法调用结果.对象为空

* **类型:** `成员常量`
* **名称:** `对象为空`
* **数据类型:** `COM方法调用结果`

##### 火山.基本.COM方法调用结果.无法调用

* **类型:** `成员常量`
* **名称:** `无法调用`
* **数据类型:** `COM方法调用结果`
* **描述:** 指定对象没有调用接口

##### 火山.基本.COM方法调用结果.无类型信息

* **类型:** `成员常量`
* **名称:** `无类型信息`
* **数据类型:** `COM方法调用结果`
* **描述:** 指定对象没有找到对应类型信息

##### 火山.基本.COM方法调用结果.参数数目错误

* **类型:** `成员常量`
* **名称:** `参数数目错误`
* **数据类型:** `COM方法调用结果`

##### 火山.基本.COM方法调用结果.参数类型无效

* **类型:** `成员常量`
* **名称:** `参数类型无效`
* **数据类型:** `COM方法调用结果`
* **描述:** 无效的参数类型

##### 火山.基本.COM方法调用结果.异常

* **类型:** `成员常量`
* **名称:** `异常`
* **数据类型:** `COM方法调用结果`
* **描述:** 调用过程中发现异常
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.COM方法调用结果.未找到成员

* **类型:** `成员常量`
* **名称:** `未找到成员`
* **数据类型:** `COM方法调用结果`
* **描述:** 未找到所欲调用的成员

##### 火山.基本.COM方法调用结果.不支持命名参数

* **类型:** `成员常量`
* **名称:** `不支持命名参数`
* **数据类型:** `COM方法调用结果`

##### 火山.基本.COM方法调用结果.溢出

* **类型:** `成员常量`
* **名称:** `溢出`
* **数据类型:** `COM方法调用结果`

##### 火山.基本.COM方法调用结果.参数未找到

* **类型:** `成员常量`
* **名称:** `参数未找到`
* **数据类型:** `COM方法调用结果`
* **描述:** 未找到所指定的参数

##### 火山.基本.COM方法调用结果.类型不匹配

* **类型:** `成员常量`
* **名称:** `类型不匹配`
* **数据类型:** `COM方法调用结果`
* **描述:** 参数的数据类型不匹配

##### 火山.基本.COM方法调用结果.必需参数被省略

* **类型:** `成员常量`
* **名称:** `必需参数被省略`
* **数据类型:** `COM方法调用结果`
* **描述:** 必需的参数数据被省略

##### 火山.基本.COM方法调用结果.获取结果失败

* **类型:** `成员常量`
* **名称:** `获取结果失败`
* **数据类型:** `COM方法调用结果`
* **描述:** 获取所返回结果失败

##### 火山.基本.COM方法调用结果.其它

* **类型:** `成员常量`
* **名称:** `其它`
* **数据类型:** `COM方法调用结果`
* **描述:** 其它原因导致调用失败

---

#### 火山.基本.COM对象类

* **类型:** `类`
* **名称:** `COM对象类`
* **描述:** 用作封装COM对象操作
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main)

##### 火山.基本.COM对象类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
* **特性:**
	* `静态`
* **描述:** 返回本对象的内容是否为空
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.COM对象类.取COM对象指针

* **类型:** `方法`
* **名称:** `取COM对象指针`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所操作本对象` (`COM对象类`)
* **特性:**
	* `静态`
* **描述:** 返回本对象中所记录的IUnknown接口指针值,如尚未设置(为空)则返回0.
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main)

##### 火山.基本.COM对象类.置COM对象指针

* **类型:** `方法`
* **名称:** `置COM对象指针`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `所欲设置接口指针` (`变整数`): 本参数值必须为有效的 IUnknown* 指针值或者0.
* **特性:**
	* `静态`
* **描述:** 设置本对象中所记录的IUnknown接口指针值

##### 火山.基本.COM对象类.置COM对象

* **类型:** `方法`
* **名称:** `置COM对象`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `所欲设置对象` (`COM对象类`): 该对象中的IUnknown接口指针将被设置到本对象中
* **特性:**
	* `静态`
* **描述:** 设置本对象中所记录的IUnknown接口指针值

##### 火山.基本.COM对象类.清除

* **类型:** `方法`
* **名称:** `清除`
* **参数:**
	* `所操作本对象` (`COM对象类`)
* **特性:**
	* `静态`
* **描述:** 将本对象的内容释放并清空. 如果不调用本方法,则对象在退出其作用区域时会自动被释放.
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.COM对象类.是否相等

* **类型:** `方法`
* **名称:** `是否相等`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `欲检查的对象` (`COM对象类`)
* **特性:**
	* `静态`
* **描述:** 返回本对象的内容是否与指定对象的内容相等

##### 火山.基本.COM对象类.取火山对象

* **类型:** `方法`
* **名称:** `取火山对象`
* **返回值数据类型:** `调用本方法时为"所欲获取对象类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `所欲获取对象类型` (`对象类(需求:数据类型)`): 提供所欲获取的火山对象的类型
* **特性:**
	* `静态`
* **描述:** 获取本对象中存放的指定类型火山对象参考,如果所存储的数据不为该类型的火山对象,将返回一个该类型的空火山对象(在该对象上调用"是否为空对象"方法返回真).
* **返回值描述:** 成功返回所存储的火山对象参考,失败返回一个空对象.

##### 火山.基本.COM对象类.置火山对象

* **类型:** `方法`
* **名称:** `置火山对象`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `所欲写入的值` (`对象类`): 提供所欲写入的火山对象数据内容
* **特性:**
	* `静态`
* **描述:** 将所指定的火山对象复制一份后置入本对象中,所置入对象可以通过"取火山对象"方法返回,本对象中的原有内容将被覆盖.

##### 火山.基本.COM对象类.创建

* **类型:** `方法`
* **名称:** `创建`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `对象类型` (`文本型`): 指定对象的类型文本,可以为其可识别名称: 譬如"Excel.Application"/"Word.Application",也可以是其CLSID,如"{0003088F-0000-0000-C000-000000000058}".
	* `类型库文件名` (`文本型`, 默认值: `""`): 如果需要通过类型库才能访问指定对象,可在本参数中提供其类型库或类型库数据所在文件名. 注意如果没有提供文件名,且在当前目录下无法找到该文件,系统将自动进行搜索.
* **特性:**
	* `静态`
* **描述:** 创建指定类型的 COM 对象并填入本对象中,本对象中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,否则返回假.

##### 火山.基本.COM对象类.获取

* **类型:** `方法`
* **名称:** `获取`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `对象类型` (`文本型`): 指定对象的类型文本,可以为其可识别名称: 譬如"Excel.Application"/"Word.Application",也可以是其CLSID,如"{0003088F-0000-0000-C000-000000000058}".
* **特性:**
	* `静态`
* **描述:** 获取当前操作系统中已经存在的指定类型 COM 对象并填入本对象中,本对象中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,否则返回假.

##### 火山.基本.COM对象类.取接口

* **类型:** `方法`
* **名称:** `取接口`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `接口标志符` (`文本型`): 指定欲获取接口的具体名称或其全球唯一标志符(GUID),如"IDispatch",{B8AB1733C-F55B-4347-A61C-B257280F9967}等. 如果本参数为空文本,则默认取出本对象的IUnknown基本接口.
	* `所欲填写到的对象` (`COM对象类`): 提供将所获取到的接口对象所填写到的对象,可以是本对象自身.
* **特性:**
	* `静态`
* **描述:** 获取本对象中的指定接口,然后将其填入所指定对象中,该对象中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.COM对象类.取接口对象

* **类型:** `方法`
* **名称:** `取接口对象`
* **返回值数据类型:** `调用本方法时为"所欲获取数据类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `接口标志符` (`文本型`): 指定欲获取接口的具体名称或其全球唯一标志符(GUID),如"IDispatch",{B8AB1733C-F55B-4347-A61C-B257280F9967}等. 如果本参数为空文本,则默认取出本对象的IUnknown基本接口.
	* `所欲获取数据类型` (`COM对象类(需求:数据类型)`): 提供所欲获得的接口对象数据类型
* **特性:**
	* `静态`
* **描述:** 获取并返回本对象中的指定接口对象. 执行本方法如果失败,返回内容为空的该类对象(COM对象类的"是否为空"方法返回真).

##### 火山.基本.COM对象类.创建图片对象

* **类型:** `方法`
* **名称:** `创建图片对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `所基于的位图对象` (`位图对象类`)
* **特性:**
	* `静态`
* **描述:** 为指定图片创建对应的 COM 图片对象并填入本对象中,本对象中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.COM对象类.取回图片

* **类型:** `方法`
* **名称:** `取回图片`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `结果存储字节集` (`字节集类`): 成功将所获得的图片数据置入此参数字节集中
* **特性:**
	* `静态`
* **描述:** 如果本对象为 COM 图片对象,则取回其具体图片数据.
* **返回值描述:** 成功返回真且将所获得的图片数据存放入"结果存储字节集"参数字节集中,失败返回假.

##### 火山.基本.COM对象类.创建字体对象

* **类型:** `方法`
* **名称:** `创建字体对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `所基于的字体对象` (`字体对象类`)
* **特性:**
	* `静态`
* **描述:** 为指定字体数据创建对应的 COM 字体对象并填入本对象中,本对象中的原有内容将被覆盖.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.COM对象类.取回字体

* **类型:** `方法`
* **名称:** `取回字体`
* **返回值数据类型:** `字体对象类`
* **参数:**
	* `所操作本对象` (`COM对象类`)
* **特性:**
	* `静态`
* **描述:** 如果本对象为 COM 字体对象,则取回其中的具体字体数据.
* **返回值描述:** 成功所返回的字体对象不为空(其"为空"方法返回假),失败为空(其"为空"方法返回真).

##### 火山.基本.COM对象类.取错误

* **类型:** `方法`
* **名称:** `取错误`
* **返回值数据类型:** `COM方法调用结果`
* **参数:**
	* `所操作本对象` (`COM对象类`)
* **特性:**
	* `静态`
* **描述:** 当读写对象属性/执行对象方法时,紧跟该语句后执行本方法可以检查其是否执行成功.
* **返回值描述:** 返回"COM方法调用结果.成功"表示上一方法执行成功,否则提供具体的错误类型值.
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.COM对象类.是否成功

* **类型:** `方法`
* **名称:** `是否成功`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
* **特性:**
	* `静态`
* **描述:** 当读写对象属性/执行对象方法时,紧跟该语句后执行本方法可以检查其是否执行成功.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.COM对象类.读属性

* **类型:** `方法`
* **名称:** `读属性`
* **返回值数据类型:** `调用本方法时为"所欲获取数据类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `属性名称` (`文本型`): 提供所欲读取属性的名称
	* `所欲获取数据类型` (`通用型(需求:数据类型)`): 提供所欲获得的返回值数据类型. 注意: 只能为基本数据类型/常量类/COM对象类/COM变体型,否则本地编译器将编译出错.如果欲读取数据类型为"COM对象类"的继承类,请使用"读对象型属性".
	* `参数数据` (`通用型`, `可扩展`): 提供所有的具体调用参数.请注意以下事项: 1. 参数的数据类型只能为以下几种,否则本方法执行将失败: A. 基本数据类型; B. 基本数据类型对应的封装类,即:字节类/短整数类/字符类/整数类/变整数类/长整数类/单精度小数类/小数类/逻辑型类; C. COM对象类; D. COM变体型. 2. 如果所调用COM方法的某个参数将以参考的方式返回数据,对于基本数据类型数据,请提供对应类型的封装类对象,类库中将自动进行转换,对于非基本数据类型数据,直接提供对应的类对象即可; 3. 如果所调用COM方法的某个参数具有默认值且欲使用该默认值,提供"取空基本对象 ()"即可.
* **特性:**
	* `静态`
* **描述:** 读取并返回本对象中所指定名称属性的值. 执行本方法如果失败,"所欲获取数据类型"为数值型时返回0,为逻辑型时返回假,为文本型时返回空文本,为COM对象类或COM变体型时返回内容为空的该类对象(COM对象类/COM变体型的"是否为空"方法返回真). 紧跟本方法后调用"是否成功"方法将返回本方法是否执行成功,调用"取错误"方法将返回具体的错误码值(成功将返回"COM方法调用结果.成功").

##### 火山.基本.COM对象类.读对象型属性

* **类型:** `方法`
* **名称:** `读对象型属性`
* **返回值数据类型:** `调用本方法时为"所欲获取数据类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `属性名称` (`文本型`): 提供所欲读取属性的名称
	* `所欲获取数据类型` (`COM对象类(需求:数据类型)`): 提供所欲获得的返回值数据类型
	* `参数数据` (`通用型`, `可扩展`): 提供所有的具体调用参数.请注意以下事项: 1. 参数的数据类型只能为以下几种,否则本方法执行将失败: A. 基本数据类型; B. 基本数据类型对应的封装类,即:字节类/短整数类/字符类/整数类/变整数类/长整数类/单精度小数类/小数类/逻辑型类; C. COM对象类; D. COM变体型. 2. 如果所调用COM方法的某个参数将以参考的方式返回数据,对于基本数据类型数据,请提供对应类型的封装类对象,类库中将自动进行转换,对于非基本数据类型数据,直接提供对应的类对象即可; 3. 如果所调用COM方法的某个参数具有默认值且欲使用该默认值,提供"取空基本对象 ()"即可.
* **特性:**
	* `静态`
* **描述:** 读取并返回本对象中所指定名称COM对象类属性的值. 执行本方法如果失败,返回内容为空的该类对象(COM对象类的"是否为空"方法返回真). 紧跟本方法后调用"是否成功"方法将返回本方法是否执行成功,调用"取错误"方法将返回具体的错误码值(成功将返回"COM方法调用结果.成功").

##### 火山.基本.COM对象类.读无参数属性

* **类型:** `方法`
* **名称:** `读无参数属性`
* **返回值数据类型:** `调用本方法时为"所欲获取数据类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `属性名称` (`文本型`): 提供所欲读取属性的名称
	* `所欲获取数据类型` (`通用型(需求:数据类型)`): 提供所欲获得的返回值数据类型. 注意: 只能为基本数据类型/常量类/COM对象类/COM变体型,否则本地编译器将编译出错.如果欲读取数据类型为"COM对象类"的继承类,请使用"读无参数对象型属性".
* **特性:**
	* `静态`
* **描述:** 读取并返回本对象中所指定名称属性的值. 本方法用作读取无参数的COM属性值. 执行本方法如果失败,"所欲获取数据类型"为数值型时返回0,为逻辑型时返回假,为文本型时返回空文本,为COM对象类或COM变体型时返回内容为空的该类对象(COM对象类/COM变体型的"是否为空"方法返回真). 紧跟本方法后调用"是否成功"方法将返回本方法是否执行成功,调用"取错误"方法将返回具体的错误码值(成功将返回"COM方法调用结果.成功").

##### 火山.基本.COM对象类.读无参数对象型属性

* **类型:** `方法`
* **名称:** `读无参数对象型属性`
* **返回值数据类型:** `调用本方法时为"所欲获取数据类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `属性名称` (`文本型`): 提供所欲读取属性的名称
	* `所欲获取数据类型` (`COM对象类(需求:数据类型)`): 提供所欲获得的返回值数据类型
* **特性:**
	* `静态`
* **描述:** 读取并返回本对象中所指定名称COM对象类属性的值. 本方法用作读取无参数的COM属性值. 执行本方法如果失败,返回内容为空的该类对象(COM对象类的"是否为空"方法返回真). 紧跟本方法后调用"是否成功"方法将返回本方法是否执行成功,调用"取错误"方法将返回具体的错误码值(成功将返回"COM方法调用结果.成功").

##### 火山.基本.COM对象类.写属性

* **类型:** `方法`
* **名称:** `写属性`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `属性名称` (`文本型`): 提供所欲设置属性的名称
	* `参数数据` (`通用型`, `可扩展`): 提供所有的具体调用参数.请注意以下事项: 1. 参数的数据类型只能为以下几种,否则本方法执行将失败: A. 基本数据类型; B. 基本数据类型对应的封装类,即:字节类/短整数类/字符类/整数类/变整数类/长整数类/单精度小数类/小数类/逻辑型类; C. COM对象类; D. COM变体型. 2. 如果所调用COM方法的某个参数将以参考的方式返回数据,对于基本数据类型数据,请提供对应类型的封装类对象,类库中将自动进行转换,对于非基本数据类型数据,直接提供对应的类对象即可; 3. 如果所调用COM方法的某个参数具有默认值且欲使用该默认值,提供"取空基本对象 ()"即可.
* **特性:**
	* `静态`
* **描述:** 设置本对象指定名称属性的值.
* **返回值描述:** 返回执行本方法是否成功.如果失败,紧跟本方法后调用"取错误"方法将返回具体的错误码值.

##### 火山.基本.COM对象类.写无参数属性

* **类型:** `方法`
* **名称:** `写无参数属性`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `属性名称` (`文本型`): 提供所欲设置属性的名称
* **特性:**
	* `静态`
* **描述:** 设置本对象指定名称属性的值. 本方法用作写无参数的COM属性值.
* **返回值描述:** 返回执行本方法是否成功.如果失败,紧跟本方法后调用"取错误"方法将返回具体的错误码值.

##### 火山.基本.COM对象类.方法

* **类型:** `方法`
* **名称:** `方法`
* **返回值数据类型:** `调用本方法时为"所欲获取数据类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `方法名称` (`文本型`): 提供所欲执行方法的名称
	* `所欲获取数据类型` (`通用型(需求:数据类型)`): 提供所欲获得的返回值数据类型. 注意: 只能为基本数据类型/常量类/COM对象类/COM变体型,否则本地编译器将编译出错.如果欲读取数据类型为"COM对象类"的继承类,请使用"对象型方法".
	* `参数数据` (`通用型`, `可扩展`): 提供所有的具体调用参数.请注意以下事项: 1. 参数的数据类型只能为以下几种,否则本方法执行将失败: A. 基本数据类型; B. 基本数据类型对应的封装类,即:字节类/短整数类/字符类/整数类/变整数类/长整数类/单精度小数类/小数类/逻辑型类; C. COM对象类; D. COM变体型. 2. 如果所调用COM方法的某个参数将以参考的方式返回数据,对于基本数据类型数据,请提供对应类型的封装类对象,类库中将自动进行转换,对于非基本数据类型数据,直接提供对应的类对象即可; 3. 如果所调用COM方法的某个参数具有默认值且欲使用该默认值,提供"取空基本对象 ()"即可.
* **特性:**
	* `静态`
* **描述:** 执行本对象中所指定名称的方法,返回该方法执行后的结果值. 执行本方法如果失败,"所欲获取数据类型"为数值型时返回0,为逻辑型时返回假,为文本型时返回空文本,为COM对象类或COM变体型时返回内容为空的该类对象(COM对象类/COM变体型的"是否为空"方法返回真). 紧跟本方法后调用"是否成功"方法将返回本方法是否执行成功,调用"取错误"方法将返回具体的错误码值(成功将返回"COM方法调用结果.成功").

##### 火山.基本.COM对象类.对象型方法

* **类型:** `方法`
* **名称:** `对象型方法`
* **返回值数据类型:** `调用本方法时为"所欲获取数据类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `方法名称` (`文本型`): 提供所欲执行方法的名称
	* `所欲获取数据类型` (`COM对象类(需求:数据类型)`): 提供所欲获得的返回值数据类型
	* `参数数据` (`通用型`, `可扩展`): 提供所有的具体调用参数.请注意以下事项: 1. 参数的数据类型只能为以下几种,否则本方法执行将失败: A. 基本数据类型; B. 基本数据类型对应的封装类,即:字节类/短整数类/字符类/整数类/变整数类/长整数类/单精度小数类/小数类/逻辑型类; C. COM对象类; D. COM变体型. 2. 如果所调用COM方法的某个参数将以参考的方式返回数据,对于基本数据类型数据,请提供对应类型的封装类对象,类库中将自动进行转换,对于非基本数据类型数据,直接提供对应的类对象即可; 3. 如果所调用COM方法的某个参数具有默认值且欲使用该默认值,提供"取空基本对象 ()"即可.
* **特性:**
	* `静态`
* **描述:** 执行本对象中所指定名称的方法,返回该方法执行后的结果值. 执行本方法如果失败,返回内容为空的该类对象(COM对象类的"是否为空"方法返回真). 紧跟本方法后调用"是否成功"方法将返回本方法是否执行成功,调用"取错误"方法将返回具体的错误码值(成功将返回"COM方法调用结果.成功").

##### 火山.基本.COM对象类.无返回值方法

* **类型:** `方法`
* **名称:** `无返回值方法`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `方法名称` (`文本型`): 提供所欲执行方法的名称
	* `参数数据` (`通用型`, `可扩展`): 提供所有的具体调用参数.请注意以下事项: 1. 参数的数据类型只能为以下几种,否则本方法执行将失败: A. 基本数据类型; B. 基本数据类型对应的封装类,即:字节类/短整数类/字符类/整数类/变整数类/长整数类/单精度小数类/小数类/逻辑型类; C. COM对象类; D. COM变体型. 2. 如果所调用COM方法的某个参数将以参考的方式返回数据,对于基本数据类型数据,请提供对应类型的封装类对象,类库中将自动进行转换,对于非基本数据类型数据,直接提供对应的类对象即可; 3. 如果所调用COM方法的某个参数具有默认值且欲使用该默认值,提供"取空基本对象 ()"即可.
* **特性:**
	* `静态`
* **描述:** 执行本对象中所指定名称的方法. 本方法用作执行无返回值COM方法或者执行COM方法但不需要返回数据.
* **返回值描述:** 返回执行本方法是否成功.如果失败,紧跟本方法后调用"取错误"方法将返回具体的错误码值.

##### 火山.基本.COM对象类.无参数方法

* **类型:** `方法`
* **名称:** `无参数方法`
* **返回值数据类型:** `调用本方法时为"所欲获取数据类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `方法名称` (`文本型`): 提供所欲执行方法的名称
	* `所欲获取数据类型` (`通用型(需求:数据类型)`): 提供所欲获得的返回值数据类型. 注意: 只能为基本数据类型/常量类/COM对象类/COM变体型,否则本地编译器将编译出错.如果欲读取数据类型为"COM对象类"的继承类,请使用"无参数对象型方法".
* **特性:**
	* `静态`
* **描述:** 执行本对象中所指定名称的方法,返回该方法执行后的结果值. 本方法用作执行无参数的COM方法. 执行本方法如果失败,"所欲获取数据类型"为数值型时返回0,为逻辑型时返回假,为文本型时返回空文本,为COM对象类或COM变体型时返回内容为空的该类对象(COM对象类/COM变体型的"是否为空"方法返回真). 紧跟本方法后调用"是否成功"方法将返回本方法是否执行成功,调用"取错误"方法将返回具体的错误码值(成功将返回"COM方法调用结果.成功").

##### 火山.基本.COM对象类.无参数对象型方法

* **类型:** `方法`
* **名称:** `无参数对象型方法`
* **返回值数据类型:** `调用本方法时为"所欲获取数据类型"参数所提供数据的实际类型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `方法名称` (`文本型`): 提供所欲执行方法的名称
	* `所欲获取数据类型` (`COM对象类(需求:数据类型)`): 提供所欲获得的返回值数据类型
* **特性:**
	* `静态`
* **描述:** 执行本对象中所指定名称的方法,返回该方法执行后的结果值. 本方法用作执行无参数的COM方法. 执行本方法如果失败,返回内容为空的该类对象(COM对象类的"是否为空"方法返回真). 紧跟本方法后调用"是否成功"方法将返回本方法是否执行成功,调用"取错误"方法将返回具体的错误码值(成功将返回"COM方法调用结果.成功").

##### 火山.基本.COM对象类.无参数及返回值方法

* **类型:** `方法`
* **名称:** `无参数及返回值方法`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `方法名称` (`文本型`): 提供所欲执行方法的名称
* **特性:**
	* `静态`
* **描述:** 执行本对象中所指定名称的方法. 本方法用作执行无参数且无返回值COM方法或者执行无参数COM方法但不需要返回数据.
* **返回值描述:** 返回执行本方法是否成功.如果失败,紧跟本方法后调用"取错误"方法将返回具体的错误码值.

##### 火山.基本.COM对象类.查看接口

* **类型:** `方法`
* **名称:** `查看接口`
* **参数:**
	* `所操作本对象` (`COM对象类`)
	* `父窗口句柄` (`变整数`, 默认值: `0`): 提供对话框的父窗口句柄,为0表示使用默认父窗口.
* **特性:**
	* `静态`
* **描述:** 启动一个对话框来显示本对象的COM接口信息. 注意: 本方法只能在主界面线程中执行.

---

#### 火山.基本.COM对象事件类

* **类型:** `类`
* **名称:** `COM对象事件类`
* **描述:** 用作提供对COM对象事件的挂接操作

##### 火山.基本.COM对象事件类.接收到事件

* **类型:** `事件定义方法`
* **名称:** `接收到事件`
* **返回值数据类型:** `整数`
* **参数:**
	* `来源COM对象` (`COM对象类`): 提供挂接事件时所提供的来源COM对象
	* `事件方法ID` (`整数`): 提供所触发的具体事件的对应COM方法ID值
	* `事件参数` (`COM变体型数组类`): 提供事件的所有参数数据
	* `事件返回值` (`COM变体型`): 仅用作输出. 事件处理完毕后如果需要返回数据,请将所欲返回数据值填入到此参数变量中.
* **描述:** 当接收到所挂接COM事件时,本事件被触发.

##### 火山.基本.COM对象事件类.挂接

* **类型:** `方法`
* **名称:** `挂接`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `来源COM对象` (`COM对象类`): 提供欲挂接其中事件的具体COM对象. 该对象在"接收到事件"事件方法中将反馈过去.
	* `事件接口名称` (`文本型`, 默认值: `""`): 提供所欲挂接的事件接口IID文本,如"{bdfff072-497b-407b-a8f2-450d6e7b6827}",如果为空文本,则自动去查找使用"来源COM对象"所实现的默认事件来源接口.
* **描述:** 挂接指定COM对象的指定事件接口,返回是否成功.

##### 火山.基本.COM对象事件类.取消挂接

* **类型:** `方法`
* **名称:** `取消挂接`
* **描述:** 取消先前所挂接的COM事件

---

#### 火山.基本.COM字体类

* **类型:** `类`
* **名称:** `COM字体类`
* **基础类:** `COM对象类`
* **描述:** 用作记录一个COM字体对象(IFontDisp)

##### 火山.基本.COM字体类.从描述文本创建字体

* **类型:** `方法`
* **名称:** `从描述文本创建字体`
* **返回值数据类型:** `COM字体类`
* **参数:**
	* `字体描述文本` (`文本型`): 本参数的格式为: "字体名, 字体尺寸, 是否为粗体, 是否为斜体, 是否有下划线, 是否有删除线, 旋转角度",其中"是否"字段,用1代表真,0代表假,可以被省略.字体尺寸单位为磅,旋转角度单位为1/10度. 例子: "宋体, 10", "宋体, 10, 0, 1, 1, 0, 100".
* **特性:**
	* `静态`
* **描述:** 从一个指定格式的字体描述文本创建字体对象
* **返回值描述:** 成功所返回的COM对象不为空("是否为空"方法返回假),失败为空("是否为空"方法返回真).

##### 火山.基本.COM字体类.创建默认GUI字体

* **类型:** `方法`
* **名称:** `创建默认GUI字体`
* **返回值数据类型:** `COM字体类`
* **特性:**
	* `静态`
* **描述:** 创建操作系统所使用的默认GUI字体对象
* **返回值描述:** 成功所返回的COM对象不为空("是否为空"方法返回假),失败为空("是否为空"方法返回真).

##### 火山.基本.COM字体类.创建字体

* **类型:** `方法`
* **名称:** `创建字体`
* **返回值数据类型:** `COM字体类`
* **参数:**
	* `字体名称` (`文本型`): 提供所欲创建字体的名称
	* `字体尺寸` (`整数`): 提供所欲创建字体的尺寸,单位为磅.
	* `是否粗体` (`逻辑型`, 默认值: `假`)
	* `是否斜体` (`逻辑型`, 默认值: `假`)
	* `是否有下划线` (`逻辑型`, 默认值: `假`)
	* `是否有删除线` (`逻辑型`, 默认值: `假`)
	* `旋转角度` (`整数`, 默认值: `0`): 提供字体的旋转角度,单位为十分之一度.
* **特性:**
	* `静态`
* **描述:** 从指定参数创建并返回一个字体对象
* **返回值描述:** 成功所返回的COM对象不为空("是否为空"方法返回假),失败为空("是否为空"方法返回真).

---

#### 火山.基本.COM图片类

* **类型:** `类`
* **名称:** `COM图片类`
* **基础类:** `COM对象类`
* **描述:** 用作记录一个COM图片对象(IPictureDisp)

##### 火山.基本.COM图片类.从资源创建图片

* **类型:** `方法`
* **名称:** `从资源创建图片`
* **返回值数据类型:** `COM图片类`
* **参数:**
	* `所欲载入的位图` (`位图资源`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的位图资源(所支持格式: gif/bmp/emf/wmf/jpg//png/tif/ico),返回所载入的图片对象.
* **返回值描述:** 成功所返回的COM对象不为空("是否为空"方法返回假),失败为空("是否为空"方法返回真).

##### 火山.基本.COM图片类.从文件创建图片

* **类型:** `方法`
* **名称:** `从文件创建图片`
* **返回值数据类型:** `COM图片类`
* **参数:**
	* `所欲载入的位图文件` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的位图文件(所支持格式: gif/bmp/emf/wmf/jpg//png/tif/ico),返回所载入的图片对象.
* **返回值描述:** 成功所返回的COM对象不为空("是否为空"方法返回假),失败为空("是否为空"方法返回真).

##### 火山.基本.COM图片类.从数据创建图片

* **类型:** `方法`
* **名称:** `从数据创建图片`
* **返回值数据类型:** `COM图片类`
* **参数:**
	* `所欲载入的位图数据` (`字节集类`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的位图数据(所支持格式: gif/bmp/emf/wmf/jpg//png/tif/ico),返回所载入的图片对象.
* **返回值描述:** 成功所返回的COM对象不为空("是否为空"方法返回假),失败为空("是否为空"方法返回真).

---

#### 火山.基本.服务事件类型

* **类型:** `类`
* **名称:** `服务事件类型`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `服务.辅助类`

##### 火山.基本.服务事件类型.成功

* **类型:** `成员常量`
* **名称:** `成功`
* **数据类型:** `服务事件类型`

##### 火山.基本.服务事件类型.错误

* **类型:** `成员常量`
* **名称:** `错误`
* **数据类型:** `服务事件类型`

##### 火山.基本.服务事件类型.警告

* **类型:** `成员常量`
* **名称:** `警告`
* **数据类型:** `服务事件类型`

##### 火山.基本.服务事件类型.信息

* **类型:** `成员常量`
* **名称:** `信息`
* **数据类型:** `服务事件类型`

##### 火山.基本.服务事件类型.审核成功

* **类型:** `成员常量`
* **名称:** `审核成功`
* **数据类型:** `服务事件类型`

##### 火山.基本.服务事件类型.审核失败

* **类型:** `成员常量`
* **名称:** `审核失败`
* **数据类型:** `服务事件类型`

---

#### 火山.基本.服务类

* **类型:** `类`
* **名称:** `服务类`

##### 火山.基本.服务类.运行

* **类型:** `方法`
* **名称:** `运行`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所提供的服务处理类` (`服务处理类(需求:数据类型)`): 提供具体的服务处理类,必须为"服务处理类"的继承类.
	* `为调试版时直接运行` (`逻辑型`, 默认值: `假`): 指定在编译本程序的调试版本时,是否编译为普通的非服务程序后直接运行所提供的服务处理器,用作支持在IDE中直接调试服务程序.在编译发布版本时不受本参数影响会编译出正常的Windows服务程序.
* **特性:**
	* `静态`
* **描述:** 开始运行所指定的服务处理程序,返回是否成功. 注意: 一旦服务开始运行,本方法将一直等待到该服务运行完毕后才会返回.

##### 火山.基本.服务类.记录事件

* **类型:** `方法`
* **名称:** `记录事件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `事件来源名称` (`文本型`): 提供事件来源的名称,不能为空文本.一般情况下,可以使用自己的服务名称.
	* `事件消息` (`文本型`): 提供所需要记录的具体事件消息文本,不能为空文本.
	* `事件类型` (`服务事件类型`, 默认值: `服务事件类型.信息`): 提供具体的事件类型
	* `事件分类` (`短整数`, 默认值: `0`): 提供事件分类,由用户自定义.
	* `事件ID` (`整数`, 默认值: `0`): 提供事件的ID值,由用户自定义.
* **特性:**
	* `静态`
* **描述:** 在操作系统事件信息表中记录所指定的事件信息,该信息可以通过操作系统的"事件查看器"工具软件来查看.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.服务类.服务是否被安装

* **类型:** `方法`
* **名称:** `服务是否被安装`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `服务名称` (`文本型`): 提供服务的具体名称,不能为空文本.
* **特性:**
	* `静态`
* **描述:** 返回所指定名称的服务是否已经被安装

##### 火山.基本.服务类.安装服务

* **类型:** `方法`
* **名称:** `安装服务`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `服务名称` (`文本型`): 提供所安装服务的名称,不能为空文本.
	* `服务显示名称` (`文本型`, 默认值: `""`): 提供所安装服务的显示用名称,如果为空文本则等于"服务名称".
	* `服务描述` (`文本型`, 默认值: `""`): 提供所安装服务的描述信息,为空文本表示无.
	* `服务文件名` (`文本型`, 默认值: `""`): 提供用作执行所安装服务功能的可执行文件名称,为空文本表示使用当前程序的文件名.
	* `是否自动启动` (`逻辑型`, 默认值: `真`): 指定所安装的服务是否在操作系统启动后被自动启动,为假则需要用户手动启动.
	* `启动参数` (`文本型`, 默认值: `""`): 提供服务启动参数
* **特性:**
	* `静态`
* **描述:** 安装所指定名称的服务
* **返回值描述:** 成功返回真,失败或该名称的服务已经被安装返回假.

##### 火山.基本.服务类.卸载服务

* **类型:** `方法`
* **名称:** `卸载服务`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `服务名称` (`文本型`): 提供所欲卸载服务的名称,不能为空文本.
* **特性:**
	* `静态`
* **描述:** 卸载所指定名称的服务
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.服务类.启动服务

* **类型:** `方法`
* **名称:** `启动服务`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `服务名称` (`文本型`): 提供所欲启动服务的名称,不能为空文本.
	* `启动参数数组` (`文本数组类`, 默认值: `空对象`): 提供启动参数数组(注意类库会自动在首部加入所启动服务名称),为空对象表示无.
* **特性:**
	* `静态`
* **描述:** 启动所指定名称的服务
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.服务类.停止服务

* **类型:** `方法`
* **名称:** `停止服务`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `服务名称` (`文本型`): 提供所欲停止服务的名称,不能为空文本.
* **特性:**
	* `静态`
* **描述:** 停止所指定名称服务的运行
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.服务类.暂停服务

* **类型:** `方法`
* **名称:** `暂停服务`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `服务名称` (`文本型`): 提供所指定服务的名称,不能为空文本.
* **特性:**
	* `静态`
* **描述:** 暂停所指定名称服务的运行(本功能需要服务本身的支持)
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.服务类.继续服务

* **类型:** `方法`
* **名称:** `继续服务`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `服务名称` (`文本型`): 提供所指定服务的名称,不能为空文本.
* **特性:**
	* `静态`
* **描述:** 继续运行已经被暂停的所指定名称服务(本功能需要服务本身的支持)
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.服务类.取服务状态

* **类型:** `方法`
* **名称:** `取服务状态`
* **返回值数据类型:** `整数`
* **参数:**
	* `服务名称` (`文本型`): 提供所指定服务的名称,不能为空文本.
* **特性:**
	* `静态`
* **描述:** 成功返回所指定名称服务的当前运行状态,失败或服务不存在返回0.
* **返回值描述:** 返回值为以下值之一: 获取失败: 0 已停止: 1 准备启动: 2 准备停止: 3 正在运行: 4 准备继续运行: 5 准备暂停: 6 已暂停: 7

##### 火山.基本.服务类.取服务类型

* **类型:** `方法`
* **名称:** `取服务类型`
* **返回值数据类型:** `整数`
* **参数:**
	* `服务名称` (`文本型`): 提供所指定服务的名称,不能为空文本.
* **特性:**
	* `静态`
* **描述:** 成功返回所指定名称服务的组合类型,失败或服务不存在返回0.
* **返回值描述:** 返回值为以下值之一或组合: 核心驱动: 1 文件系统驱动: 2 适配器: 4 识别器驱动: 8 自有进程: 16 公用进程: 32 交互式进程: 256

##### 火山.基本.服务类.取服务文件名

* **类型:** `方法`
* **名称:** `取服务文件名`
* **返回值数据类型:** `文本型`
* **参数:**
	* `服务名称` (`文本型`): 提供所指定服务的名称,不能为空文本.
* **特性:**
	* `静态`
* **描述:** 成功返回所指定名称服务的文件名,失败或服务不存在返回空文本.

##### 火山.基本.服务类.取服务启动类型

* **类型:** `方法`
* **名称:** `取服务启动类型`
* **返回值数据类型:** `整数`
* **参数:**
	* `服务名称` (`文本型`): 提供所指定服务的名称,不能为空文本.
* **特性:**
	* `静态`
* **描述:** 成功返回所指定名称服务的启动类型,失败或服务不存在返回0.
* **返回值描述:** 返回值为以下值之一: 获取失败: -1 操作系统载入时自动启动(仅针对驱动类型的服务): 0 操作系统初始化时自动启动(仅针对驱动类型的服务): 1 操作系统服务控制器自动启动: 2 手动启动: 3 禁止启动: 4

##### 火山.基本.服务类.取服务显示名称

* **类型:** `方法`
* **名称:** `取服务显示名称`
* **返回值数据类型:** `文本型`
* **参数:**
	* `服务名称` (`文本型`): 提供所指定服务的名称,不能为空文本.
* **特性:**
	* `静态`
* **描述:** 成功返回所指定名称服务的显示名称,失败或服务不存在返回空文本.

---

#### 火山.基本.服务处理类

* **类型:** `类`
* **名称:** `服务处理类`

##### 火山.基本.服务处理类.准备

* **类型:** `方法`
* **名称:** `准备`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `启动参数数组` (`文本数组类`): 提供所有的启动参数文本
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 当服务准备开始运行前本方法被调用,用户继承类可以覆盖本方法以完成自己的处理准备工作,注意耗时不要太长. 注意: 在本方法中不能显示任何界面窗口(包括信息框),否则将会导致服务卡死.
* **返回值描述:** 返回准备工作是否成功,如果返回假,服务不会被运行.

##### 火山.基本.服务处理类.处理

* **类型:** `方法`
* **名称:** `处理`
* **参数:**
	* `启动参数数组` (`文本数组类`): 提供所有的启动参数文本
	* `退出通知` (`同步事件类`): 注意: 在本处理方法的服务处理循环中,一旦发现本退出事件被置位(即"退出通知.等待 (真)"或"退出通知.限时等待 (xxx)"方法调用返回真),此时表示服务已经被操作系统服务管理器通知退出,就需要尽快退出本方法,否则可能会被操作系统强行中止.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 服务启动后本方法被调用,用户继承类应该覆盖本方法以进行自己的服务处理循环. 如果"准备"方法返回假,本方法不会被调用,否则必定在"准备"方法之后被调用. 注意: 在本方法中不能显示任何界面窗口(包括信息框),否则将会导致服务卡死.

##### 火山.基本.服务处理类.停止

* **类型:** `方法`
* **名称:** `停止`
* **特性:**
	* `静态`
* **描述:** 用作设置停止执行服务处理的状态,仅支持在本类或其继承类的"处理"方法内调用. 本方法执行后,"处理"方法的"退出通知"参数将被置位.

---

#### 火山.基本.网络通信

* **类型:** `类`
* **名称:** `网络通信`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)

##### 火山.基本.网络通信.取主机名

* **类型:** `全局方法`
* **名称:** `取主机名`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回本机的主机名,用作在网络通讯中标志本机地址.

##### 火山.基本.网络通信.通信测试

* **类型:** `全局方法`
* **名称:** `通信测试`
* **返回值数据类型:** `整数`
* **参数:**
	* `被测试主机地址` (`文本型`): 提供被测试主机地址,可以为主机名或IP地址等.
	* `最长等待时间` (`整数`, 默认值: `10000`): 指定最长等待被测试主机响应的时间,单位为毫秒,超过此时间即认为无法与被测试主机通讯.
* **特性:**
	* `静态`
* **描述:** 测试与指定主机是否能够正常通讯,返回被测试主机的通讯响应时间(单位毫秒).如果无法通讯或者测试失败,返回-1.

##### 火山.基本.网络通信.转换为主机名

* **类型:** `全局方法`
* **名称:** `转换为主机名`
* **返回值数据类型:** `文本型`
* **参数:**
	* `欲转换IP地址` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将指定的 IP 地址转换为其主机名,如果失败返回空文本.

##### 火山.基本.网络通信.转换为IP地址

* **类型:** `全局方法`
* **名称:** `转换为IP地址`
* **返回值数据类型:** `文本型`
* **参数:**
	* `欲转换主机名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将指定的主机名转换为其 IP 地址,如果失败返回空文本.

---

#### 火山.基本.数据报

* **类型:** `类`
* **名称:** `数据报`
* **相关例程:** [vol-数据报-udp-main](#vol-数据报-udp-main)

##### 火山.基本.数据报.端口

* **类型:** `属性写方法`
* **名称:** `端口`
* **参数:**
	* `所欲监听的端口号` (`整数`): 可以是大于 0 小于 32767 的任何自定整数值
* **描述:** 指定监听数据到达的端口号,如果为0表示不监听数据到达. 如果不进行设置,默认值为0. 注意,修改端口后,如果先前设置有相关传输选项(譬如多播相关),需要重新设置.
* **相关例程:** [vol-数据报-udp-main](#vol-数据报-udp-main)

##### 火山.基本.数据报.端口

* **类型:** `属性读方法`
* **名称:** `端口`
* **返回值数据类型:** `整数`
* **描述:** 返回当前所设置的监听数据到达的端口号
* **相关例程:** [vol-数据报-udp-main](#vol-数据报-udp-main)

##### 火山.基本.数据报.数据到达

* **类型:** `事件定义方法`
* **名称:** `数据到达`
* **返回值数据类型:** `整数`
* **参数:**
	* `所接收到的数据` (`字节集类`): 提供所接收到的数据,必定不为空字节集.
	* `对方地址` (`文本型`): 提供数据来源方的IP地址
	* `对方端口` (`整数`): 提供数据来源方的端口
* **描述:** 当有数据到达后,会产生本事件.
* **相关例程:** [vol-数据报-udp-main](#vol-数据报-udp-main)

##### 火山.基本.数据报.初始化

* **类型:** `方法`
* **名称:** `初始化`
* **返回值数据类型:** `逻辑型`
* **描述:** 初始化本对象,如果"端口"属性值不为0,则开始在其所指定的端口上监听数据到达. 返回是否成功. 注意,本对象初始化后,如果先前设置有相关传输选项(譬如多播相关),需要重新设置.
* **相关例程:** [vol-数据报-udp-main](#vol-数据报-udp-main)

##### 火山.基本.数据报.发送数据

* **类型:** `方法`
* **名称:** `发送数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `接收主机地址` (`文本型`, 默认值: `""`): 可以为主机名/IP地址等.如果提供空文本,则在指定端口广播欲发送数据.
	* `接收主机端口号` (`整数`)
	* `所欲发送的所有数据` (`通用型`, `可扩展`): 提供所欲发送的所有数据,可以为基本数据类型或字节集类数据.
* **描述:** 发送数据到指定主机上的指定端口,本对象必须已经初始化. 成功返回真,失败返回假.
* **相关例程:** [vol-数据报-udp-main](#vol-数据报-udp-main)

##### 火山.基本.数据报.置多播传出接口

* **类型:** `方法`
* **名称:** `置多播传出接口`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `主机地址` (`文本型`, 默认值: `""`): 可以为主机名/IP地址等,用作提供多播输出接口使用的本地地址,为空文本表示回送到本地默认接口.
* **描述:** 设置通过本对象发送多播数据时所使用的本地传出接口地址. 此选项不会更改用于接收多播数据的本地默认接口地址. 除非本机具有多个网络接口或多个IP地址,否则不用设置本选项直接使用本地默认接口地址即可.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.数据报.置多播超时TTL

* **类型:** `方法`
* **名称:** `置多播超时TTL`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲设置的值` (`整数`, 默认值: `255`): 提供所欲设置的超时TTL值,有效值范围在0到255之间,当转发的次数大于等于此值时,则不再转发.
* **描述:** 设置多播流量关联的超时 TTL 值.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.数据报.是否允许多播回送

* **类型:** `方法`
* **名称:** `是否允许多播回送`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `是否允许回送` (`逻辑型`, 默认值: `真`): 此参数值为真时本对象将接收当前计算机发送的匹配多播数据包,为假时即使本对象的关联套接字在环回接口上打开,也不会接收从本地计算机发送的多播数据包.
* **描述:** 本对象如果加入到一个或多个多播组,此方法指定是否接收通过所选多播接口发送到这些多播组的传出数据包的副本. 默认情况下,本选项值为真.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.数据报.加入多播组

* **类型:** `方法`
* **名称:** `加入多播组`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `多播组主机地址` (`文本型`): 可以为主机名/IP地址等,用作提供具体加入的多播组主机地址.
	* `多播接口地址` (`文本型`, 默认值: `""`): 提供所使用多播接口的本地地址,为空文本表示使用本地默认多播接口地址.
* **描述:** 加入指定多播接口中的指定多播组. 可以同时加入多个多播组. 多播组的程序操作步骤顺序大致如下: 1. 设置多播超时TTL值 (可选) 2. 设置是否允许多播回送 (可选) 3. 加入多播组 4. 发送/接收数据 (发送数据到多播组主机地址即可发送数据到此整个多播组) 5. 离开多播组注意: 在Windows系统下使用多播组注意设置系统防火墙.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.数据报.离开多播组

* **类型:** `方法`
* **名称:** `离开多播组`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `多播组主机地址` (`文本型`): 可以为主机名/IP地址等,用作提供具体离开的多播组主机地址.
	* `多播接口地址` (`文本型`, 默认值: `""`): 提供所使用多播接口的本地地址,为空文本表示使用本地默认多播接口地址.
* **描述:** 离开指定多播接口中的指定多播组
* **返回值描述:** 成功返回真,失败返回假.

---

#### 火山.基本.客户

* **类型:** `类`
* **名称:** `客户`
* **相关例程:** [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main)

##### 火山.基本.客户.数据到达

* **类型:** `事件定义方法`
* **名称:** `数据到达`
* **返回值数据类型:** `整数`
* **参数:**
	* `所接收到的数据` (`字节集类`): 提供所接收到的数据,必定不为空字节集.
* **描述:** 当服务器端将数据发送过来后,会产生本事件.
* **相关例程:** [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main)

##### 火山.基本.客户.连接断开

* **类型:** `事件定义方法`
* **名称:** `连接断开`
* **返回值数据类型:** `整数`
* **描述:** 当连接被服务器端断开后,会产生本事件.
* **相关例程:** [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main)

##### 火山.基本.客户.连接

* **类型:** `方法`
* **名称:** `连接`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `服务器地址` (`文本型`): 可以为主机名/IP地址等
	* `服务器端口号` (`整数`): 该端口必须已经被服务器组件监听
* **描述:** 连接到指定主机上的指定端口,该主机上的该端口必须已经被某一服务器监听. 成功返回真,失败返回假.
* **相关例程:** [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main)

##### 火山.基本.客户.断开连接

* **类型:** `方法`
* **名称:** `断开连接`
* **描述:** 断开与服务器的已有连接
* **相关例程:** [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main)

##### 火山.基本.客户.发送数据

* **类型:** `方法`
* **名称:** `发送数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲发送的所有数据` (`通用型`, `可扩展`): 提供所欲发送的所有数据,可以为基本数据类型或字节集类数据.
* **描述:** 在成功建立与服务器的连接后,发送数据到服务器端组件. 成功返回真,失败返回假.
* **相关例程:** [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main)

##### 火山.基本.客户.发送数据2

* **类型:** `方法`
* **名称:** `发送数据2`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `最长等待时间` (`整数`): 指定等待发送成功的最长时间,单位为秒.如果为-1,表示为无限等待.
	* `所欲发送的所有数据` (`通用型`, `可扩展`): 提供所欲发送的所有数据,可以为基本数据类型或字节集类数据.
* **描述:** 在成功建立与服务器的连接后,发送数据到服务器端组件. 成功返回真,失败返回假.

##### 火山.基本.客户.是否已连接

* **类型:** `方法`
* **名称:** `是否已连接`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回当前是否已经连接到了服务器
* **相关例程:** [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main)

---

#### 火山.基本.服务器

* **类型:** `类`
* **名称:** `服务器`
* **相关例程:** [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main)

##### 火山.基本.服务器.端口

* **类型:** `属性写方法`
* **名称:** `端口`
* **参数:**
	* `所欲监听的端口号` (`整数`): 可以是大于 0 小于 32767 的任何自定整数值
* **描述:** 指定监听客户连接的端口号,如果不进行设置,默认为19730.

##### 火山.基本.服务器.端口

* **类型:** `属性读方法`
* **名称:** `端口`
* **返回值数据类型:** `整数`
* **描述:** 返回当前所设置的监听数据到达的端口号

##### 火山.基本.服务器.数据到达

* **类型:** `事件定义方法`
* **名称:** `数据到达`
* **返回值数据类型:** `整数`
* **参数:**
	* `客户地址` (`文本型`): 提供所对应客户的地址文本: IP地址 + 端口
	* `所接收到的数据` (`字节集类`): 提供所接收到的数据,必定不为空字节集.
* **描述:** 当有客户端数据到达后,会产生本事件.
* **相关例程:** [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main)

##### 火山.基本.服务器.客户进入

* **类型:** `事件定义方法`
* **名称:** `客户进入`
* **返回值数据类型:** `整数`
* **参数:**
	* `所进入客户地址` (`文本型`): 提供所进入客户的地址文本: IP地址 + 端口
* **描述:** 当有新客户连接入本服务器后,会产生本事件.
* **相关例程:** [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main)

##### 火山.基本.服务器.客户离开

* **类型:** `事件定义方法`
* **名称:** `客户离开`
* **返回值数据类型:** `整数`
* **参数:**
	* `所离开客户地址` (`文本型`): 提供所离开客户的地址文本: IP地址 + 端口
* **描述:** 当有已连接客户断开与本服务器的连接后,会产生本事件.
* **相关例程:** [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main)

##### 火山.基本.服务器.开始监听

* **类型:** `方法`
* **名称:** `开始监听`
* **返回值数据类型:** `逻辑型`
* **描述:** 开始在"端口"属性所指定的端口上监听客户端连接及数据到达,返回是否成功.
* **相关例程:** [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main)

##### 火山.基本.服务器.停止监听

* **类型:** `方法`
* **名称:** `停止监听`
* **描述:** 断开所有已连接客户端(注意不会发送"客户离开"事件),停止监听端口.

##### 火山.基本.服务器.发送数据

* **类型:** `方法`
* **名称:** `发送数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `接收客户地址` (`文本型`): 为"数据到达"/"客户进入"事件或"取客户"方法中所提供的客户地址文本,为空文本表示向所有现有客户发送数据.
	* `最长等待时间` (`整数`, 默认值: `-1`): 指定等待发送到每个客户成功的最长时间,单位为秒.如果为-1,表示为无限等待.
	* `所欲发送的所有数据` (`通用型`, `可扩展`): 提供所欲发送的所有数据,可以为基本数据类型或字节集类数据.
* **描述:** 向指定已经连接进来的客户发送数据. 成功返回真,失败返回假.
* **相关例程:** [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main)

##### 火山.基本.服务器.断开客户

* **类型:** `方法`
* **名称:** `断开客户`
* **参数:**
	* `欲断开客户` (`文本型`): 为"数据到达"/"客户进入"事件或"取客户"方法中所提供的客户地址文本,为空文本表示断开所有现有客户.
* **描述:** 断开与指定客户之间的连接,发送"客户离开"事件.
* **相关例程:** [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main)

##### 火山.基本.服务器.取客户数目

* **类型:** `方法`
* **名称:** `取客户数目`
* **返回值数据类型:** `整数`
* **描述:** 返回当前所有已经连接客户的数目

##### 火山.基本.服务器.取客户

* **类型:** `方法`
* **名称:** `取客户`
* **返回值数据类型:** `文本型`
* **参数:**
	* `客户索引位置` (`整数`): 提供所欲获取已连接客户的索引位置,必须大于等于0且小于"取客户数目"方法的返回值,如索引值无效将返回空文本.
* **描述:** 返回所指定索引位置处已连接客户的地址文本

##### 火山.基本.服务器.取客户句柄

* **类型:** `方法`
* **名称:** `取客户句柄`
* **返回值数据类型:** `变整数`
* **参数:**
	* `客户索引位置` (`整数`): 提供所欲获取已连接客户的索引位置,必须大于等于0且小于"取客户数目"方法的返回值,如索引值无效将返回-1.
* **描述:** 返回所指定索引位置处已连接客户的 HSOCKET 句柄值

##### 火山.基本.服务器.查找客户句柄

* **类型:** `方法`
* **名称:** `查找客户句柄`
* **返回值数据类型:** `变整数`
* **参数:**
	* `客户地址文本` (`文本型`): 为"数据到达"/"客户进入"事件或"取客户"方法中所提供的客户地址文本
* **描述:** 返回所指定地址文本客户所对应的 HSOCKET 句柄值,不存在返回0.

---

#### 火山.基本.服务器2

* **类型:** `类`
* **名称:** `服务器2`
* **描述:** 提供直接基于SOCKET句柄进行高效网络操作的服务器类. 注意: 相比"服务器"类,本类未在内部维护已连接客户列表,用户需要自行管理.

##### 火山.基本.服务器2.端口

* **类型:** `属性写方法`
* **名称:** `端口`
* **参数:**
	* `所欲监听的端口号` (`整数`): 可以是大于 0 小于 32767 的任何自定整数值
* **描述:** 指定监听客户连接的端口号,如果不进行设置,默认为19730.

##### 火山.基本.服务器2.端口

* **类型:** `属性读方法`
* **名称:** `端口`
* **返回值数据类型:** `整数`
* **描述:** 返回当前所设置的监听数据到达的端口号

##### 火山.基本.服务器2.数据到达

* **类型:** `事件定义方法`
* **名称:** `数据到达`
* **返回值数据类型:** `整数`
* **参数:**
	* `客户句柄` (`变整数`): 提供所对应客户的SOCKET句柄值
	* `所接收到的数据` (`字节集类`): 提供所接收到的数据,必定不为空字节集.
* **描述:** 当有客户端数据到达后,会产生本事件.

##### 火山.基本.服务器2.客户进入

* **类型:** `事件定义方法`
* **名称:** `客户进入`
* **返回值数据类型:** `整数`
* **参数:**
	* `客户句柄` (`变整数`): 提供所对应客户的SOCKET句柄值
* **描述:** 当有新客户连接入本服务器后,会产生本事件.

##### 火山.基本.服务器2.客户离开

* **类型:** `事件定义方法`
* **名称:** `客户离开`
* **返回值数据类型:** `整数`
* **参数:**
	* `客户句柄` (`变整数`): 提供所对应客户的SOCKET句柄值
* **描述:** 当有已连接客户断开与本服务器的连接后,会产生本事件.

##### 火山.基本.服务器2.启动

* **类型:** `方法`
* **名称:** `启动`
* **返回值数据类型:** `逻辑型`
* **描述:** 开始在"端口"属性所指定的端口上监听客户端连接及数据到达,返回是否成功.

##### 火山.基本.服务器2.停止

* **类型:** `方法`
* **名称:** `停止`
* **描述:** 停止监听端口,断开与所有客户的连接,如需再使用本对象,需要重新启动.

##### 火山.基本.服务器2.发送数据

* **类型:** `方法`
* **名称:** `发送数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `客户句柄` (`变整数`): 为"数据到达"/"客户进入"事件或"取客户"方法中所提供的客户SOCKET句柄值
	* `最长等待时间` (`整数`, 默认值: `-1`): 指定等待发送到每个客户成功的最长时间,单位为秒.如果为-1,表示为无限等待.
	* `所欲发送的所有数据` (`通用型`, `可扩展`): 提供所欲发送的所有数据,可以为基本数据类型或字节集类数据.
* **描述:** 向指定已经连接进来的客户发送数据. 成功返回真,失败返回假. 本方法支持在多线程环境下运行.

##### 火山.基本.服务器2.断开客户

* **类型:** `方法`
* **名称:** `断开客户`
* **参数:**
	* `客户句柄` (`变整数`): 为"数据到达"/"客户进入"事件或"取客户"方法中所提供的客户SOCKET句柄值
* **描述:** 断开与指定客户之间的连接(注意不会发送"客户离开"事件). 本方法支持在多线程环境下运行.

##### 火山.基本.服务器2.取客户地址

* **类型:** `方法`
* **名称:** `取客户地址`
* **返回值数据类型:** `文本型`
* **参数:**
	* `客户句柄` (`变整数`): 为"数据到达"/"客户进入"事件或"取客户"方法中所提供的客户SOCKET句柄值
* **特性:**
	* `静态`
* **描述:** 成功返回所指定客户的地址文本(格式为"IP地址:端口"),失败返回空文本.

---

#### 火山.基本.串口流控制模式

* **类型:** `类`
* **名称:** `串口流控制模式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `串口通讯.辅助类`

##### 火山.基本.串口流控制模式.默认

* **类型:** `成员常量`
* **名称:** `默认`
* **数据类型:** `串口流控制模式`
* **初始值:** `0`

##### 火山.基本.串口流控制模式.禁止

* **类型:** `成员常量`
* **名称:** `禁止`
* **数据类型:** `串口流控制模式`
* **初始值:** `1`

##### 火山.基本.串口流控制模式.启用

* **类型:** `成员常量`
* **名称:** `启用`
* **数据类型:** `串口流控制模式`
* **初始值:** `2`

---

#### 火山.基本.串口流控制方案

* **类型:** `类`
* **名称:** `串口流控制方案`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `串口通讯.辅助类`

##### 火山.基本.串口流控制方案.无

* **类型:** `成员常量`
* **名称:** `无`
* **数据类型:** `串口流控制方案`
* **初始值:** `0`

##### 火山.基本.串口流控制方案.CtsRts

* **类型:** `成员常量`
* **名称:** `CtsRts`
* **数据类型:** `串口流控制方案`
* **初始值:** `1`

##### 火山.基本.串口流控制方案.CtsDtr

* **类型:** `成员常量`
* **名称:** `CtsDtr`
* **数据类型:** `串口流控制方案`
* **初始值:** `2`

##### 火山.基本.串口流控制方案.DsrRts

* **类型:** `成员常量`
* **名称:** `DsrRts`
* **数据类型:** `串口流控制方案`
* **初始值:** `3`

##### 火山.基本.串口流控制方案.DsrDtr

* **类型:** `成员常量`
* **名称:** `DsrDtr`
* **数据类型:** `串口流控制方案`
* **初始值:** `4`

##### 火山.基本.串口流控制方案.XonXoff

* **类型:** `成员常量`
* **名称:** `XonXoff`
* **数据类型:** `串口流控制方案`
* **初始值:** `5`

---

#### 火山.基本.串口停止位数

* **类型:** `类`
* **名称:** `串口停止位数`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `串口通讯.辅助类`
* **描述:** 提供串口停止位的数目

##### 火山.基本.串口停止位数.一位

* **类型:** `成员常量`
* **名称:** `一位`
* **数据类型:** `串口停止位数`
* **初始值:** `1`
* **描述:** 1位

##### 火山.基本.串口停止位数.一点五位

* **类型:** `成员常量`
* **名称:** `一点五位`
* **数据类型:** `串口停止位数`
* **初始值:** `2`
* **描述:** 1.5位

##### 火山.基本.串口停止位数.二位

* **类型:** `成员常量`
* **名称:** `二位`
* **数据类型:** `串口停止位数`
* **初始值:** `3`
* **描述:** 2位

---

#### 火山.基本.串口奇偶校验方式

* **类型:** `类`
* **名称:** `串口奇偶校验方式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `串口通讯.辅助类`

##### 火山.基本.串口奇偶校验方式.无

* **类型:** `成员常量`
* **名称:** `无`
* **数据类型:** `串口奇偶校验方式`
* **初始值:** `0`

##### 火山.基本.串口奇偶校验方式.奇校验

* **类型:** `成员常量`
* **名称:** `奇校验`
* **数据类型:** `串口奇偶校验方式`
* **初始值:** `1`

##### 火山.基本.串口奇偶校验方式.偶校验

* **类型:** `成员常量`
* **名称:** `偶校验`
* **数据类型:** `串口奇偶校验方式`
* **初始值:** `2`

##### 火山.基本.串口奇偶校验方式.标志校验

* **类型:** `成员常量`
* **名称:** `标志校验`
* **数据类型:** `串口奇偶校验方式`
* **初始值:** `3`

##### 火山.基本.串口奇偶校验方式.空白校验

* **类型:** `成员常量`
* **名称:** `空白校验`
* **数据类型:** `串口奇偶校验方式`
* **初始值:** `4`

---

#### 火山.基本.串口类

* **类型:** `类`
* **名称:** `串口类`
* **文档分类:** `串口通讯`
* **描述:** 提供对串口操作的支持

##### 火山.基本.串口类.端口号

* **类型:** `属性成员变量`
* **名称:** `端口号`
* **数据类型:** `整数`
* **初始值:** `1`
* **描述:** 提供所欲访问的端口号,从 1 开始.

##### 火山.基本.串口类.波特率

* **类型:** `属性成员变量`
* **名称:** `波特率`
* **数据类型:** `整数`
* **初始值:** `19200`
* **描述:** 指定通信端口所使用的波特率,比较常用的波特率有: 110, 300, 600, 1200, 2400, 4800, 9600, 14400, 19200, 38400, 56000, 57600, 115200, 128000, 256000.

##### 火山.基本.串口类.数据位数

* **类型:** `属性成员变量`
* **名称:** `数据位数`
* **数据类型:** `整数`
* **初始值:** `8`

##### 火山.基本.串口类.停止位数

* **类型:** `属性成员变量`
* **名称:** `停止位数`
* **数据类型:** `串口停止位数`
* **初始值:** `串口停止位数.一位`

##### 火山.基本.串口类.奇偶校验

* **类型:** `属性成员变量`
* **名称:** `奇偶校验`
* **数据类型:** `逻辑型`
* **初始值:** `假`
* **描述:** 指定通信时对数据是否进行奇偶校验

##### 火山.基本.串口类.事件字符

* **类型:** `属性成员变量`
* **名称:** `事件字符`
* **数据类型:** `字符`
* **初始值:** `'\0'`
* **描述:** 指定用作触发事件的字符,必须为ASCII字符,为'\0'表示不支持事件字符.

##### 火山.基本.串口类.等待时间

* **类型:** `属性成员变量`
* **名称:** `等待时间`
* **数据类型:** `整数`
* **初始值:** `1000`
* **描述:** 指定在进行端口读写操作时最长等待时间,单位毫秒.为0表示无限等待.

##### 火山.基本.串口类.奇偶校验方案

* **类型:** `属性成员变量`
* **名称:** `奇偶校验方案`
* **数据类型:** `串口奇偶校验方式`
* **初始值:** `串口奇偶校验方式.无`
* **描述:** 指定通信时所使用的具体奇偶校验位方案

##### 火山.基本.串口类.流控制方案

* **类型:** `属性成员变量`
* **名称:** `流控制方案`
* **数据类型:** `串口流控制方案`
* **初始值:** `串口流控制方案.无`
* **描述:** 指定通信时所使用的流控制方案

##### 火山.基本.串口类.Rts流控制

* **类型:** `属性成员变量`
* **名称:** `Rts流控制`
* **数据类型:** `串口流控制模式`
* **初始值:** `串口流控制模式.默认`
* **描述:** 指定通信时是否启用Rts流控制

##### 火山.基本.串口类.Dtr流控制

* **类型:** `属性成员变量`
* **名称:** `Dtr流控制`
* **数据类型:** `串口流控制模式`
* **初始值:** `串口流控制模式.默认`
* **描述:** 指定通信时是否启用Dtr流控制

##### 火山.基本.串口类.收到信号

* **类型:** `事件定义方法`
* **名称:** `收到信号`
* **返回值数据类型:** `整数`
* **参数:**
	* `信号类型` (`整数`): 指示具体检测到信号状态的类型,为以下值之一: 1: BREAK信号; 2:CTS上升沿信号;  3: DSR上升沿信号; 4: ERR信号; 5: RING信号; 6: RLSD上升沿信号; 7: 事件字符到达; 8: CTS下降沿信号; 9: DSR下降沿信号; 10: RLSD下降沿信号.
* **描述:** 当通信端口的信号状态发生改变时,会产生本事件.

##### 火山.基本.串口类.数据到达

* **类型:** `事件定义方法`
* **名称:** `数据到达`
* **返回值数据类型:** `整数`
* **参数:**
	* `数据字节值` (`整数`): 提供所接收到的数据字节值
* **描述:** 每当通信端口接收到一个数据字节,就会产生本事件.

##### 火山.基本.串口类.启动

* **类型:** `方法`
* **名称:** `启动`
* **返回值数据类型:** `逻辑型`
* **描述:** 启动或重新启动对指定端口的操作. 在对端口进行操作之前必须首先启动,如在端口启动后又更改了端口属性必须重新启动.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.串口类.停止

* **类型:** `方法`
* **名称:** `停止`
* **描述:** 关闭已经启动的指定端口

##### 火山.基本.串口类.发送数据

* **类型:** `方法`
* **名称:** `发送数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲发送的所有数据` (`通用型`, `可扩展`): 提供所欲发送的所有数据,可以为基本数据类型或字节集类数据. 注意: 文本型数据为Unicode编码且包括结束零字符,如需以其它编码或格式发送文本,请将其转换为相应字节集.
* **描述:** 从端口发送指定的数据
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.串口类.信号操作

* **类型:** `方法`
* **名称:** `信号操作`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `操作类型` (`整数`): 本参数可以为以下值之一:  1: 清除信号;  2: 发送或置位.
	* `欲操作信号类型` (`整数`): 本参数可以为以下值之一:  1: DTR信号;  2: RTS信号; 3: Break信号
* **描述:** 本命令可以设置或清除通讯端口上指定信号的状态
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.串口类.取可用串口

* **类型:** `方法`
* **名称:** `取可用串口`
* **返回值数据类型:** `整数`
* **参数:**
	* `结果存储参数` (`文本排序数组类`): 本参数用作存储所有获得的串口名称
* **特性:**
	* `静态`
* **描述:** 从注册表中获取系统中当前所有可用串口列表
* **返回值描述:** 返回所获得串口名称的数目

---

#### 火山.基本.媒体播放类

* **类型:** `类`
* **名称:** `媒体播放类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `媒体播放`

##### 火山.基本.媒体播放类.播放WAV资源

* **类型:** `全局方法`
* **名称:** `播放WAV资源`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲播放的WAV资源` (`WAV资源`)
	* `是否循环播放` (`逻辑型`, 默认值: `假`): 指定是否循环播放所指定的声音
	* `是否同步播放` (`逻辑型`, 默认值: `假`): 参数值如果为真,则本方法一直等到声音播放完毕后才会返回,否则将立即返回而声音将异步播放.
* **特性:**
	* `静态`
* **描述:** 播放所指定的WAV声音资源
* **返回值描述:** 返回是否播放成功
* **相关例程:** [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-wav播放-wav_play-main](#vol-wav播放-wav_play-main)

##### 火山.基本.媒体播放类.播放WAV文件

* **类型:** `全局方法`
* **名称:** `播放WAV文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲播放的WAV文件` (`文本型`)
	* `是否循环播放` (`逻辑型`, 默认值: `假`): 指定是否循环播放所指定的声音
	* `是否同步播放` (`逻辑型`, 默认值: `假`): 参数值如果为真,则本方法一直等到声音播放完毕后才会返回,否则将立即返回而声音将异步播放.
* **特性:**
	* `静态`
* **描述:** 播放所指定的WAV声音文件
* **返回值描述:** 返回是否播放成功
* **相关例程:** [vol-wav播放-wav_play-main](#vol-wav播放-wav_play-main)

##### 火山.基本.媒体播放类.播放WAV数据

* **类型:** `全局方法`
* **名称:** `播放WAV数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲播放的WAV数据` (`字节集类`)
	* `是否循环播放` (`逻辑型`, 默认值: `假`): 指定是否循环播放所指定的声音
	* `是否同步播放` (`逻辑型`, 默认值: `假`): 参数值如果为真,则本方法一直等到声音播放完毕后才会返回,否则将立即返回而声音将异步播放.
* **特性:**
	* `静态`
* **描述:** 播放所指定的WAV声音数据
* **返回值描述:** 返回是否播放成功
* **相关例程:** [vol-wav播放-wav_play-main](#vol-wav播放-wav_play-main)

##### 火山.基本.媒体播放类.停止播放Wav声音

* **类型:** `全局方法`
* **名称:** `停止播放Wav声音`
* **特性:**
	* `静态`
* **描述:** 停止当前正在进行的所有异步WAV声音播放
* **相关例程:** [vol-wav播放-wav_play-main](#vol-wav播放-wav_play-main)

---

#### 火山.基本.声音播放器

* **类型:** `类`
* **名称:** `声音播放器`
* **基础类:** `参考对象类`
* **文档分类:** `媒体播放`
* **描述:** 用作支持对各种格式声音的播放,可以定义本类的多个实例以支持同时播放多个声音.
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

##### 火山.基本.声音播放器.音量

* **类型:** `属性读方法`
* **名称:** `音量`
* **返回值数据类型:** `小数`
* **描述:** 返回当前所设置的播放音量
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

##### 火山.基本.声音播放器.音量

* **类型:** `属性写方法`
* **名称:** `音量`
* **参数:**
	* `所欲设置的音量` (`小数`): 提供播放音量,音量值从0到1. 0表示静默,1表示使用声音原始音量.
* **描述:** 设置当前播放音量
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

##### 火山.基本.声音播放器.声道均衡值

* **类型:** `属性读方法`
* **名称:** `声道均衡值`
* **返回值数据类型:** `小数`
* **描述:** 返回当前所设置的左右声道均衡值
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

##### 火山.基本.声音播放器.声道均衡值

* **类型:** `属性写方法`
* **名称:** `声道均衡值`
* **参数:**
	* `所欲设置的均衡值` (`小数`): 提供左右声道均衡值. 从-1到1, -1表示左声道音量最大右声道完全静默,1表示右声道音量最大左声道完全静默,0表示左右声道均为最大音量.
* **描述:** 设置当前播放时所使用的左右声道均衡值
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

##### 火山.基本.声音播放器.播放文件

* **类型:** `方法`
* **名称:** `播放文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲播放的声音文件名` (`文本型`): 提供所欲播放的声音文件名,目前支持wav或mp3格式.
	* `是否循环播放` (`逻辑型`, 默认值: `假`): 指定是否循环播放所指定的音乐
* **描述:** 播放所指定的声音文件,返回是否成功.
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

##### 火山.基本.声音播放器.播放数据

* **类型:** `方法`
* **名称:** `播放数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲播放的声音数据` (`字节集类`): 提供所欲播放的声音数据,目前支持wav或mp3格式.
	* `是否循环播放` (`逻辑型`, 默认值: `假`): 指定是否循环播放所指定的音乐
* **描述:** 播放所指定的声音字节集数据,返回是否成功.

##### 火山.基本.声音播放器.播放资源

* **类型:** `方法`
* **名称:** `播放资源`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲播放的声音资源` (`声音资源`): 提供所欲播放的声音资源数据,目前支持wav或mp3格式.
	* `是否循环播放` (`逻辑型`, 默认值: `假`): 指定是否循环播放所指定的音乐
* **描述:** 播放所指定的声音资源数据,返回是否成功.
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

##### 火山.基本.声音播放器.停止

* **类型:** `方法`
* **名称:** `停止`
* **描述:** 停止当前正在播放的声音
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

##### 火山.基本.声音播放器.暂停

* **类型:** `方法`
* **名称:** `暂停`
* **描述:** 暂停当前正在播放的声音
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

##### 火山.基本.声音播放器.继续

* **类型:** `方法`
* **名称:** `继续`
* **描述:** 继续播放当前被暂停播放的声音
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

##### 火山.基本.声音播放器.是否循环播放

* **类型:** `方法`
* **名称:** `是否循环播放`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回当前是否设置为循环播放

##### 火山.基本.声音播放器.是否正在播放

* **类型:** `方法`
* **名称:** `是否正在播放`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回当前是否正在进行播放
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

---

#### 火山.基本.流错误码

* **类型:** `类`
* **名称:** `流错误码`
* **文档分类:** `流操作.辅助类`
* **描述:** 流操作错误码列表
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.流错误码.无错误

* **类型:** `成员常量`
* **名称:** `无错误`
* **数据类型:** `整数`

##### 火山.基本.流错误码.空流

* **类型:** `成员常量`
* **名称:** `空流`
* **数据类型:** `整数`
* **描述:** 流对象为空

##### 火山.基本.流错误码.未知错误

* **类型:** `成员常量`
* **名称:** `未知错误`
* **数据类型:** `整数`

##### 火山.基本.流错误码.读出错

* **类型:** `成员常量`
* **名称:** `读出错`
* **数据类型:** `整数`

##### 火山.基本.流错误码.写出错

* **类型:** `成员常量`
* **名称:** `写出错`
* **数据类型:** `整数`

##### 火山.基本.流错误码.定位出错

* **类型:** `成员常量`
* **名称:** `定位出错`
* **数据类型:** `整数`

##### 火山.基本.流错误码.内存分配失败

* **类型:** `成员常量`
* **名称:** `内存分配失败`
* **数据类型:** `整数`

##### 火山.基本.流错误码.无效数据

* **类型:** `成员常量`
* **名称:** `无效数据`
* **数据类型:** `整数`
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

---

#### 火山.基本.基本流类

* **类型:** `类`
* **名称:** `基本流类`
* **文档分类:** `流操作`
* **描述:** 所有流操作类的基础类
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.基本流类.错误码

* **类型:** `属性读方法`
* **名称:** `错误码`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作对象` (`基本流类`)
* **特性:**
	* `静态`
* **描述:** 返回流中的当前错误码. 如果错误码不为"流错误码.无错误",则说明流当前处于出错状态,此时该流其后所有的流操作都将失败.
* **返回值描述:** 所返回值为"流错误码"类中的常量值或者用户自定义值
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.基本流类.错误码

* **类型:** `属性写方法`
* **名称:** `错误码`
* **参数:**
	* `所操作对象` (`基本流类`)
	* `所欲设置的错误码` (`整数`): 为"流错误码"类中的常量值或者用户自定义值,注意用户自定义值必须大于0.
* **特性:**
	* `静态`
* **描述:** 设置流的当前错误码值. 所有流操作一旦失败,都将自动在流中设置对应的错误码.用户也可以在流操作过程中使用本属性设置自己定义的错误码(错误码值必须大于0,以免与系统内置的冲突).一旦流的错误码值不为"流错误码.无错误",则说明流当前处于出错状态,此时该流其后所有的流操作都将失败.
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.基本流类.关闭

* **类型:** `方法`
* **名称:** `关闭`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`基本流类`)
* **特性:**
	* `静态`
* **描述:** 关闭流. 流操作结束后可以将其关闭,本操作不是必需的,流对象销毁时会自动关闭. 本方法会自动清除流中的现有出错状态.
* **返回值描述:** 返回是否关闭成功
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.基本流类.流是否为空

* **类型:** `方法`
* **名称:** `流是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`基本流类`)
* **特性:**
	* `静态`
* **描述:** 返回本流对象是否为空状态(即其中尚未置入任何实质的流数据来源)

##### 火山.基本.基本流类.清除错误

* **类型:** `方法`
* **名称:** `清除错误`
* **参数:**
	* `所操作对象` (`基本流类`)
* **特性:**
	* `静态`
* **描述:** 清除流的出错状态. 本操作等效于"错误码 = 流错误码.无错误"语句. 所有流操作一旦失败,都将自动在流中设置对应的错误码.用户也可以在流操作过程中使用"错误码"属性设置自己定义的错误码(错误码值必须大于0,以免与系统内置的冲突).一旦流的错误码值不为"流错误码.无错误",则说明流当前处于出错状态,此时该流其后所有的流操作都将失败.

##### 火山.基本.基本流类.是否成功

* **类型:** `方法`
* **名称:** `是否成功`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`基本流类`)
* **特性:**
	* `静态`
* **描述:** 返回流当前是否不处于出错状态,即"错误码"属性值是否为"流错误码.无错误". 流一旦处于出错状态,该流其后所有的流操作都将失败.

##### 火山.基本.基本流类.是否出错

* **类型:** `方法`
* **名称:** `是否出错`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`基本流类`)
* **特性:**
	* `静态`
* **描述:** 返回流当前是否处于出错状态,即"错误码"属性值是否不为"流错误码.无错误". 流一旦处于出错状态,该流其后所有的流操作都将失败.
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

---

#### 火山.基本.输入流类

* **类型:** `类`
* **名称:** `输入流类`
* **基础类:** `基本流类`
* **文档分类:** `流操作`
* **描述:** 所有输入流操作类的基础类
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.输入流类.重置

* **类型:** `方法`
* **名称:** `重置`
* **参数:**
	* `所操作对象` (`输入流类`)
	* `缓冲区尺寸` (`整数`, 默认值: `4096`): 提供所欲设置的数据读入缓冲区尺寸,小于等于0表示不使用缓冲区.
* **特性:**
	* `静态`
* **描述:** 关闭本输入流,重置其所使用的数据读入缓冲区尺寸. 数据读入缓冲区用作提高数据读入的效率,默认使用的数据读入缓冲区尺寸为4096字节,可以通过调用本方法重置为更大或更小的尺寸.

##### 火山.基本.输入流类.前移

* **类型:** `方法`
* **名称:** `前移`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`输入流类`)
	* `所前移的距离` (`整数`): 提供将当前读指针向前移动的字节数,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 将当前读指针向前移动所指定的尺寸,返回是否成功. 本操作如果失败,将自动在流中设置对应的出错状态.

##### 火山.基本.输入流类.是否到尾部

* **类型:** `方法`
* **名称:** `是否到尾部`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`输入流类`)
* **特性:**
	* `静态`
* **描述:** 返回当前读指针是否已经到了输入流的尾部. 注意: 如果流当前处于出错状态,本方法将始终返回真.

##### 火山.基本.输入流类.取读位置

* **类型:** `方法`
* **名称:** `取读位置`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作对象` (`输入流类`)
* **特性:**
	* `静态`
* **描述:** 返回当前读指针相对流首部的偏移位置

##### 火山.基本.输入流类.读数据

* **类型:** `方法`
* **名称:** `读数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`输入流类`)
	* `所欲读入数据尺寸` (`整数`): 提供所欲读入数据的尺寸
	* `所欲保存到的字节集` (`字节集类`): 所读入数据将存放进此字节集中,其中原有数据将被覆盖.
* **特性:**
	* `静态`
* **描述:** 从本输入流中读入所指定尺寸的数据. 本操作如果失败或未读取到所指定尺寸的数据,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回是否成功读入了所指定尺寸的数据

##### 火山.基本.输入流类.读数据2

* **类型:** `方法`
* **名称:** `读数据2`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作对象` (`输入流类`)
	* `所欲读入数据尺寸` (`整数`): 提供所欲读入数据的尺寸
	* `所欲保存到的字节集` (`字节集类`): 所读入数据将存放进此字节集中,其中原有数据将被覆盖.
* **特性:**
	* `静态`
* **描述:** 从本输入流中读入所指定尺寸的数据. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回所实际读入的字节数

##### 火山.基本.输入流类.读内存

* **类型:** `方法`
* **名称:** `读内存`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作对象` (`输入流类`)
	* `所欲读入数据尺寸` (`整数`): 提供所欲读入数据的尺寸
	* `所欲保存到的内存地址` (`变整数`): 所读入数据将存放到此地址处,请确保从此地址开始具有足够尺寸的有效内存空间.
* **特性:**
	* `静态`
* **描述:** 从本输入流中读入数据到所指定的内存地址. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回所实际读入的字节数

##### 火山.基本.输入流类.读到尾部

* **类型:** `方法`
* **名称:** `读到尾部`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作对象` (`输入流类`)
	* `所欲保存到的字节集` (`字节集类`): 所读入数据将存放进此字节集中,其中原有数据将被覆盖.
* **特性:**
	* `静态`
* **描述:** 从本输入流中当前读入指针位置处一直读入到流尾部,将所读取到的所有数据保存到所指定的字节集变量. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回所实际读入的字节数

##### 火山.基本.输入流类.读

* **类型:** `方法`
* **名称:** `读`
* **返回值数据类型:** `输入流类`
* **参数:**
	* `所操作对象` (`输入流类`)
	* `所读取数据的存放变量` (`通用基本型(需求:可写入变量)`): 本变量的数据类型决定了所欲读取数据的类型
* **特性:**
	* `静态`
* **描述:** 读入所指定的基本数据类型数据. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回本流对象,用作支持连续读入.
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.输入流类.读对象

* **类型:** `方法`
* **名称:** `读对象`
* **返回值数据类型:** `输入流类`
* **参数:**
	* `所操作对象` (`输入流类`)
	* `欲读取数据的对象` (`对象类`): 将调用该对象所处类的"流读入"方法(由用户自行定义或由 系统编译器默认生成)来完成对此对象数据内容的读入.
* **特性:**
	* `静态`
* **描述:** 调用所指定对象中的数据. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回本流对象,用作支持连续读入.
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.输入流类.读数组

* **类型:** `方法`
* **名称:** `读数组`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`输入流类`)
	* `所欲读取的数组` (`通用非文本基本型数组(需求:可写入变量)`): 提供所欲读取其内容的数组变量,所读取尺寸等于该数组的定义尺寸.
* **特性:**
	* `静态`
* **描述:** 读入所指定基本类型的数组内容. 本操作如果失败或未读取到整个数组的全部数据,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回是否成功读入了整个数组的全部数据

---

#### 火山.基本.输出流类

* **类型:** `类`
* **名称:** `输出流类`
* **基础类:** `基本流类`
* **文档分类:** `流操作`
* **描述:** 所有输出流操作类的基础类
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.输出流类.重置

* **类型:** `方法`
* **名称:** `重置`
* **参数:**
	* `所操作对象` (`输出流类`)
	* `缓冲区尺寸` (`整数`, 默认值: `4096`): 提供所欲设置的数据输出缓冲区尺寸,小于等于0表示不使用缓冲区.
* **特性:**
	* `静态`
* **描述:** 关闭本输出流,重置其所使用的数据输出缓冲区尺寸. 数据输出缓冲区用作提高数据输出的效率,默认使用的数据输出缓冲区尺寸为4096字节,可以通过调用本方法重置为更大或更小的尺寸.

##### 火山.基本.输出流类.刷新

* **类型:** `方法`
* **名称:** `刷新`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`基本流类`)
* **特性:**
	* `静态`
* **描述:** 刷新写出流,将流中的所有缓存数据进行实际写出. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回是否刷新成功

##### 火山.基本.输出流类.写数据

* **类型:** `方法`
* **名称:** `写数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`输出流类`)
	* `所欲写出的数据` (`字节集类`): 提供所欲写出的数据
* **特性:**
	* `静态`
* **描述:** 写出所指定尺寸的数据到本输出流. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回是否成功写出了所指定尺寸的数据

##### 火山.基本.输出流类.写内存

* **类型:** `方法`
* **名称:** `写内存`
* **返回值数据类型:** `整数`
* **参数:**
	* `所操作对象` (`输出流类`)
	* `所欲写出数据的地址` (`变整数`): 提供所欲写出数据的内存地址指针值
	* `所欲写出数据尺寸` (`整数`): 提供所欲写出数据的尺寸
* **特性:**
	* `静态`
* **描述:** 写出所指定尺寸的内存数据到本输出流. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回是否成功写出了所指定尺寸的数据

##### 火山.基本.输出流类.写

* **类型:** `方法`
* **名称:** `写`
* **返回值数据类型:** `输出流类`
* **参数:**
	* `所操作对象` (`输出流类`)
	* `所欲写出的数据` (`通用基本型`): 本参数的数据类型决定了所欲写出数据的类型
* **特性:**
	* `静态`
* **描述:** 写出所指定的基本数据类型数据到本输出流. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回本流对象,用作支持连续写出.
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.输出流类.写对象

* **类型:** `方法`
* **名称:** `写对象`
* **返回值数据类型:** `输出流类`
* **参数:**
	* `所操作对象` (`输出流类`)
	* `所欲写出的对象` (`对象类`): 将调用该对象所处类的"流写出"方法(由用户自行定义或由 系统编译器默认生成)来完成对此对象数据内容的写出.
* **特性:**
	* `静态`
* **描述:** 写出所指定对象中的数据. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回本流对象,用作支持连续写出.
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.输出流类.写数组

* **类型:** `方法`
* **名称:** `写数组`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`输出流类`)
	* `所欲写出的数组` (`通用非文本基本型数组`): 提供所欲写出其内容的数组变量,所写出数据尺寸等于该数组的定义尺寸.
* **特性:**
	* `静态`
* **描述:** 写出所指定基本类型的数组内容. 本操作如果失败,将自动在流中设置对应的出错状态.
* **返回值描述:** 返回是否成功写出了整个数组的全部数据

---

#### 火山.基本.文件输入流

* **类型:** `类`
* **名称:** `文件输入流`
* **基础类:** `输入流类`
* **文档分类:** `流操作`
* **描述:** 用作输入来自文件中的流数据
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.文件输入流.打开

* **类型:** `方法`
* **名称:** `打开`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`文件输入流`)
	* `所欲打开文件名` (`文本型`): 提供所欲打开读入的文件名
* **特性:**
	* `静态`
* **描述:** 打开所指定名称文件准备进行读入
* **返回值描述:** 返回是否打开成功
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

---

#### 火山.基本.文件输出流

* **类型:** `类`
* **名称:** `文件输出流`
* **基础类:** `输出流类`
* **文档分类:** `流操作`
* **描述:** 用作写出流数据到所指定文件中
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.文件输出流.打开

* **类型:** `方法`
* **名称:** `打开`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`文件输出流`)
	* `所欲打开文件名` (`文本型`): 提供所欲打开写出的文件名,如果该文件不存在,将自动创建.
	* `是否附加` (`逻辑型`, 默认值: `假`): 本参数值为真则销毁所指定文件中的原有内容,从文件首部开始写出,为假则从所指定文件的原有内容尾部开始写出.
* **特性:**
	* `静态`
* **描述:** 打开所指定名称文件准备进行写出
* **返回值描述:** 返回是否打开成功
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

---

#### 火山.基本.加密文件输入流

* **类型:** `类`
* **名称:** `加密文件输入流`
* **基础类:** `输入流类`
* **文档分类:** `流操作`
* **描述:** 用作输入来自加密文件中的流数据
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.加密文件输入流.打开

* **类型:** `方法`
* **名称:** `打开`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`加密文件输入流`)
	* `所欲打开文件名` (`文本型`): 提供所欲打开读入的文件名
	* `密码文本` (`文本型`, 默认值: `""`): 提供具体的密码文本,为空文本表示无.
	* `明文区长度` (`整数`, 默认值: `0`): 本参数指定从文件首部开始不希望被加密部分的长度,类库在读写此区域内的数据时,不会使用密码对其进行加解密操作. 此参数用作将加密文件分为明文区和密文区两部分,以方便某些应用程序同时保存一些明文数据.注意当打开已有加密数据的文件时,此参数值必须与新建此加密文件时所提供的参数值一致,否则会造成数据访问错误.
* **特性:**
	* `静态`
* **描述:** 打开所指定名称加密文件准备进行读入
* **返回值描述:** 返回是否打开成功
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

---

#### 火山.基本.加密文件输出流

* **类型:** `类`
* **名称:** `加密文件输出流`
* **基础类:** `输出流类`
* **文档分类:** `流操作`
* **描述:** 用作写出流数据到所指定加密文件中
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.加密文件输出流.打开

* **类型:** `方法`
* **名称:** `打开`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所操作对象` (`加密文件输出流`)
	* `所欲打开文件名` (`文本型`): 提供所欲打开写出的文件名,如果该文件不存在,将自动创建.
	* `密码文本` (`文本型`, 默认值: `""`): 提供具体的密码文本,为空文本表示无.
	* `明文区长度` (`整数`, 默认值: `0`): 本参数指定从文件首部开始不希望被加密部分的长度,类库在读写此区域内的数据时,不会使用密码对其进行加解密操作. 此参数用作将加密文件分为明文区和密文区两部分,以方便某些应用程序同时保存一些明文数据.
* **特性:**
	* `静态`
* **描述:** 打开所指定名称加密文件准备进行写出
* **返回值描述:** 返回是否打开成功
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

---

#### 火山.基本.内存输入流

* **类型:** `类`
* **名称:** `内存输入流`
* **基础类:** `输入流类`
* **文档分类:** `流操作`
* **描述:** 用作输入来自内存中的流数据
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.内存输入流.打开

* **类型:** `方法`
* **名称:** `打开`
* **参数:**
	* `所操作对象` (`内存输入流`)
	* `所欲读入数据` (`字节集类`): 提供所欲打开读入的数据,该数据会被复制一份到流对象中,因此无需保留.
* **特性:**
	* `静态`
* **描述:** 打开所指定内存数据准备进行读入
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.内存输入流.打开2

* **类型:** `方法`
* **名称:** `打开2`
* **参数:**
	* `所操作对象` (`内存输入流`)
	* `所欲读入数据的地址` (`变整数`): 提供所欲打开读入数据的内存地址首指针,该数据会被复制一份到流对象中,因此无需保留.
	* `所欲读入数据的尺寸` (`整数`): 提供所提供数据的尺寸
* **特性:**
	* `静态`
* **描述:** 打开所指定内存数据准备进行读入

---

#### 火山.基本.内存输出流

* **类型:** `类`
* **名称:** `内存输出流`
* **基础类:** `输出流类`
* **文档分类:** `流操作`
* **描述:** 用作将流数据输出到内存中
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.内存输出流.置预分配尺寸

* **类型:** `方法`
* **名称:** `置预分配尺寸`
* **参数:**
	* `所操作对象` (`内存输出流`)
	* `所欲设置的预分配尺寸` (`整数`): 提供所欲设置的预分配尺寸,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 本流中存在一个用作存储所写入数据的内部字节集对象.为了快速进行数据写入操作,本方法可以设置该字节集所使用的空间分配尺寸,每次该字节集需要调整其空间大小时,都使用本属性值作为空间调整基准尺寸.值越大,写入数据时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.

##### 火山.基本.内存输出流.清空

* **类型:** `方法`
* **名称:** `清空`
* **参数:**
	* `所操作对象` (`内存输出流`)
* **特性:**
	* `静态`
* **描述:** 清空先前所已经写入的所有流数据

##### 火山.基本.内存输出流.取数据

* **类型:** `方法`
* **名称:** `取数据`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所操作对象` (`内存输出流`)
* **特性:**
	* `静态`
* **描述:** 返回所有已经写入到本流中的数据. 注意: 不要修改所返回字节集对象的内容
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

---

#### 火山.基本.互斥锁类

* **类型:** `类`
* **名称:** `互斥锁类`
* **基础类:** `参考对象类`
* **描述:** 用作加锁同时只能一个线程进入的关键段区域. 本线程锁可以重入.
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.互斥锁类.加锁

* **类型:** `方法`
* **名称:** `加锁`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `是否仅尝试` (`逻辑型`, 默认值: `假`): 如果本参数值为真,则会尝试加锁,如果能够成功加锁,则加锁后返回真,如果不能(譬如已经被其它线程锁住)则立即返回假. 如果本参数值为假,则无限等待直到能够成功加锁,此时本方法始终返回真.
* **描述:** 将本互斥锁加锁,如果本锁当前已经被另一线程锁住,则进入等待状态.
* **返回值描述:** 见"是否仅尝试"参数说明
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.互斥锁类.解锁

* **类型:** `方法`
* **名称:** `解锁`
* **描述:** 如果先前加锁成功,解开此锁,以允许其它线程加锁成功.
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

---

#### 火山.基本.信号灯类

* **类型:** `类`
* **名称:** `信号灯类`
* **基础类:** `参考对象类`
* **描述:** 用作在线程之间基于一个信号灯值进行同步,信号灯的初始值为0. 本线程锁可以重入.

##### 火山.基本.信号灯类.等待

* **类型:** `方法`
* **名称:** `等待`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `是否仅尝试` (`逻辑型`, 默认值: `假`): 如果本参数值为真,则只测试下信号灯值,如果值大于0,则将其减1后立即成功返回真,否则立即返回假. 如果本参数值为假,则无限等待直到信号值大于0,然后将其减1返回真.
* **描述:** 如果当前信号灯值大于0,则将其减去1后返回.
* **返回值描述:** 见"是否仅尝试"参数说明

##### 火山.基本.信号灯类.限时等待

* **类型:** `方法`
* **名称:** `限时等待`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `最大等待时间` (`整数`): 指定所欲等待的最多毫秒数,必须大于等于0.
* **描述:** 等待指定的毫秒数,直到信号值大于0,然后将其减1返回真. 如果在所指定的时间内信号灯值一直小于等于0,则返回假.

##### 火山.基本.信号灯类.放行

* **类型:** `方法`
* **名称:** `放行`
* **描述:** 将信号灯值加1,从而允许一个正在等待加锁信号灯的线程成功通过.

##### 火山.基本.信号灯类.重置

* **类型:** `方法`
* **名称:** `重置`
* **描述:** 将信号灯值重置为0

##### 火山.基本.信号灯类.取句柄

* **类型:** `方法`
* **名称:** `取句柄`
* **返回值数据类型:** `变整数`
* **描述:** 返回本对象所对应的Windows句柄值

---

#### 火山.基本.同步事件类

* **类型:** `类`
* **名称:** `同步事件类`
* **基础类:** `参考对象类`
* **描述:** 用作在线程之间基于一个逻辑型的事件值进行同步,该事件值初始为假. 本线程锁可以重入.

##### 火山.基本.同步事件类.等待

* **类型:** `方法`
* **名称:** `等待`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `是否仅尝试` (`逻辑型`, 默认值: `假`): 如果本参数值为真,且事件值为真,则将其重置为假后立即返回真,否则立即返回假. 如果本参数值为假,则无限等待直到事件值为真,然后将其重置为假后返回真.
* **描述:** 如果当前事件值为真,则将其重置为假后返回.
* **返回值描述:** 见"是否仅尝试"参数说明

##### 火山.基本.同步事件类.限时等待

* **类型:** `方法`
* **名称:** `限时等待`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `最大等待时间` (`整数`): 指定所欲等待的最多毫秒数,必须大于等于0.
* **描述:** 等待指定的毫秒数,直到事件值为真,然后将其重置为假后返回真. 如果在所指定的时间内事件值一直为假,则返回假.

##### 火山.基本.同步事件类.放行

* **类型:** `方法`
* **名称:** `放行`
* **描述:** 将当前事件值设置为真,从而允许一个正在等待此事件的线程成功通过,然后立即将事件值重置为假.

##### 火山.基本.同步事件类.重置

* **类型:** `方法`
* **名称:** `重置`
* **描述:** 将事件值重置为假

##### 火山.基本.同步事件类.取句柄

* **类型:** `方法`
* **名称:** `取句柄`
* **返回值数据类型:** `变整数`
* **描述:** 返回本对象所对应的Windows句柄值

---

#### 火山.基本.读写锁类

* **类型:** `类`
* **名称:** `读写锁类`
* **基础类:** `参考对象类`
* **描述:** 用作支持多个线程读,单个线程写. 读写锁的特点: 任何时候,如果有写线程成功加锁,那么其它读/写线程都将不能再加锁(欲加锁将进入等待状态),如果有读线程成功加锁,那么其它写线程将不能加锁(欲加锁将进入等待状态),但是其它读线程能够成功加锁.

##### 火山.基本.读写锁类.开始读

* **类型:** `方法`
* **名称:** `开始读`
* **描述:** 读线程调用本方法用作加锁以开始进行读操作,如果不能加锁,将一直等待. 注意: 本方法返回后即表示当前线程获得了读权力,读操作完毕后必须调用"结束读"方法释放锁.

##### 火山.基本.读写锁类.结束读

* **类型:** `方法`
* **名称:** `结束读`
* **描述:** 先前调用"开始读"方法成功加锁的读线程必须调用 本方法结束读操作,以放行其它等待操作的线程.

##### 火山.基本.读写锁类.开始写

* **类型:** `方法`
* **名称:** `开始写`
* **描述:** 写线程调用本方法用作加锁以开始进行写操作,如果不能加锁,将一直等待. 注意: 本方法返回后即表示当前线程获得了写权力,写操作完毕后必须调用"结束写"方法释放锁.

##### 火山.基本.读写锁类.结束写

* **类型:** `方法`
* **名称:** `结束写`
* **描述:** 先前调用"开始写"方法成功加锁的写线程必须调用 本方法结束写操作,以放行其它等待操作的线程.

---

#### 火山.基本.简单完成端口信息

* **类型:** `类`
* **名称:** `简单完成端口信息`

##### 火山.基本.简单完成端口信息.信息码

* **类型:** `成员变量`
* **名称:** `信息码`
* **数据类型:** `整数`
* **描述:** 本成员对应 GetQueuedCompletionStatus 的 lpNumberOfBytes 参数.

##### 火山.基本.简单完成端口信息.参数1

* **类型:** `成员变量`
* **名称:** `参数1`
* **数据类型:** `变整数`
* **描述:** 本成员对应 GetQueuedCompletionStatus 的 lpCompletionKey 参数.

##### 火山.基本.简单完成端口信息.参数2

* **类型:** `成员变量`
* **名称:** `参数2`
* **数据类型:** `变整数`
* **描述:** 本成员对应 GetQueuedCompletionStatus 的 lpOverlapped 参数.

---

#### 火山.基本.简单完成端口类

* **类型:** `类`
* **名称:** `简单完成端口类`
* **基础类:** `参考对象类`
* **描述:** 本类实现了一个简单的基于完成端口(IOCP)的线程通讯类,用作在多线程之间传递简单数据使用.

##### 火山.基本.简单完成端口类.创建

* **类型:** `方法`
* **名称:** `创建`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲绑定文件句柄` (`变整数`, 默认值: `-1`): 提供所欲绑定到完成端口的文件句柄值,为-1表示无.
	* `绑定到完成端口句柄` (`变整数`, 默认值: `0`): 提供所欲绑定到的完成端口句柄,为0表示无.
	* `用户参数` (`变整数`, 默认值: `0`): 将在"等待"方法的"简单完成端口信息.参数1"中返回. 本参数对应 CreateIoCompletionPort 的 CompletionKey 参数.
* **描述:** 创建完成端口,返回是否成功. 如果先前已经创建了完成端口,将会自动被销毁.

##### 火山.基本.简单完成端口类.销毁

* **类型:** `方法`
* **名称:** `销毁`
* **描述:** 销毁所已经创建的完成端口. 本方法调用不是必需的,本类对象销毁时,会自动销毁已创建的完成端口.

##### 火山.基本.简单完成端口类.取句柄

* **类型:** `方法`
* **名称:** `取句柄`
* **返回值数据类型:** `变整数`
* **描述:** 返回所已经创建的完成端口句柄,返回0表示尚未创建.

##### 火山.基本.简单完成端口类.投递

* **类型:** `方法`
* **名称:** `投递`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `信息码` (`整数`, 默认值: `0`): 本参数对应 PostQueuedCompletionStatus 的 dwNumberOfBytesTransferred 参数.
	* `参数1` (`变整数`, 默认值: `0`): 本参数对应 PostQueuedCompletionStatus 的 CompletionKey 参数.
	* `参数2` (`变整数`, 默认值: `0`): 本参数对应 PostQueuedCompletionStatus 的 lpOverlapped  参数.
* **描述:** 在本完成端口对象上投递所指定的信息,返回是否成功. 注意: 调用本方法之前必须已经成功创建.

##### 火山.基本.简单完成端口类.投递2

* **类型:** `方法`
* **名称:** `投递2`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲投递的信息` (`简单完成端口信息`)
* **描述:** 在本完成端口对象上投递所指定的信息,返回是否成功. 注意: 调用本方法之前必须已经成功创建.

##### 火山.基本.简单完成端口类.等待

* **类型:** `方法`
* **名称:** `等待`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所接收到的信息` (`简单完成端口信息`): 当本方法返回真时,用作存储所获得的信息(由"投递"/"投递2"方法发送)
	* `最大等待时间` (`整数`, 默认值: `-1`): 指定所欲等待的最多毫秒数,为-1表示无限等待.
* **描述:** 等待本完成端口对象上通过"投递"/"投递2"方法发送过来信息,返回是否成功. 注意: 调用本方法之前必须已经成功创建.

---

#### 火山.基本.线程优先级

* **类型:** `类`
* **名称:** `线程优先级`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `多线程.辅助类`
* **描述:** 提供线程的优先级别,类中的常量按优先级从小到大顺序排列.
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.线程优先级.空闲

* **类型:** `成员常量`
* **名称:** `空闲`
* **数据类型:** `线程优先级`

##### 火山.基本.线程优先级.通常低

* **类型:** `成员常量`
* **名称:** `通常低`
* **数据类型:** `线程优先级`

##### 火山.基本.线程优先级.通常

* **类型:** `成员常量`
* **名称:** `通常`
* **数据类型:** `线程优先级`
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.线程优先级.通常高

* **类型:** `成员常量`
* **名称:** `通常高`
* **数据类型:** `线程优先级`

##### 火山.基本.线程优先级.高

* **类型:** `成员常量`
* **名称:** `高`
* **数据类型:** `线程优先级`

##### 火山.基本.线程优先级.关键

* **类型:** `成员常量`
* **名称:** `关键`
* **数据类型:** `线程优先级`

---

#### 火山.基本.线程状态类

* **类型:** `类`
* **名称:** `线程状态类`
* **基础类:** `参考对象类`
* **描述:** 提供线程的当前状态,并提供相关操作支持. 本类中的所有方法均支持在多线程环境中使用.
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.线程状态类.置用户对象1

* **类型:** `方法`
* **名称:** `置用户对象1`
* **参数:**
	* `所欲设置对象` (`对象类`): 本参数对象的内容将被复制到本对象中的用户对象1,如果为"空对象"("是否为空对象"全局方法返回真),则先前所存在用户对象1将被删除.
* **描述:** 设置所欲保存到本对象中的用户对象1,先前所存在用户对象1将被覆盖.
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.线程状态类.取用户对象1

* **类型:** `方法`
* **名称:** `取用户对象1`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `结果获取对象` (`对象类`): 提供欲将所获取的用户对象1数据填入的对象,其实际数据类型需要与本对象中所保存用户对象1的实际数据类型匹配(为其实际数据类型或基础类).
* **描述:** 如果所提供欲填入对象的实际数据类型匹配本对象中所保存用户对象1的实际 数据类型(为其实际数据类型或基础类),则将本对象中所保存用户对象1的内容复制到"所欲填入对象"参数对象中后返回真,否则失败返回假. 如果本对象中尚未置入用户对象1,将返回假.
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.线程状态类.置用户对象2

* **类型:** `方法`
* **名称:** `置用户对象2`
* **参数:**
	* `所欲设置对象` (`对象类`): 本参数对象的内容将被复制到本对象中的用户对象2,如果为"空对象"("是否为空对象"全局方法返回真),则先前所存在用户对象2将被删除.
* **描述:** 设置所欲保存到本对象中的用户对象2,先前所存在用户对象2将被覆盖.

##### 火山.基本.线程状态类.取用户对象2

* **类型:** `方法`
* **名称:** `取用户对象2`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `结果获取对象` (`对象类`): 提供欲将所获取的用户对象2数据填入的对象,其实际数据类型需要与本对象中所保存用户对象2的实际数据类型匹配(为其实际数据类型或基础类).
* **描述:** 如果所提供欲填入对象的实际数据类型匹配本对象中所保存用户对象2的实际 数据类型(为其实际数据类型或基础类),则将本对象中所保存用户对象2的内容复制到"所欲填入对象"参数对象中后返回真,否则失败返回假. 如果本对象中尚未置入用户对象2,将返回假.

##### 火山.基本.线程状态类.置用户值

* **类型:** `方法`
* **名称:** `置用户值`
* **参数:**
	* `所欲设置的值` (`变整数`)
* **描述:** 设置欲保存到本对象中的用户变整数值
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.线程状态类.取用户值

* **类型:** `方法`
* **名称:** `取用户值`
* **返回值数据类型:** `变整数`
* **描述:** 返回所保存到本对象中的用户变整数值
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.线程状态类.是否正在运行

* **类型:** `方法`
* **名称:** `是否正在运行`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回所绑定线程是否处于正在运行状态

##### 火山.基本.线程状态类.通知并等待线程退出

* **类型:** `方法`
* **名称:** `通知并等待线程退出`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `最大等待时间` (`整数`, 默认值: `-1`): 指定最大等待线程退出的时间(单位毫秒),为-1表示无限等待,为0表示不等待.
* **描述:** 本方法只能在所绑定线程以外的线程中执行,用作通知并等待所绑定线程退出. 为了支持本方法,所绑定线程必须尽可能快地频繁调用"线程是否被通知退出"方法,一旦发现该方法返回真,则需要尽快结束线程的执行,否则本方法在无限等待的时候将进入死等状态. 注意: 一旦使用本机制,在所绑定线程中不允许对窗口界面直接进行操作,否则可能导致死锁.
* **返回值描述:** 返回线程是否已经退出
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.线程状态类.线程是否被通知退出

* **类型:** `方法`
* **名称:** `线程是否被通知退出`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `最大检查等待时间` (`整数`, 默认值: `0`): 指定检查线程是否需要退出的最大等待时间(单位毫秒),为-1表示无限等待,为0表示不等待.
* **描述:** 本方法只能在所绑定线程中执行,一旦发现本方法返回真,必须尽快结束线程的执行,否则将导致另一线程中的"通知并等待线程退出"方法调用在进行无限等待时进入死等状态. 本方法用作和"通知并等待线程退出"方法配套使用,如果外部线程中不会调用"通知并等待线程退出"方法,则亦无需调用本方法检查是否退出. 注意: 一旦使用本机制,在所绑定线程中不允许对窗口界面直接进行操作,否则可能导致死锁.
* **返回值描述:** 返回线程是否需要尽快退出
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

---

#### 火山.基本.线程操作类

* **类型:** `类`
* **名称:** `线程操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **描述:** 提供线程的相关操作功能支持

##### 火山.基本.线程操作类.等待超时

* **类型:** `成员常量`
* **名称:** `等待超时`
* **数据类型:** `整数`
* **描述:** 用作表示等待事件已经超时

##### 火山.基本.线程操作类.等待多个事件

* **类型:** `全局方法`
* **名称:** `等待多个事件`
* **返回值数据类型:** `整数`
* **参数:**
	* `事件句柄数组` (`变整数 []`): 提供所欲等待的所有事件的句柄值,可以为"信号灯类"或"同步事件类"的"取句柄"的返回值.
	* `最大等待时间` (`整数`, 默认值: `-1`): 指定所欲等待的最多毫秒数,为-1表示无限等待.
* **特性:**
	* `静态`
* **描述:** 同时等待多个多线程同步事件,如果其中任何一个事件等待通过或所指定的等待时间达到,则返回.
* **返回值描述:** 如果任意一个事件成功等待通过,返回该事件句柄在"事件句柄数组"参数中的索引位置,如果等待时间超时,返回"线程操作类.等待超时"常量值.

##### 火山.基本.线程操作类.启动线程

* **类型:** `全局方法`
* **名称:** `启动线程`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `线程函数` (`线程模板函数1(指定格式方法)`): 提供所欲执行的线程函数
	* `用户参数` (`变整数`, 默认值: `0`): 提供传递到线程函数的用户参数值
	* `堆栈尺寸` (`整数`, 默认值: `0`): 提供线程所使用的堆栈尺寸,单位字节.为0表示使用默认尺寸.
	* `优先级` (`线程优先级`, 默认值: `线程优先级.通常`): 提供线程的优先级别
	* `是否等待线程执行完毕` (`逻辑型`, 默认值: `假`): 指定本方法是否一直等待线程执行完毕后才会返回
* **特性:**
	* `静态`
* **描述:** 启动一个线程
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main)

##### 火山.基本.线程操作类.启动有状态线程

* **类型:** `全局方法`
* **名称:** `启动有状态线程`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `线程状态对象` (`线程状态类`): 本参数对象将与所启动线程绑定,用作对所启动线程进行相关操作. 如果本参数对象已经与另一线程绑定且该线程处于正在运行状态,本方法将失败返回假.
	* `线程函数` (`线程模板函数2(指定格式方法)`): 提供所欲执行的线程函数
	* `堆栈尺寸` (`整数`, 默认值: `0`): 提供线程所使用的堆栈尺寸,单位字节.为0表示使用默认尺寸.
	* `优先级` (`线程优先级`, 默认值: `线程优先级.通常`): 提供线程的优先级别
* **特性:**
	* `静态`
* **描述:** 启动一个绑定有对应"线程状态类"状态对象的线程
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.线程操作类.取主线程ID

* **类型:** `全局方法`
* **名称:** `取主线程ID`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回当前程序的主线程(即启动线程)ID

##### 火山.基本.线程操作类.取当前线程ID

* **类型:** `全局方法`
* **名称:** `取当前线程ID`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回当前线程的ID值

##### 火山.基本.线程操作类.是否为主线程

* **类型:** `全局方法`
* **名称:** `是否为主线程`
* **返回值数据类型:** `逻辑型`
* **特性:**
	* `静态`
* **描述:** 返回当前线程是否为程序的主线程

##### 火山.基本.线程操作类.取当前进程ID

* **类型:** `全局方法`
* **名称:** `取当前进程ID`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回当前进程的ID值

---

#### 火山.基本.主线程处理器

* **类型:** `类`
* **名称:** `主线程处理器`
* **描述:** 本类用作在其它线程中发送通知消息到程序的主UI线程中处理
* **相关例程:** [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main)

##### 火山.基本.主线程处理器.接收到通知

* **类型:** `事件定义方法`
* **名称:** `接收到通知`
* **返回值数据类型:** `整数`
* **参数:**
	* `通知码` (`变整数`)
	* `参数1` (`变整数`)
	* `参数2` (`变整数`): 如果本事件由"投递通知"方法调用触发,本参数值将始终为0.
* **描述:** 在其它线程中调用本对象的"发送通知"/"投递通知"方法后,本事件将被触发. 本事件的接收方法将始终在程序的UI主线程中执行. 本事件中的参数值为调用"发送通知"/"投递通知"方法时所提供的对应参数值.
* **返回值描述:** 如果本事件由"发送通知"方法调用触发,事件处理方法的返回值将返回到"发送通知"方法的调用方.
* **相关例程:** [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main)

##### 火山.基本.主线程处理器.发送通知

* **类型:** `方法`
* **名称:** `发送通知`
* **返回值数据类型:** `整数`
* **参数:**
	* `通知码` (`变整数`)
	* `参数1` (`变整数`, 默认值: `0`)
	* `参数2` (`变整数`, 默认值: `0`)
* **描述:** 从其它线程发送通知到本对象,本对象的"接收到通知"事件将在程序主线程中触发以处理该通知. 本方法将等待本对象的"接收到通知"事件处理完毕后才会返回.
* **返回值描述:** 返回"接收到通知"事件处理方法的返回值,如果发送通知失败,将返回0(注意即使成功接收到通知,也可能返回0).
* **相关例程:** [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main)

##### 火山.基本.主线程处理器.投递通知

* **类型:** `方法`
* **名称:** `投递通知`
* **参数:**
	* `通知码` (`变整数`)
	* `参数1` (`变整数`, 默认值: `0`)
* **描述:** 从其它线程投递通知到本对象,本对象的"接收到通知"事件将稍后在程序主线程中触发以处理该通知. 本方法调用后会立即返回,并不会等待本对象的"接收到通知"事件处理完毕,因此请确保调用本方法时所提供的参数能够在"接收到通知"事件处理方法中保持有效.

---

#### 火山.基本.高级主线程处理器

* **类型:** `类`
* **名称:** `高级主线程处理器`
* **描述:** 本类用作在其它线程中发送通知消息到程序的主UI线程中处理
* **相关例程:** [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.高级主线程处理器.通知保留时间

* **类型:** `属性读方法`
* **名称:** `通知保留时间`
* **返回值数据类型:** `整数`
* **描述:** 返回被投递(调用"投递通知"方法)通知的最大保留时间(单位毫秒),为0表示永远保留直到投递成功.

##### 火山.基本.高级主线程处理器.通知保留时间

* **类型:** `属性写方法`
* **名称:** `通知保留时间`
* **参数:**
	* `欲设置属性值` (`整数`)
* **描述:** 设置被投递(调用"投递通知"方法)通知的最大保留时间(单位毫秒),超过最大保留时间尚未投递成功的通知将被自动删除,为0表示永远保留直到投递成功. 默认值为1000毫秒.

##### 火山.基本.高级主线程处理器.接收到通知

* **类型:** `事件定义方法`
* **名称:** `接收到通知`
* **返回值数据类型:** `整数`
* **参数:**
	* `通知码` (`变整数`)
	* `参数1` (`变整数`)
	* `参数2` (`变整数`)
	* `参数对象` (`对象包装类`): 包装中为发送/投递通知时所提供对象的复制对象,如果未提供则为空("参数对象.是否为空"方法返回真).
* **描述:** 在其它线程中调用本对象的"发送通知"/"投递通知"方法后,本事件将被触发. 本事件的接收方法将始终在程序的UI主线程中执行. 本事件中的参数值为调用"发送通知"/"投递通知"方法时所提供的对应参数值.
* **返回值描述:** 如果本事件由"发送通知"方法调用触发,事件处理方法的返回值将返回到"发送通知"方法的调用方.
* **相关例程:** [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.高级主线程处理器.发送通知

* **类型:** `方法`
* **名称:** `发送通知`
* **返回值数据类型:** `整数`
* **参数:**
	* `通知码` (`变整数`)
	* `参数1` (`变整数`, 默认值: `0`)
	* `参数2` (`变整数`, 默认值: `0`)
	* `参数对象` (`对象类`, 默认值: `空对象`): 提供欲传递到"接收到通知"事件的"参数对象"参数内容,为空对象表示无.
* **描述:** 从其它线程发送通知到本对象,本对象的"接收到通知"事件将在程序主线程中触发以处理该通知. 本方法将等待本对象的"接收到通知"事件处理完毕后才会返回.
* **返回值描述:** 返回"接收到通知"事件处理方法的返回值,如果发送通知失败,将返回0(注意即使成功接收到通知,也可能返回0).
* **相关例程:** [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.高级主线程处理器.投递通知

* **类型:** `方法`
* **名称:** `投递通知`
* **参数:**
	* `通知码` (`变整数`)
	* `参数1` (`变整数`, 默认值: `0`): 如果本参数为指向外部数据的指针,请确保此数据在"接收到通知"事件触发时依旧有效.
	* `参数2` (`变整数`, 默认值: `0`): 如果本参数为指向外部数据的指针,请确保此数据在"接收到通知"事件触发时依旧有效.
	* `参数对象` (`对象类`, 默认值: `空对象`): 提供欲传递到"接收到通知"事件的"参数对象"参数内容,为空对象表示无. 本参数对象将被自动创建一个同内容复制对象,因此无需保持其一直有效.
* **描述:** 从其它线程投递通知到本对象,本对象的"接收到通知"事件将稍后在程序主线程中触发以处理该通知. 本方法调用后会立即返回,并不会等待本对象的"接收到通知"事件处理完毕. 被投递通知如果在"通知保留时间"属性所指定的时间内未投递成功,将被销毁不再投递.
* **相关例程:** [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main)

---

#### 火山.基本.基本原子类型模板类

* **类型:** `类`
* **名称:** `基本原子类型模板类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **描述:** 本类用作支持在多线程中以原子的方式访问数据(即在同一时间只有一个线程能够访问该数据). 原子模板类. 模板类型1: 值数据类型,仅支持非文本型基本类型实现.

##### 火山.基本.基本原子类型模板类.是否无锁

* **类型:** `属性读方法`
* **名称:** `是否无锁`
* **返回值数据类型:** `逻辑型`
* **描述:** 如果当前原子对象上的原子操作是无锁的,返回真,否则返回假.

##### 火山.基本.基本原子类型模板类.取值

* **类型:** `方法`
* **名称:** `取值`
* **返回值数据类型:** `模板类型1`
* **描述:** 原子取值

##### 火山.基本.基本原子类型模板类.置值

* **类型:** `方法`
* **名称:** `置值`
* **参数:**
	* `欲写入值` (`模板类型1`)
* **描述:** 原子置值

##### 火山.基本.基本原子类型模板类.替换值

* **类型:** `方法`
* **名称:** `替换值`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `新值` (`模板类型1`)
* **描述:** 原子替换当前原子数据的值
* **返回值描述:** 返回被替换之前的值

##### 火山.基本.基本原子类型模板类.加

* **类型:** `方法`
* **名称:** `加`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `加数` (`模板类型1`): 提供加数
* **描述:** 原子加法运算,将当前值与指定加数相加,当前对象中的值替换为运算结果.
* **返回值描述:** 返回运算之前的值

##### 火山.基本.基本原子类型模板类.减

* **类型:** `方法`
* **名称:** `减`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `减数` (`模板类型1`): 提供减数
* **描述:** 原子减法运算,将当前值与指定加数相减,当前对象中的值替换为运算结果.
* **返回值描述:** 返回运算之前的值

##### 火山.基本.基本原子类型模板类.按位与

* **类型:** `方法`
* **名称:** `按位与`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `运算值` (`模板类型1`): 提供所欲与其进行位运算的值
* **描述:** 原子位运算,将当前值的每一位指定值的对应位进行与操作,当前对象中的值替换为运算结果.
* **返回值描述:** 返回运算之前的值

##### 火山.基本.基本原子类型模板类.按位或

* **类型:** `方法`
* **名称:** `按位或`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `运算值` (`模板类型1`): 提供所欲与其进行位运算的值
* **描述:** 原子位运算,将当前值的每一位指定值的对应位进行或操作,当前对象中的值替换为运算结果.
* **返回值描述:** 返回运算之前的值

##### 火山.基本.基本原子类型模板类.按位异或

* **类型:** `方法`
* **名称:** `按位异或`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `运算值` (`模板类型1`): 提供所欲与其进行位运算的值
* **描述:** 原子位运算,将当前值的每一位指定值的对应位进行异或操作,当前对象中的值替换为运算结果.
* **返回值描述:** 返回运算之前的值

##### 火山.基本.基本原子类型模板类.等待值改变

* **类型:** `方法`
* **名称:** `等待值改变`
* **参数:**
	* `旧值` (`模板类型1`)
* **描述:** 阻塞当前线程直到当前原子对象的旧值的原子操作执行完毕.

##### 火山.基本.基本原子类型模板类.比较赋值

* **类型:** `方法`
* **名称:** `比较赋值`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `比较值` (`模板类型1`): 提供所欲与其对比的值,如果当前原子对象中所包含值与该比较值不匹配,新值将不会被赋值.
	* `新值` (`模板类型1`): 提供所欲设置的新值,仅当比较成功(本方法返回真)后会赋新值,否则将丢弃该值.
* **描述:** 提供指定值与当前原子对象中所包含值对比,对比完成后赋一个新值.
* **返回值描述:** 如果原子值与比较值相等返回真,否则返回假.

---

#### 火山.基本.原子字节类

* **类型:** `类`
* **名称:** `原子字节类`
* **模板基础类:** `基本原子类型模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节`

---

#### 火山.基本.原子短整数类

* **类型:** `类`
* **名称:** `原子短整数类`
* **模板基础类:** `基本原子类型模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `短整数`

---

#### 火山.基本.原子字符类

* **类型:** `类`
* **名称:** `原子字符类`
* **模板基础类:** `基本原子类型模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字符`

---

#### 火山.基本.原子整数类

* **类型:** `类`
* **名称:** `原子整数类`
* **模板基础类:** `基本原子类型模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`

---

#### 火山.基本.原子变整数类

* **类型:** `类`
* **名称:** `原子变整数类`
* **模板基础类:** `基本原子类型模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `变整数`

---

#### 火山.基本.原子长整数类

* **类型:** `类`
* **名称:** `原子长整数类`
* **模板基础类:** `基本原子类型模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `长整数`

---

#### 火山.基本.原子单精度小数类

* **类型:** `类`
* **名称:** `原子单精度小数类`
* **模板基础类:** `基本原子类型模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `单精度小数`

---

#### 火山.基本.原子小数类

* **类型:** `类`
* **名称:** `原子小数类`
* **模板基础类:** `基本原子类型模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `小数`

---

#### 火山.基本.原子逻辑型类

* **类型:** `类`
* **名称:** `原子逻辑型类`
* **模板基础类:** `基本原子类型模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `逻辑型`

---

#### 火山.基本.线程类

* **类型:** `类`
* **名称:** `线程类`
* **基础类:** `参考对象类`
* **描述:** 用作封装一个单独的线程. 注意: 当本类对象被销毁(譬如离开其作用域)时,将自动调用本对象的"停止"方法通知本对象中的线程结束运行并等待对应的"线程运行"事件处理方法执行完毕.如果此时对应的"线程运行"事件处理方法中没有及时检查处理本对象的"是否需要退出"方法,程序将进入死锁状态.
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.线程类.线程运行

* **类型:** `事件定义方法`
* **名称:** `线程运行`
* **返回值数据类型:** `整数`
* **描述:** 用户需要接收并处理本事件以执行所需要的功能,该事件处理方法将在一个单独的线程中运行. 注意: 1. 在本事件的接收处理方法中,必须尽可能快地频繁调用本对象的"是否需要退出"方法,一旦发现该方法返回真,则需要尽快结束执行并返回,否则将导致另一线程中的"停止"方法调用进入死等状态; 2. 在本事件的接收处理方法中不允许对窗口界面直接进行操作,否则可能导致死锁.
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.线程类.启动

* **类型:** `方法`
* **名称:** `启动`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `堆栈尺寸` (`整数`, 默认值: `0`): 提供线程所使用的堆栈尺寸,单位字节.为0表示使用默认尺寸.
* **描述:** 启动本对象中的线程,开始执行其"线程运行"事件的处理方法. 如果线程当前正在运行,将会直接返回真.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.线程类.是否正在运行

* **类型:** `方法`
* **名称:** `是否正在运行`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本对象中的线程是否处于正在运行状态

##### 火山.基本.线程类.停止

* **类型:** `方法`
* **名称:** `停止`
* **描述:** 本方法只能在本对象中线程以外的线程(譬如主线程)中执行,用作通知并等待本对象的对应"线程运行"事件处理方法执行完毕退出. 为了支持本方法,本对象的对应"线程运行"事件处理方法中必须尽可能快地频繁调用本对象的"是否需要退出"方法,一旦发现该方法返回真,则需要尽快结束执行并返回,否则本方法将进入死等状态.
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main)

##### 火山.基本.线程类.通知停止

* **类型:** `方法`
* **名称:** `通知停止`
* **描述:** 本方法只能在本对象中线程以外的线程(譬如主线程)中执行,用作通知本对象的对应"线程运行"事件处理方法执行完毕退出. 本方法与"停止"方法不同之处在于,本方法仅仅发出退出通知而不会一直等待其退出.

##### 火山.基本.线程类.是否需要退出

* **类型:** `方法`
* **名称:** `是否需要退出`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `最大检查等待时间` (`整数`, 默认值: `10`): 指定检查线程退出通知(由"停止"或"通知停止"方法发出)的最大等待 时间(单位毫秒),为0表示不等待,为-1表示一直等待.
* **描述:** 本方法只能在本对象的线程(即对应"线程运行"事件处理方法)中执行,一旦发现本方法返回真,必须尽快结束"线程运行"事件处理方法的执行并返回,否则将导致另一线程中的"停止"方法调用进入死等状态.
* **返回值描述:** 返回线程是否需要尽快退出
* **相关例程:** [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main)

---

#### 火山.基本.全局线程池

* **类型:** `类`
* **名称:** `全局线程池`
* **描述:** 用作提供对全局线程池的相关操作. 注意本类中的方法除了"是否需要退出"均只能在主线程中执行.
* **相关例程:** [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main)

##### 火山.基本.全局线程池.置最多空闲线程数

* **类型:** `方法`
* **名称:** `置最多空闲线程数`
* **参数:**
	* `最多空闲线程数` (`整数`): 提供最多能同时保留的空闲线程数目,为0表示使用默认值(根据计算机中当前CPU计算核心的数目自动选择).
* **特性:**
	* `静态`
* **描述:** 设置最多能同时保留的空闲线程数目,超出所指定数目的空闲线程将被释放. 注意本方法只能在主线程中执行.
* **相关例程:** [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main)

##### 火山.基本.全局线程池.置最大允许空闲时间

* **类型:** `方法`
* **名称:** `置最大允许空闲时间`
* **参数:**
	* `最大允许空闲时间` (`整数`): 提供线程最大允许空闲时间(单位毫秒),为0表示使用默认值16000毫秒.
* **特性:**
	* `静态`
* **描述:** 设置线程最大允许空闲时间(单位毫秒),超出所指定时间的空闲线程将被释放. 注意本方法只能在主线程中执行.

##### 火山.基本.全局线程池.更新

* **类型:** `方法`
* **名称:** `更新`
* **参数:**
	* `是否立即更新` (`逻辑型`, 默认值: `真`): 为真立即更新,为假则首先检查距上次更新是否超过了所指定时间,如已经超过则更新,未超过则不更新. 在系统空闲时手动调用本方法时可以提供为假,以避免过于频繁地操作.
* **特性:**
	* `静态`
* **描述:** 更新线程池,可以在需要时手动调用本方法进行更新. 线程池更新时主要做以下工作: 1. 检查删除线程池中所有超出最大空闲时间的线程; 2. 检查删除线程池中所保留的过多数目空闲线程. 本方法调用不是必需的,对于MFC/WTL界面应用程序,系统会自动在系统空闲时调用本方法. 注意本方法只能在主线程中执行.

##### 火山.基本.全局线程池.清理

* **类型:** `方法`
* **名称:** `清理`
* **特性:**
	* `静态`
* **描述:** 清理线程池的内容,停止并销毁本线程池中的所有线程(包括正在运行或空闲的线程). 注意本方法只能在主线程中执行.

##### 火山.基本.全局线程池.启动线程

* **类型:** `方法`
* **名称:** `启动线程`
* **返回值数据类型:** `变整数`
* **参数:**
	* `线程函数` (`线程模板函数(指定格式方法)`): 提供所欲执行的用户线程函数. 注意: 1. 在该用户线程函数中,必须尽可能快地频繁调用本对象的"是否需要退出"方法,一旦发现该方法返回真,则需要尽快结束执行并返回,否则将导致另一线程中的"停止"方法调用进入死等状态; 2. 在该用户线程函数中不允许对窗口界面直接进行操作,否则可能导致死锁.
	* `用户参数1` (`变整数`, 默认值: `0`): 提供传递到用户线程函数的用户参数值1
	* `用户参数2` (`变整数`, 默认值: `0`): 提供传递到用户线程函数的用户参数值2
* **特性:**
	* `静态`
* **描述:** 创建并启动一个新线程,该线程会优先从线程池的空闲线程中提取使用. 注意: 1. 在所提供用户线程函数执行完毕后,该线程将会被自动释放进线程池中,此时对应句柄值将自然永久失效; 2. 如果所提供用户线程函数启动后一直在执行,可以调用"停止线程"方法通知用户线程函数停止执行. 3. 本方法只能在主线程中执行.
* **返回值描述:** 成功返回所创建线程的非0句柄值,失败返回0.

##### 火山.基本.全局线程池.停止线程

* **类型:** `方法`
* **名称:** `停止线程`
* **参数:**
	* `线程句柄` (`变整数`): 提供所欲停止的由"启动线程"方法返回的线程句柄值.如果该句柄值为0或已经自然失效,将返回不进行任何处理.
* **特性:**
	* `静态`
* **描述:** 等待所指定线程的用户线程函数执行完毕,然后将该线程放进线程池用作以后使用. 注意本方法只能在主线程中执行.

##### 火山.基本.全局线程池.是否正在运行

* **类型:** `方法`
* **名称:** `是否正在运行`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `线程句柄` (`变整数`): 提供所欲检查的由"启动线程"方法返回的线程句柄值.如果该句柄值为0或已经自然失效,将返回假.
* **特性:**
	* `静态`
* **描述:** 返回所指定线程是否正在运行. 注意本方法只能在主线程中执行.

##### 火山.基本.全局线程池.是否需要退出

* **类型:** `方法`
* **名称:** `是否需要退出`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `线程句柄` (`变整数`): 提供由"启动线程"方法返回的线程句柄值.如果该句柄值为0或已经自然失效,本方法将始终返回真.
	* `最大检查等待时间` (`整数`, 默认值: `10`): 指定检查线程是否需要退出的最大等待时间(单位毫秒),为0表示不等待,为-1表示一直等待.
* **特性:**
	* `静态`
* **描述:** 本方法只能在"启动线程"方法所启动线程的用户线程函数中执行,一旦发现本方法返回真,用户线程函数必须尽快结束执行并返回,否则将导致程序卡死.
* **返回值描述:** 返回线程是否需要尽快退出

##### 火山.基本.全局线程池.取调试展示内容

* **类型:** `方法`
* **名称:** `取调试展示内容`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 将全局线程池中的当前内容用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用. 本方法仅在调试版本中具有作用,非调试版本将返回空文本. 注意本方法只能在主线程中执行.
* **相关例程:** [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main)

##### 火山.基本.全局线程池.启用调试跟踪

* **类型:** `方法`
* **名称:** `启用调试跟踪`
* **特性:**
	* `静态`
* **描述:** 在对全局线程池进行操作时,调用本方法以在调试版本下启用即时在火山开发环境调试窗口中显示相关操作跟踪信息.
* **相关例程:** [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main)

---

#### 火山.基本.缓存线程类

* **类型:** `类`
* **名称:** `缓存线程类`
* **基础类:** `参考对象类`
* **描述:** 支持自动在全局线程池中缓存的线程. 注意: 1. 当调用"启动"方法的本类对象被销毁(譬如离开其作用域)时,将自动调用本对象的"停止"方法通知本对象中的线程结束运行并等待对应的"线程运行"事件处理方法执行完毕.如果此时对应的"线程运行"事件处理方法中没有及时检查处理本对象的"是否需要退出"方法,程序将进入死锁状态; 2. 本类中的方法除了"是否需要退出"均只能在主线程中执行.
* **相关例程:** [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main)

##### 火山.基本.缓存线程类.线程运行

* **类型:** `事件定义方法`
* **名称:** `线程运行`
* **返回值数据类型:** `整数`
* **参数:**
	* `线程句柄` (`变整数`): 提供所启动线程在线程池中的句柄值,必定不为0.
	* `用户参数` (`变整数`): 提供启动时传递到线程函数的用户参数值
	* `退出事件` (`变整数`): 本参数普通用户无需使用
* **描述:** 用户需要接收并处理本事件以执行所需要的功能,该事件处理方法将在一个单独的线程中运行. 注意: 1. 在本事件的接收处理方法中,必须尽可能快地频繁调用本对象的"是否需要退出"方法,一旦发现该方法返回真,则需要尽快结束执行并返回,否则将导致另一线程中的"停止"方法调用进入死等状态; 2. 在本事件的接收处理方法中不允许对窗口界面直接进行操作,否则可能导致死锁.
* **相关例程:** [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main)

##### 火山.基本.缓存线程类.启动

* **类型:** `方法`
* **名称:** `启动`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `用户参数` (`变整数`, 默认值: `0`): 提供传递到"线程运行"事件方法的用户参数值
* **描述:** 启动本对象中的线程,开始执行其"线程运行"事件的处理方法.如果线程当前正在运行,将会将其先停止. 注意本方法只能在主线程中执行.
* **返回值描述:** 成功返回真,失败返回假.
* **相关例程:** [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main)

##### 火山.基本.缓存线程类.停止

* **类型:** `方法`
* **名称:** `停止`
* **描述:** 通知并等待本对象的对应"线程运行"事件处理方法执行完毕退出. 为了支持本方法,本对象的对应"线程运行"事件处理方法中必须尽可能快地频繁调用本对象的"是否需要退出"方法,一旦发现该方法返回真,则需要尽快结束执行并返回,否则本方法将进入死等状态. 注意本方法只能在主线程中执行.

##### 火山.基本.缓存线程类.是否正在运行

* **类型:** `方法`
* **名称:** `是否正在运行`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本对象的线程是否正在运行. 注意本方法只能在主线程中执行.

##### 火山.基本.缓存线程类.是否需要退出

* **类型:** `方法`
* **名称:** `是否需要退出`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `线程句柄` (`变整数`): 需要提供在"线程运行"事件中提供过来的"线程句柄"参数值
	* `最大检查等待时间` (`整数`, 默认值: `10`): 指定检查线程退出通知(由"停止"方法发出)的最大等待时间(单位毫秒),为0表示不等待,为-1表示一直等待.
* **特性:**
	* `静态`
* **描述:** 本方法只能在本对象的线程(即对应"线程运行"事件处理方法)中执行,一旦发现本方法返回真,必须尽快结束"线程运行"事件处理方法的执行并返回,否则将导致另一线程中的"停止"方法调用进入死等状态.
* **返回值描述:** 返回线程是否需要尽快退出
* **相关例程:** [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main)

---

#### 火山.基本.基本火山异常类

* **类型:** `类`
* **名称:** `基本火山异常类`
* **描述:** 为所有火山异常类的最基础类

##### 火山.基本.基本火山异常类.异常代码

* **类型:** `属性读方法`
* **名称:** `异常代码`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的本对象` (`基本火山异常类`)
* **特性:**
	* `静态`
* **描述:** 返回当前异常代码: 等于0表示无异常; 小于0表示为系统异常; 大于0表示为用户异常.

##### 火山.基本.基本火山异常类.异常描述

* **类型:** `属性读方法`
* **名称:** `异常描述`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的本对象` (`基本火山异常类`)
* **特性:**
	* `静态`
* **描述:** 返回有关当前异常的具体描述文本

---

#### 火山.基本.异常管理

* **类型:** `类`
* **名称:** `异常管理`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **描述:** 提供异常管理机制

##### 火山.基本.异常管理.开始俘获异常

* **类型:** `全局方法`
* **名称:** `开始俘获异常`
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
	* 本方法调用语句后方必须为以下任一方法的调用语句: [俘获异常](#火山.基本.异常管理.俘获异常), [俘获火山异常](#火山.基本.异常管理.俘获火山异常), [俘获所有异常](#火山.基本.异常管理.俘获所有异常)
* **描述:** 开始俘获异常

##### 火山.基本.异常管理.俘获异常

* **类型:** `全局方法`
* **名称:** `俘获异常`
* **参数:**
	* `欲俘获异常类型` (`通用型(需求:数据类型)`): 提供用作匹配"抛出异常"方法所抛出数据的数据类型,只有数据类型匹配时,所对应的异常才能被俘获到. 提示: 基础类能够匹配所有继承类. 在本方法调用语句的子语句块中,可以通过调用"取被俘获异常数据"方法来获得具体所抛出的异常数据.
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
	* 本方法调用语句前方必须为以下任一方法的调用语句: [开始俘获异常](#火山.基本.异常管理.开始俘获异常), [俘获异常](#火山.基本.异常管理.俘获异常), [俘获火山异常](#火山.基本.异常管理.俘获火山异常)
* **描述:** 俘获所抛出异常数据为指定数据类型的异常

##### 火山.基本.异常管理.取被俘获异常数据

* **类型:** `全局方法`
* **名称:** `取被俘获异常数据`
* **返回值数据类型:** `调用本方法时为"所俘获异常类型"参数所提供数据的实际类型`
* **参数:**
	* `所俘获异常类型` (`通用型(需求:数据类型)`): 提供所俘获数据的数据类型,必须与所属"俘获异常"方法调用父语句中指定的数据类型一致.
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [俘获异常](#火山.基本.异常管理.俘获异常)
* **描述:** 本方法只能在"俘获异常"方法调用语句的子语句体中使用,用作取回所俘获的具体异常数据.

##### 火山.基本.异常管理.俘获火山异常

* **类型:** `全局方法`
* **名称:** `俘获火山异常`
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
	* 本方法调用语句前方必须为以下任一方法的调用语句: [开始俘获异常](#火山.基本.异常管理.开始俘获异常), [俘获异常](#火山.基本.异常管理.俘获异常)
* **描述:** 俘获所抛出的火山异常对象

##### 火山.基本.异常管理.取被俘获火山异常

* **类型:** `全局方法`
* **名称:** `取被俘获火山异常`
* **返回值数据类型:** `基本火山异常类`
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [俘获火山异常](#火山.基本.异常管理.俘获火山异常)
* **描述:** 本方法只能在"俘获火山异常"方法调用语句的子语句体中使用,用作取回所俘获的具体异常对象.

##### 火山.基本.异常管理.俘获所有异常

* **类型:** `全局方法`
* **名称:** `俘获所有异常`
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
	* 本方法调用语句前方必须为以下任一方法的调用语句: [开始俘获异常](#火山.基本.异常管理.开始俘获异常), [俘获火山异常](#火山.基本.异常管理.俘获火山异常), [俘获异常](#火山.基本.异常管理.俘获异常)
* **描述:** 俘获任何异常,匹配所有异常数据的数据类型.

##### 火山.基本.异常管理.抛出异常

* **类型:** `全局方法`
* **名称:** `抛出异常`
* **参数:**
	* `所抛出数据` (`通用型`): 提供欲抛出的异常数据,该数据可以在匹配其数据类型的"俘获异常"方法调用语句的子语句块中调用"取被俘获异常数据"获得. 注意: 该数据也可以为火山异常类对象
* **特性:**
	* `静态`
* **描述:** 抛出一个携带所指定数据的异常

##### 火山.基本.异常管理.抛出火山异常

* **类型:** `全局方法`
* **名称:** `抛出火山异常`
* **参数:**
	* `异常代码` (`整数`): 提供具体的异常代码值,应该大于0,因为小于0的值被系统保留使用.
	* `描述文本` (`文本型`, 默认值: `""`): 提供异常的具体描述文本
* **特性:**
	* `静态`
* **描述:** 抛出一个基本火山异常对象

##### 火山.基本.异常管理.再次抛出异常

* **类型:** `全局方法`
* **名称:** `再次抛出异常`
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [俘获异常](#火山.基本.异常管理.俘获异常), [俘获火山异常](#火山.基本.异常管理.俘获火山异常), [俘获所有异常](#火山.基本.异常管理.俘获所有异常)
* **描述:** 将所俘获到的异常再次抛出,本方法必须在"俘获异常"/"俘获火山异常"/"俘获所有异常"的子语句块中使用.

---

#### 火山.基本.BASE64编码方式

* **类型:** `类`
* **名称:** `BASE64编码方式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `字节集操作.辅助类`
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main)

##### 火山.基本.BASE64编码方式.标准

* **类型:** `成员常量`
* **名称:** `标准`
* **数据类型:** `BASE64编码方式`
* **初始值:** `0`
* **描述:** 标准Base64编码格式
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main)

##### 火山.基本.BASE64编码方式.URL专用

* **类型:** `成员常量`
* **名称:** `URL专用`
* **数据类型:** `BASE64编码方式`
* **初始值:** `1`
* **描述:** URL专用的Base64编码格式
* **相关例程:** [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main)

##### 火山.基本.BASE64编码方式.正则专用

* **类型:** `成员常量`
* **名称:** `正则专用`
* **数据类型:** `BASE64编码方式`
* **初始值:** `2`
* **描述:** 正则表达式专用的Base64编码格式

---

#### 火山.基本.字节集类

* **类型:** `类`
* **名称:** `字节集类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `字节集操作`
* **描述:** 用作保存一段字节数据的字节集类
* **相关例程:** [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-空对象测试-null_object_test-main](#vol-空对象测试-null_object_test-main), [vol-位图处理-adv_bitmap-main](#vol-位图处理-adv_bitmap-main), [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-程序崩溃回调-breakpad-main](#vol-程序崩溃回调-breakpad-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-被调用动态链接库-dll_test-main](#vol-被调用动态链接库-dll_test-main), [vol-调用动态链接库-dll_call-main](#vol-调用动态链接库-dll_call-main), [vol-被调用部件动态链接库-com_dll-main](#vol-被调用部件动态链接库-com_dll-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-串口通讯-cserialport-main](#vol-串口通讯-cserialport-main), [vol-摄像头操作-directshow-main](#vol-摄像头操作-directshow-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-数据报-udp-main](#vol-数据报-udp-main), [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main), [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-elk微型js引擎-elk_js-main](#vol-elk微型js引擎-elk_js-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-wav播放-wav_play-main](#vol-wav播放-wav_play-main), [vol-人脸性别识别-gender_recognition-main](#vol-人脸性别识别-gender_recognition-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main)

##### 火山.基本.字节集类.取字节集预分配尺寸

* **类型:** `全局方法`
* **名称:** `取字节集预分配尺寸`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 返回本字节集为了快速进行数据的添加/删除处理使用的空间分配尺寸,每次字节集需要调整其空间大小时,都使用本属性值作为空间调整基准尺寸.值越大,批量加入/删除数据时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.置字节集预分配尺寸

* **类型:** `全局方法`
* **名称:** `置字节集预分配尺寸`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲设置的预分配尺寸` (`整数`): 提供所欲设置的预分配尺寸,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 设置本字节集为了快速进行数据的添加/删除处理使用的空间分配尺寸,每次字节集需要调整其空间大小时,都使用本属性值作为空间调整基准尺寸.值越大,批量加入/删除数据时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.到字节集

* **类型:** `全局方法`
* **名称:** `到字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲转换的数据` (`通用基本型`)
* **特性:**
	* `静态`
* **描述:** 根据所指定基本数据类型数据生成并返回对应的字节集. 注意: 如果是文本型数据,其尾部的结束零字符不会被加入.
* **相关例程:** [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main)

##### 火山.基本.字节集类.创建字节集

* **类型:** `全局方法`
* **名称:** `创建字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `字节数值` (`整数`, `可扩展`): 提供所欲加入的所有字节值,注意所提供值必须在0到255之间.
* **特性:**
	* `静态`
* **描述:** 根据所提供的一系列整数字节值建立并返回一个字节集对象
* **相关例程:** [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-被调用部件动态链接库-com_dll-main](#vol-被调用部件动态链接库-com_dll-main)

##### 火山.基本.字节集类.组合字节集

* **类型:** `全局方法`
* **名称:** `组合字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `欲组合的所有数据` (`通用型`, `可扩展`): 提供所欲组合的所有数据,可以为基本数据类型或字节集类数据.
* **特性:**
	* `静态`
* **描述:** 将所提供的一系列数据组合起来建立并返回一个字节集对象

##### 火山.基本.字节集类.添加字节集内容

* **类型:** `全局方法`
* **名称:** `添加字节集内容`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `字节数值` (`整数`, `可扩展`): 提供所欲添加的所有字节值,注意所提供值必须在0到255之间.
* **特性:**
	* `静态`
* **描述:** 将所提供的一系列整数字节值添加到本字节集对象现有内容的尾部

##### 火山.基本.字节集类.数组到字节集

* **类型:** `全局方法`
* **名称:** `数组到字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲转换的数据` (`通用非文本基本型数组`)
* **特性:**
	* `静态`
* **描述:** 根据所指定非文本基本数据类型数组数据生成并返回对应的字节集

##### 火山.基本.字节集类.指针到字节集

* **类型:** `全局方法`
* **名称:** `指针到字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `数据指针` (`变整数`): 指向欲加入数据的指针值
	* `数据尺寸` (`整数`): 提供所欲加入数据的尺寸(单位字节),必须确保指针所指向地址处尺寸 为本参数值的地址空间有效.
* **特性:**
	* `静态`
* **描述:** 根据所指定指针处的数据建立并返回一个对应的字节集对象. 除非必要且对指针概念有透彻的了解,不要使用本方法.
* **相关例程:** [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-摄像头操作-directshow-main](#vol-摄像头操作-directshow-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main)

##### 火山.基本.字节集类.字节集内容是否相同

* **类型:** `全局方法`
* **名称:** `字节集内容是否相同`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `字节集1` (`字节集类`)
	* `字节集2` (`字节集类`)
* **特性:**
	* `静态`
* **描述:** 判断两个字节集的内容是否相同. 注: 调用"对象内容是否相同"方法是同样的效果.

##### 火山.基本.字节集类.文件资源到字节集

* **类型:** `全局方法`
* **名称:** `文件资源到字节集`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲载入的数据资源` (`视窗文件资源`): 用作提供所欲载入的RCDATA类型资源,如果为"空资源.空文件",将返回空字节集.
	* `所欲写出到的字节集` (`字节集类`): 用作接收所载入的资源数据,其中的原有内容将被覆盖.
* **特性:**
	* `静态`
* **描述:** 载入所指定的字节集数据资源,返回是否载入成功.
* **相关例程:** [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main)

##### 火山.基本.字节集类.取字节集左边

* **类型:** `全局方法`
* **名称:** `取字节集左边`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `欲取出字节的数目` (`整数`): 提供欲取出字节的数目,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 返回一个字节集,其中包含指定字节集中从左边算起指定数量的字节.

##### 火山.基本.字节集类.取字节集右边

* **类型:** `全局方法`
* **名称:** `取字节集右边`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `欲取出字节的数目` (`整数`): 提供欲取出字节的数目,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 返回一个字节集,其中包含指定字节集中从右边算起指定数量的字节.
* **相关例程:** [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main)

##### 火山.基本.字节集类.取字节集中间

* **类型:** `全局方法`
* **名称:** `取字节集中间`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `起始取出索引位置` (`整数`): 提供所欲取出的首字节在字节集中的偏移位置,必须大于等于0且小于等于字节集长度.
	* `欲取出字节的数目` (`整数`): 提供欲取出字节的数目,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 返回一个字节集,其中包含指定字节集中从指定位置算起指定数量的字节.

##### 火山.基本.字节集类.分配字节集

* **类型:** `全局方法`
* **名称:** `分配字节集`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲分配空间尺寸` (`整数`): 提供所欲分配的数据内容空间尺寸,必须大于等于0.
	* `是否清零` (`逻辑型`, 默认值: `真`): 是否将所分配的内容空间清除为字节值零. 如果本参数值为假,所分配的字节集内容空间将为随机值.
* **特性:**
	* `静态`
* **描述:** 为本字节集分配所指定尺寸的数据内容空间,其中的原有内容将被覆盖.
* **返回值描述:** 返回所分配字节集内容空间的指针值.除非必要且对指针概念有透彻的了解,不要使用该返回值.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.重分配字节集

* **类型:** `全局方法`
* **名称:** `重分配字节集`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲重分配空间尺寸` (`整数`): 提供所欲重新分配的数据内容空间尺寸,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 为本字节集重新分配所指定尺寸的数据内容空间. 与"分配字节集"不同的是: 位于重分配空间中的字节集原有数据内容将被保留不受影响.如果相比先前尺寸存在多余部分,该部分将为随机值.如果相比先前尺寸更小,则原有尾部数据内容将会被剪切掉.
* **返回值描述:** 返回重分配字节集数据内容空间后的指针值.除非必要且对指针概念有透彻的了解,不要使用该返回值.

##### 火山.基本.字节集类.释放字节集

* **类型:** `全局方法`
* **名称:** `释放字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 删除本字节集中的所有当前内容,并释放所占用的对应内存空间. 本方法调用后,本字节集的长度将为0.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.清空字节集

* **类型:** `全局方法`
* **名称:** `清空字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 删除本字节集中的所有当前内容,与"释放字节集"不同的是本方法并不立即释放所占用的对应内存空间. 如果后面会继续使用本字节集,使用本方法清空字节集内容可以避免频繁分配/释放所占用的内存空间,加快处理速度. 本方法调用后,本字节集的长度将为0.
* **相关例程:** [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main)

##### 火山.基本.字节集类.取字节集指针

* **类型:** `全局方法`
* **名称:** `取字节集指针`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 返回当前字节集数据内容的指针值,如果当前字节集内容为空,将返回0. 除非必要且对指针概念有透彻的了解,不要使用本方法.
* **相关例程:** [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.取字节集尾指针

* **类型:** `全局方法`
* **名称:** `取字节集尾指针`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 返回当前字节集数据内容的尾部指针值(最后一个字节后面),如果当前字节集内容为空,将返回0. 除非必要且对指针概念有透彻的了解,不要使用本方法.

##### 火山.基本.字节集类.为字节集尾字符

* **类型:** `全局方法`
* **名称:** `为字节集尾字符`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲检测的字符` (`字符`): 提供所欲检测的字符值
* **特性:**
	* `静态`
* **描述:** 返回位于当前字节集尾部的字符是否为所指定的字符. 如果当前字节集的尺寸比一个字符的尺寸小,将直接返回假.

##### 火山.基本.字节集类.指针数据位于字节集

* **类型:** `全局方法`
* **名称:** `指针数据位于字节集`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `数据指针` (`变整数`): 指向欲检测的指针值
	* `数据尺寸` (`整数`): 提供所欲检测的数据尺寸(单位字节)
* **特性:**
	* `静态`
* **描述:** 返回指针所指向的指定尺寸数据是否全部位于本字节集内

##### 火山.基本.字节集类.偏移数据位于字节集

* **类型:** `全局方法`
* **名称:** `偏移数据位于字节集`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `数据偏移` (`整数`): 指向欲检测的数据偏移位置值
	* `数据尺寸` (`整数`): 提供所欲检测的数据尺寸(单位字节)
* **特性:**
	* `静态`
* **描述:** 返回所指定偏移位置处的指定尺寸数据是否全部位于本字节集内

##### 火山.基本.字节集类.取字节集长度

* **类型:** `全局方法`
* **名称:** `取字节集长度`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 返回本字节集中已有数据内容的尺寸(单位字节)
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-被调用动态链接库-dll_test-main](#vol-被调用动态链接库-dll_test-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-elk微型js引擎-elk_js-main](#vol-elk微型js引擎-elk_js-main)

##### 火山.基本.字节集类.取字节集值数目

* **类型:** `全局方法`
* **名称:** `取字节集值数目`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲检查的数据类型` (`通用基本型(需求:数据类型)`): 提供所欲获取其存在数目的数据类型. 注意: 如果为文本型,则固定返回0.
* **特性:**
	* `静态`
* **描述:** 返回字节集中包含所指定基本数据类型数据值的数目

##### 火山.基本.字节集类.取字节集单精度小数数目

* **类型:** `全局方法`
* **名称:** `取字节集单精度小数数目`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 返回字节集中包含单精度小数值的数目

##### 火山.基本.字节集类.字节集是否为空

* **类型:** `全局方法`
* **名称:** `字节集是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 返回当前字节集的数据内容是否为空
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.寻找字节集

* **类型:** `全局方法`
* **名称:** `寻找字节集`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲查找的字节集` (`字节集类`): 提供所欲查找的字节集内容
	* `起始查找位置` (`整数`, 默认值: `0`): 提供起始查找偏移位置,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 返回所指定字节集在本字节集中最先出现的偏移位置,如果未找到则返回-1.

##### 火山.基本.字节集类.倒找字节集

* **类型:** `全局方法`
* **名称:** `倒找字节集`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲查找的字节集` (`字节集类`): 提供所欲查找的字节集内容
	* `起始查找位置` (`整数`, 默认值: `数值范围.最大整数值`): 提供起始查找偏移位置,如果超出当前字节集的尺寸,则从当前字节集的尾部开始. 必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 返回所指定字节集在本字节集中最后出现的偏移位置,如果未找到则返回-1.

##### 火山.基本.字节集类.分割字节集

* **类型:** `全局方法`
* **名称:** `分割字节集`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `用作分割的字节集` (`字节集类`): 本方法将基于此字节集内容对本字节集进行分割
	* `结果存放字节集数组` (`字节集数组类`): 用作存放所获得的子字节集对象,其中原有内容将被清空.
	* `欲返回子字节集数目` (`整数`, 默认值: `0`): 提供所欲返回子字节集的最大数目,为0表示返回全部被分割后的子字节集.
* **特性:**
	* `静态`
* **描述:** 将本字节集进行分割,将分割后的所有子字节集存放入"结果存放字节集数组"参数所指定的数组对象中,返回所存放进去的子字节集对象数目.

##### 火山.基本.字节集类.从文件读字节集

* **类型:** `全局方法`
* **名称:** `从文件读字节集`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲读取文件名` (`文本型`): 提供所欲读取文件的路径名称
	* `所欲读取数据尺寸` (`整数`, 默认值: `-1`): 提供所欲读取数据的尺寸,为-1表示全部读取.
* **特性:**
	* `静态`
* **描述:** 从所指定路径文件中读入指定尺寸的数据,成功返回所实际读入数据尺寸,失败返回-1.
* **相关例程:** [vol-wav播放-wav_play-main](#vol-wav播放-wav_play-main)

##### 火山.基本.字节集类.写字节集到文件

* **类型:** `全局方法`
* **名称:** `写字节集到文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲写到文件名` (`文本型`): 提供所欲写到文件的路径名称
	* `所欲写出数据尺寸` (`整数`, 默认值: `-1`): 提供所欲写出数据的尺寸,为-1表示全部写出.
* **特性:**
	* `静态`
* **描述:** 将本字节集的内容写入到所指定路径的文件中,返回是否写出成功.

##### 火山.基本.字节集类.取空白字节集

* **类型:** `全局方法`
* **名称:** `取空白字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `零字节数目` (`整数`): 指定所欲重置为的零字节数目,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 返回具有所指定次数的零字节值重复数据的字节集
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.字节集类.取重复字节集

* **类型:** `全局方法`
* **名称:** `取重复字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `待重复的字节集` (`字节集类`): 提供所欲重复添加的字节集
	* `重复次数` (`整数`): 提供重复添加的次数
* **特性:**
	* `静态`
* **描述:** 返回具有所指定次数的指定字节集重复数据的字节集

##### 火山.基本.字节集类.清零字节集

* **类型:** `全局方法`
* **名称:** `清零字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 将本字节集的当前数据内容全部清除为字节值零
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.字节集替换

* **类型:** `全局方法`
* **名称:** `字节集替换`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `起始替换位置` (`整数`): 提供被替换内容的起始偏移位置,必须大于等于0且小于等于字节集长度.
	* `替换尺寸` (`整数`): 提供具体的替换尺寸,单位字节,必须大于等于0.
	* `用作替换的字节集` (`字节集类`): 提供用来替换本字节集所指定部分内容的字节集
* **特性:**
	* `静态`
* **描述:** 将本字节集的某一部分用其它的字节集替换

##### 火山.基本.字节集类.指针字节集替换

* **类型:** `全局方法`
* **名称:** `指针字节集替换`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `起始替换位置` (`整数`): 提供被替换内容的起始偏移位置,必须大于等于0.
	* `替换尺寸` (`整数`): 提供具体的替换尺寸,单位字节,必须大于等于0.
	* `用作替换数据的指针` (`变整数`): 指向用来替换本字节集所指定部分内容的数据地址
	* `用作替换数据的尺寸` (`整数`): 提供替换数据的尺寸,调用方必须确保所指定指针指向地址处尺寸为本参数值的内容空间可读.
* **特性:**
	* `静态`
* **描述:** 将本字节集的某一部分用指针所指向的数据替换. 除非必要且对指针概念有透彻的了解,不要使用本方法.

##### 火山.基本.字节集类.子字节集替换

* **类型:** `全局方法`
* **名称:** `子字节集替换`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `欲被替换的子字节集` (`字节集类`): 提供所欲被替换的字节集内容,本字节集中的所有此内容将被替换.
	* `用作替换的子字节集` (`字节集类`): 提供用作替换的字节集内容
	* `进行替换的起始位置` (`整数`, 默认值: `0`): 提供被替换子字节集的起始搜索位置,必须大于等于0.
	* `替换进行的次数` (`整数`, 默认值: `0`): 提供欲进行替换的次数,为0表示进行所有可能的替换.
* **特性:**
	* `静态`
* **描述:** 将本字节集中为指定子字节集的内容替换成另一子字节集所指定的内容

##### 火山.基本.字节集类.取字节集数据

* **类型:** `全局方法`
* **名称:** `取字节集数据`
* **返回值数据类型:** `调用本方法时为"所欲获取数据的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `数据偏移位置` (`整数`, 默认值: `0`): 提供所欲获取数据在本字节集中的偏移位置,必须大于等于0.
	* `所欲获取数据的类型` (`通用基本型(需求:数据类型)`): 提供所欲获取数据的数据类型
* **特性:**
	* `静态`
* **描述:** 取出字节集中指定位置指定数据类型的数据
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-被调用动态链接库-dll_test-main](#vol-被调用动态链接库-dll_test-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-redis-redis-main](#vol-redis-redis-main)

##### 火山.基本.字节集类.置字节集值

* **类型:** `全局方法`
* **名称:** `置字节集值`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `数据偏移位置` (`整数`, 默认值: `0`): 提供所欲设置数据在本字节集中的偏移位置,必须大于等于0.
	* `所欲设置的值` (`通用非文本基本型`): 提供具体所欲设置的值,如欲明确指定其数据类型,可以使用强制类型转换操作符.
* **特性:**
	* `静态`
* **描述:** 设置字节集中指定位置处的指定数据类型值
* **相关例程:** [vol-程序崩溃回调-breakpad-main](#vol-程序崩溃回调-breakpad-main)

##### 火山.基本.字节集类.取字节集小数

* **类型:** `全局方法`
* **名称:** `取字节集小数`
* **返回值数据类型:** `小数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `数据偏移位置` (`整数`, 默认值: `0`): 提供所欲获取数据在本字节集中的偏移位置,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 取出字节集中指定位置的小数值

##### 火山.基本.字节集类.置字节集小数

* **类型:** `全局方法`
* **名称:** `置字节集小数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `数据偏移位置` (`整数`, 默认值: `0`): 提供所欲设置数据在本字节集中的偏移位置,必须大于等于0.
	* `所欲设置的值` (`小数`): 提供具体所欲设置的小数值
* **特性:**
	* `静态`
* **描述:** 设置字节集中指定位置处的小数值

##### 火山.基本.字节集类.取字节集单精度小数

* **类型:** `全局方法`
* **名称:** `取字节集单精度小数`
* **返回值数据类型:** `单精度小数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `数据偏移位置` (`整数`, 默认值: `0`): 提供所欲获取数据在本字节集中的偏移位置,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 取出字节集中指定位置的单精度小数值

##### 火山.基本.字节集类.置字节集单精度小数

* **类型:** `全局方法`
* **名称:** `置字节集单精度小数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `数据偏移位置` (`整数`, 默认值: `0`): 提供所欲设置数据在本字节集中的偏移位置,必须大于等于0.
	* `所欲设置的值` (`单精度小数`): 提供具体所欲设置的单精度小数值
* **特性:**
	* `静态`
* **描述:** 设置字节集中指定位置处的单精度小数值

##### 火山.基本.字节集类.置为空白字节集

* **类型:** `全局方法`
* **名称:** `置为空白字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `零字节数目` (`整数`): 指定所欲重置为的零字节数目,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 将本字节集的内容设置为指定次数的零字节重复结果,原有内容将被覆盖.

##### 火山.基本.字节集类.置为重复字节集

* **类型:** `全局方法`
* **名称:** `置为重复字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `待添加的字节集` (`字节集类`): 提供所欲重复添加的字节集
	* `重复次数` (`整数`): 提供重复添加的次数
* **特性:**
	* `静态`
* **描述:** 将本字节集的内容设置为指定次数的字节集重复结果,原有内容将被覆盖.

##### 火山.基本.字节集类.指针复制字节集

* **类型:** `全局方法`
* **名称:** `指针复制字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `数据指针` (`变整数`): 指向所欲复制数据的指针值
	* `所欲复制数据尺寸` (`整数`): 提供所欲复制数据的尺寸(单位字节),必须确保指针所指向地址处尺寸为本参数值的地址空间有效.
* **特性:**
	* `静态`
* **描述:** 将所指定指针处的数据复制到本字节集,字节集中的原有内容将被覆盖. 除非必要且对指针概念有透彻的了解,不要使用本方法.

##### 火山.基本.字节集类.添加字节集

* **类型:** `全局方法`
* **名称:** `添加字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲添加的字节集` (`字节集类`): 提供所欲添加到本字节集尾部的字节集内容
* **特性:**
	* `静态`
* **描述:** 将所指定字节集内容添加到本字节集内容的尾部
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.指针添加字节集

* **类型:** `全局方法`
* **名称:** `指针添加字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `数据指针` (`变整数`): 指向所欲添加数据的指针值
	* `所欲添加数据尺寸` (`整数`): 提供所欲添加数据的尺寸(单位字节),必须确保指针所指向地址处尺寸为本参数值的地址空间可读.
* **特性:**
	* `静态`
* **描述:** 将所指定指针处的数据添加到本字节集的尾部. 除非必要且对指针概念有透彻的了解,不要使用本方法.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.添加数组到字节集

* **类型:** `全局方法`
* **名称:** `添加数组到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲添加的数据` (`通用非文本基本型数组`)
* **特性:**
	* `静态`
* **描述:** 将所指定非文本基本数据类型数组数据添加到本字节集的尾部
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.字节集类.添加值到字节集

* **类型:** `全局方法`
* **名称:** `添加值到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲添加的值` (`通用非文本基本型`): 提供所欲添加到本字节集尾部的值,如欲明确指定其数据类型,可以使用强制类型转换操作符.
* **特性:**
	* `静态`
* **描述:** 将所指定数据类型的值添加到本字节集尾部
* **相关例程:** [vol-调用动态链接库-dll_call-main](#vol-调用动态链接库-dll_call-main)

##### 火山.基本.字节集类.添加单精度小数到字节集

* **类型:** `全局方法`
* **名称:** `添加单精度小数到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲添加的值` (`小数`): 提供所欲添加到本字节集尾部的值,该值将被强制转换为单精度小数后添加进去.
* **特性:**
	* `静态`
* **描述:** 将所指定的单精度小数值添加到本字节集尾部

##### 火山.基本.字节集类.添加文本到字节集

* **类型:** `全局方法`
* **名称:** `添加文本到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲添加的文本` (`文本型`): 提供所欲添加到本字节集尾部的文本内容
	* `是否添加结束零字符` (`逻辑型`, 默认值: `假`): 是否将文本尾部的结束零字符添加到字节集尾部
* **特性:**
	* `静态`
* **描述:** 将所指定文本内容添加到本字节集尾部

##### 火山.基本.字节集类.添加字节集空间

* **类型:** `全局方法`
* **名称:** `添加字节集空间`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `内容空间尺寸` (`整数`): 提供所欲添加内容空间的尺寸,必须大于等于0.
	* `是否清零` (`逻辑型`, 默认值: `真`): 是否将所添加的内容空间部分清除为字节值零
* **特性:**
	* `静态`
* **描述:** 将所指定尺寸的数据内容空间添加到字节集尾部
* **返回值描述:** 返回所添加内容空间部分的首地址指针值,除非必要且对指针概念有透彻的了解,不要使用本返回值.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.添加重复字符到字节集

* **类型:** `全局方法`
* **名称:** `添加重复字符到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲添加的字符` (`字符`): 提供所欲添加的具体字符
	* `所欲添加的次数` (`整数`): 提供所欲添加的次数,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 添加指定数目的字符到本字节集尾部

##### 火山.基本.字节集类.添加部分文本到字节集

* **类型:** `全局方法`
* **名称:** `添加部分文本到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲添加的文本` (`文本型`): 提供所欲添加到本字节集尾部的文本
	* `所欲添加文本的长度` (`整数`): 提供所欲添加文本的长度(单位字符),必须大于等于0且小于等于所指定文本的长度.
* **特性:**
	* `静态`
* **描述:** 将所指定文本的部分内容添加到本字节集尾部

##### 火山.基本.字节集类.指针添加文本到字节集

* **类型:** `全局方法`
* **名称:** `指针添加文本到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲添加的文本指针` (`变整数`): 提供所欲添加到本字节集尾部的文本数据指针
	* `所欲添加文本的长度` (`整数`): 提供所欲添加文本的长度(单位字符),必须确保指针所指向地址处尺寸为"本参数值*单个字符数据尺寸"的地址空间可读.
* **特性:**
	* `静态`
* **描述:** 将所指定长度的文本内容添加到本字节集尾部. 除非必要且对指针概念有透彻的了解,不要使用本方法.

##### 火山.基本.字节集类.添加重复字节集

* **类型:** `全局方法`
* **名称:** `添加重复字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `待添加的字节集` (`字节集类`): 提供所欲重复添加的字节集
	* `重复次数` (`整数`): 提供重复添加的次数
* **特性:**
	* `静态`
* **描述:** 将指定字节集重复添加所指定次数到本字节集的尾部

##### 火山.基本.字节集类.插入字节集

* **类型:** `全局方法`
* **名称:** `插入字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `插入偏移位置` (`整数`): 提供在本字节集中的具体插入偏移位置,必须大于等于0且小于等于本字节集的长度.
	* `所欲插入的字节集` (`字节集类`): 提供所欲插入到本字节集中的字节集内容
* **特性:**
	* `静态`
* **描述:** 将所指定字节集内容插入到本字节集内容的指定偏移位置处
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main)

##### 火山.基本.字节集类.指针插入字节集

* **类型:** `全局方法`
* **名称:** `指针插入字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `插入偏移位置` (`整数`): 提供在本字节集中的具体插入偏移位置,必须大于等于0且小于等于本字节集的长度.
	* `数据指针` (`变整数`): 指向所欲插入数据的指针值
	* `所欲插入数据尺寸` (`整数`): 提供所欲插入数据的尺寸(单位字节),必须确保指针所指向地址处尺寸为本参数值的地址空间可读.
* **特性:**
	* `静态`
* **描述:** 将所指定指针处的数据插入到本字节集所指定偏移位置处. 除非必要且对指针概念有透彻的了解,不要使用本方法.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.插入值到字节集

* **类型:** `全局方法`
* **名称:** `插入值到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `插入偏移位置` (`整数`): 提供在本字节集中的具体插入偏移位置,必须大于等于0且小于等于本字节集的长度.
	* `所欲插入的值` (`通用非文本基本型`): 提供具体所欲插入的值,如欲明确指定其数据类型,可以使用强制类型转换操作符.
* **特性:**
	* `静态`
* **描述:** 将所指定数据类型的值插入到本字节集所指定偏移位置处

##### 火山.基本.字节集类.插入单精度小数到字节集

* **类型:** `全局方法`
* **名称:** `插入单精度小数到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `插入偏移位置` (`整数`): 提供在本字节集中的具体插入偏移位置,必须大于等于0且小于等于本字节集的长度.
	* `所欲插入的值` (`小数`): 提供具体所欲插入的值,该值将被强制转换为单精度小数后插入字节集中.
* **特性:**
	* `静态`
* **描述:** 将所指定的单精度小数值插入到本字节集所指定偏移位置处

##### 火山.基本.字节集类.插入文本到字节集

* **类型:** `全局方法`
* **名称:** `插入文本到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `插入偏移位置` (`整数`): 提供在本字节集中的具体插入偏移位置,必须大于等于0且小于等于本字节集的长度.
	* `所欲插入的文本内容` (`文本型`): 提供具体所欲插入的文本内容
	* `是否插入结束零字符` (`逻辑型`, 默认值: `假`): 是否将文本尾部的结束零字符插入进字节集
* **特性:**
	* `静态`
* **描述:** 将所指定文本内容插入到本字节集所指定偏移位置处.
* **相关例程:** [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main)

##### 火山.基本.字节集类.插入字节集空间

* **类型:** `全局方法`
* **名称:** `插入字节集空间`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `插入偏移位置` (`整数`): 提供在本字节集中的具体插入偏移位置,必须大于等于0且小于等于本字节集长度.
	* `内容空间尺寸` (`整数`): 提供所欲插入内容空间的尺寸,必须大于等于0.
	* `是否清零` (`逻辑型`, 默认值: `真`): 是否将所插入的内容空间部分清除为字节值零
* **特性:**
	* `静态`
* **描述:** 将所指定尺寸的数据内容空间插入到字节集所指定位置处
* **返回值描述:** 返回所插入内容空间部分的首地址指针值,除非必要且对指针概念有透彻的了解,不要使用本返回值.

##### 火山.基本.字节集类.插入部分文本到字节集

* **类型:** `全局方法`
* **名称:** `插入部分文本到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `插入偏移位置` (`整数`): 提供在本字节集中的具体插入偏移位置,必须大于等于0且小于等于本字节集长度.
	* `所欲插入的文本` (`文本型`): 提供所欲插入到本字节集中的文本数据
	* `所欲插入文本的长度` (`整数`): 提供所欲插入文本的长度(单位字符),必须大于等于0且小于等于所指定文本长度.
* **特性:**
	* `静态`
* **描述:** 将所指定文本的一部分插入到字节集所指定位置处

##### 火山.基本.字节集类.指针插入文本到字节集

* **类型:** `全局方法`
* **名称:** `指针插入文本到字节集`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `插入偏移位置` (`整数`): 提供在本字节集中的具体插入偏移位置,必须大于等于0且小于等于本字节集长度.
	* `所欲插入的文本指针` (`变整数`): 提供所欲插入到本字节集中的文本数据指针
	* `所欲插入文本的长度` (`整数`): 提供所欲插入文本的长度(单位字符),必须确保指针所指向地址处尺寸为"本参数值*单个字符数据尺寸"的地址空间可读.
* **特性:**
	* `静态`
* **描述:** 将所指定长度的文本内容插入到字节集所指定位置处. 除非必要且对指针概念有透彻的了解,不要使用本方法.

##### 火山.基本.字节集类.字节集删除

* **类型:** `全局方法`
* **名称:** `字节集删除`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `起始删除位置` (`整数`): 提供被删除内容的起始偏移位置,必须大于等于-1. 如果为-1,则从尾部开始向前逆向删除所指定尺寸.
	* `所欲删除数据的尺寸` (`整数`): 提供具体的删除尺寸,单位字节,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 删除本字节集的某一部分内容
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.删除字节集尾部数据

* **类型:** `全局方法`
* **名称:** `删除字节集尾部数据`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `所欲保留数据的尺寸` (`整数`): 提供所欲保留的位于当前字节集首部的数据尺寸,必须大于等于0且小于等于本字节集的长度.
* **特性:**
	* `静态`
* **描述:** 保留当前字节集首部的指定尺寸数据,将后面的数据全部删除.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.字节集类.删除字节集尾字符零

* **类型:** `全局方法`
* **名称:** `删除字节集尾字符零`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 如果当前字节集尾部为零字符,则将其删除,否则不进行任何操作.

##### 火山.基本.字节集类.取字节集哈希值

* **类型:** `全局方法`
* **名称:** `取字节集哈希值`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 计算并返回所指定字节集的哈希值. 字节集哈希值可以在需要快速比较两个字节集是否相同时使用(即如果两个字节集的哈希值不同,则两个字节集必定不相同).

##### 火山.基本.字节集类.字节集到十六进制文本

* **类型:** `全局方法`
* **名称:** `字节集到十六进制文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
* **特性:**
	* `静态`
* **描述:** 将本字节集的内容转换为十六进制格式的连续文本
* **相关例程:** [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main)

##### 火山.基本.字节集类.十六进制文本到字节集

* **类型:** `全局方法`
* **名称:** `十六进制文本到字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `十六进制文本` (`文本型`): 必须为"字节集到十六进制文本"所返回的格式文本
* **特性:**
	* `静态`
* **描述:** 根据"字节集到十六进制文本"方法返回的文本内容创建并返回一个字节集
* **相关例程:** [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.字节集类.添加十六进制文本到字节集

* **类型:** `全局方法`
* **名称:** `添加十六进制文本到字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `十六进制文本` (`文本型`): 必须为"字节集到十六进制文本"所返回的格式文本
* **特性:**
	* `静态`
* **描述:** 根据"字节集到十六进制文本"方法返回的文本内容创建一个字节集并将其添加到本字节集的尾部
* **返回值描述:** 返回添加后的本字节集对象

##### 火山.基本.字节集类.字节集到BASE64文本

* **类型:** `全局方法`
* **名称:** `字节集到BASE64文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `编码格式` (`BASE64编码方式`, 默认值: `BASE64编码方式.标准`): 提供具体的编码格式
	* `每行最大字符数` (`整数`, 默认值: `0`): 指定每行编码文本的最大字符数,小于0表示无限制,等于0表示使用默认每行字符数(76).
* **特性:**
	* `静态`
* **描述:** 返回本字节集数据所对应的BASE64编码格式文本内容
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main)

##### 火山.基本.字节集类.BASE64文本到字节集

* **类型:** `全局方法`
* **名称:** `BASE64文本到字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `BASE64编码文本` (`文本型`): 提供所欲解码的BASE64编码文本
	* `编码格式` (`BASE64编码方式`, 默认值: `BASE64编码方式.标准`): 提供具体的编码格式,必须与编码时指定的格式相同.
* **特性:**
	* `静态`
* **描述:** 将所指定的BASE64编码格式文本解码为对应的字节集后返回
* **相关例程:** [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main)

##### 火山.基本.字节集类.字节集到Quoted文本

* **类型:** `全局方法`
* **名称:** `字节集到Quoted文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作本对象` (`字节集类`): 提供所欲操作的字节集对象
	* `每行最大字符数` (`整数`, 默认值: `0`): 指定每行编码文本的最大字符数,小于0表示无限制,等于0表示使用默认每行字符数(76).
* **特性:**
	* `静态`
* **描述:** 返回本字节集数据所对应的Quoted-Printable编码格式文本内容

##### 火山.基本.字节集类.Quoted文本到字节集

* **类型:** `全局方法`
* **名称:** `Quoted文本到字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `Quoted编码文本` (`文本型`): 提供所欲解码的Quoted-Printable编码文本
* **特性:**
	* `静态`
* **描述:** 将所指定的Quoted-Printable编码格式文本解码为对应的字节集后返回

---

#### 火山.基本.字符串资源

* **类型:** `类`
* **名称:** `字符串资源`
* **特性:**
	* `常量类`(对应数据类型: `整数`; 初始值数据类型: `文本型`)
* **描述:** 用作记录一个字符串资源

---

#### 火山.基本.视窗文件资源

* **类型:** `类`
* **名称:** `视窗文件资源`
* **特性:**
	* `常量类`(对应数据类型: `整数`; 初始值数据类型: `文本型`)
	* `文件名`
* **描述:** 所有基于文件数据内容资源的基础类,所有以本类为基础类的资源将直接把相关文件的全部数据以RCDATA类型(除非继承类中使用"@视窗.资源类型"属性进行了修改)放入到编译后的目的程序资源段中. 如果初始值提供一个空文件名,将代表为空文件资源.空资源一般用作取消先前所已经设置资源的作用效果.
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-cximage高级图像处理-cximage-main](#vol-cximage高级图像处理-cximage-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-网页解析-html_parser-main](#vol-网页解析-html_parser-main), [vol-高级网页解析-adv_html_parser-main](#vol-高级网页解析-adv_html_parser-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main)

---

#### 火山.基本.图标资源

* **类型:** `类`
* **名称:** `图标资源`
* **基础类:** `视窗文件资源`
* **特性:**
	* `常量类`(对应数据类型: `整数`; 初始值数据类型: `文本型`)
	* `文件名`
* **描述:** 用作代表一个ico图标资源,本类资源将把所指定的ico图标数据以ICON类型放入到编译后的目的程序资源段中. 如果初始值提供一个空文件名,将代表为空图标资源.
* **相关例程:** [vol-对话框-dialog_test-main](#vol-对话框-dialog_test-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

---

#### 火山.基本.位图资源

* **类型:** `类`
* **名称:** `位图资源`
* **基础类:** `视窗文件资源`
* **特性:**
	* `常量类`(对应数据类型: `整数`; 初始值数据类型: `文本型`)
	* `文件名`
* **描述:** 用作代表一个通用位图资源,本类资源将把所指定的位图数据以RCDATA类型放入到编译后的目的程序资源段中. 如果初始值提供一个空文件名,将代表为空位图资源.
* **相关例程:** [vol-半透明图片演示-alpha_pic_draw-main](#vol-半透明图片演示-alpha_pic_draw-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-位图处理-adv_bitmap-main](#vol-位图处理-adv_bitmap-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main)

---

#### 火山.基本.BMP位图资源

* **类型:** `类`
* **名称:** `BMP位图资源`
* **基础类:** `视窗文件资源`
* **特性:**
	* `常量类`(对应数据类型: `整数`; 初始值数据类型: `文本型`)
	* `文件名`
* **描述:** 用作代表一个BITMAP位图资源,本类资源将把所指定的位图数据以BITMAP类型放入到编译后的目的程序资源段中. 如果初始值提供一个空文件名,将代表为空BITMAP位图资源.
* **相关例程:** [vol-带按钮列表框-vs_list_box-main](#vol-带按钮列表框-vs_list_box-main)

---

#### 火山.基本.图片组资源

* **类型:** `类`
* **名称:** `图片组资源`
* **基础类:** `位图资源`
* **特性:**
	* `常量类`(对应数据类型: `整数`; 初始值数据类型: `文本型`)
	* `文件名`
* **描述:** 用作代表一个基于位图的图片组资源,本类资源将把所指定的位图数据以RCDATA类型放入到编译后的目的程序资源段中. 用来作为图片组的位图内容格式具有以下要求: 1. 必须为图片组中所有单个图片的横向排列组合,即图片组中单个图片的高度等于整个图片组位图的高度,图片组中所有单个图片的总宽度等于整个图片组位图的宽度; 2. 图片组中单个图片的宽度等于其高度,如果不为偶数值,则就近向上取偶(如:高度为15,则宽度为16); 3. 位图中的透明部分用洋红色(红绿蓝分量值分别为: 255, 0, 255)填充标记.
* **相关例程:** [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main)

---

#### 火山.基本.鼠标指针资源

* **类型:** `类`
* **名称:** `鼠标指针资源`
* **基础类:** `视窗文件资源`
* **特性:**
	* `常量类`(对应数据类型: `整数`; 初始值数据类型: `文本型`)
	* `文件名`
* **描述:** 用作代表一个鼠标指针图像资源,本类资源将把所指定的鼠标指针图片数据以CURSOR类型放入到编译后的目的程序资源段中. 如果初始值提供一个空文件名,将代表为空鼠标指针资源.

---

#### 火山.基本.WAV资源

* **类型:** `类`
* **名称:** `WAV资源`
* **基础类:** `视窗文件资源`
* **特性:**
	* `常量类`(对应数据类型: `整数`; 初始值数据类型: `文本型`)
	* `文件名`
* **描述:** 用作代表一个wav声音文件资源. 如果初始值提供一个空文件名,将代表为空wav资源.
* **相关例程:** [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-wav播放-wav_play-main](#vol-wav播放-wav_play-main)

---

#### 火山.基本.声音资源

* **类型:** `类`
* **名称:** `声音资源`
* **基础类:** `视窗文件资源`
* **特性:**
	* `常量类`(对应数据类型: `整数`; 初始值数据类型: `文本型`)
	* `文件名`
* **描述:** 用作代表一个wav或mp3声音文件资源. 如果初始值提供一个空文件名,将代表为空wav或mp3资源.
* **相关例程:** [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main)

---

#### 火山.基本.空资源

* **类型:** `类`
* **名称:** `空资源`
* **描述:** 提供以上各种资源所对应的空资源常量,空资源一般用作取消先前所已经设置资源的作用效果.
* **相关例程:** [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main)

##### 火山.基本.空资源.空字符串

* **类型:** `成员常量`
* **名称:** `空字符串`
* **数据类型:** `字符串资源`
* **初始值:** `""`

##### 火山.基本.空资源.空图标

* **类型:** `成员常量`
* **名称:** `空图标`
* **数据类型:** `图标资源`
* **初始值:** `""`
* **相关例程:** [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main)

##### 火山.基本.空资源.空位图

* **类型:** `成员常量`
* **名称:** `空位图`
* **数据类型:** `位图资源`
* **初始值:** `""`

##### 火山.基本.空资源.空BMP位图

* **类型:** `成员常量`
* **名称:** `空BMP位图`
* **数据类型:** `BMP位图资源`
* **初始值:** `""`

##### 火山.基本.空资源.空鼠标指针

* **类型:** `成员常量`
* **名称:** `空鼠标指针`
* **数据类型:** `鼠标指针资源`
* **初始值:** `""`

##### 火山.基本.空资源.空文件

* **类型:** `成员常量`
* **名称:** `空文件`
* **数据类型:** `视窗文件资源`
* **初始值:** `""`

##### 火山.基本.空资源.空WAV声音

* **类型:** `成员常量`
* **名称:** `空WAV声音`
* **数据类型:** `WAV资源`
* **初始值:** `""`

##### 火山.基本.空资源.空声音

* **类型:** `成员常量`
* **名称:** `空声音`
* **数据类型:** `声音资源`
* **初始值:** `""`

---

#### 火山.基本.资源操作类

* **类型:** `类`
* **名称:** `资源操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `资源.处理类`

##### 火山.基本.资源操作类.载入字符串资源

* **类型:** `全局方法`
* **名称:** `载入字符串资源`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲载入的字符串` (`字符串资源`)
* **特性:**
	* `静态`
* **描述:** 载入并返回所指定的字符串资源,载入失败将返回空文本.

##### 火山.基本.资源操作类.载入字符串资源2

* **类型:** `全局方法`
* **名称:** `载入字符串资源2`
* **参数:**
	* `所欲载入的字符串` (`字符串资源`)
	* `结果存储参数` (`文本型`): 所载入的字符串资源将保存进此参数中,载入失败将置入空文本.
* **特性:**
	* `静态`
* **描述:** 载入并返回所指定的字符串资源

---

#### 火山.基本.GDI资源类

* **类型:** `类`
* **名称:** `GDI资源类`
* **基础类:** `参考对象类`
* **文档分类:** `资源.处理类`
* **描述:** 用作记录一个GDI对象的句柄,支持在不使用后自动对其进行释放.

##### 火山.基本.GDI资源类.为空

* **类型:** `方法`
* **名称:** `为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本对象内是否未记录有一个非0句柄值

##### 火山.基本.GDI资源类.取句柄值

* **类型:** `方法`
* **名称:** `取句柄值`
* **返回值数据类型:** `变整数`
* **描述:** 返回对象中所保存的GDI对象句柄值,不存在返回0.

---

#### 火山.基本.图标对象类

* **类型:** `类`
* **名称:** `图标对象类`
* **基础类:** `GDI资源类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `资源.处理类`
* **描述:** 用作记录一个图标句柄(HICON)及对应的相关操作

##### 火山.基本.图标对象类.置图标句柄值

* **类型:** `方法`
* **名称:** `置图标句柄值`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲设置的句柄值` (`变整数`): 提供所欲置入的图标句柄值(HICON),调用方必须确保该句柄值的正确性. 注意: 该句柄的释放工作将交由本对象负责,调用方不再需要管理.
	* `是否自动释放` (`逻辑型`): 指定是否需要自动释放所置入的句柄值
* **描述:** 将一个所指定图标句柄(HICON)置入本对象中.
* **返回值描述:** 返回所置入的句柄值是否不为NULL

##### 火山.基本.图标对象类.载入图标资源

* **类型:** `全局方法`
* **名称:** `载入图标资源`
* **返回值数据类型:** `图标对象类`
* **参数:**
	* `所欲载入的图标` (`图标资源`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的图标资源,返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败或所提供资源为空资源则为空("为空"方法返回真).

##### 火山.基本.图标对象类.载入图标文件

* **类型:** `全局方法`
* **名称:** `载入图标文件`
* **返回值数据类型:** `图标对象类`
* **参数:**
	* `所欲载入的图标文件` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的图标文件,返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败或所提供资源为空资源则为空("为空"方法返回真).

---

#### 火山.基本.位图对象类

* **类型:** `类`
* **名称:** `位图对象类`
* **基础类:** `GDI资源类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `资源.处理类`
* **描述:** 用作记录一个bmp位图句柄(HBITMAP)及对应的相关操作
* **相关例程:** [vol-半透明图片演示-alpha_pic_draw-main](#vol-半透明图片演示-alpha_pic_draw-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.位图对象类.载入位图资源

* **类型:** `全局方法`
* **名称:** `载入位图资源`
* **返回值数据类型:** `位图对象类`
* **参数:**
	* `所欲载入的位图` (`位图资源`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的位图资源(所支持格式: gif/bmp/emf/wmf/jpg//png/tif/ico),返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败或所提供资源为空资源则为空("为空"方法返回真).
* **相关例程:** [vol-半透明图片演示-alpha_pic_draw-main](#vol-半透明图片演示-alpha_pic_draw-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main)

##### 火山.基本.位图对象类.载入位图文件

* **类型:** `全局方法`
* **名称:** `载入位图文件`
* **返回值数据类型:** `位图对象类`
* **参数:**
	* `所欲载入的位图文件` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的位图文件(所支持格式: gif/bmp/emf/wmf/jpg//png/tif/ico),返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败或所提供资源为空资源则为空("为空"方法返回真).

##### 火山.基本.位图对象类.载入位图数据

* **类型:** `全局方法`
* **名称:** `载入位图数据`
* **返回值数据类型:** `位图对象类`
* **参数:**
	* `所欲载入的位图数据` (`字节集类`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的位图数据(所支持格式: gif/bmp/emf/wmf/jpg//png/tif/ico),返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败或所提供资源为空资源则为空("为空"方法返回真).

##### 火山.基本.位图对象类.置位图句柄值

* **类型:** `方法`
* **名称:** `置位图句柄值`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲设置的句柄值` (`变整数`): 提供所欲置入的位图句柄值(HBITMAP),调用方必须确保该句柄值的正确性. 注意: 该句柄的释放工作将交由本对象负责,调用方不再需要管理.
	* `是否自动释放` (`逻辑型`): 指定是否需要自动释放所置入的句柄值
* **描述:** 将一个所指定位图句柄(HBITMAP)置入本对象中.
* **返回值描述:** 返回所置入的句柄值是否不为NULL

##### 火山.基本.位图对象类.取图片尺寸

* **类型:** `方法`
* **名称:** `取图片尺寸`
* **返回值数据类型:** `尺寸类`
* **描述:** 返回当前位图的尺寸,单位像素. 如果当前尚未设置有效位图,则返回零尺寸.

##### 火山.基本.位图对象类.取图片数据

* **类型:** `方法`
* **名称:** `取图片数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `数据存放字节集` (`字节集类`): 用作存放所获得的BMP图片文件数据
	* `输出宽度` (`整数`, 默认值: `0`): 指定图片的输出宽度. 如果小于0,参数值指定的是最终图片输出宽度相对于当前图片宽度的百分比(最小为10%); 如果等于0,则按图片原宽度输出; 如果大于0,指定输出图片的绝对宽度.
	* `输出高度` (`整数`, 默认值: `0`): 指定图片的输出高度. 如果小于0,参数值指定的是最终图片输出高度相对于当前图片高度的百分比(最小为10%); 如果等于0,则按图片原高度输出; 如果大于0,指定输出图片的绝对高度.
* **描述:** 获取当前位图所对应的BMP图片文件数据
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.位图对象类.写图片文件

* **类型:** `方法`
* **名称:** `写图片文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲写到的文件名` (`文本型`): 提供所欲写到的BMP文件名
	* `输出宽度` (`整数`, 默认值: `0`): 指定图片的输出宽度. 如果小于0,参数值指定的是最终图片输出宽度相对于当前图片宽度的百分比(最小为10%); 如果等于0,则按图片原宽度输出; 如果大于0,指定输出图片的绝对宽度.
	* `输出高度` (`整数`, 默认值: `0`): 指定图片的输出高度. 如果小于0,参数值指定的是最终图片输出高度相对于当前图片高度的百分比(最小为10%); 如果等于0,则按图片原高度输出; 如果大于0,指定输出图片的绝对高度.
* **描述:** 获取当前位图所对应的BMP图片文件数据,并将其写出到所指定名称的文件.
* **返回值描述:** 成功返回真,失败返回假.

---

#### 火山.基本.图片组对象类

* **类型:** `类`
* **名称:** `图片组对象类`
* **基础类:** `GDI资源类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `资源.处理类`
* **描述:** 用作记录一个图片组句柄(HIMAGELIST)及对应的相关操作
* **相关例程:** [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main)

##### 火山.基本.图片组对象类.置图片组句柄值

* **类型:** `方法`
* **名称:** `置图片组句柄值`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲设置的句柄值` (`变整数`): 提供所欲置入的图片组句柄值(HIMAGELIST),调用方必须确保该句柄值的正确性. 注意: 该句柄的释放工作将交由本对象负责,调用方不再需要管理.
	* `是否自动释放` (`逻辑型`): 指定是否需要自动释放所置入的句柄值
* **描述:** 将一个所指定图片组句柄(HIMAGELIST)置入本对象中.
* **返回值描述:** 返回所置入的句柄值是否不为NULL

##### 火山.基本.图片组对象类.载入图片组资源

* **类型:** `全局方法`
* **名称:** `载入图片组资源`
* **返回值数据类型:** `图片组对象类`
* **参数:**
	* `所欲载入的图片组` (`图片组资源`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的图片组资源,返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败或所提供资源为空资源则为空("为空"方法返回真).
* **相关例程:** [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main)

##### 火山.基本.图片组对象类.载入图片组文件

* **类型:** `全局方法`
* **名称:** `载入图片组文件`
* **返回值数据类型:** `图片组对象类`
* **参数:**
	* `所欲载入的图片组文件` (`文本型`): 提供用作保存图片组的图片文件名,该图片文件的格式必须符合"图片组资源"类中所说明的要求.
* **特性:**
	* `静态`
* **描述:** 载入所指定的图片组文件,返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败或所提供资源为空资源则为空("为空"方法返回真).
* **相关例程:** [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main)

##### 火山.基本.图片组对象类.载入图片组数据

* **类型:** `全局方法`
* **名称:** `载入图片组数据`
* **返回值数据类型:** `图片组对象类`
* **参数:**
	* `所欲载入的图片组文件数据` (`字节集类`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的图片组数据,返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败或所提供资源为空资源则为空("为空"方法返回真).
* **相关例程:** [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main)

---

#### 火山.基本.标准鼠标指针类型

* **类型:** `类`
* **名称:** `标准鼠标指针类型`
* **特性:**
	* `常量类`(对应数据类型: `变整数`)
* **文档分类:** `资源.处理类.辅助类`
* **描述:** 提供各种视窗系统标准的鼠标指针类型

##### 火山.基本.标准鼠标指针类型.标准箭头型

* **类型:** `成员常量`
* **名称:** `标准箭头型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.十字型

* **类型:** `成员常量`
* **名称:** `十字型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.文本编辑型

* **类型:** `成员常量`
* **名称:** `文本编辑型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.沙漏型

* **类型:** `成员常量`
* **名称:** `沙漏型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.箭头及问号型

* **类型:** `成员常量`
* **名称:** `箭头及问号型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.箭头及沙漏型

* **类型:** `成员常量`
* **名称:** `箭头及沙漏型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.禁止符型

* **类型:** `成员常量`
* **名称:** `禁止符型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.四向箭头型

* **类型:** `成员常量`
* **名称:** `四向箭头型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.北东箭头型

* **类型:** `成员常量`
* **名称:** `北东箭头型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.北南箭头型

* **类型:** `成员常量`
* **名称:** `北南箭头型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.北西箭头型

* **类型:** `成员常量`
* **名称:** `北西箭头型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.西东箭头型

* **类型:** `成员常量`
* **名称:** `西东箭头型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.向上箭头型

* **类型:** `成员常量`
* **名称:** `向上箭头型`
* **数据类型:** `标准鼠标指针类型`

##### 火山.基本.标准鼠标指针类型.手型

* **类型:** `成员常量`
* **名称:** `手型`
* **数据类型:** `标准鼠标指针类型`

---

#### 火山.基本.鼠标指针对象类

* **类型:** `类`
* **名称:** `鼠标指针对象类`
* **基础类:** `GDI资源类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `资源.处理类`
* **描述:** 用作记录一个鼠标指针句柄(HCURSOR)及对应的相关操作

##### 火山.基本.鼠标指针对象类.置鼠标指针句柄值

* **类型:** `方法`
* **名称:** `置鼠标指针句柄值`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲设置的句柄值` (`变整数`): 提供所欲置入的鼠标指针句柄值(HCURSOR),调用方必须确保该句柄值的正确性. 注意: 该句柄的释放工作将交由本对象负责,调用方不再需要管理.
	* `是否自动释放` (`逻辑型`): 指定是否需要自动释放所置入的句柄值
* **描述:** 将一个所指定鼠标指针句柄(HCURSOR)置入本对象中.
* **返回值描述:** 返回所置入的句柄值是否不为NULL

##### 火山.基本.鼠标指针对象类.载入鼠标指针资源

* **类型:** `全局方法`
* **名称:** `载入鼠标指针资源`
* **返回值数据类型:** `鼠标指针对象类`
* **参数:**
	* `所欲载入的鼠标指针` (`鼠标指针资源`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的鼠标指针资源,返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败或所提供资源为空资源则为空("为空"方法返回真).

##### 火山.基本.鼠标指针对象类.载入鼠标指针文件

* **类型:** `全局方法`
* **名称:** `载入鼠标指针文件`
* **返回值数据类型:** `鼠标指针对象类`
* **参数:**
	* `所欲载入的鼠标指针文件` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 载入所指定的鼠标指针文件,返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败或所提供资源为空资源则为空("为空"方法返回真).

##### 火山.基本.鼠标指针对象类.取标准鼠标指针

* **类型:** `全局方法`
* **名称:** `取标准鼠标指针`
* **返回值数据类型:** `鼠标指针对象类`
* **参数:**
	* `所欲载入的鼠标指针` (`标准鼠标指针类型`)
* **特性:**
	* `静态`
* **描述:** 获取所指定的标准鼠标指针资源,返回所载入的句柄对象.
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败为空("为空"方法返回真).

---

#### 火山.基本.字体对象类

* **类型:** `类`
* **名称:** `字体对象类`
* **基础类:** `GDI资源类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `资源.处理类`
* **描述:** 用作记录一个字体句柄(HFONT)及对应的相关操作
* **相关例程:** [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.字体对象类.置字体句柄值

* **类型:** `方法`
* **名称:** `置字体句柄值`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲设置的句柄值` (`变整数`): 提供所欲置入的字体句柄值(HFONT),调用方必须确保该句柄值的正确性. 注意: 该句柄的释放工作将交由本对象负责,调用方不再需要管理.
	* `是否自动释放` (`逻辑型`): 指定是否需要自动释放所置入的句柄值
* **描述:** 将一个所指定字体句柄(HFONT)置入本对象中.

##### 火山.基本.字体对象类.磅字体尺寸到像素

* **类型:** `全局方法`
* **名称:** `磅字体尺寸到像素`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲转换的字体尺寸` (`整数`): 本尺寸以磅为单位
* **特性:**
	* `静态`
* **描述:** 将以磅为单位的字体尺寸转换为以屏幕像素为单位的尺寸
* **返回值描述:** 返回转换尺寸结果,以屏幕像素为单位.

##### 火山.基本.字体对象类.像素字体尺寸到磅

* **类型:** `全局方法`
* **名称:** `像素字体尺寸到磅`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲转换的字体尺寸` (`整数`): 本尺寸以屏幕像素为单位
* **特性:**
	* `静态`
* **描述:** 将以屏幕像素为单位的字体尺寸转换为以磅为单位的尺寸
* **返回值描述:** 返回转换尺寸结果,以磅为单位.

##### 火山.基本.字体对象类.从描述文本创建字体

* **类型:** `全局方法`
* **名称:** `从描述文本创建字体`
* **返回值数据类型:** `字体对象类`
* **参数:**
	* `字体描述文本` (`文本型`): 本参数的格式为: "字体名, 字体尺寸, 是否为粗体, 是否为斜体, 是否有下划线, 是否有删除线, 旋转角度",其中"是否"字段,用1代表真,0代表假,可以被省略.字体尺寸单位为磅,旋转角度单位为1/10度. 例子: "宋体, 10", "宋体, 10, 0, 1, 1, 0, 100".
* **特性:**
	* `静态`
* **描述:** 从一个指定格式的字体描述文本创建字体
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败为空("为空"方法返回真).

##### 火山.基本.字体对象类.取字体描述文本

* **类型:** `方法`
* **名称:** `取字体描述文本`
* **返回值数据类型:** `文本型`
* **描述:** 返回当前字体的描述文本. 描述文本的格式为: "字体名, 字体尺寸, 是否为粗体, 是否为斜体, 是否有下划线, 是否有删除线, 旋转角度",其中"是否"字段,用1代表真,0代表假,可以被省略.字体尺寸单位为磅, 旋转角度单位为1/10度. 例子: "宋体, 10", "宋体, 10, 0, 1, 1, 0, 100".

##### 火山.基本.字体对象类.创建字体

* **类型:** `全局方法`
* **名称:** `创建字体`
* **返回值数据类型:** `字体对象类`
* **参数:**
	* `字体名称` (`文本型`): 提供所欲创建字体的名称
	* `字体尺寸` (`整数`): 提供所欲创建字体的尺寸,单位为磅.
	* `是否粗体` (`逻辑型`, 默认值: `假`)
	* `是否斜体` (`逻辑型`, 默认值: `假`)
	* `是否有下划线` (`逻辑型`, 默认值: `假`)
	* `是否有删除线` (`逻辑型`, 默认值: `假`)
	* `旋转角度` (`整数`, 默认值: `0`): 提供字体的旋转角度,单位为十分之一度.
* **特性:**
	* `静态`
* **描述:** 从指定参数创建并返回一个字体对象
* **返回值描述:** 成功所返回的句柄对象不为空("为空"方法返回假),失败为空("为空"方法返回真).

##### 火山.基本.字体对象类.取默认GUI字体

* **类型:** `全局方法`
* **名称:** `取默认GUI字体`
* **返回值数据类型:** `字体对象类`
* **特性:**
	* `静态`
* **描述:** 返回操作系统所使用的默认GUI字体
* **返回值描述:** 所返回字体对象必定有效
* **相关例程:** [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.字体对象类.取字体句柄

* **类型:** `方法`
* **名称:** `取字体句柄`
* **返回值数据类型:** `变整数`
* **描述:** 返回本对象中所保存的字体句柄,如果为NULL,则返回操作系统所使用的默认GUI字体句柄.

##### 火山.基本.字体对象类.取文本尺寸

* **类型:** `方法`
* **名称:** `取文本尺寸`
* **返回值数据类型:** `尺寸类`
* **参数:**
	* `所欲检查文本` (`文本型`)
* **描述:** 返回使用本字体在屏幕上绘制指定文本时所需要的尺寸,单位像素.
* **相关例程:** [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

---

#### 火山.基本.星期类

* **类型:** `类`
* **名称:** `星期类`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `时间操作.辅助类`
* **描述:** 提供星期内各天的常量值

##### 火山.基本.星期类.星期一

* **类型:** `成员常量`
* **名称:** `星期一`
* **数据类型:** `星期类`
* **初始值:** `0`

##### 火山.基本.星期类.星期二

* **类型:** `成员常量`
* **名称:** `星期二`
* **数据类型:** `星期类`
* **初始值:** `1`

##### 火山.基本.星期类.星期三

* **类型:** `成员常量`
* **名称:** `星期三`
* **数据类型:** `星期类`
* **初始值:** `2`

##### 火山.基本.星期类.星期四

* **类型:** `成员常量`
* **名称:** `星期四`
* **数据类型:** `星期类`
* **初始值:** `3`

##### 火山.基本.星期类.星期五

* **类型:** `成员常量`
* **名称:** `星期五`
* **数据类型:** `星期类`
* **初始值:** `4`

##### 火山.基本.星期类.星期六

* **类型:** `成员常量`
* **名称:** `星期六`
* **数据类型:** `星期类`
* **初始值:** `5`

##### 火山.基本.星期类.星期日

* **类型:** `成员常量`
* **名称:** `星期日`
* **数据类型:** `星期类`
* **初始值:** `6`

---

#### 火山.基本.颜色类

* **类型:** `类`
* **名称:** `颜色类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `其它`
* **描述:** 提供对颜色值的各种操作支持
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-半透明图片演示-alpha_pic_draw-main](#vol-半透明图片演示-alpha_pic_draw-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main](#vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main), [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.颜色类.黑色

* **类型:** `成员常量`
* **名称:** `黑色`
* **数据类型:** `整数`
* **相关例程:** [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.颜色类.墨绿色

* **类型:** `成员常量`
* **名称:** `墨绿色`
* **数据类型:** `整数`
* **相关例程:** [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main)

##### 火山.基本.颜色类.红褐色

* **类型:** `成员常量`
* **名称:** `红褐色`
* **数据类型:** `整数`
* **相关例程:** [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main)

##### 火山.基本.颜色类.褐绿色

* **类型:** `成员常量`
* **名称:** `褐绿色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.灰色

* **类型:** `成员常量`
* **名称:** `灰色`
* **数据类型:** `整数`
* **相关例程:** [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.颜色类.绿色

* **类型:** `成员常量`
* **名称:** `绿色`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.颜色类.红色

* **类型:** `成员常量`
* **名称:** `红色`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-半透明图片演示-alpha_pic_draw-main](#vol-半透明图片演示-alpha_pic_draw-main), [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.颜色类.黄色

* **类型:** `成员常量`
* **名称:** `黄色`
* **数据类型:** `整数`
* **相关例程:** [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main)

##### 火山.基本.颜色类.蓝灰色

* **类型:** `成员常量`
* **名称:** `蓝灰色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.嫩绿色

* **类型:** `成员常量`
* **名称:** `嫩绿色`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main)

##### 火山.基本.颜色类.黄褐色

* **类型:** `成员常量`
* **名称:** `黄褐色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.嫩黄色

* **类型:** `成员常量`
* **名称:** `嫩黄色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.紫色

* **类型:** `成员常量`
* **名称:** `紫色`
* **数据类型:** `整数`
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main](#vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main)

##### 火山.基本.颜色类.灰绿色

* **类型:** `成员常量`
* **名称:** `灰绿色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.橙黄色

* **类型:** `成员常量`
* **名称:** `橙黄色`
* **数据类型:** `整数`
* **相关例程:** [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.颜色类.芙红色

* **类型:** `成员常量`
* **名称:** `芙红色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.藏青色

* **类型:** `成员常量`
* **名称:** `藏青色`
* **数据类型:** `整数`
* **相关例程:** [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main)

##### 火山.基本.颜色类.深青色

* **类型:** `成员常量`
* **名称:** `深青色`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main)

##### 火山.基本.颜色类.紫红色

* **类型:** `成员常量`
* **名称:** `紫红色`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main)

##### 火山.基本.颜色类.浅灰色

* **类型:** `成员常量`
* **名称:** `浅灰色`
* **数据类型:** `整数`
* **相关例程:** [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.颜色类.蓝色

* **类型:** `成员常量`
* **名称:** `蓝色`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main)

##### 火山.基本.颜色类.艳青色

* **类型:** `成员常量`
* **名称:** `艳青色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.品红色

* **类型:** `成员常量`
* **名称:** `品红色`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main)

##### 火山.基本.颜色类.白色

* **类型:** `成员常量`
* **名称:** `白色`
* **数据类型:** `整数`
* **相关例程:** [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.颜色类.藏蓝色

* **类型:** `成员常量`
* **名称:** `藏蓝色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.青绿色

* **类型:** `成员常量`
* **名称:** `青绿色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.粉红色

* **类型:** `成员常量`
* **名称:** `粉红色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.银白色

* **类型:** `成员常量`
* **名称:** `银白色`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main)

##### 火山.基本.颜色类.天蓝色

* **类型:** `成员常量`
* **名称:** `天蓝色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.青蓝色

* **类型:** `成员常量`
* **名称:** `青蓝色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.桃红色

* **类型:** `成员常量`
* **名称:** `桃红色`
* **数据类型:** `整数`

##### 火山.基本.颜色类.深灰色

* **类型:** `成员常量`
* **名称:** `深灰色`
* **数据类型:** `整数`
* **相关例程:** [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.颜色类.默认色

* **类型:** `成员常量`
* **名称:** `默认色`
* **数据类型:** `整数`
* **描述:** 注意: 本颜色值不见得能够使用,能否使用请参阅对应接口的文档.
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.颜色类.透明色

* **类型:** `成员常量`
* **名称:** `透明色`
* **数据类型:** `整数`
* **描述:** 注意: 本颜色值不见得能够使用,能否使用请参阅对应接口的文档.
* **相关例程:** [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.颜色类.取颜色值

* **类型:** `全局方法`
* **名称:** `取颜色值`
* **返回值数据类型:** `整数`
* **参数:**
	* `红色分量值` (`整数`): 数值范围从 0 到 255,表示颜色中的红色分量值.
	* `绿色分量值` (`整数`): 数值范围从 0 到 255,表示颜色中的绿色分量值.
	* `蓝色分量值` (`整数`): 数值范围从 0 到 255,表示颜色中的蓝色分量值.
* **特性:**
	* `静态`
* **描述:** 将指定的RGB颜色分量组合为颜色值返回
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main)

##### 火山.基本.颜色类.取颜色红色分量

* **类型:** `全局方法`
* **名称:** `取颜色红色分量`
* **返回值数据类型:** `整数`
* **参数:**
	* `颜色值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 从指定颜色值中取出其红色分量,即red.

##### 火山.基本.颜色类.取颜色绿色分量

* **类型:** `全局方法`
* **名称:** `取颜色绿色分量`
* **返回值数据类型:** `整数`
* **参数:**
	* `颜色值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 从指定颜色值中取出其绿色分量,即green.

##### 火山.基本.颜色类.取颜色蓝色分量

* **类型:** `全局方法`
* **名称:** `取颜色蓝色分量`
* **返回值数据类型:** `整数`
* **参数:**
	* `颜色值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 从指定颜色值中取出其蓝色分量,即blue.

##### 火山.基本.颜色类.颜色偏移

* **类型:** `全局方法`
* **名称:** `颜色偏移`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲处理的颜色值` (`整数`)
	* `所欲添加的偏移量` (`整数`): 偏移量可以是正值或负值
* **特性:**
	* `静态`
* **描述:** 将颜色值加上所指定的偏移量后返回

---

#### 火山.基本.时间转换部分

* **类型:** `类`
* **名称:** `时间转换部分`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `时间操作.辅助类`
* **相关例程:** [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-cron时间表达式-cron-main](#vol-cron时间表达式-cron-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main)

##### 火山.基本.时间转换部分.全部转换

* **类型:** `成员常量`
* **名称:** `全部转换`
* **数据类型:** `时间转换部分`
* **初始值:** `0`
* **相关例程:** [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-cron时间表达式-cron-main](#vol-cron时间表达式-cron-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main)

##### 火山.基本.时间转换部分.日期部分

* **类型:** `成员常量`
* **名称:** `日期部分`
* **数据类型:** `时间转换部分`
* **初始值:** `1`

##### 火山.基本.时间转换部分.时间部分

* **类型:** `成员常量`
* **名称:** `时间部分`
* **数据类型:** `时间转换部分`
* **初始值:** `2`

---

#### 火山.基本.时间字段类型

* **类型:** `类`
* **名称:** `时间字段类型`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `时间操作.辅助类`
* **相关例程:** [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.时间字段类型.年份

* **类型:** `成员常量`
* **名称:** `年份`
* **数据类型:** `时间字段类型`
* **初始值:** `0`

##### 火山.基本.时间字段类型.季度

* **类型:** `成员常量`
* **名称:** `季度`
* **数据类型:** `时间字段类型`
* **初始值:** `1`

##### 火山.基本.时间字段类型.月份

* **类型:** `成员常量`
* **名称:** `月份`
* **数据类型:** `时间字段类型`
* **初始值:** `2`

##### 火山.基本.时间字段类型.周

* **类型:** `成员常量`
* **名称:** `周`
* **数据类型:** `时间字段类型`
* **初始值:** `3`

##### 火山.基本.时间字段类型.日

* **类型:** `成员常量`
* **名称:** `日`
* **数据类型:** `时间字段类型`
* **初始值:** `4`

##### 火山.基本.时间字段类型.小时

* **类型:** `成员常量`
* **名称:** `小时`
* **数据类型:** `时间字段类型`
* **初始值:** `5`
* **相关例程:** [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.时间字段类型.分钟

* **类型:** `成员常量`
* **名称:** `分钟`
* **数据类型:** `时间字段类型`
* **初始值:** `6`

##### 火山.基本.时间字段类型.秒

* **类型:** `成员常量`
* **名称:** `秒`
* **数据类型:** `时间字段类型`
* **初始值:** `7`

##### 火山.基本.时间字段类型.毫秒

* **类型:** `成员常量`
* **名称:** `毫秒`
* **数据类型:** `时间字段类型`
* **初始值:** `8`

---

#### 火山.基本.时间部分类型

* **类型:** `类`
* **名称:** `时间部分类型`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `时间操作.辅助类`

##### 火山.基本.时间部分类型.年份

* **类型:** `成员常量`
* **名称:** `年份`
* **数据类型:** `时间部分类型`
* **初始值:** `0`

##### 火山.基本.时间部分类型.季度

* **类型:** `成员常量`
* **名称:** `季度`
* **数据类型:** `时间部分类型`
* **初始值:** `1`

##### 火山.基本.时间部分类型.月份

* **类型:** `成员常量`
* **名称:** `月份`
* **数据类型:** `时间部分类型`
* **初始值:** `2`

##### 火山.基本.时间部分类型.自年首周数

* **类型:** `成员常量`
* **名称:** `自年首周数`
* **数据类型:** `时间部分类型`
* **初始值:** `3`
* **描述:** 从1开始

##### 火山.基本.时间部分类型.日

* **类型:** `成员常量`
* **名称:** `日`
* **数据类型:** `时间部分类型`
* **初始值:** `4`

##### 火山.基本.时间部分类型.小时

* **类型:** `成员常量`
* **名称:** `小时`
* **数据类型:** `时间部分类型`
* **初始值:** `5`

##### 火山.基本.时间部分类型.分钟

* **类型:** `成员常量`
* **名称:** `分钟`
* **数据类型:** `时间部分类型`
* **初始值:** `6`

##### 火山.基本.时间部分类型.秒

* **类型:** `成员常量`
* **名称:** `秒`
* **数据类型:** `时间部分类型`
* **初始值:** `7`

##### 火山.基本.时间部分类型.星期几

* **类型:** `成员常量`
* **名称:** `星期几`
* **数据类型:** `时间部分类型`
* **初始值:** `8`

##### 火山.基本.时间部分类型.自年首天数

* **类型:** `成员常量`
* **名称:** `自年首天数`
* **数据类型:** `时间部分类型`
* **初始值:** `9`
* **描述:** 从1开始

---

#### 火山.基本.时间操作类

* **类型:** `类`
* **名称:** `时间操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `时间操作`
* **描述:** 提供常用日期时间操作支持. 注意: 日期时间值使用小数来记录
* **相关例程:** [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-cron时间表达式-cron-main](#vol-cron时间表达式-cron-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.时间操作类.时间到文本

* **类型:** `全局方法`
* **名称:** `时间到文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `日期时间值` (`小数`): 提供具体所欲转换的日期时间值
	* `转换部分` (`时间转换部分`, 默认值: `时间转换部分.全部转换`): 提供时间的哪些部分需要被转换
	* `是否采用中文格式` (`逻辑型`, 默认值: `真`): 指定是否返回中文格式的日期时间文本
* **特性:**
	* `静态`
* **描述:** 将所指定的日期时间值转换到文本格式后返回. 所返回日期时间文本内容的格式如下(时分秒为0将被省略): 中文格式: 1973年11月15日12时30分25秒非中文格式: 11/15/1973 12:30:25
* **返回值描述:** 成功返回对应的日期时间文本,失败返回空文本.
* **相关例程:** [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-cron时间表达式-cron-main](#vol-cron时间表达式-cron-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main)

##### 火山.基本.时间操作类.时间到格式文本

* **类型:** `全局方法`
* **名称:** `时间到格式文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `日期时间值` (`小数`): 提供具体所欲转换的日期时间值
	* `转换格式` (`文本型`, 默认值: `"%Y年%#m月%#d日%#H时%#M分%#S秒"`): 提供具体的转换格式文本,其中可以包括以'%'开头的替换符,可以使用的替换符由如下这些: %a: 星期缩写名称; %A: 星期完整名称; %b: 月份缩写名称; %B: 月份完整名称; %c: 本地日期时间描述文本; %#c: 本地日期时间长描述文本,如: "Tuesday, March 14, 1995, 12:41:29"; %d: 在月份中的日 (01 – 31); %H: 小时(24小时制) (00 – 23); %I: 小时(12小时制) (01 – 12); %j: 在年中的日 (001 – 366); %m: 月份 (01 – 12); %M: 分钟 (00 – 59); %p: 现行本地的 A.M./P.M 标识, 用作表示12小时时钟; %S: 秒 (00 – 59); %U: 在年中的星期,以周日为每星期的第一天 (00 – 53); %w: 在星期中的天 (0 – 6; 周日为 0); %W: 在年中的星期,以周一为每星期的第一天 (00 – 53); %x: 本地日期描述文本; %#x 本地日期长描述文本,如: "Tuesday, March 14, 1995"; %X: 本地时间描述文本; %y: 不携带世纪部分的年份 (00 – 99); %Y: 年份; %z, %Z: 时区的名称或缩写,为空如果时区未知; %%: 百分号字符本身; %#d, %#H, %#I, %#j, %#m, %#M, %#S, %#U, %#w, %#W, %#y, %#Y: 不加'#'字符的对应替换符,但是替换文本去除掉首部的零. 格式文本中的非替换符部分原样输出到转换结果文本中.
* **特性:**
	* `静态`
* **描述:** 将日期时间值按照所指定的格式转换到文本格式后返回
* **返回值描述:** 成功返回对应的日期时间文本,失败返回空文本.
* **相关例程:** [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.时间操作类.到时间

* **类型:** `全局方法`
* **名称:** `到时间`
* **返回值数据类型:** `小数`
* **参数:**
	* `日期时间文本` (`文本型`): 提供具体所欲转换的日期时间文本内容,年份以后的所有部分均可以省略. 格式要求如下: 中文格式(年月日排列顺序为年月日),例如: 1. 1973年11月15日12时30分25秒 2. 1973/11/15 12:30:25 3. 1973/11/15/12/30/25 4. 1973/11/15/12:30:25 5. 1973-11-15-12-30-25 6. 1973-11-15-12:30:25 7. 1973.11.15 12:30:25 8. 19731115123025非中文格式(年月日排列顺序为月日年),例如: 1. 11/15/1973 12:30:25 2. 11/15/1973/12/30/25 4. 11/15/1973/12:30:25 5. 11-15-1973-12-30-25 6. 11-15-1973-12:30:25 7. 11.15.1973 12:30:25
	* `是否为中文格式` (`逻辑型`, 默认值: `真`): 指定所提供的日期时间文本内容是否为中文格式
* **特性:**
	* `静态`
* **描述:** 指定文本转换为时间并返回,如果给定文本不符合书写格式要求或者时间值错误导致不能进行转换,将返回"数值范围.最小日期时间值"常量值(100年1月1日),可以使用"为最小时间"方法进行判断.

##### 火山.基本.时间操作类.为有效时间

* **类型:** `全局方法`
* **名称:** `为有效时间`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `日期时间值` (`小数`): 提供具体所欲检查的日期时间值
* **特性:**
	* `静态`
* **描述:** 返回所提供的日期时间值是否有效

##### 火山.基本.时间操作类.为最小时间

* **类型:** `全局方法`
* **名称:** `为最小时间`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `日期时间值` (`小数`): 提供具体所欲检查的日期时间值
* **特性:**
	* `静态`
* **描述:** 返回所提供的日期时间值是否为最小有效时间

##### 火山.基本.时间操作类.增减时间

* **类型:** `全局方法`
* **名称:** `增减时间`
* **返回值数据类型:** `小数`
* **参数:**
	* `被处理的时间` (`小数`)
	* `被增加字段` (`时间字段类型`): 指定时间的哪一部分被进行增减操作
	* `增加值` (`长整数`): 相对于被增加部分的增加或减少数值
* **特性:**
	* `静态`
* **描述:** 返回一个时间,这一时间被加上或减去了一段间隔. 如果改变后的时间无效,将自动靠近最近的有效时间.
* **相关例程:** [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.时间操作类.取时间间隔

* **类型:** `全局方法`
* **名称:** `取时间间隔`
* **返回值数据类型:** `小数`
* **参数:**
	* `时间1` (`小数`)
	* `时间2` (`小数`)
	* `所欲取间隔的字段` (`时间字段类型`)
* **特性:**
	* `静态`
* **描述:** 返回"时间1"减去"时间2"之后的间隔数目. 注意: 每个星期以星期天为第一天.

##### 火山.基本.时间操作类.取某月天数

* **类型:** `全局方法`
* **名称:** `取某月天数`
* **返回值数据类型:** `整数`
* **参数:**
	* `年份` (`整数`): 指定年份,有效参数值从 100 到 9999.
	* `月份` (`整数`): 指定月份,有效参数值从 1 到 12.
* **特性:**
	* `静态`
* **描述:** 返回指定月份所包含的天数,如果给定的月份无效,返回0.

##### 火山.基本.时间操作类.取时间部分

* **类型:** `全局方法`
* **名称:** `取时间部分`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲取其部分的时间` (`小数`)
	* `欲取的时间部分` (`时间部分类型`)
* **特性:**
	* `静态`
* **描述:** 返回一个包含已知时间指定部分的值,如所提供时间无效,将返回-1.

##### 火山.基本.时间操作类.取年份

* **类型:** `全局方法`
* **名称:** `取年份`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个值为 100 到 9999 之间的整数,表示指定时间中的年份.

##### 火山.基本.时间操作类.取月份

* **类型:** `全局方法`
* **名称:** `取月份`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个值为 1 到 12 之间的整数,表示指定时间中的月份.

##### 火山.基本.时间操作类.取日

* **类型:** `全局方法`
* **名称:** `取日`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个值为 1 到 31 之间的整数,表示一个月中的某一日.

##### 火山.基本.时间操作类.取星期几

* **类型:** `全局方法`
* **名称:** `取星期几`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个值为 1 到 7 之间的整数,表示一个星期中的某一日. 星期日为 1,星期一为 2,依此类推.

##### 火山.基本.时间操作类.取小时

* **类型:** `全局方法`
* **名称:** `取小时`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个值为 0 到 23 之间的整数,表示一天中的某一小时.
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.时间操作类.取分钟

* **类型:** `全局方法`
* **名称:** `取分钟`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个值为 0 到 59 之间的整数,表示一小时中的某一分钟.
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.时间操作类.取秒

* **类型:** `全局方法`
* **名称:** `取秒`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个值为 0 到 59 之间的整数,表示一分钟中的某一秒.
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.时间操作类.指定时间

* **类型:** `全局方法`
* **名称:** `指定时间`
* **返回值数据类型:** `小数`
* **参数:**
	* `年` (`整数`)
	* `月` (`整数`, 默认值: `1`)
	* `日` (`整数`, 默认值: `1`)
	* `小时` (`整数`, 默认值: `0`)
	* `分钟` (`整数`, 默认值: `0`)
	* `秒` (`整数`, 默认值: `0`)
* **特性:**
	* `静态`
* **描述:** 返回包含指定年,月,日,小时,分,秒的时间. 如果指定了无效时间,将返回"数值范围.最小日期时间值"常量值(100年1月1日),可以使用"为最小时间"方法进行判断.
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main)

##### 火山.基本.时间操作类.取现行时间

* **类型:** `全局方法`
* **名称:** `取现行时间`
* **返回值数据类型:** `小数`
* **特性:**
	* `静态`
* **描述:** 返回当前操作系统日期及时间
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-cron时间表达式-cron-main](#vol-cron时间表达式-cron-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.时间操作类.置现行时间

* **类型:** `全局方法`
* **名称:** `置现行时间`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲设置的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 设置当前操作系统日期及时间,返回是否成功.

##### 火山.基本.时间操作类.取日期

* **类型:** `全局方法`
* **名称:** `取日期`
* **返回值数据类型:** `小数`
* **参数:**
	* `所欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个日期时间型数据的日期部分,其小时/分钟/秒被固定设置为0时0分0秒.

##### 火山.基本.时间操作类.取时间

* **类型:** `全局方法`
* **名称:** `取时间`
* **返回值数据类型:** `小数`
* **参数:**
	* `所欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个日期时间型数据的时间部分,其年/月/日被固定设置为2000年1月1日.

##### 火山.基本.时间操作类.取经历秒数

* **类型:** `全局方法`
* **名称:** `取经历秒数`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回基于一个过去特定基准时间(北京时间 2017/7/5 15:55)的已经经过的秒数,必定大于等于0.

##### 火山.基本.时间操作类.取时间戳

* **类型:** `全局方法`
* **名称:** `取时间戳`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回所指定时间相对1970年1月1日0时0分0秒所经过的秒数(UNIX时间戳)
* **相关例程:** [vol-cron时间表达式-cron-main](#vol-cron时间表达式-cron-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.时间操作类.时间戳到时间

* **类型:** `全局方法`
* **名称:** `时间戳到时间`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲处理的时间戳` (`整数`): 相对1970年1月1日0时0分0秒所经过的秒数(UNIX时间戳)
* **特性:**
	* `静态`
* **描述:** 将所指定时间戳值转换到时间
* **相关例程:** [vol-cron时间表达式-cron-main](#vol-cron时间表达式-cron-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.时间操作类.取毫秒时间戳

* **类型:** `全局方法`
* **名称:** `取毫秒时间戳`
* **返回值数据类型:** `长整数`
* **参数:**
	* `欲处理的时间` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回所指定时间相对1970年1月1日0时0分0秒所经过的毫秒数(UNIX时间戳)
* **相关例程:** [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main)

##### 火山.基本.时间操作类.毫秒时间戳到时间

* **类型:** `全局方法`
* **名称:** `毫秒时间戳到时间`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲处理的时间戳` (`长整数`): 相对1970年1月1日0时0分0秒所经过的毫秒数(UNIX时间戳)
* **特性:**
	* `静态`
* **描述:** 将所指定毫秒时间戳值转换到时间

---

#### 火山.基本.横向对齐模式

* **类型:** `类`
* **名称:** `横向对齐模式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `其它`
* **描述:** 提供各种横向对齐模式

##### 火山.基本.横向对齐模式.左边

* **类型:** `成员常量`
* **名称:** `左边`
* **数据类型:** `横向对齐模式`

##### 火山.基本.横向对齐模式.居中

* **类型:** `成员常量`
* **名称:** `居中`
* **数据类型:** `横向对齐模式`

##### 火山.基本.横向对齐模式.右边

* **类型:** `成员常量`
* **名称:** `右边`
* **数据类型:** `横向对齐模式`

---

#### 火山.基本.纵向对齐模式

* **类型:** `类`
* **名称:** `纵向对齐模式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `其它`
* **描述:** 提供各种纵向对齐模式

##### 火山.基本.纵向对齐模式.顶边

* **类型:** `成员常量`
* **名称:** `顶边`
* **数据类型:** `纵向对齐模式`

##### 火山.基本.纵向对齐模式.居中

* **类型:** `成员常量`
* **名称:** `居中`
* **数据类型:** `纵向对齐模式`

##### 火山.基本.纵向对齐模式.底边

* **类型:** `成员常量`
* **名称:** `底边`
* **数据类型:** `纵向对齐模式`

---

#### 火山.基本.辅助键状态

* **类型:** `类`
* **名称:** `辅助键状态`
* **文档分类:** `常用功能.辅助类`
* **描述:** 提供各种辅助键的状态值. 这些状态值可以相加在一起以表达辅助键组合状态值,要判断组合状态值中是否按下了某个辅助键,使用"位与"命令进行比较即可. 另外,辅助键组合状态值可以与"按键码"类中的按键代码常量值相加组合起来代表一个组合键.

##### 火山.基本.辅助键状态.Ctrl

* **类型:** `成员常量`
* **名称:** `Ctrl`
* **数据类型:** `整数`

##### 火山.基本.辅助键状态.Shift

* **类型:** `成员常量`
* **名称:** `Shift`
* **数据类型:** `整数`

##### 火山.基本.辅助键状态.Alt

* **类型:** `成员常量`
* **名称:** `Alt`
* **数据类型:** `整数`

---

#### 火山.基本.按键码

* **类型:** `类`
* **名称:** `按键码`
* **文档分类:** `常用功能.辅助类`
* **描述:** 提供所有按键的代码值
* **相关例程:** [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-系统全局热键-syshotkey-main](#vol-系统全局热键-syshotkey-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main)

##### 火山.基本.按键码.空

* **类型:** `成员常量`
* **名称:** `空`
* **数据类型:** `整数`
* **描述:** 表示不为任何按键
* **相关例程:** [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main), [vol-系统全局热键-syshotkey-main](#vol-系统全局热键-syshotkey-main)

##### 火山.基本.按键码.鼠标左键

* **类型:** `成员常量`
* **名称:** `鼠标左键`
* **数据类型:** `整数`
* **描述:** 鼠标左键
* **相关例程:** [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main)

##### 火山.基本.按键码.鼠标右键

* **类型:** `成员常量`
* **名称:** `鼠标右键`
* **数据类型:** `整数`
* **描述:** 鼠标右键

##### 火山.基本.按键码.Break键

* **类型:** `成员常量`
* **名称:** `Break键`
* **数据类型:** `整数`

##### 火山.基本.按键码.鼠标中键

* **类型:** `成员常量`
* **名称:** `鼠标中键`
* **数据类型:** `整数`
* **描述:** 鼠标中键

##### 火山.基本.按键码.鼠标X1键

* **类型:** `成员常量`
* **名称:** `鼠标X1键`
* **数据类型:** `整数`
* **描述:** Windows 2000 鼠标X1键

##### 火山.基本.按键码.鼠标X2键

* **类型:** `成员常量`
* **名称:** `鼠标X2键`
* **数据类型:** `整数`
* **描述:** Windows 2000 鼠标X2键

##### 火山.基本.按键码.退格键

* **类型:** `成员常量`
* **名称:** `退格键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Tab键

* **类型:** `成员常量`
* **名称:** `Tab键`
* **数据类型:** `整数`

##### 火山.基本.按键码.副键盘中键

* **类型:** `成员常量`
* **名称:** `副键盘中键`
* **数据类型:** `整数`

##### 火山.基本.按键码.回车键

* **类型:** `成员常量`
* **名称:** `回车键`
* **数据类型:** `整数`
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main)

##### 火山.基本.按键码.Shift键

* **类型:** `成员常量`
* **名称:** `Shift键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Ctrl键

* **类型:** `成员常量`
* **名称:** `Ctrl键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Alt键

* **类型:** `成员常量`
* **名称:** `Alt键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Pause键

* **类型:** `成员常量`
* **名称:** `Pause键`
* **数据类型:** `整数`

##### 火山.基本.按键码.CapsLock键

* **类型:** `成员常量`
* **名称:** `CapsLock键`
* **数据类型:** `整数`
* **相关例程:** [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.按键码.KANA键

* **类型:** `成员常量`
* **名称:** `KANA键`
* **数据类型:** `整数`
* **描述:** KANA, HANGEUL, HANGUL 按键

##### 火山.基本.按键码.JUNJA键

* **类型:** `成员常量`
* **名称:** `JUNJA键`
* **数据类型:** `整数`

##### 火山.基本.按键码.FINAL键

* **类型:** `成员常量`
* **名称:** `FINAL键`
* **数据类型:** `整数`

##### 火山.基本.按键码.HANJA键

* **类型:** `成员常量`
* **名称:** `HANJA键`
* **数据类型:** `整数`
* **描述:** HANJA, KANJI 按键

##### 火山.基本.按键码.Esc键

* **类型:** `成员常量`
* **名称:** `Esc键`
* **数据类型:** `整数`

##### 火山.基本.按键码.转换键

* **类型:** `成员常量`
* **名称:** `转换键`
* **数据类型:** `整数`

##### 火山.基本.按键码.不转换键

* **类型:** `成员常量`
* **名称:** `不转换键`
* **数据类型:** `整数`

##### 火山.基本.按键码.认可键

* **类型:** `成员常量`
* **名称:** `认可键`
* **数据类型:** `整数`

##### 火山.基本.按键码.模式改变键

* **类型:** `成员常量`
* **名称:** `模式改变键`
* **数据类型:** `整数`

##### 火山.基本.按键码.空格键

* **类型:** `成员常量`
* **名称:** `空格键`
* **数据类型:** `整数`
* **相关例程:** [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main)

##### 火山.基本.按键码.PageUp键

* **类型:** `成员常量`
* **名称:** `PageUp键`
* **数据类型:** `整数`

##### 火山.基本.按键码.PageDown键

* **类型:** `成员常量`
* **名称:** `PageDown键`
* **数据类型:** `整数`

##### 火山.基本.按键码.End键

* **类型:** `成员常量`
* **名称:** `End键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Home键

* **类型:** `成员常量`
* **名称:** `Home键`
* **数据类型:** `整数`

##### 火山.基本.按键码.左光标键

* **类型:** `成员常量`
* **名称:** `左光标键`
* **数据类型:** `整数`
* **相关例程:** [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main)

##### 火山.基本.按键码.上光标键

* **类型:** `成员常量`
* **名称:** `上光标键`
* **数据类型:** `整数`

##### 火山.基本.按键码.右光标键

* **类型:** `成员常量`
* **名称:** `右光标键`
* **数据类型:** `整数`
* **相关例程:** [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main)

##### 火山.基本.按键码.下光标键

* **类型:** `成员常量`
* **名称:** `下光标键`
* **数据类型:** `整数`

##### 火山.基本.按键码.选择键

* **类型:** `成员常量`
* **名称:** `选择键`
* **数据类型:** `整数`

##### 火山.基本.按键码.打印键

* **类型:** `成员常量`
* **名称:** `打印键`
* **数据类型:** `整数`

##### 火山.基本.按键码.执行键

* **类型:** `成员常量`
* **名称:** `执行键`
* **数据类型:** `整数`

##### 火山.基本.按键码.截屏键

* **类型:** `成员常量`
* **名称:** `截屏键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Ins键

* **类型:** `成员常量`
* **名称:** `Ins键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Del键

* **类型:** `成员常量`
* **名称:** `Del键`
* **数据类型:** `整数`

##### 火山.基本.按键码.帮助键

* **类型:** `成员常量`
* **名称:** `帮助键`
* **数据类型:** `整数`

##### 火山.基本.按键码.键0

* **类型:** `成员常量`
* **名称:** `键0`
* **数据类型:** `整数`

##### 火山.基本.按键码.键1

* **类型:** `成员常量`
* **名称:** `键1`
* **数据类型:** `整数`

##### 火山.基本.按键码.键2

* **类型:** `成员常量`
* **名称:** `键2`
* **数据类型:** `整数`

##### 火山.基本.按键码.键3

* **类型:** `成员常量`
* **名称:** `键3`
* **数据类型:** `整数`

##### 火山.基本.按键码.键4

* **类型:** `成员常量`
* **名称:** `键4`
* **数据类型:** `整数`

##### 火山.基本.按键码.键5

* **类型:** `成员常量`
* **名称:** `键5`
* **数据类型:** `整数`

##### 火山.基本.按键码.键6

* **类型:** `成员常量`
* **名称:** `键6`
* **数据类型:** `整数`

##### 火山.基本.按键码.键7

* **类型:** `成员常量`
* **名称:** `键7`
* **数据类型:** `整数`

##### 火山.基本.按键码.键8

* **类型:** `成员常量`
* **名称:** `键8`
* **数据类型:** `整数`

##### 火山.基本.按键码.键9

* **类型:** `成员常量`
* **名称:** `键9`
* **数据类型:** `整数`

##### 火山.基本.按键码.A键

* **类型:** `成员常量`
* **名称:** `A键`
* **数据类型:** `整数`
* **相关例程:** [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main)

##### 火山.基本.按键码.B键

* **类型:** `成员常量`
* **名称:** `B键`
* **数据类型:** `整数`

##### 火山.基本.按键码.C键

* **类型:** `成员常量`
* **名称:** `C键`
* **数据类型:** `整数`
* **相关例程:** [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main)

##### 火山.基本.按键码.D键

* **类型:** `成员常量`
* **名称:** `D键`
* **数据类型:** `整数`

##### 火山.基本.按键码.E键

* **类型:** `成员常量`
* **名称:** `E键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F键

* **类型:** `成员常量`
* **名称:** `F键`
* **数据类型:** `整数`

##### 火山.基本.按键码.G键

* **类型:** `成员常量`
* **名称:** `G键`
* **数据类型:** `整数`

##### 火山.基本.按键码.H键

* **类型:** `成员常量`
* **名称:** `H键`
* **数据类型:** `整数`

##### 火山.基本.按键码.I键

* **类型:** `成员常量`
* **名称:** `I键`
* **数据类型:** `整数`

##### 火山.基本.按键码.J键

* **类型:** `成员常量`
* **名称:** `J键`
* **数据类型:** `整数`

##### 火山.基本.按键码.K键

* **类型:** `成员常量`
* **名称:** `K键`
* **数据类型:** `整数`
* **相关例程:** [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main)

##### 火山.基本.按键码.L键

* **类型:** `成员常量`
* **名称:** `L键`
* **数据类型:** `整数`

##### 火山.基本.按键码.M键

* **类型:** `成员常量`
* **名称:** `M键`
* **数据类型:** `整数`

##### 火山.基本.按键码.N键

* **类型:** `成员常量`
* **名称:** `N键`
* **数据类型:** `整数`

##### 火山.基本.按键码.O键

* **类型:** `成员常量`
* **名称:** `O键`
* **数据类型:** `整数`
* **相关例程:** [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main)

##### 火山.基本.按键码.P键

* **类型:** `成员常量`
* **名称:** `P键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Q键

* **类型:** `成员常量`
* **名称:** `Q键`
* **数据类型:** `整数`

##### 火山.基本.按键码.R键

* **类型:** `成员常量`
* **名称:** `R键`
* **数据类型:** `整数`

##### 火山.基本.按键码.S键

* **类型:** `成员常量`
* **名称:** `S键`
* **数据类型:** `整数`

##### 火山.基本.按键码.T键

* **类型:** `成员常量`
* **名称:** `T键`
* **数据类型:** `整数`

##### 火山.基本.按键码.U键

* **类型:** `成员常量`
* **名称:** `U键`
* **数据类型:** `整数`

##### 火山.基本.按键码.V键

* **类型:** `成员常量`
* **名称:** `V键`
* **数据类型:** `整数`

##### 火山.基本.按键码.W键

* **类型:** `成员常量`
* **名称:** `W键`
* **数据类型:** `整数`

##### 火山.基本.按键码.X键

* **类型:** `成员常量`
* **名称:** `X键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Y键

* **类型:** `成员常量`
* **名称:** `Y键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Z键

* **类型:** `成员常量`
* **名称:** `Z键`
* **数据类型:** `整数`

##### 火山.基本.按键码.左WIN键

* **类型:** `成员常量`
* **名称:** `左WIN键`
* **数据类型:** `整数`

##### 火山.基本.按键码.右WIN键

* **类型:** `成员常量`
* **名称:** `右WIN键`
* **数据类型:** `整数`

##### 火山.基本.按键码.应用程序键

* **类型:** `成员常量`
* **名称:** `应用程序键`
* **数据类型:** `整数`

##### 火山.基本.按键码.睡眠键

* **类型:** `成员常量`
* **名称:** `睡眠键`
* **数据类型:** `整数`

##### 火山.基本.按键码.副键盘星号

* **类型:** `成员常量`
* **名称:** `副键盘星号`
* **数据类型:** `整数`

##### 火山.基本.按键码.副键盘加号

* **类型:** `成员常量`
* **名称:** `副键盘加号`
* **数据类型:** `整数`

##### 火山.基本.按键码.F1键

* **类型:** `成员常量`
* **名称:** `F1键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F2键

* **类型:** `成员常量`
* **名称:** `F2键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F3键

* **类型:** `成员常量`
* **名称:** `F3键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F4键

* **类型:** `成员常量`
* **名称:** `F4键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F5键

* **类型:** `成员常量`
* **名称:** `F5键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F6键

* **类型:** `成员常量`
* **名称:** `F6键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F7键

* **类型:** `成员常量`
* **名称:** `F7键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F8键

* **类型:** `成员常量`
* **名称:** `F8键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F9键

* **类型:** `成员常量`
* **名称:** `F9键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F10键

* **类型:** `成员常量`
* **名称:** `F10键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F11键

* **类型:** `成员常量`
* **名称:** `F11键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F12键

* **类型:** `成员常量`
* **名称:** `F12键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F13键

* **类型:** `成员常量`
* **名称:** `F13键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F14键

* **类型:** `成员常量`
* **名称:** `F14键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F15键

* **类型:** `成员常量`
* **名称:** `F15键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F16键

* **类型:** `成员常量`
* **名称:** `F16键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F17键

* **类型:** `成员常量`
* **名称:** `F17键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F18键

* **类型:** `成员常量`
* **名称:** `F18键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F19键

* **类型:** `成员常量`
* **名称:** `F19键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F20键

* **类型:** `成员常量`
* **名称:** `F20键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F21键

* **类型:** `成员常量`
* **名称:** `F21键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F22键

* **类型:** `成员常量`
* **名称:** `F22键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F23键

* **类型:** `成员常量`
* **名称:** `F23键`
* **数据类型:** `整数`

##### 火山.基本.按键码.F24键

* **类型:** `成员常量`
* **名称:** `F24键`
* **数据类型:** `整数`

##### 火山.基本.按键码.NumLock键

* **类型:** `成员常量`
* **名称:** `NumLock键`
* **数据类型:** `整数`

##### 火山.基本.按键码.ScrollLock键

* **类型:** `成员常量`
* **名称:** `ScrollLock键`
* **数据类型:** `整数`

##### 火山.基本.按键码.字典键

* **类型:** `成员常量`
* **名称:** `字典键`
* **数据类型:** `整数`

##### 火山.基本.按键码.取消单词登记键

* **类型:** `成员常量`
* **名称:** `取消单词登记键`
* **数据类型:** `整数`

##### 火山.基本.按键码.单词登记键

* **类型:** `成员常量`
* **名称:** `单词登记键`
* **数据类型:** `整数`

##### 火山.基本.按键码.左OYAYUBI键

* **类型:** `成员常量`
* **名称:** `左OYAYUBI键`
* **数据类型:** `整数`

##### 火山.基本.按键码.右OYAYUBI键

* **类型:** `成员常量`
* **名称:** `右OYAYUBI键`
* **数据类型:** `整数`

##### 火山.基本.按键码.左Shift键

* **类型:** `成员常量`
* **名称:** `左Shift键`
* **数据类型:** `整数`

##### 火山.基本.按键码.右Shift键

* **类型:** `成员常量`
* **名称:** `右Shift键`
* **数据类型:** `整数`

##### 火山.基本.按键码.左Ctrl键

* **类型:** `成员常量`
* **名称:** `左Ctrl键`
* **数据类型:** `整数`

##### 火山.基本.按键码.右Ctrl键

* **类型:** `成员常量`
* **名称:** `右Ctrl键`
* **数据类型:** `整数`

##### 火山.基本.按键码.左菜单键

* **类型:** `成员常量`
* **名称:** `左菜单键`
* **数据类型:** `整数`

##### 火山.基本.按键码.右菜单键

* **类型:** `成员常量`
* **名称:** `右菜单键`
* **数据类型:** `整数`

##### 火山.基本.按键码.浏览器回退键

* **类型:** `成员常量`
* **名称:** `浏览器回退键`
* **数据类型:** `整数`

##### 火山.基本.按键码.浏览器前进键

* **类型:** `成员常量`
* **名称:** `浏览器前进键`
* **数据类型:** `整数`

##### 火山.基本.按键码.浏览器刷新键

* **类型:** `成员常量`
* **名称:** `浏览器刷新键`
* **数据类型:** `整数`

##### 火山.基本.按键码.浏览器停止键

* **类型:** `成员常量`
* **名称:** `浏览器停止键`
* **数据类型:** `整数`

##### 火山.基本.按键码.浏览器搜索键

* **类型:** `成员常量`
* **名称:** `浏览器搜索键`
* **数据类型:** `整数`

##### 火山.基本.按键码.浏览器收藏键

* **类型:** `成员常量`
* **名称:** `浏览器收藏键`
* **数据类型:** `整数`

##### 火山.基本.按键码.浏览器主页键

* **类型:** `成员常量`
* **名称:** `浏览器主页键`
* **数据类型:** `整数`

##### 火山.基本.按键码.音量静音键

* **类型:** `成员常量`
* **名称:** `音量静音键`
* **数据类型:** `整数`

##### 火山.基本.按键码.降低音量键

* **类型:** `成员常量`
* **名称:** `降低音量键`
* **数据类型:** `整数`

##### 火山.基本.按键码.提高音量键

* **类型:** `成员常量`
* **名称:** `提高音量键`
* **数据类型:** `整数`

##### 火山.基本.按键码.下一曲目键

* **类型:** `成员常量`
* **名称:** `下一曲目键`
* **数据类型:** `整数`

##### 火山.基本.按键码.前一曲目键

* **类型:** `成员常量`
* **名称:** `前一曲目键`
* **数据类型:** `整数`

##### 火山.基本.按键码.停止媒体键

* **类型:** `成员常量`
* **名称:** `停止媒体键`
* **数据类型:** `整数`

##### 火山.基本.按键码.播放暂停键

* **类型:** `成员常量`
* **名称:** `播放暂停键`
* **数据类型:** `整数`

##### 火山.基本.按键码.邮件键

* **类型:** `成员常量`
* **名称:** `邮件键`
* **数据类型:** `整数`

##### 火山.基本.按键码.选择媒体键

* **类型:** `成员常量`
* **名称:** `选择媒体键`
* **数据类型:** `整数`

##### 火山.基本.按键码.应用程序键1

* **类型:** `成员常量`
* **名称:** `应用程序键1`
* **数据类型:** `整数`

##### 火山.基本.按键码.应用程序键2

* **类型:** `成员常量`
* **名称:** `应用程序键2`
* **数据类型:** `整数`

##### 火山.基本.按键码.分号键

* **类型:** `成员常量`
* **名称:** `分号键`
* **数据类型:** `整数`
* **描述:** ';'

##### 火山.基本.按键码.等号键

* **类型:** `成员常量`
* **名称:** `等号键`
* **数据类型:** `整数`
* **描述:** '='

##### 火山.基本.按键码.逗号键

* **类型:** `成员常量`
* **名称:** `逗号键`
* **数据类型:** `整数`
* **描述:** ','

##### 火山.基本.按键码.减号键

* **类型:** `成员常量`
* **名称:** `减号键`
* **数据类型:** `整数`
* **描述:** '-'

##### 火山.基本.按键码.圆点键

* **类型:** `成员常量`
* **名称:** `圆点键`
* **数据类型:** `整数`
* **描述:** '.'

##### 火山.基本.按键码.除号键

* **类型:** `成员常量`
* **名称:** `除号键`
* **数据类型:** `整数`
* **描述:** '/'

##### 火山.基本.按键码.反撇号键

* **类型:** `成员常量`
* **名称:** `反撇号键`
* **数据类型:** `整数`
* **描述:** '`'

##### 火山.基本.按键码.左中括号键

* **类型:** `成员常量`
* **名称:** `左中括号键`
* **数据类型:** `整数`
* **描述:** '['

##### 火山.基本.按键码.斜杠键

* **类型:** `成员常量`
* **名称:** `斜杠键`
* **数据类型:** `整数`
* **描述:** '\'

##### 火山.基本.按键码.右中括号键

* **类型:** `成员常量`
* **名称:** `右中括号键`
* **数据类型:** `整数`
* **描述:** ']'

##### 火山.基本.按键码.单引号键

* **类型:** `成员常量`
* **名称:** `单引号键`
* **数据类型:** `整数`
* **描述:** '''

##### 火山.基本.按键码.OemAX键

* **类型:** `成员常量`
* **名称:** `OemAX键`
* **数据类型:** `整数`
* **描述:** 扩展/增强键盘: 日式键盘上的'AX'按键

##### 火山.基本.按键码.Oem102键

* **类型:** `成员常量`
* **名称:** `Oem102键`
* **数据类型:** `整数`
* **描述:** 扩展/增强键盘: RT 102键盘上的"<>"或"\|"按键

##### 火山.基本.按键码.Ico帮助键

* **类型:** `成员常量`
* **名称:** `Ico帮助键`
* **数据类型:** `整数`
* **描述:** 扩展/增强键盘: ICO键盘上的帮助键

##### 火山.基本.按键码.Ico00键

* **类型:** `成员常量`
* **名称:** `Ico00键`
* **数据类型:** `整数`
* **描述:** 扩展/增强键盘: ICO键盘上的00键

##### 火山.基本.按键码.处理键

* **类型:** `成员常量`
* **名称:** `处理键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Ico清理键

* **类型:** `成员常量`
* **名称:** `Ico清理键`
* **数据类型:** `整数`

##### 火山.基本.按键码.包装键

* **类型:** `成员常量`
* **名称:** `包装键`
* **数据类型:** `整数`
* **描述:** 用于传递 Unicode 字符,就好像它们是击键一样.

##### 火山.基本.按键码.Oem重置键

* **类型:** `成员常量`
* **名称:** `Oem重置键`
* **数据类型:** `整数`
* **描述:** 以下为诺基亚或爱立信定义的按键码

##### 火山.基本.按键码.Oem跳转键

* **类型:** `成员常量`
* **名称:** `Oem跳转键`
* **数据类型:** `整数`

##### 火山.基本.按键码.OemPA1键

* **类型:** `成员常量`
* **名称:** `OemPA1键`
* **数据类型:** `整数`

##### 火山.基本.按键码.OemPA2键

* **类型:** `成员常量`
* **名称:** `OemPA2键`
* **数据类型:** `整数`

##### 火山.基本.按键码.OemPA3键

* **类型:** `成员常量`
* **名称:** `OemPA3键`
* **数据类型:** `整数`

##### 火山.基本.按键码.OemWSCTRL键

* **类型:** `成员常量`
* **名称:** `OemWSCTRL键`
* **数据类型:** `整数`

##### 火山.基本.按键码.OemCUSEL键

* **类型:** `成员常量`
* **名称:** `OemCUSEL键`
* **数据类型:** `整数`

##### 火山.基本.按键码.OemATTN键

* **类型:** `成员常量`
* **名称:** `OemATTN键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Oem完成键

* **类型:** `成员常量`
* **名称:** `Oem完成键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Oem复制键

* **类型:** `成员常量`
* **名称:** `Oem复制键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Oem自动键

* **类型:** `成员常量`
* **名称:** `Oem自动键`
* **数据类型:** `整数`

##### 火山.基本.按键码.OemENLW键

* **类型:** `成员常量`
* **名称:** `OemENLW键`
* **数据类型:** `整数`

##### 火山.基本.按键码.Oem回退制表键

* **类型:** `成员常量`
* **名称:** `Oem回退制表键`
* **数据类型:** `整数`

##### 火山.基本.按键码.ATTN键

* **类型:** `成员常量`
* **名称:** `ATTN键`
* **数据类型:** `整数`

##### 火山.基本.按键码.CRSEL键

* **类型:** `成员常量`
* **名称:** `CRSEL键`
* **数据类型:** `整数`

##### 火山.基本.按键码.EXSEL键

* **类型:** `成员常量`
* **名称:** `EXSEL键`
* **数据类型:** `整数`

##### 火山.基本.按键码.EREOF键

* **类型:** `成员常量`
* **名称:** `EREOF键`
* **数据类型:** `整数`

##### 火山.基本.按键码.播放键

* **类型:** `成员常量`
* **名称:** `播放键`
* **数据类型:** `整数`

##### 火山.基本.按键码.缩放键

* **类型:** `成员常量`
* **名称:** `缩放键`
* **数据类型:** `整数`

##### 火山.基本.按键码.无名键

* **类型:** `成员常量`
* **名称:** `无名键`
* **数据类型:** `整数`

##### 火山.基本.按键码.PA1键

* **类型:** `成员常量`
* **名称:** `PA1键`
* **数据类型:** `整数`

##### 火山.基本.按键码.OEM清除键

* **类型:** `成员常量`
* **名称:** `OEM清除键`
* **数据类型:** `整数`

---

#### 火山.基本.按键操作类

* **类型:** `类`
* **名称:** `按键操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `常用功能`
* **描述:** 提供常用按键操作功能

##### 火山.基本.按键操作类.取按键名称

* **类型:** `全局方法`
* **名称:** `取按键名称`
* **返回值数据类型:** `文本型`
* **参数:**
	* `按键代码值` (`整数`): 为"按键码"类中的按键代码常量值,可以加入辅助键组合状态值以代表一个组合键.
* **特性:**
	* `静态`
* **描述:** 返回所指定按键代码对应的名称文本

##### 火山.基本.按键操作类.按键码是否有效

* **类型:** `全局方法`
* **名称:** `按键码是否有效`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `按键代码值` (`整数`): 为"按键码"类中的按键代码常量值,可以加入辅助键组合状态值以代表一个组合键.
* **特性:**
	* `静态`
* **描述:** 返回所指定的按键代码是否对应有真实的按键.

##### 火山.基本.按键操作类.取按键字符

* **类型:** `全局方法`
* **名称:** `取按键字符`
* **返回值数据类型:** `字符`
* **参数:**
	* `按键代码值` (`整数`): 为"按键码"类中的按键代码常量值,注意不能包含辅助键组合状态值.
* **特性:**
	* `静态`
* **描述:** 如果所指定的按键代码对应有一个文本字符,将其返回,否则返回零字符.

##### 火山.基本.按键操作类.取锁定键状态

* **类型:** `全局方法`
* **名称:** `取锁定键状态`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲检查锁定键` (`整数`): 为"按键码.CapsLock键"/"按键码.NumLock键"/"按键码.ScrollLock键"三个常量值之一
* **特性:**
	* `静态`
* **描述:** 返回指定锁定键的当前锁定状态
* **返回值描述:** 返回真表示已经锁定,返回假表示未锁定.
* **相关例程:** [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.按键操作类.取键按下状态

* **类型:** `全局方法`
* **名称:** `取键按下状态`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲检查键代码` (`整数`): 为"按键码"类中的常量值之一
* **特性:**
	* `静态`
* **描述:** 返回所指定键当前是否处于被按下状态

---

#### 火山.基本.系统热键类

* **类型:** `类`
* **名称:** `系统热键类`
* **描述:** 用作登记并处理Windows系统全局热键
* **相关例程:** [vol-系统全局热键-syshotkey-main](#vol-系统全局热键-syshotkey-main)

##### 火山.基本.系统热键类.热键

* **类型:** `属性写方法`
* **名称:** `热键`
* **参数:**
	* `按键代码值` (`整数`): 为"按键码"类中的按键代码常量值,可以加入辅助键组合状态值以代表一个组合键. 如果为"按键码.空",则取消先前所登记的热键.
* **描述:** 设置所欲登记到Windows系统中的热键,后设置的热键将覆盖前面所设置的热键,如欲同时设置多个热键,请建立本类的多个对象实例. 本类对象被释放时,所登记热键将被自动取消.
* **相关例程:** [vol-系统全局热键-syshotkey-main](#vol-系统全局热键-syshotkey-main)

##### 火山.基本.系统热键类.热键被按下

* **类型:** `事件定义方法`
* **名称:** `热键被按下`
* **返回值数据类型:** `整数`
* **描述:** 当所登记的热键按下后本事件被发送
* **相关例程:** [vol-系统全局热键-syshotkey-main](#vol-系统全局热键-syshotkey-main)

---

#### 火山.基本.指针操作类

* **类型:** `类`
* **名称:** `指针操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `常用功能`
* **描述:** 提供对于指针的相关操作支持. 除非必要且对指针概念有透彻的了解,不要使用本类中的方法.

##### 火山.基本.指针操作类.取静态方法地址

* **类型:** `全局方法`
* **名称:** `取静态方法地址`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲处理的方法` (`任意格式静态方法`): 指定欲获取其地址的类静态方法
* **特性:**
	* `静态`
* **描述:** 返回所指定类静态方法的地址指针值
* **相关例程:** [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-轮廓查找-find_contour-main](#vol-轮廓查找-find_contour-main), [vol-图像二值化-threshold-main](#vol-图像二值化-threshold-main)

##### 火山.基本.指针操作类.调用静态方法

* **类型:** `全局方法`
* **名称:** `调用静态方法`
* **返回值数据类型:** `调用本方法时为"返回值类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲调用的方法地址` (`变整数`): 提供所欲调用类静态方法的地址,该地址可以使用"取静态方法地址"方法获取.
	* `返回值类型` (`通用型(需求:数据类型)`): 该返回值数据类型必须与被调用方法的返回值数据类型保持一致,否则将导致不可意料的问题.
	* `调用参数表` (`通用型`, `可扩展`): 调用参数表的格式务必和被调用方法的参数表一致,否则将导致不可意料的问题.
* **特性:**
	* `静态`
* **描述:** 调用所指定的类静态方法

##### 火山.基本.指针操作类.调用无参数静态方法

* **类型:** `全局方法`
* **名称:** `调用无参数静态方法`
* **返回值数据类型:** `调用本方法时为"返回值类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲调用的方法地址` (`变整数`): 提供所欲调用类静态方法的地址,该地址可以使用"取静态方法地址"方法获取.
	* `返回值类型` (`通用型(需求:数据类型)`): 该返回值数据类型必须与被调用方法的返回值数据类型保持一致,否则将导致不可意料的问题.
* **特性:**
	* `静态`
* **描述:** 调用所指定的类静态方法

##### 火山.基本.指针操作类.调用无返回值静态方法

* **类型:** `全局方法`
* **名称:** `调用无返回值静态方法`
* **参数:**
	* `所欲调用的方法地址` (`变整数`): 提供所欲调用类静态方法的地址,该地址可以使用"取静态方法地址"方法获取.
	* `调用参数表` (`通用型`, `可扩展`): 调用参数表的格式务必和被调用方法的参数表一致,否则将导致不可意料的问题.
* **特性:**
	* `静态`
* **描述:** 调用所指定的类静态方法

##### 火山.基本.指针操作类.调用无参数无返回值静态方法

* **类型:** `全局方法`
* **名称:** `调用无参数无返回值静态方法`
* **参数:**
	* `所欲调用的方法地址` (`变整数`): 提供所欲调用类静态方法的地址,该地址可以使用"取静态方法地址"方法获取.
* **特性:**
	* `静态`
* **描述:** 调用所指定的类静态方法

##### 火山.基本.指针操作类.调用静态方法2

* **类型:** `全局方法`
* **名称:** `调用静态方法2`
* **返回值数据类型:** `调用本方法时为"返回值类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲调用的方法` (`任意格式静态方法`): 指定欲调用的类静态方法
	* `返回值类型` (`通用型(需求:数据类型)`): 该返回值数据类型必须与被调用方法的返回值数据类型保持一致,否则将导致不可意料的问题.
	* `调用参数表` (`通用型`, `可扩展`): 调用参数表的格式务必和被调用方法的参数表一致,否则将导致不可意料的问题.
* **特性:**
	* `静态`
* **描述:** 调用所指定的类静态方法

##### 火山.基本.指针操作类.调用无参数静态方法2

* **类型:** `全局方法`
* **名称:** `调用无参数静态方法2`
* **返回值数据类型:** `调用本方法时为"返回值类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲调用的方法` (`任意格式静态方法`): 指定欲调用的类静态方法
	* `返回值类型` (`通用型(需求:数据类型)`): 该返回值数据类型必须与被调用方法的返回值数据类型保持一致,否则将导致不可意料的问题.
* **特性:**
	* `静态`
* **描述:** 调用所指定的类静态方法

##### 火山.基本.指针操作类.调用无返回值静态方法2

* **类型:** `全局方法`
* **名称:** `调用无返回值静态方法2`
* **参数:**
	* `所欲调用的方法` (`任意格式静态方法`): 指定欲调用的类静态方法
	* `调用参数表` (`通用型`, `可扩展`): 调用参数表的格式务必和被调用方法的参数表一致,否则将导致不可意料的问题.
* **特性:**
	* `静态`
* **描述:** 调用所指定的类静态方法

##### 火山.基本.指针操作类.调用无参数无返回值静态方法2

* **类型:** `全局方法`
* **名称:** `调用无参数无返回值静态方法2`
* **参数:**
	* `所欲调用的方法` (`任意格式静态方法`): 指定欲调用的类静态方法
* **特性:**
	* `静态`
* **描述:** 调用所指定的类静态方法

##### 火山.基本.指针操作类.取变整数尺寸

* **类型:** `全局方法`
* **名称:** `取变整数尺寸`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 变整数在编译64位程序时其字节数为8,编译32位程序时字节数为4,本方法可以根据当前实际情况返回对应的字节数.

##### 火山.基本.指针操作类.取数据类型尺寸

* **类型:** `全局方法`
* **名称:** `取数据类型尺寸`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲检查的数据类型` (`通用型(需求:数据类型)`)
* **特性:**
	* `静态`
* **描述:** 返回指定数据类型所占用的存储空间尺寸(单位字节)
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-被调用动态链接库-dll_test-main](#vol-被调用动态链接库-dll_test-main)

##### 火山.基本.指针操作类.取数据尺寸

* **类型:** `全局方法`
* **名称:** `取数据尺寸`
* **返回值数据类型:** `整数`
* **参数:**
	* `所检查数据` (`通用型`)
* **特性:**
	* `静态`
* **描述:** 返回指定数据所占用的存储空间尺寸(单位字节)

##### 火山.基本.指针操作类.取数组数据尺寸

* **类型:** `全局方法`
* **名称:** `取数组数据尺寸`
* **返回值数据类型:** `整数`
* **参数:**
	* `数组数据` (`通用型数组`)
* **特性:**
	* `静态`
* **描述:** 返回所指定数组数据所占用的存储空间尺寸(单位字节)

##### 火山.基本.指针操作类.取结构数据尺寸

* **类型:** `全局方法`
* **名称:** `取结构数据尺寸`
* **返回值数据类型:** `整数`
* **参数:**
	* `结构类型` (`对象类(需求:数据类型)`): 注意: 所提供类的类型必须为结构类(即定义有"@视窗.结构类"属性),否则将编译出错.
* **特性:**
	* `静态`
* **描述:** 返回所指定结构类中封装的C++结构数据部分尺寸
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.指针操作类.取结构数据

* **类型:** `全局方法`
* **名称:** `取结构数据`
* **返回值数据类型:** `变整数`
* **参数:**
	* `结构类对象` (`对象类`): 注意: 所提供结构类对象的类型必须为结构类(即定义有"@视窗.结构类"属性),否则将编译出错.
	* `数据存储字节集` (`字节集类`): 提供用作保存所获取结果数据的字节集对象,所获取的C++结构数据将保存到此字节集中.
* **特性:**
	* `静态`
* **描述:** 获取指定结构类对象对应的C++结构数据
* **返回值描述:** 返回保存到"数据存储字节集"参数中的C++结构数据地址指针
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.指针操作类.取结构数据到地址

* **类型:** `全局方法`
* **名称:** `取结构数据到地址`
* **参数:**
	* `结构类对象` (`对象类`): 注意: 所提供结构类对象的类型必须为结构类(即定义有"@视窗.结构类"属性),否则将编译出错.
	* `所欲保存到的地址` (`变整数`): 提供用作保存所获取结果数据的地址指针,所获取的C++结构数据将保存到该地址处,因此必须确保该地址处具有足够的存储空间.
* **特性:**
	* `静态`
* **描述:** 获取指定结构类对象对应的C++结构数据
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.指针操作类.加入结构数据

* **类型:** `全局方法`
* **名称:** `加入结构数据`
* **返回值数据类型:** `变整数`
* **参数:**
	* `结构类对象` (`对象类`): 注意: 所提供结构类对象的类型必须为结构类(即定义有"@视窗.结构类"属性),否则将编译出错.
	* `欲加入到字节集` (`字节集类`): 提供用作保存所获取结果数据的字节集对象,所获取的C++结构数据将添加到此字节集尾部.
* **特性:**
	* `静态`
* **描述:** 获取指定结构类对象对应的C++结构数据并将其添加到指定字节集尾部
* **返回值描述:** 返回添加到"欲加入到字节集"参数字节集尾部的C++结构数据地址指针
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.指针操作类.插入结构数据

* **类型:** `全局方法`
* **名称:** `插入结构数据`
* **返回值数据类型:** `变整数`
* **参数:**
	* `结构类对象` (`对象类`): 注意: 所提供结构类对象的类型必须为结构类(即定义有"@视窗.结构类"属性),否则将编译出错.
	* `欲插入到字节集` (`字节集类`): 提供用作保存所获取结果数据的字节集对象,所获取的C++结构数据将插入到此字节集指定位置.
	* `插入偏移位置` (`整数`): 提供具体的插入偏移位置
* **特性:**
	* `静态`
* **描述:** 获取指定结构类对象对应的C++结构数据并将其插入到字节集的指定位置
* **返回值描述:** 返回插入到"欲插入到字节集"参数字节集中的C++结构数据地址指针
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.指针操作类.置结构数据

* **类型:** `全局方法`
* **名称:** `置结构数据`
* **参数:**
	* `结构类对象` (`对象类`): 提供所欲填写的结构类对象. 注意: 所提供结构类对象的类型必须为结构类(即定义有"@视窗.结构类"属性),否则将编译出错.
	* `结构数据` (`字节集类`): 提供欲填入"结构类对象"的C++结构数据,注意必须为"取结构数据"方法所返回或在其基础上修改后的数据内容,尺寸必须等于"取结构数据尺寸"方法的返回值.
	* `起始偏移` (`整数`, 默认值: `0`)
* **特性:**
	* `静态`
* **描述:** 将所提供的C++结构数据填写进对应的结构类对象中
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.指针操作类.取变量地址

* **类型:** `全局方法`
* **名称:** `取变量地址`
* **返回值数据类型:** `变整数`
* **参数:**
	* `变量数据` (`通用型(需求:可写入变量)`)
* **特性:**
	* `静态`
* **描述:** 返回指定基本数据类型变量的内存空间地址指针值. 除非必要且对指针概念有透彻的了解,不要使用本方法.
* **相关例程:** [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main)

##### 火山.基本.指针操作类.取数组变量地址

* **类型:** `全局方法`
* **名称:** `取数组变量地址`
* **返回值数据类型:** `变整数`
* **参数:**
	* `数组变量数据` (`通用型数组(需求:可写入变量)`)
* **特性:**
	* `静态`
* **描述:** 返回指定基本数据类型数组变量的内存空间地址指针值. 除非必要且对指针概念有透彻的了解,不要使用本方法.
* **相关例程:** [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main)

##### 火山.基本.指针操作类.内存复制

* **类型:** `全局方法`
* **名称:** `内存复制`
* **参数:**
	* `目的内存空间指针` (`变整数`): 指向所欲复制到的目的内存空间地址指针,必须确保从该指针地址开始的尺寸为"欲复制数据尺寸"的内存空间可写.
	* `来源内存空间指针` (`变整数`): 指向所欲复制来源数据的内存空间地址指针,必须确保从该指针地址开始的尺寸为"欲复制数据尺寸"的内存空间可读.
	* `欲复制数据尺寸` (`整数`): 提供所欲复制来源数据的尺寸,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 将一段所指定数据复制到指针所指向的内存空间. 与"内存移动"方法不同的是: 复制的来源和目的空间地址不能相互重叠.

##### 火山.基本.指针操作类.内存移动

* **类型:** `全局方法`
* **名称:** `内存移动`
* **参数:**
	* `目的内存空间指针` (`变整数`): 指向所欲复制到的目的内存空间地址指针,必须确保从该指针地址开始的尺寸为"欲复制数据尺寸"的内存空间可写.
	* `来源内存空间指针` (`变整数`): 指向所欲复制来源数据的内存空间地址指针,必须确保从该指针地址开始的尺寸为"欲复制数据尺寸"的内存空间可读.
	* `欲复制数据尺寸` (`整数`): 提供所欲复制来源数据的尺寸,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 将一段所指定数据复制到指针所指向的内存空间. 与"内存复制"方法不同的是: 复制的来源和目的空间地址可以相互重叠.

##### 火山.基本.指针操作类.内存清零

* **类型:** `全局方法`
* **名称:** `内存清零`
* **参数:**
	* `内存空间指针` (`变整数`): 指向所欲清零的目的内存空间地址指针,必须确保从该指针地址开始的尺寸为"欲清零空间尺寸"的内存空间可写.
	* `欲清零空间尺寸` (`整数`): 提供所欲清零空间的尺寸,必须大于等于0.
* **特性:**
	* `静态`
* **描述:** 将一段所指定内存空间清零

##### 火山.基本.指针操作类.内存填充

* **类型:** `全局方法`
* **名称:** `内存填充`
* **参数:**
	* `内存空间指针` (`变整数`): 指向所欲填充的目的内存空间地址指针,必须确保从该指针地址开始的尺寸为"欲填充空间尺寸"的内存空间可写.
	* `欲填充空间尺寸` (`整数`): 提供所欲填充空间的尺寸,必须大于等于0.
	* `所欲填充值` (`字节`): 提供具体的所欲填充的字节值
* **特性:**
	* `静态`
* **描述:** 将一段所指定内存空间用所指定字节值填充

##### 火山.基本.指针操作类.读指针处值

* **类型:** `全局方法`
* **名称:** `读指针处值`
* **返回值数据类型:** `调用本方法时为"所欲读取值的类型"参数所提供数据的实际类型`
* **参数:**
	* `数据指针值` (`变整数`): 提供所欲读取其中值的数据指针
	* `所欲读取值的类型` (`通用非文本基本型(需求:数据类型)`): 提供所欲读取值的数据类型,必须确保指针所指向的尺寸为此数据类型尺寸的内存空间可读.
* **特性:**
	* `静态`
* **描述:** 读取并返回指针所指向地址处的非文本基本数据类型值
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.指针操作类.写指针处值

* **类型:** `全局方法`
* **名称:** `写指针处值`
* **参数:**
	* `数据指针值` (`变整数`): 提供所欲修改其中值的数据指针
	* `所欲写入的值` (`通用非文本基本型`): 提供具体所欲写入的值,必须确保指针所指向的尺寸为此值数据类型尺寸的内存空间可写.
* **特性:**
	* `静态`
* **描述:** 设置指针所指向地址处的非文本基本数据类型值
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main)

##### 火山.基本.指针操作类.创建对象指针

* **类型:** `全局方法`
* **名称:** `创建对象指针`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲创建对象的类型` (`对象类(需求:数据类型)`): 提供所欲创建对象的数据类型
* **特性:**
	* `静态`
* **描述:** 创建并返回指向所指定类型对象的指针. 注意: 该指针不再使用时,必须使用"销毁对象指针"方法将其释放. 访问所返回的指针对象可以使用"读指针处对象"/"写指针处对象"方法

##### 火山.基本.指针操作类.销毁对象指针

* **类型:** `全局方法`
* **名称:** `销毁对象指针`
* **参数:**
	* `对象指针` (`变整数`): 该指针值必须为"创建对象指针"方法所返回
* **特性:**
	* `静态`
* **描述:** 释放并销毁由"创建对象指针"所创建的对象指针

##### 火山.基本.指针操作类.读指针处对象

* **类型:** `全局方法`
* **名称:** `读指针处对象`
* **返回值数据类型:** `调用本方法时为"所欲读取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `数据指针值` (`变整数`): 提供所欲读取其中值的数据指针
	* `所欲读取对象的类型` (`对象类(需求:数据类型)`)
* **特性:**
	* `静态`
* **描述:** 读取并返回指针所指向地址处类对象实例的参考
* **相关例程:** [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main)

##### 火山.基本.指针操作类.写指针处对象

* **类型:** `全局方法`
* **名称:** `写指针处对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `对象指针值` (`变整数`): 提供所欲写入其中内容的对象指针
	* `所欲复制的对象` (`对象类`): 提供所欲复制到"对象指针值"参数所指向对象的内容对象,其实际数据类型需要与"对象指针值"参数所指向对象的实际数据类型匹配(为该对象的实际数据类型或其继承类),否则本方法将失败返回假.
* **特性:**
	* `静态`
* **描述:** 如果所提供欲复制对象的实际数据类型匹配"对象指针值"参数所指向对象的实际数 据类型(为该对象的实际数据类型或其继承类),则将所指定对象的内容复制到该对象中后返回真,否则失败返回假.

##### 火山.基本.指针操作类.分配内存

* **类型:** `全局方法`
* **名称:** `分配内存`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲分配内存的尺寸` (`整数`): 提供所欲分配内存的尺寸,必须大于0.
* **特性:**
	* `静态`
* **描述:** 分配一段所指定尺寸的内存,返回所分配内存的地址指针. 注意: 所返回的内存地址指针在不再使用后必须使用"释放内存"方法将其释放(除非调用了"重分配内存"方法将其重新分配).
* **返回值描述:** 成功返回所分配内存的地址指针,失败返回0.
* **相关例程:** [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main)

##### 火山.基本.指针操作类.重分配内存

* **类型:** `全局方法`
* **名称:** `重分配内存`
* **返回值数据类型:** `变整数`
* **参数:**
	* `先前所分配内存地址` (`变整数`): 提供先前调用"分配内存"或"重分配内存"方法所返回的内存地址指针,注意所提供的先前内存地址指针在重分配后将不再有效(注意本方法也可能返回相同的地址指针值).
	* `所欲重分配内存的尺寸` (`整数`): 提供所欲重新分配内存的尺寸,必须大于0.
* **特性:**
	* `静态`
* **描述:** 重新分配先前所已分配内存的尺寸,返回重分配后的内存地址指针. 注意: 先前内存中的数据内容将被保留,即使本方法返回了不同的地址指针.
* **返回值描述:** 成功返回所重分配内存的地址指针,失败返回0.

##### 火山.基本.指针操作类.释放内存

* **类型:** `全局方法`
* **名称:** `释放内存`
* **参数:**
	* `先前所分配内存地址` (`变整数`): 提供先前调用"分配内存"或"重分配内存"方法所返回的内存地址指针,注意所提供的内存地址指针在释放后将不再有效.
* **特性:**
	* `静态`
* **描述:** 释放先前调用"分配内存"或"重分配内存"方法所分配的内存
* **相关例程:** [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main)

---

#### 火山.基本.流程控制类

* **类型:** `类`
* **名称:** `流程控制类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `流程控制`
* **描述:** 提供对于流程控制的相关额外支持

##### 火山.基本.流程控制类.如果真

* **类型:** `全局方法`
* **名称:** `如果真`
* **参数:**
	* `条件参数` (`逻辑型`)
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
* **描述:** 当所指定的条件参数值为真,则执行子语句体,否则将其跳过.
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-树形框-tree_box-main](#vol-树形框-tree_box-main), [vol-状态条-status_bar-main](#vol-状态条-status_bar-main), [vol-表格-grid-main](#vol-表格-grid-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-打印测试-print_test-main](#vol-打印测试-print_test-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-密码管理-pw-main](#vol-密码管理-pw-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main), [vol-rvm人像抠图-rvm_segmentation-main](#vol-rvm人像抠图-rvm_segmentation-main), [vol-目标跟踪-target_tracking-main](#vol-目标跟踪-target_tracking-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main), [vol-形态学运算-morphological-main](#vol-形态学运算-morphological-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.流程控制类.计次循环

* **类型:** `全局方法`
* **名称:** `计次循环`
* **参数:**
	* `循环次数` (`整数`)
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 将子语句体循环指定所指定的次数. 在子语句体中,可以使用"取循环索引"方法取回当前循环索引值(0到"循环次数"参数值-1).
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-半透明图片演示-alpha_pic_draw-main](#vol-半透明图片演示-alpha_pic_draw-main), [vol-属性表格-property_grid-main](#vol-属性表格-property_grid-main), [vol-带按钮列表框-vs_list_box-main](#vol-带按钮列表框-vs_list_box-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览框自定义菜单-webview2_contextmenu-main](#vol-edge浏览框自定义菜单-webview2_contextmenu-main), [vol-打印测试-print_test-main](#vol-打印测试-print_test-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-条码检测-barcode_detection-main](#vol-条码检测-barcode_detection-main), [vol-相关性多模板匹配-ncc_matching-main](#vol-相关性多模板匹配-ncc_matching-main), [vol-yolop全景驾驶感知-yolop-main](#vol-yolop全景驾驶感知-yolop-main), [vol-yolov5目标检测-yolov5-main](#vol-yolov5目标检测-yolov5-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main), [vol-角点检测-corner_detection-main](#vol-角点检测-corner_detection-main), [vol-灰度直方图-histogram-main](#vol-灰度直方图-histogram-main), [vol-dnn目标检测-dnn_objectdetection-main](#vol-dnn目标检测-dnn_objectdetection-main), [vol-dnn文本检测-dnn_text_detection_recognition-main](#vol-dnn文本检测-dnn_text_detection_recognition-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.流程控制类.逆向计次循环

* **类型:** `全局方法`
* **名称:** `逆向计次循环`
* **参数:**
	* `循环次数` (`整数`)
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 将子语句体逆向循环指定所指定的次数. 在子语句体中,可以使用"取循环索引"方法取回当前循环索引值("循环次数"参数值-1 到 0).

##### 火山.基本.流程控制类.取循环索引

* **类型:** `全局方法`
* **名称:** `取循环索引`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [计次循环](#火山.基本.流程控制类.计次循环), [逆向计次循环](#火山.基本.流程控制类.逆向计次循环)
* **描述:** 只能在"计次循环"/"逆向计次循环"语句的子语句体中使用,用作取回当前循环索引值,所取回的值范围为从0到"计次循环"调用语句中所指定的"循环次数"参数值-1. 如果有多层"计次循环"/"逆向计次循环"嵌套,本方法将返回所处最近层"计次循环"/"逆向计次循环"的索引值.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-属性表格-property_grid-main](#vol-属性表格-property_grid-main), [vol-带按钮列表框-vs_list_box-main](#vol-带按钮列表框-vs_list_box-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览框自定义菜单-webview2_contextmenu-main](#vol-edge浏览框自定义菜单-webview2_contextmenu-main), [vol-打印测试-print_test-main](#vol-打印测试-print_test-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-条码检测-barcode_detection-main](#vol-条码检测-barcode_detection-main), [vol-相关性多模板匹配-ncc_matching-main](#vol-相关性多模板匹配-ncc_matching-main), [vol-yolop全景驾驶感知-yolop-main](#vol-yolop全景驾驶感知-yolop-main), [vol-yolov5目标检测-yolov5-main](#vol-yolov5目标检测-yolov5-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main), [vol-角点检测-corner_detection-main](#vol-角点检测-corner_detection-main), [vol-灰度直方图-histogram-main](#vol-灰度直方图-histogram-main), [vol-dnn目标检测-dnn_objectdetection-main](#vol-dnn目标检测-dnn_objectdetection-main), [vol-dnn文本检测-dnn_text_detection_recognition-main](#vol-dnn文本检测-dnn_text_detection_recognition-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.流程控制类.循环判断首

* **类型:** `全局方法`
* **名称:** `循环判断首`
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
	* 本方法调用语句后方必须为以下任一方法的调用语句: [循环判断尾](#火山.基本.流程控制类.循环判断尾)
* **描述:** 首先执行循环子语句体,在子语句体的尾部判断是否是否继续循环. 本语句的后面必须跟随一个"循环判断尾"语句.
* **相关例程:** [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.流程控制类.循环判断尾

* **类型:** `全局方法`
* **名称:** `循环判断尾`
* **参数:**
	* `是否继续循环` (`逻辑型`): 参数值为真继续循环,否则退出循环.
* **特性:**
	* `静态`
	* 本方法调用语句前方必须为以下任一方法的调用语句: [循环判断首](#火山.基本.流程控制类.循环判断首)
* **描述:** 本方法的调用语句必须紧跟在"循环判断首"语句的后面,用作根据所提供的条件参数决定是否继续循环.
* **相关例程:** [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.流程控制类.分支判断

* **类型:** `全局方法`
* **名称:** `分支判断`
* **参数:**
	* `欲判断检查的值` (`整数`)
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
	* 本方法调用语句的子语句体中必须至少存在一个以下任一方法的调用语句: [分支](#火山.基本.流程控制类.分支), [默认分支](#火山.基本.流程控制类.默认分支)
* **描述:** 开始对一个整数参数的值进行分支判断处理. 本方法的子语句体中只能存在"分支"或"默认分支"方法的调用语句,并且至少包含一个.
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-设计并处理重叠界面-over_ui-main](#vol-设计并处理重叠界面-over_ui-main), [vol-超级菜单演示-adv_menu-main](#vol-超级菜单演示-adv_menu-main), [vol-窗口组件动态消息过滤-msg_filter-main](#vol-窗口组件动态消息过滤-msg_filter-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.流程控制类.分支

* **类型:** `全局方法`
* **名称:** `分支`
* **参数:**
	* `欲检查是否相等的值` (`整数(需求:立即数或常量)`): 本参数值只能提供立即数或常量值
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
	* 本方法调用语句前方必须为以下任一方法的调用语句: [分支](#火山.基本.流程控制类.分支)
	* 本方法调用语句后方必须为以下任一方法的调用语句: [分支](#火山.基本.流程控制类.分支), [默认分支](#火山.基本.流程控制类.默认分支)
	* 本方法调用语句必须位于以下任一方法调用语句的直接子语句体中: [分支判断](#火山.基本.流程控制类.分支判断)
* **描述:** 本方法的调用语句只能在"分支判断"语句的直接子语句体中使用,用作提供一个判断检查分支. 当"分支判断"语句的"欲判断检查的值"参数等于本语句中的"欲检查是否相等的值"时,将去执行本语句的子语句体中的代码并跳过后续所有其它判断检查分支,否则将跳过本语句的子语句体转去检查后续的下一分支是否满足要求. 注意: 不能多个判断检查分支具有相同的"欲检查是否相等的值",此时对应本地编译器将会报错.
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-设计并处理重叠界面-over_ui-main](#vol-设计并处理重叠界面-over_ui-main), [vol-超级菜单演示-adv_menu-main](#vol-超级菜单演示-adv_menu-main), [vol-窗口组件动态消息过滤-msg_filter-main](#vol-窗口组件动态消息过滤-msg_filter-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.流程控制类.默认分支

* **类型:** `全局方法`
* **名称:** `默认分支`
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
	* 本方法调用语句前方必须为以下任一方法的调用语句: [分支](#火山.基本.流程控制类.分支)
	* 本方法调用语句必须为所处子语句体的最后一条语句
	* 本方法调用语句必须位于以下任一方法调用语句的直接子语句体中: [分支判断](#火山.基本.流程控制类.分支判断)
* **描述:** 本方法的调用语句只能在"分支判断"语句的直接子语句体的尾部使用,用作提供一个判断检查分支. 当前面所有判断检查分支均不满足时将最终执行本语句的子语句体中的代码.
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-超级菜单演示-adv_menu-main](#vol-超级菜单演示-adv_menu-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.流程控制类.跳出分支

* **类型:** `全局方法`
* **名称:** `跳出分支`
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [分支](#火山.基本.流程控制类.分支), [默认分支](#火山.基本.流程控制类.默认分支)
* **描述:** 本语句只能在"分支"或"默认分支"语句的直接/间接子语句体中使用,用作跳转去执行所处"分支判断"语句的下一条语句.
* **相关例程:** [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.流程控制类.结束

* **类型:** `全局方法`
* **名称:** `结束`
* **参数:**
	* `结束代码` (`整数`, 默认值: `0`): 本结束代码值将被返回到程序的调用方
* **特性:**
	* `静态`
* **描述:** 结束当前程序的运行. 尽量以关闭程序主窗口的方式而不要使用本方法来结束程序,以正常释放程序运行中所占用的资源以及作相关善后处理.

##### 火山.基本.流程控制类.选择

* **类型:** `全局方法`
* **名称:** `选择`
* **返回值数据类型:** `调用本方法时为"备选参数1"参数所提供数据的实际类型`
* **参数:**
	* `用作选择的逻辑值` (`逻辑型`): 如果参数值为真,将返回备选参数1,否则返回备选参数2.
	* `备选参数1` (`通用型`): 如果"用作选择的逻辑值"参数值为真,方法将返回本参数值.
	* `备选参数2` (`等于前参数值类型`): 如果"用作选择的逻辑值"参数值为假,方法将返回本参数值.
* **特性:**
	* `静态`
* **描述:** 根据所提供参数的值,返回两个备选参数中的一个.
* **相关例程:** [vol-选择夹2-tab_demo-main](#vol-选择夹2-tab_demo-main), [vol-状态条-status_bar-main](#vol-状态条-status_bar-main), [vol-表格-grid-main](#vol-表格-grid-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-属性表格-property_grid-main](#vol-属性表格-property_grid-main), [vol-超级菜单演示-adv_menu-main](#vol-超级菜单演示-adv_menu-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-菜单-menu_demo-main](#vol-菜单-menu_demo-main), [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main), [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-系统全局热键-syshotkey-main](#vol-系统全局热键-syshotkey-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-yyjson数据访问-yyjson-main](#vol-yyjson数据访问-yyjson-main), [vol-rar文件解压-unrar-main](#vol-rar文件解压-unrar-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-redis连接池-redisconnectpool-main](#vol-redis连接池-redisconnectpool-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.流程控制类.多项选择

* **类型:** `全局方法`
* **名称:** `多项选择`
* **返回值数据类型:** `调用本方法时为"待选择数据1"参数所提供数据的实际类型`
* **参数:**
	* `索引值` (`整数`): 方法会根据本索引值来返回选择项列表中的某个值,索引值从0开始. 如果索引值是0,则命令会返回列表中的第1个选择项.如果索引值是1,则会返回列表中的第2个选择项,以此类推.
	* `待选择数据1` (`通用基本型`): 提供待选择的数据
	* `后续待选择数据` (`等于前参数值类型`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 从参数列表项目中选择并返回一个值
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-摄像头操作-directshow-main](#vol-摄像头操作-directshow-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main)

---

#### 火山.基本.变量操作类

* **类型:** `类`
* **名称:** `变量操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `变量操作`

##### 火山.基本.变量操作类.连续赋值

* **类型:** `全局方法`
* **名称:** `连续赋值`
* **参数:**
	* `所欲赋予的值` (`通用型`)
	* `所欲赋值到的变量` (`匹配前参数值类型(需求:可写入变量)`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 将一个值连续赋予到所指定的一系列同类型变量中

##### 火山.基本.变量操作类.连续清零

* **类型:** `全局方法`
* **名称:** `连续清零`
* **参数:**
	* `所欲清零的变量` (`通用非文本基本型(需求:可写入变量)`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 将所指定的一系列数值变量清零,逻辑型变量则清除为假.

##### 火山.基本.变量操作类.连续清空

* **类型:** `全局方法`
* **名称:** `连续清空`
* **参数:**
	* `所欲清空的变量` (`文本型(需求:可写入变量)`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 将所指定的一系列文本型变量清除为空文本

##### 火山.基本.变量操作类.交换变量

* **类型:** `全局方法`
* **名称:** `交换变量`
* **参数:**
	* `变量1` (`通用型(需求:可写入变量)`)
	* `变量2` (`等于前参数值类型(需求:可写入变量)`)
* **特性:**
	* `静态`
* **描述:** 交换两个同类型变量的值

##### 火山.基本.变量操作类.连续位或

* **类型:** `全局方法`
* **名称:** `连续位或`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲进行运算的值1` (`整数`)
	* `欲进行运算的值2` (`整数`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 将多个整数值进行位或运算,返回运算后的结果.
* **相关例程:** [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main)

##### 火山.基本.变量操作类.连续位与

* **类型:** `全局方法`
* **名称:** `连续位与`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲进行运算的值1` (`整数`)
	* `欲进行运算的值2` (`整数`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 将多个整数值进行位与运算,返回运算后的结果.

##### 火山.基本.变量操作类.连续位异或

* **类型:** `全局方法`
* **名称:** `连续位异或`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲进行运算的值1` (`整数`)
	* `欲进行运算的值2` (`整数`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 将多个整数值进行位异或运算,返回运算后的结果.

---

#### 火山.基本.程序调试类

* **类型:** `类`
* **名称:** `程序调试类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `程序调试`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.程序调试类.取源文件名

* **类型:** `全局方法`
* **名称:** `取源文件名`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回当前语句所处源文件的名称

##### 火山.基本.程序调试类.取源行号

* **类型:** `全局方法`
* **名称:** `取源行号`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回当前语句在所处源文件中的行号位置

##### 火山.基本.程序调试类.取源包名

* **类型:** `全局方法`
* **名称:** `取源包名`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回当前语句所处包的名称

##### 火山.基本.程序调试类.取源类名

* **类型:** `全局方法`
* **名称:** `取源类名`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回当前语句所处类的名称

##### 火山.基本.程序调试类.取源方法名

* **类型:** `全局方法`
* **名称:** `取源方法名`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回当前语句所处方法的名称

##### 火山.基本.程序调试类.取当前语句位置

* **类型:** `全局方法`
* **名称:** `取当前语句位置`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回当前语句的详细源代码位置文本,文本格式为: <所处源文件名>, 所处源文件行号, 所处包名.所处类名, 所处方法名

##### 火山.基本.程序调试类.调试输出当前语句位置

* **类型:** `全局方法`
* **名称:** `调试输出当前语句位置`
* **特性:**
	* `静态`
* **描述:** 向系统调试器内输出当前语句的位置信息

##### 火山.基本.程序调试类.调试输出

* **类型:** `全局方法`
* **名称:** `调试输出`
* **参数:**
	* `所欲输出的数据` (`通用型`, `可扩展`): 支持提供对象数据(譬如字节集类,所有基本数据封装类,以及所有以"扩展对象类"为直接/间接基础类并覆盖了其"取展示内容"方法的类对象. 每个所输出数据后附加一个", "文本用作分隔,输出行的最后添加一个换行符.
* **特性:**
	* `静态`
* **描述:** 向系统调试器内输出所指定数据的调试用文本并自动换行
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-媒体播放器-win_media_player-main](#vol-媒体播放器-win_media_player-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览框扩展-webview2_extensions-main](#vol-edge浏览框扩展-webview2_extensions-main), [vol-edge浏览框自定义菜单-webview2_contextmenu-main](#vol-edge浏览框自定义菜单-webview2_contextmenu-main), [vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main](#vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main), [vol-空对象测试-null_object_test-main](#vol-空对象测试-null_object_test-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-cximage高级图像处理-cximage-main](#vol-cximage高级图像处理-cximage-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-网页解析-html_parser-main](#vol-网页解析-html_parser-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-大整数运算-bnsample-main](#vol-大整数运算-bnsample-main), [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-rar文件解压-unrar-main](#vol-rar文件解压-unrar-main), [vol-yaml数据访问-yaml-main](#vol-yaml数据访问-yaml-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-ado-ado_sample-main](#vol-ado-ado_sample-main), [vol-redis连接池-redisconnectpool-main](#vol-redis连接池-redisconnectpool-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-elk微型js引擎-elk_js-main](#vol-elk微型js引擎-elk_js-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main), [vol-特征检测与匹配-bfmatcher-main](#vol-特征检测与匹配-bfmatcher-main), [vol-人脸性别识别-gender_recognition-main](#vol-人脸性别识别-gender_recognition-main), [vol-图像融合-image_fusion-main](#vol-图像融合-image_fusion-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.程序调试类.调试输出2

* **类型:** `全局方法`
* **名称:** `调试输出2`
* **参数:**
	* `最大允许展示数据尺寸` (`整数`, 默认值: `0`): 指定所允许的最大展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
	* `所欲输出的数据` (`通用型`, `可扩展`): 支持提供对象数据(譬如字节集类,所有基本数据封装类,以及所有以"扩展对象类"为直接/间接基础类并覆盖了其"取展示内容"方法的类对象. 每个所输出数据后附加一个", "文本用作分隔,输出行的最后添加一个换行符.
* **特性:**
	* `静态`
* **描述:** 向系统调试器内输出所指定数据的调试用文本并自动换行. 本方法与"调试输出"方法的不同之处在于可以指定所允许的最大展示数据尺寸,一般用作限制大数量型数据(譬如字节集类)的输出.

##### 火山.基本.程序调试类.调试输出3

* **类型:** `全局方法`
* **名称:** `调试输出3`
* **参数:**
	* `所欲输出的数据` (`通用型`, `可扩展`): 支持提供对象数据(譬如字节集类,所有基本数据封装类,以及所有以"扩展对象类"为直接/间接基础类并覆盖了其"取展示内容"方法的类对象. 每个所输出数据后附加一个", "文本用作分隔,输出行的最后添加一个换行符.
* **特性:**
	* `静态`
* **描述:** 向系统调试器内输出所指定数据的调试用文本并自动换行. 本方法与"调试输出"和"调试输出2"方法的不同之处在于将以字符串格式来输出文本数据.

##### 火山.基本.程序调试类.可跳转调试输出

* **类型:** `全局方法`
* **名称:** `可跳转调试输出`
* **参数:**
	* `所欲输出的数据` (`通用型`, `可扩展`): 支持提供对象数据(譬如字节集类,所有基本数据封装类,以及所有以"扩展对象类"为直接/间接基础类并覆盖了其"取展示内容"方法的类对象. 每个所输出数据后附加一个", "文本用作分隔,输出行的最后添加一个换行符.
* **特性:**
	* `静态`
* **描述:** 向系统调试器内输出所指定数据的调试用文本并自动换行. 本方法与"调试输出"和"调试输出2"和"调试输出3"方法的不同之处在于所输出行的首部将携带当前源码位置,在输出窗口中双击此行即可跳转到该源码位置.

##### 火山.基本.程序调试类.调试信息框

* **类型:** `全局方法`
* **名称:** `调试信息框`
* **参数:**
	* `所欲输出的数据` (`通用型`, `可扩展`): 支持提供对象数据(譬如字节集类,所有基本数据封装类,以及所有以"扩展对象类"为直接/间接基础类并覆盖了其"取展示内容"方法的类对象. 每个所输出数据后附加一个", "文本用作分隔,输出行的最后添加一个换行符.
* **特性:**
	* `静态`
* **描述:** 以信息框的方式输出所指定数据的调试用文本,本方法在编译非调试版时不进行任何操作.

##### 火山.基本.程序调试类.调试信息框2

* **类型:** `全局方法`
* **名称:** `调试信息框2`
* **参数:**
	* `最大允许展示数据尺寸` (`整数`, 默认值: `0`): 指定所允许的最大展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
	* `所欲输出的数据` (`通用型`, `可扩展`): 支持提供对象数据(譬如字节集类,所有基本数据封装类,以及所有以"扩展对象类"为直接/间接基础类并覆盖了其"取展示内容"方法的类对象. 每个所输出数据后附加一个", "文本用作分隔,输出行的最后添加一个换行符.
* **特性:**
	* `静态`
* **描述:** 以信息框的方式输出所指定数据的调试用文本,本方法在编译非调试版时不进行任何操作. 本方法与"调试信息框"方法的不同之处在于可以指定所允许的最大展示数据尺寸,一般用作限制大数量型数据(譬如字节集类)的输出.

##### 火山.基本.程序调试类.调试信息框3

* **类型:** `全局方法`
* **名称:** `调试信息框3`
* **参数:**
	* `所欲输出的数据` (`通用型`, `可扩展`): 支持提供对象数据(譬如字节集类,所有基本数据封装类,以及所有以"扩展对象类"为直接/间接基础类并覆盖了其"取展示内容"方法的类对象. 每个所输出数据后附加一个", "文本用作分隔,输出行的最后添加一个换行符.
* **特性:**
	* `静态`
* **描述:** 以信息框的方式输出所指定数据的调试用文本,本方法在编译非调试版时不进行任何操作. 本方法与"调试信息框"和"调试信息框2"方法的不同之处在于将以字符串格式来输出文本数据.

##### 火山.基本.程序调试类.取调试文本

* **类型:** `全局方法`
* **名称:** `取调试文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲输出的数据` (`通用型`, `可扩展`): 支持提供对象数据(譬如字节集类,所有基本数据封装类,以及所有以"扩展对象类"为直接/间接基础类并覆盖了其"取展示内容"方法的类对象. 每个所输出数据后附加一个", "文本用作分隔,输出行的最后添加一个换行符.
* **特性:**
	* `静态`
* **描述:** 返回所指定数据的调试用文本,本方法在编译非调试版时始终返回空文本.

##### 火山.基本.程序调试类.取调试文本2

* **类型:** `全局方法`
* **名称:** `取调试文本2`
* **返回值数据类型:** `文本型`
* **参数:**
	* `最大允许展示数据尺寸` (`整数`): 指定所允许的最大展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
	* `所欲输出的数据` (`通用型`, `可扩展`): 支持提供对象数据(譬如字节集类,所有基本数据封装类,以及所有以"扩展对象类"为直接/间接基础类并覆盖了其"取展示内容"方法的类对象. 每个所输出数据后附加一个", "文本用作分隔,输出行的最后添加一个换行符.
* **特性:**
	* `静态`
* **描述:** 返回所指定数据的调试用文本,本方法在编译非调试版时始终返回空文本. 本方法与"取调试信息"方法的不同之处在于可以指定所允许的最大展示数据尺寸,一般用作限制大数量型数据(譬如字节集类)的输出.

##### 火山.基本.程序调试类.取调试文本3

* **类型:** `全局方法`
* **名称:** `取调试文本3`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲输出的数据` (`通用型`, `可扩展`): 支持提供对象数据(譬如字节集类,所有基本数据封装类,以及所有以"扩展对象类"为直接/间接基础类并覆盖了其"取展示内容"方法的类对象. 每个所输出数据后附加一个", "文本用作分隔,输出行的最后添加一个换行符.
* **特性:**
	* `静态`
* **描述:** 返回所指定数据的调试用文本,本方法在编译非调试版时始终返回空文本. 本方法与"取调试信息"和"取调试信息2"方法的不同之处在于将以字符串格式来输出文本数据.

##### 火山.基本.程序调试类.格式调试输出

* **类型:** `全局方法`
* **名称:** `格式调试输出`
* **参数:**
	* `格式文本` (`文本型`): 提供其中可以包含格式替换符的文本,其中的格式替换符将被后续对应参数所替换. 以下为常用的格式替换符,详细信息请参阅C++文档中关于sprintf函数的说明. %c: 字符 %d: 整数(以有符号十进制格式替换) %o: 整数(以无符号八进制格式替换) %u: 整数(以无符号十进制格式替换) %x: 整数(以无符号小写十六进制格式替换) %X: 整数(以无符号大写十六进制格式替换) %I64d: 长整数(以有符号十进制格式替换) %I64o: 长整数(以无符号八进制格式替换) %I64u: 长整数(以无符号十进制格式替换) %I64x: 长整数(以无符号小写十六进制格式替换) %I64X: 长整数(以无符号大写十六进制格式替换) %e, %E: 小数(以指数形式替换) %f: 小数(以非指数形式替换) %.8f: 小数(用来表达小数的带宽度限制的常用格式替换符) %g, %G: 小数(根据值大小自动选择是否以指数形式替换) %s: 文本型 %%: 百分号字符本身注意: 如果欲格式化"变整数"值,请务必将其先强制转换为整数或者长整数,再使用对应的格式替换符.
	* `替换数据` (`通用基本型`, `可扩展`): 用作给格式文本中的格式替换符提供替换数据,格式替换符的数目和数据类型必须与替换数据保持一致.
* **特性:**
	* `静态`
* **描述:** 向系统调试器内输出所指定格式数据的调试用文本并自动换行
* **相关例程:** [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-yaml数据访问-yaml-main](#vol-yaml数据访问-yaml-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main)

##### 火山.基本.程序调试类.是否为调试版

* **类型:** `全局方法`
* **名称:** `是否为调试版`
* **返回值数据类型:** `逻辑型`
* **特性:**
	* `静态`
* **描述:** 返回当前所运行程序是否为在火山中调试运行时所编译出来的
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.目标操作系统类别

* **类型:** `类`
* **名称:** `目标操作系统类别`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `常用功能.辅助类`
* **描述:** 用作提供当前目标程序所对应的操作系统类别

##### 火山.基本.目标操作系统类别.未知

* **类型:** `成员常量`
* **名称:** `未知`
* **数据类型:** `目标操作系统类别`
* **初始值:** `0`

##### 火山.基本.目标操作系统类别.Windows

* **类型:** `成员常量`
* **名称:** `Windows`
* **数据类型:** `目标操作系统类别`
* **初始值:** `1`
* **描述:** Windows视窗操作系统

##### 火山.基本.目标操作系统类别.Linux

* **类型:** `成员常量`
* **名称:** `Linux`
* **数据类型:** `目标操作系统类别`
* **初始值:** `2`
* **描述:** Linux操作系统

---

#### 火山.基本.程序窗口显示方式

* **类型:** `类`
* **名称:** `程序窗口显示方式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `常用功能.辅助类`
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main)

##### 火山.基本.程序窗口显示方式.隐藏窗口

* **类型:** `成员常量`
* **名称:** `隐藏窗口`
* **数据类型:** `程序窗口显示方式`

##### 火山.基本.程序窗口显示方式.普通激活

* **类型:** `成员常量`
* **名称:** `普通激活`
* **数据类型:** `程序窗口显示方式`
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main)

##### 火山.基本.程序窗口显示方式.最小化激活

* **类型:** `成员常量`
* **名称:** `最小化激活`
* **数据类型:** `程序窗口显示方式`

##### 火山.基本.程序窗口显示方式.最大化激活

* **类型:** `成员常量`
* **名称:** `最大化激活`
* **数据类型:** `程序窗口显示方式`

##### 火山.基本.程序窗口显示方式.普通不激活

* **类型:** `成员常量`
* **名称:** `普通不激活`
* **数据类型:** `程序窗口显示方式`

##### 火山.基本.程序窗口显示方式.最小化不激活

* **类型:** `成员常量`
* **名称:** `最小化不激活`
* **数据类型:** `程序窗口显示方式`

---

#### 火山.基本.鸣叫声音类型

* **类型:** `类`
* **名称:** `鸣叫声音类型`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `常用功能.辅助类`
* **相关例程:** [vol-窗口组件动态消息过滤-msg_filter-main](#vol-窗口组件动态消息过滤-msg_filter-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.鸣叫声音类型.标准

* **类型:** `成员常量`
* **名称:** `标准`
* **数据类型:** `鸣叫声音类型`
* **初始值:** `-1`

##### 火山.基本.鸣叫声音类型.特别

* **类型:** `成员常量`
* **名称:** `特别`
* **数据类型:** `鸣叫声音类型`

##### 火山.基本.鸣叫声音类型.感叹

* **类型:** `成员常量`
* **名称:** `感叹`
* **数据类型:** `鸣叫声音类型`

##### 火山.基本.鸣叫声音类型.拒绝

* **类型:** `成员常量`
* **名称:** `拒绝`
* **数据类型:** `鸣叫声音类型`
* **相关例程:** [vol-窗口组件动态消息过滤-msg_filter-main](#vol-窗口组件动态消息过滤-msg_filter-main)

##### 火山.基本.鸣叫声音类型.询问

* **类型:** `成员常量`
* **名称:** `询问`
* **数据类型:** `鸣叫声音类型`

##### 火山.基本.鸣叫声音类型.默认

* **类型:** `成员常量`
* **名称:** `默认`
* **数据类型:** `鸣叫声音类型`
* **相关例程:** [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

---

#### 火山.基本.注册表根目录类型

* **类型:** `类`
* **名称:** `注册表根目录类型`
* **特性:**
	* `常量类`(对应数据类型: `变整数`)
* **文档分类:** `常用功能.辅助类`

##### 火山.基本.注册表根目录类型.根类

* **类型:** `成员常量`
* **名称:** `根类`
* **数据类型:** `注册表根目录类型`

##### 火山.基本.注册表根目录类型.现行设置

* **类型:** `成员常量`
* **名称:** `现行设置`
* **数据类型:** `注册表根目录类型`

##### 火山.基本.注册表根目录类型.现行用户

* **类型:** `成员常量`
* **名称:** `现行用户`
* **数据类型:** `注册表根目录类型`

##### 火山.基本.注册表根目录类型.本地机器

* **类型:** `成员常量`
* **名称:** `本地机器`
* **数据类型:** `注册表根目录类型`

##### 火山.基本.注册表根目录类型.所有用户

* **类型:** `成员常量`
* **名称:** `所有用户`
* **数据类型:** `注册表根目录类型`

---

#### 火山.基本.可执行文件位数

* **类型:** `类`
* **名称:** `可执行文件位数`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `常用功能.辅助类`
* **相关例程:** [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main)

##### 火山.基本.可执行文件位数.未知

* **类型:** `成员常量`
* **名称:** `未知`
* **数据类型:** `可执行文件位数`
* **描述:** 未知或获取失败

##### 火山.基本.可执行文件位数.WIN32

* **类型:** `成员常量`
* **名称:** `WIN32`
* **数据类型:** `可执行文件位数`
* **描述:** 32位应用程序
* **相关例程:** [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main)

##### 火山.基本.可执行文件位数.X64

* **类型:** `成员常量`
* **名称:** `X64`
* **数据类型:** `可执行文件位数`
* **描述:** 64位应用程序
* **相关例程:** [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main)

---

#### 火山.基本.特定目录类型

* **类型:** `类`
* **名称:** `特定目录类型`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `常用功能.辅助类`
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.特定目录类型.我的文档

* **类型:** `成员常量`
* **名称:** `我的文档`
* **数据类型:** `特定目录类型`
* **初始值:** `1`

##### 火山.基本.特定目录类型.我的收藏夹

* **类型:** `成员常量`
* **名称:** `我的收藏夹`
* **数据类型:** `特定目录类型`
* **初始值:** `2`

##### 火山.基本.特定目录类型.系统桌面

* **类型:** `成员常量`
* **名称:** `系统桌面`
* **数据类型:** `特定目录类型`
* **初始值:** `3`
* **相关例程:** [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.特定目录类型.系统字体

* **类型:** `成员常量`
* **名称:** `系统字体`
* **数据类型:** `特定目录类型`
* **初始值:** `4`

##### 火山.基本.特定目录类型.开始菜单组

* **类型:** `成员常量`
* **名称:** `开始菜单组`
* **数据类型:** `特定目录类型`
* **初始值:** `5`

##### 火山.基本.特定目录类型.程序菜单组

* **类型:** `成员常量`
* **名称:** `程序菜单组`
* **数据类型:** `特定目录类型`
* **初始值:** `6`

##### 火山.基本.特定目录类型.启动菜单组

* **类型:** `成员常量`
* **名称:** `启动菜单组`
* **数据类型:** `特定目录类型`
* **初始值:** `7`

##### 火山.基本.特定目录类型.程序数据目录

* **类型:** `成员常量`
* **名称:** `程序数据目录`
* **数据类型:** `特定目录类型`
* **初始值:** `8`

##### 火山.基本.特定目录类型.Windows安装目录

* **类型:** `成员常量`
* **名称:** `Windows安装目录`
* **数据类型:** `特定目录类型`
* **初始值:** `9`

##### 火山.基本.特定目录类型.Windows系统目录

* **类型:** `成员常量`
* **名称:** `Windows系统目录`
* **数据类型:** `特定目录类型`
* **初始值:** `10`

##### 火山.基本.特定目录类型.临时文件目录

* **类型:** `成员常量`
* **名称:** `临时文件目录`
* **数据类型:** `特定目录类型`
* **初始值:** `11`
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main)

---

#### 火山.基本.特定目录类型2

* **类型:** `类`
* **名称:** `特定目录类型2`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `常用功能.辅助类`

##### 火山.基本.特定目录类型2.桌面

* **类型:** `成员常量`
* **名称:** `桌面`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.互联网

* **类型:** `成员常量`
* **名称:** `互联网`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.程序菜单组

* **类型:** `成员常量`
* **名称:** `程序菜单组`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.控制面板

* **类型:** `成员常量`
* **名称:** `控制面板`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.打印机

* **类型:** `成员常量`
* **名称:** `打印机`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.我的文档

* **类型:** `成员常量`
* **名称:** `我的文档`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.我的收藏夹

* **类型:** `成员常量`
* **名称:** `我的收藏夹`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.启动菜单组

* **类型:** `成员常量`
* **名称:** `启动菜单组`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.现行文档

* **类型:** `成员常量`
* **名称:** `现行文档`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.发送到

* **类型:** `成员常量`
* **名称:** `发送到`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.回收站

* **类型:** `成员常量`
* **名称:** `回收站`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.开始菜单组

* **类型:** `成员常量`
* **名称:** `开始菜单组`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.我的音乐

* **类型:** `成员常量`
* **名称:** `我的音乐`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.我的视频

* **类型:** `成员常量`
* **名称:** `我的视频`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.系统桌面

* **类型:** `成员常量`
* **名称:** `系统桌面`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.我的计算机

* **类型:** `成员常量`
* **名称:** `我的计算机`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.网络

* **类型:** `成员常量`
* **名称:** `网络`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.网络连接

* **类型:** `成员常量`
* **名称:** `网络连接`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.系统字体

* **类型:** `成员常量`
* **名称:** `系统字体`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.模板

* **类型:** `成员常量`
* **名称:** `模板`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常开始菜单组

* **类型:** `成员常量`
* **名称:** `通常开始菜单组`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常程序菜单组

* **类型:** `成员常量`
* **名称:** `通常程序菜单组`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常启动菜单组

* **类型:** `成员常量`
* **名称:** `通常启动菜单组`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常桌面

* **类型:** `成员常量`
* **名称:** `通常桌面`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.程序数据目录

* **类型:** `成员常量`
* **名称:** `程序数据目录`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.打印机连接

* **类型:** `成员常量`
* **名称:** `打印机连接`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.本地程序数据

* **类型:** `成员常量`
* **名称:** `本地程序数据`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.非本地启动菜单组

* **类型:** `成员常量`
* **名称:** `非本地启动菜单组`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.非本地通常启动菜单组

* **类型:** `成员常量`
* **名称:** `非本地通常启动菜单组`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常收藏夹

* **类型:** `成员常量`
* **名称:** `通常收藏夹`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.互联网缓冲

* **类型:** `成员常量`
* **名称:** `互联网缓冲`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.Cookies

* **类型:** `成员常量`
* **名称:** `Cookies`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.历史

* **类型:** `成员常量`
* **名称:** `历史`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常程序数据

* **类型:** `成员常量`
* **名称:** `通常程序数据`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.Windows安装目录

* **类型:** `成员常量`
* **名称:** `Windows安装目录`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.Windows系统目录

* **类型:** `成员常量`
* **名称:** `Windows系统目录`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.Windows程序目录

* **类型:** `成员常量`
* **名称:** `Windows程序目录`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.我的图片

* **类型:** `成员常量`
* **名称:** `我的图片`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.配置文件

* **类型:** `成员常量`
* **名称:** `配置文件`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.X86系统目录

* **类型:** `成员常量`
* **名称:** `X86系统目录`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.X86程序目录

* **类型:** `成员常量`
* **名称:** `X86程序目录`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常程序目录

* **类型:** `成员常量`
* **名称:** `通常程序目录`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常X86程序目录

* **类型:** `成员常量`
* **名称:** `通常X86程序目录`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常模板

* **类型:** `成员常量`
* **名称:** `通常模板`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常文档

* **类型:** `成员常量`
* **名称:** `通常文档`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常管理工具

* **类型:** `成员常量`
* **名称:** `通常管理工具`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.管理工具

* **类型:** `成员常量`
* **名称:** `管理工具`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.网络或拨号连接

* **类型:** `成员常量`
* **名称:** `网络或拨号连接`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常音乐

* **类型:** `成员常量`
* **名称:** `通常音乐`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常图片

* **类型:** `成员常量`
* **名称:** `通常图片`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常视频

* **类型:** `成员常量`
* **名称:** `通常视频`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.资源

* **类型:** `成员常量`
* **名称:** `资源`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.非本地资源

* **类型:** `成员常量`
* **名称:** `非本地资源`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.通常OEM连接

* **类型:** `成员常量`
* **名称:** `通常OEM连接`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.CD刻录区

* **类型:** `成员常量`
* **名称:** `CD刻录区`
* **数据类型:** `特定目录类型2`

##### 火山.基本.特定目录类型2.附近的计算机

* **类型:** `成员常量`
* **名称:** `附近的计算机`
* **数据类型:** `特定目录类型2`

---

#### 火山.基本.系统关闭方式

* **类型:** `类`
* **名称:** `系统关闭方式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `常用功能.辅助类`

##### 火山.基本.系统关闭方式.关机

* **类型:** `成员常量`
* **名称:** `关机`
* **数据类型:** `系统关闭方式`
* **初始值:** `1`

##### 火山.基本.系统关闭方式.重启

* **类型:** `成员常量`
* **名称:** `重启`
* **数据类型:** `系统关闭方式`
* **初始值:** `2`

##### 火山.基本.系统关闭方式.注销

* **类型:** `成员常量`
* **名称:** `注销`
* **数据类型:** `系统关闭方式`
* **初始值:** `3`

##### 火山.基本.系统关闭方式.休眠

* **类型:** `成员常量`
* **名称:** `休眠`
* **数据类型:** `系统关闭方式`
* **初始值:** `4`

##### 火山.基本.系统关闭方式.冬眠

* **类型:** `成员常量`
* **名称:** `冬眠`
* **数据类型:** `系统关闭方式`
* **初始值:** `5`

---

#### 火山.基本.返回按钮类型

* **类型:** `类`
* **名称:** `返回按钮类型`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `常用功能.辅助类`
* **描述:** 用作提供信息框方法的返回按钮类型
* **相关例程:** [vol-选择夹1-tab_demo-main](#vol-选择夹1-tab_demo-main), [vol-选择夹2-tab_demo-main](#vol-选择夹2-tab_demo-main), [vol-选择夹3-tab_demo3-main](#vol-选择夹3-tab_demo3-main), [vol-对话框-dialog_test-main](#vol-对话框-dialog_test-main), [vol-文件浏览-file_viewer-main](#vol-文件浏览-file_viewer-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-树形框-tree_box-main](#vol-树形框-tree_box-main), [vol-工具条-tool_bar-main](#vol-工具条-tool_bar-main), [vol-状态条-status_bar-main](#vol-状态条-status_bar-main), [vol-表格-grid-main](#vol-表格-grid-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-设计并处理重叠界面-over_ui-main](#vol-设计并处理重叠界面-over_ui-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-用户自定义窗口组件-user_control-main](#vol-用户自定义窗口组件-user_control-main), [vol-祖国您好-base_test-main](#vol-祖国您好-base_test-main), [vol-菜单-menu_demo-main](#vol-菜单-menu_demo-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-系统全局热键-syshotkey-main](#vol-系统全局热键-syshotkey-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-演示dll-sampledll-main](#vol-演示dll-sampledll-main), [vol-条件编译项目1-cond_compile1-main](#vol-条件编译项目1-cond_compile1-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-调用动态链接库-dll_call-main](#vol-调用动态链接库-dll_call-main), [vol-一步一步跟我学火山-step_by_step-main](#vol-一步一步跟我学火山-step_by_step-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-密码管理-pw-main](#vol-密码管理-pw-main), [vol-高级网页解析-adv_html_parser-main](#vol-高级网页解析-adv_html_parser-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-大整数运算-bnsample-main](#vol-大整数运算-bnsample-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-正则表达式2-regex-main](#vol-正则表达式2-regex-main), [vol-串口通讯-cserialport-main](#vol-串口通讯-cserialport-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-tcp转发-tcp_forward-main](#vol-tcp转发-tcp_forward-main), [vol-数据报-udp-main](#vol-数据报-udp-main), [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main), [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件发送-send_email-main](#vol-邮件发送-send_email-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-ado-ado_sample-main](#vol-ado-ado_sample-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-redis连接池-redisconnectpool-main](#vol-redis连接池-redisconnectpool-main), [vol-mysql连接池-mysql_connectionpool-main](#vol-mysql连接池-mysql_connectionpool-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-rvm人像抠图-rvm_segmentation-main](#vol-rvm人像抠图-rvm_segmentation-main), [vol-图像融合-image_fusion-main](#vol-图像融合-image_fusion-main), [vol-形态学运算-morphological-main](#vol-形态学运算-morphological-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.返回按钮类型.确认钮

* **类型:** `成员常量`
* **名称:** `确认钮`
* **数据类型:** `返回按钮类型`
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main)

##### 火山.基本.返回按钮类型.取消钮

* **类型:** `成员常量`
* **名称:** `取消钮`
* **数据类型:** `返回按钮类型`

##### 火山.基本.返回按钮类型.放弃钮

* **类型:** `成员常量`
* **名称:** `放弃钮`
* **数据类型:** `返回按钮类型`

##### 火山.基本.返回按钮类型.重试钮

* **类型:** `成员常量`
* **名称:** `重试钮`
* **数据类型:** `返回按钮类型`

##### 火山.基本.返回按钮类型.忽略钮

* **类型:** `成员常量`
* **名称:** `忽略钮`
* **数据类型:** `返回按钮类型`

##### 火山.基本.返回按钮类型.是钮

* **类型:** `成员常量`
* **名称:** `是钮`
* **数据类型:** `返回按钮类型`
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.返回按钮类型.否钮

* **类型:** `成员常量`
* **名称:** `否钮`
* **数据类型:** `返回按钮类型`
* **相关例程:** [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main)

---

#### 火山.基本.信息框按钮

* **类型:** `类`
* **名称:** `信息框按钮`
* **文档分类:** `常用功能.辅助类`
* **描述:** 用作指定信息框方法所显示按钮的类型. 可以将本类中的常量值相加以组合"信息框"方法的"按钮"参数值,注意每组常量只能取用一个(第五组除外)
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-表格-grid-main](#vol-表格-grid-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-mysql连接池-mysql_connectionpool-main](#vol-mysql连接池-mysql_connectionpool-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-rvm人像抠图-rvm_segmentation-main](#vol-rvm人像抠图-rvm_segmentation-main), [vol-图像融合-image_fusion-main](#vol-图像融合-image_fusion-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.信息框按钮.确认钮

* **类型:** `成员常量`
* **名称:** `确认钮`
* **数据类型:** `整数`
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.信息框按钮.确认取消钮

* **类型:** `成员常量`
* **名称:** `确认取消钮`
* **数据类型:** `整数`
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main)

##### 火山.基本.信息框按钮.放弃重试忽略钮

* **类型:** `成员常量`
* **名称:** `放弃重试忽略钮`
* **数据类型:** `整数`

##### 火山.基本.信息框按钮.取消是否钮

* **类型:** `成员常量`
* **名称:** `取消是否钮`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main)

##### 火山.基本.信息框按钮.是否钮

* **类型:** `成员常量`
* **名称:** `是否钮`
* **数据类型:** `整数`
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.信息框按钮.重试取消钮

* **类型:** `成员常量`
* **名称:** `重试取消钮`
* **数据类型:** `整数`

##### 火山.基本.信息框按钮.错误图标

* **类型:** `成员常量`
* **名称:** `错误图标`
* **数据类型:** `整数`
* **相关例程:** [vol-表格-grid-main](#vol-表格-grid-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-mysql连接池-mysql_connectionpool-main](#vol-mysql连接池-mysql_connectionpool-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-rvm人像抠图-rvm_segmentation-main](#vol-rvm人像抠图-rvm_segmentation-main), [vol-图像融合-image_fusion-main](#vol-图像融合-image_fusion-main)

##### 火山.基本.信息框按钮.询问图标

* **类型:** `成员常量`
* **名称:** `询问图标`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.信息框按钮.警告图标

* **类型:** `成员常量`
* **名称:** `警告图标`
* **数据类型:** `整数`
* **相关例程:** [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.信息框按钮.信息图标

* **类型:** `成员常量`
* **名称:** `信息图标`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main)

##### 火山.基本.信息框按钮.默认按钮一

* **类型:** `成员常量`
* **名称:** `默认按钮一`
* **数据类型:** `整数`

##### 火山.基本.信息框按钮.默认按钮二

* **类型:** `成员常量`
* **名称:** `默认按钮二`
* **数据类型:** `整数`

##### 火山.基本.信息框按钮.默认按钮三

* **类型:** `成员常量`
* **名称:** `默认按钮三`
* **数据类型:** `整数`

##### 火山.基本.信息框按钮.默认按钮四

* **类型:** `成员常量`
* **名称:** `默认按钮四`
* **数据类型:** `整数`

##### 火山.基本.信息框按钮.程序等待

* **类型:** `成员常量`
* **名称:** `程序等待`
* **数据类型:** `整数`

##### 火山.基本.信息框按钮.系统等待

* **类型:** `成员常量`
* **名称:** `系统等待`
* **数据类型:** `整数`

##### 火山.基本.信息框按钮.位于前台

* **类型:** `成员常量`
* **名称:** `位于前台`
* **数据类型:** `整数`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main)

---

#### 火山.基本.系统电源状态

* **类型:** `类`
* **名称:** `系统电源状态`
* **文档分类:** `常用功能.辅助类`
* **描述:** 用于记录电源状态

##### 火山.基本.系统电源状态.电源状态

* **类型:** `成员变量`
* **名称:** `电源状态`
* **数据类型:** `整数`
* **描述:** 0 未连接电源线 1 连接电源线 255 未知状态

##### 火山.基本.系统电源状态.电池当前状态

* **类型:** `成员变量`
* **名称:** `电池当前状态`
* **数据类型:** `系统电池状态`
* **描述:** 取出电池状态

##### 火山.基本.系统电源状态.电池剩余电量

* **类型:** `成员变量`
* **名称:** `电池剩余电量`
* **数据类型:** `整数`
* **描述:** 电池剩余电量的百分比,此成员可以是 0 到 100 范围内的值，如果状态未知，则可以是 255。

##### 火山.基本.系统电源状态.电池剩余使用时间

* **类型:** `成员变量`
* **名称:** `电池剩余使用时间`
* **数据类型:** `长整数`
* **描述:** 电池剩余时间的秒数,如果剩余秒数未知或设备连接到交流电源,则为–1。

##### 火山.基本.系统电源状态.电池可用时间

* **类型:** `成员变量`
* **名称:** `电池可用时间`
* **数据类型:** `长整数`
* **描述:** 完全充电时电池寿命的秒数,如果电池的完整寿命未知或设备连接到交流电源,则为–1

---

#### 火山.基本.系统电池状态

* **类型:** `类`
* **名称:** `系统电池状态`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `常用功能.辅助类`
* **描述:** 用于记录电池状态的常量类

##### 火山.基本.系统电池状态.大于66

* **类型:** `成员常量`
* **名称:** `大于66`
* **数据类型:** `系统电池状态`
* **初始值:** `1`
* **描述:** 百分比

##### 火山.基本.系统电池状态.小于33

* **类型:** `成员常量`
* **名称:** `小于33`
* **数据类型:** `系统电池状态`
* **初始值:** `2`
* **描述:** 百分比

##### 火山.基本.系统电池状态.小于5

* **类型:** `成员常量`
* **名称:** `小于5`
* **数据类型:** `系统电池状态`
* **初始值:** `4`
* **描述:** 百分比

##### 火山.基本.系统电池状态.充电中

* **类型:** `成员常量`
* **名称:** `充电中`
* **数据类型:** `系统电池状态`
* **初始值:** `8`
* **描述:** 表示充电中

##### 火山.基本.系统电池状态.无电池

* **类型:** `成员常量`
* **名称:** `无电池`
* **数据类型:** `系统电池状态`
* **初始值:** `128`
* **描述:** 表示没有电池

##### 火山.基本.系统电池状态.未知

* **类型:** `成员常量`
* **名称:** `未知`
* **数据类型:** `系统电池状态`
* **初始值:** `255`
* **描述:** 未知状态

---

#### 火山.基本.常用功能类

* **类型:** `类`
* **名称:** `常用功能类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `常用功能`
* **相关例程:** [vol-时钟-timer-main](#vol-时钟-timer-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-演示dll-sampledll-main](#vol-演示dll-sampledll-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-yolov5目标检测-yolov5-main](#vol-yolov5目标检测-yolov5-main), [vol-dnn目标检测-dnn_objectdetection-main](#vol-dnn目标检测-dnn_objectdetection-main), [vol-dnn文本检测-dnn_text_detection_recognition-main](#vol-dnn文本检测-dnn_text_detection_recognition-main)

##### 火山.基本.常用功能类.取CPU核心数

* **类型:** `全局方法`
* **名称:** `取CPU核心数`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回当前计算机中CPU核心的数量,此值可以用作确定多线程程序中的推荐工作线程数目.

##### 火山.基本.常用功能类.取推荐工作线程数

* **类型:** `全局方法`
* **名称:** `取推荐工作线程数`
* **返回值数据类型:** `整数`
* **参数:**
	* `最多线程数` (`整数`, 默认值: `0`): 提供所允许的最多线程数目,为0表示无限制.
* **特性:**
	* `静态`
* **描述:** 根据当前计算机中CPU核心的数量计算并返回推荐工作线程的数目,使用该数目的工作线程能够最大限度地利用计算机资源而又不会让操作系统在线程切换上消耗过多.

##### 火山.基本.常用功能类.取系统电源状态

* **类型:** `全局方法`
* **名称:** `取系统电源状态`
* **返回值数据类型:** `系统电源状态`
* **特性:**
	* `静态`
* **描述:** 取出并返回系统当前电源状态

##### 火山.基本.常用功能类.为64位程序

* **类型:** `全局方法`
* **名称:** `为64位程序`
* **返回值数据类型:** `逻辑型`
* **特性:**
	* `静态`
* **描述:** 返回当前编译的是否为64位目标程序
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main)

##### 火山.基本.常用功能类.取目标操作系统

* **类型:** `全局方法`
* **名称:** `取目标操作系统`
* **返回值数据类型:** `目标操作系统类别`
* **特性:**
	* `静态`
* **描述:** 返回当前程序所对应的目标操作系统类型

##### 火山.基本.常用功能类.置入代码

* **类型:** `全局方法`
* **名称:** `置入代码`
* **参数:**
	* `代码字节` (`整数`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 将所指定的代码字节系列插入到当前程序语句编译位置. 注意: 本方法仅在编译32位程序时有效

##### 火山.基本.常用功能类.交换鼠标左右键

* **类型:** `全局方法`
* **名称:** `交换鼠标左右键`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `是否交换` (`逻辑型`, 默认值: `真`): 为真则互换两个鼠标按钮的功能,假则恢复正常状态.
* **特性:**
	* `静态`
* **描述:** 互换鼠标左右键的功能
* **返回值描述:** 返回真表示鼠标按钮的功能在调用这个函数之前已经互换,否则返回假.

##### 火山.基本.常用功能类.显示鼠标指针

* **类型:** `全局方法`
* **名称:** `显示鼠标指针`
* **返回值数据类型:** `整数`
* **参数:**
	* `是否显示` (`逻辑型`, 默认值: `真`): 为真则显示鼠标指针,为假则隐藏.
* **特性:**
	* `静态`
* **描述:** 显示或隐藏当前鼠标指针

##### 火山.基本.常用功能类.取鼠标位置

* **类型:** `全局方法`
* **名称:** `取鼠标位置`
* **返回值数据类型:** `位置类`
* **特性:**
	* `静态`
* **描述:** 返回鼠标当前在屏幕上的位置
* **相关例程:** [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main)

##### 火山.基本.常用功能类.取鼠标水平位置

* **类型:** `全局方法`
* **名称:** `取鼠标水平位置`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回鼠标当前在屏幕上的水平方向位置

##### 火山.基本.常用功能类.取鼠标垂直位置

* **类型:** `全局方法`
* **名称:** `取鼠标垂直位置`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回鼠标当前在屏幕上的垂直方向位置

##### 火山.基本.常用功能类.显示任务栏

* **类型:** `全局方法`
* **名称:** `显示任务栏`
* **参数:**
	* `是否显示任务栏` (`逻辑型`)
* **特性:**
	* `静态`
* **描述:** 显示/隐藏当前系统任务栏

##### 火山.基本.常用功能类.任务栏是否可视

* **类型:** `全局方法`
* **名称:** `任务栏是否可视`
* **返回值数据类型:** `逻辑型`
* **特性:**
	* `静态`
* **描述:** 返回系统当前任务栏是否可视

##### 火山.基本.常用功能类.锁定输入

* **类型:** `全局方法`
* **名称:** `锁定输入`
* **参数:**
	* `是否锁定输入` (`逻辑型`)
* **特性:**
	* `静态`
* **描述:** 锁定或解锁当前程序的键盘和鼠标输入事件

##### 火山.基本.常用功能类.取启动时间

* **类型:** `全局方法`
* **名称:** `取启动时间`
* **返回值数据类型:** `长整数`
* **特性:**
	* `静态`
* **描述:** 返回自从计算机系统启动以来的总共时间,单位毫秒.
* **相关例程:** [vol-时钟-timer-main](#vol-时钟-timer-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-yolov5目标检测-yolov5-main](#vol-yolov5目标检测-yolov5-main), [vol-dnn目标检测-dnn_objectdetection-main](#vol-dnn目标检测-dnn_objectdetection-main), [vol-dnn文本检测-dnn_text_detection_recognition-main](#vol-dnn文本检测-dnn_text_detection_recognition-main)

##### 火山.基本.常用功能类.打开指定网址

* **类型:** `全局方法`
* **名称:** `打开指定网址`
* **参数:**
	* `所欲浏览的超链接地址` (`文本型`): 可以是类似"http://www.voldp.com","file://c:\abc.txt"之类的传统地址文本,也可以是火山自己支持的"browse://文件路径"地址文本(用作启动操作系统资源管理器并定位到所指定的文件).
	* `窗口显示方式` (`整数`, 默认值: `-1`): 提供被启动程序的窗口显示方式,为以下值之一: -1:默认; 0:隐藏; 1:通常; 2:最小化; 3:最大化
* **特性:**
	* `静态`
* **描述:** 启动对应外部程序去打开浏览所指定的超链接地址
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main)

##### 火山.基本.常用功能类.运行

* **类型:** `全局方法`
* **名称:** `运行`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲运行的命令行` (`文本型`)
	* `是否等待程序运行完毕` (`逻辑型`, 默认值: `假`)
	* `被运行程序窗口显示方式` (`程序窗口显示方式`, 默认值: `程序窗口显示方式.普通激活`)
* **特性:**
	* `静态`
* **描述:** 运行指定的可执行文件或者外部命令,返回是否成功.
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main)

##### 火山.基本.常用功能类.取剪辑板文本

* **类型:** `全局方法`
* **名称:** `取剪辑板文本`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回存放于当前 Windows 系统剪辑板中的文本. 如果当前剪辑板中无文本数据,将返回空文本.
* **相关例程:** [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main)

##### 火山.基本.常用功能类.置剪辑板文本

* **类型:** `全局方法`
* **名称:** `置剪辑板文本`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `准备置入剪辑板的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将指定文本存放到当前 Windows 系统剪辑板中去,剪辑板中的原有内容被覆盖.
* **返回值描述:** 返回是否成功
* **相关例程:** [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main)

##### 火山.基本.常用功能类.剪辑板中可有文本

* **类型:** `全局方法`
* **名称:** `剪辑板中可有文本`
* **返回值数据类型:** `逻辑型`
* **特性:**
	* `静态`
* **描述:** 返回当前 Windows 系统剪辑板中是否有文本数据
* **相关例程:** [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.常用功能类.清除剪辑板

* **类型:** `全局方法`
* **名称:** `清除剪辑板`
* **特性:**
	* `静态`
* **描述:** 清除当前 Windows 系统剪辑板中的所有数据

##### 火山.基本.常用功能类.取屏幕宽度

* **类型:** `全局方法`
* **名称:** `取屏幕宽度`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回屏幕当前显示区域的宽度,单位为像素.
* **相关例程:** [vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main](#vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.常用功能类.取屏幕高度

* **类型:** `全局方法`
* **名称:** `取屏幕高度`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回屏幕当前显示区域的高度,单位为像素.
* **相关例程:** [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.常用功能类.取颜色数

* **类型:** `全局方法`
* **名称:** `取颜色数`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回当前显示方式所提供的最大颜色显示数目

##### 火山.基本.常用功能类.鸣叫

* **类型:** `全局方法`
* **名称:** `鸣叫`
* **参数:**
	* `声音类型` (`鸣叫声音类型`, 默认值: `鸣叫声音类型.默认`)
* **特性:**
	* `静态`
* **描述:** 通过计算机媒体设备或者喇叭发出一个声音
* **相关例程:** [vol-窗口组件动态消息过滤-msg_filter-main](#vol-窗口组件动态消息过滤-msg_filter-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.常用功能类.延时

* **类型:** `全局方法`
* **名称:** `延时`
* **参数:**
	* `欲等待的时间` (`整数`): 指定欲暂停程序执行的时间,单位为毫秒.
* **特性:**
	* `静态`
* **描述:** 暂停当前程序的运行并等待指定的时间
* **相关例程:** [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-rvm人像抠图-rvm_segmentation-main](#vol-rvm人像抠图-rvm_segmentation-main)

##### 火山.基本.常用功能类.取文本注册项

* **类型:** `全局方法`
* **名称:** `取文本注册项`
* **返回值数据类型:** `文本型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `全路径注册项名` (`文本型`)
	* `默认值` (`文本型`, 默认值: `""`): 如果指定的注册表项不存在,将返回此默认值文本.
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中返回指定的文本类型注册表项值. 如欲读取注册项默认值,请在项目名后加'\\'字符,如"vol\\".

##### 火山.基本.常用功能类.取文本注册项2

* **类型:** `全局方法`
* **名称:** `取文本注册项2`
* **返回值数据类型:** `文本型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `表项路径` (`文本型`): 提供表项所处的注册表路径文本,路径分隔符为'\\'字符.
	* `表项名称` (`文本型`): 提供表项的具体名称,如欲读取注册项默认值,请提供空文本.
	* `默认值` (`文本型`, 默认值: `""`): 如果指定的注册表项不存在,将返回此默认值文本.
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中返回指定的文本类型注册表项值

##### 火山.基本.常用功能类.取数值注册项

* **类型:** `全局方法`
* **名称:** `取数值注册项`
* **返回值数据类型:** `整数`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `全路径注册项名` (`文本型`)
	* `默认值` (`整数`, 默认值: `0`): 如果指定的注册表项不存在,将返回此默认值.
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中返回指定的数值类型注册表项值. 如欲读取注册项默认值,请在项目名后加'\\'字符,如"vol\\".

##### 火山.基本.常用功能类.取数值注册项2

* **类型:** `全局方法`
* **名称:** `取数值注册项2`
* **返回值数据类型:** `整数`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `表项路径` (`文本型`): 提供表项所处的注册表路径文本,路径分隔符为'\\'字符.
	* `表项名称` (`文本型`): 提供表项的具体名称,如欲读取注册项默认值,请提供空文本.
	* `默认值` (`整数`, 默认值: `0`): 如果指定的注册表项不存在,将返回此默认值.
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中返回指定的数值类型注册表项值

##### 火山.基本.常用功能类.取字节集注册项

* **类型:** `全局方法`
* **名称:** `取字节集注册项`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `全路径注册项名` (`文本型`)
	* `默认值` (`字节集类`, 默认值: `空对象`): 如果指定的注册表项不存在,将返回此默认字节集.如果为空对象,将返回空字节集.
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中返回指定的字节集类型注册表项值. 如欲读取注册项默认值,请在项目名后加'\\'字符,如"vol\\".

##### 火山.基本.常用功能类.取字节集注册项2

* **类型:** `全局方法`
* **名称:** `取字节集注册项2`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `表项路径` (`文本型`): 提供表项所处的注册表路径文本,路径分隔符为'\\'字符.
	* `表项名称` (`文本型`): 提供表项的具体名称,如欲读取注册项默认值,请提供空文本.
	* `默认值` (`字节集类`, 默认值: `空对象`): 如果指定的注册表项不存在,将返回此默认字节集.如果为空对象,将返回空字节集.
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中返回指定的字节集类型注册表项值

##### 火山.基本.常用功能类.写文本注册项

* **类型:** `全局方法`
* **名称:** `写文本注册项`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `全路径注册项名` (`文本型`)
	* `欲写入值` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中保存或建立指定的文本注册表项. 如欲写出注册项默认值,请在项目名后加'\\'字符,如"vol\\".
* **返回值描述:** 返回是否成功

##### 火山.基本.常用功能类.写文本注册项2

* **类型:** `全局方法`
* **名称:** `写文本注册项2`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `表项路径` (`文本型`): 提供表项所处的注册表路径文本,路径分隔符为'\\'字符.
	* `表项名称` (`文本型`): 提供表项的具体名称,如欲写出注册项默认值,请提供空文本.
	* `欲写入值` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中保存或建立指定的文本注册表项
* **返回值描述:** 返回是否成功

##### 火山.基本.常用功能类.写数值注册项

* **类型:** `全局方法`
* **名称:** `写数值注册项`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `全路径注册项名` (`文本型`)
	* `欲写入值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中保存或建立指定的数值注册表项. 如欲写出注册项默认值,请在项目名后加'\\'字符,如"vol\\".
* **返回值描述:** 返回是否成功

##### 火山.基本.常用功能类.写数值注册项2

* **类型:** `全局方法`
* **名称:** `写数值注册项2`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `表项路径` (`文本型`): 提供表项所处的注册表路径文本,路径分隔符为'\\'字符.
	* `表项名称` (`文本型`): 提供表项的具体名称,如欲写出注册项默认值,请提供空文本.
	* `欲写入值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中保存或建立指定的数值注册表项
* **返回值描述:** 返回是否成功

##### 火山.基本.常用功能类.写字节集注册项

* **类型:** `全局方法`
* **名称:** `写字节集注册项`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `全路径注册项名` (`文本型`)
	* `欲写入值` (`字节集类`)
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中保存或建立指定的数值注册表项. 如欲写出注册项默认值,请在项目名后加'\\'字符,如"vol\\".
* **返回值描述:** 返回是否成功

##### 火山.基本.常用功能类.写字节集注册项2

* **类型:** `全局方法`
* **名称:** `写字节集注册项2`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `表项路径` (`文本型`): 提供表项所处的注册表路径文本,路径分隔符为'\\'字符.
	* `表项名称` (`文本型`): 提供表项的具体名称,如欲写出注册项默认值,请提供空文本.
	* `欲写入值` (`字节集类`)
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中保存或建立指定的数值注册表项. 如欲写出注册项默认值,请在项目名后加'\\'字符,如"vol\\".
* **返回值描述:** 返回是否成功

##### 火山.基本.常用功能类.删除注册项

* **类型:** `全局方法`
* **名称:** `删除注册项`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `全路径注册项名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中删除指定注册表项或注册表目录. 如欲删除注册项默认值,请在项目名后加'\\'字符,如"vol\\".
* **返回值描述:** 返回是否成功

##### 火山.基本.常用功能类.删除注册项2

* **类型:** `全局方法`
* **名称:** `删除注册项2`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `表项路径` (`文本型`): 提供表项所处的注册表路径文本,路径分隔符为'\\'字符.
	* `表项名称` (`文本型`): 提供表项的具体名称,如欲删除注册项默认值,请提供空文本.
* **特性:**
	* `静态`
* **描述:** 在 Windows 注册表中删除指定注册表项
* **返回值描述:** 返回是否成功

##### 火山.基本.常用功能类.注册项是否存在

* **类型:** `全局方法`
* **名称:** `注册项是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `全路径注册项名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定注册表项是否存在. 如欲检查注册项是否具有默认值,请在项目名后加'\\'字符,如"vol\\".

##### 火山.基本.常用功能类.注册项是否存在2

* **类型:** `全局方法`
* **名称:** `注册项是否存在2`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `根目录` (`注册表根目录类型`)
	* `表项路径` (`文本型`): 提供表项所处的注册表路径文本,路径分隔符为'\\'字符.
	* `表项名称` (`文本型`): 提供表项的具体名称,如欲检查注册项是否具有默认值,请提供空文本.
* **特性:**
	* `静态`
* **描述:** 返回所指定注册表项是否存在

##### 火山.基本.常用功能类.取默认底色

* **类型:** `全局方法`
* **名称:** `取默认底色`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回Windows系统的默认窗口背景颜色

##### 火山.基本.常用功能类.快照

* **类型:** `全局方法`
* **名称:** `快照`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所取回图片` (`位图对象类`): 所取得的现有显示内容将被填入到此对象中
	* `窗口句柄` (`变整数`, 默认值: `0`): 提供欲捕获其显示内容的窗口句柄,如果为0则为捕获屏幕显示内容.
	* `输出宽度` (`整数`, 默认值: `0`): 指定图片的输出宽度. 如果小于0,参数值指定的是最终图片输出宽度相对于所取得图片宽度的百分比(最小为10%); 如果等于0,则按图片原宽度输出; 如果大于0,指定输出图片的绝对宽度.
	* `输出高度` (`整数`, 默认值: `0`): 指定图片的输出高度. 如果小于0,参数值指定的是最终图片输出高度相对于所取得图片高度的百分比(最小为10%); 如果等于0,则按图片原高度输出; 如果大于0,指定输出图片的绝对高度.
* **特性:**
	* `静态`
* **描述:** 取回指定窗口或屏幕上所有现有显示内容的图片对象.
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.常用功能类.读配置项

* **类型:** `全局方法`
* **名称:** `读配置项`
* **返回值数据类型:** `文本型`
* **参数:**
	* `配置文件名` (`文本型`): 指定配置文件的名称,通常以"ini"作为文件名后缀.
	* `节名称` (`文本型`): 指定欲读入配置项所处节的名称
	* `配置项名称` (`文本型`): 指定欲读入配置项在其节中的名称
	* `默认值` (`文本型`, 默认值: `""`): 如果所指定配置项不存在,将返回此默认值文本.
* **特性:**
	* `静态`
* **描述:** 读取并返回所指定配置文件中指定项目的文本内容
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main)

##### 火山.基本.常用功能类.写配置项

* **类型:** `全局方法`
* **名称:** `写配置项`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `配置文件名` (`文本型`): 指定配置文件的名称,通常以"ini"作为文件名后缀.
	* `节名称` (`文本型`): 指定欲写入配置项所处节的名称
	* `配置项名称` (`文本型`, 默认值: `空对象`): 指定欲写入配置项在其节中的名称.如果为空对象,则删除指定节及其下的所有配置项.
	* `欲写入值` (`文本型`, 默认值: `空对象`): 指定欲写入到指定配置项中的文本,如果为空对象,则删除所指定配置项.
* **特性:**
	* `静态`
* **描述:** 将指定文本内容写入指定配置项中或者删除指定的配置项或节,如果指定配置文件不存在,将会自动创建.
* **返回值描述:** 返回是否成功
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main)

##### 火山.基本.常用功能类.取配置节名

* **类型:** `全局方法`
* **名称:** `取配置节名`
* **返回值数据类型:** `文本数组类`
* **参数:**
	* `配置文件名` (`文本型`): 指定配置文件的名称,通常以"ini"作为文件名后缀.
* **特性:**
	* `静态`
* **描述:** 返回指定配置文件中所有已有节名的文本数组

##### 火山.基本.常用功能类.取操作系统类型

* **类型:** `全局方法`
* **名称:** `取操作系统类型`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回当前Windows操作系统的平台类型
* **返回值描述:** 返回值为以下值之一: 0.未知; 1.Windows 32S; 2.Windows 9X (包含Win95/Win98/WinME等); 3.Windows NT (包含WinNT、Win2000、WinXP等); 5. Windows 10; 6. Windows Server 2016 Technical Preview; 7. Windows 8.1; 8. Windows Server 2012 R2; 9. Windows 8; 10. Windows Server 2012; 11. Windows 7; 12. Windows Server 2008 R2; 13. Windows Server 2008; 14. Windows Vista

##### 火山.基本.常用功能类.取最后错误

* **类型:** `全局方法`
* **名称:** `取最后错误`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 调用操作系统的GetLastError函数,返回该API函数被调用后的返回值.

##### 火山.基本.常用功能类.取可执行文件位数

* **类型:** `全局方法`
* **名称:** `取可执行文件位数`
* **返回值数据类型:** `可执行文件位数`
* **参数:**
	* `文件名` (`文本型`): 提供所欲检查的可执行文件的名称
* **特性:**
	* `静态`
* **描述:** 返回所指定可执行文件运行时需求的CPU位数
* **返回值描述:** 无法识别或所指定文件读取失败将返回"可执行文件位数.未知"
* **相关例程:** [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main)

##### 火山.基本.常用功能类.取可执行文件设备类型

* **类型:** `全局方法`
* **名称:** `取可执行文件设备类型`
* **返回值数据类型:** `整数`
* **参数:**
	* `文件名` (`文本型`): 提供所欲检查的可执行文件的名称
* **特性:**
	* `静态`
* **描述:** 返回所指定可执行文件运行时需求的设备类型,具体可能返回值参见Windows SDK的"winnt.h"头文件中定义的"IMAGE_FILE_MACHINE_xxx"系列宏值.

##### 火山.基本.常用功能类.创建快捷方式

* **类型:** `全局方法`
* **名称:** `创建快捷方式`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `快捷方式文件名` (`文本型`): 如果文件名不包含后缀,将自动加上".lnk"后缀名.
	* `指向文件路径` (`文本型`): 提供快捷方式所指向文件的全路径名
	* `备注信息` (`文本型`, 默认值: `""`): 提供对应此快捷方式的描述文本信息
	* `命令行文本` (`文本型`, 默认值: `""`): 提供启动快捷方式指向文件时附加的命令行文本
	* `工作目录` (`文本型`, 默认值: `""`): 提供启动快捷方式指向文件时所需预置的工作目录
* **特性:**
	* `静态`
* **描述:** 建立指定的快捷方式文件,返回是否成功.

##### 火山.基本.常用功能类.查询快捷方式

* **类型:** `全局方法`
* **名称:** `查询快捷方式`
* **返回值数据类型:** `文本型`
* **参数:**
	* `快捷方式文件名` (`文本型`): 提供所欲查询的快捷方式文件名
* **特性:**
	* `静态`
* **描述:** 从指定快捷方式文件中获取该快捷方式所指向的文件路径名,如果该文件不是快捷方式文件或执行失败则返回空文本.

##### 火山.基本.常用功能类.取特定目录

* **类型:** `全局方法`
* **名称:** `取特定目录`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲获取目录类型` (`特定目录类型`): 提供所欲获取特定目录的类型
* **特性:**
	* `静态`
* **描述:** 返回指定的Windows系统特定目录,所返回目录名均以'\\'路径字符结束,如失败返回空文本.
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.常用功能类.取特定目录2

* **类型:** `全局方法`
* **名称:** `取特定目录2`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲获取目录类型` (`特定目录类型2`): 提供所欲获取特定目录的类型
* **特性:**
	* `静态`
* **描述:** 返回指定的Windows系统特定目录,所返回目录名均以'\\'路径字符结束,如失败返回空文本.

##### 火山.基本.常用功能类.关闭系统

* **类型:** `全局方法`
* **名称:** `关闭系统`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关闭方式` (`系统关闭方式`)
	* `是否强制执行` (`逻辑型`, 默认值: `假`): 是否不等待当前正在运行的所有软件正常结束而立即执行指定的操作
* **特性:**
	* `静态`
* **描述:** 可以执行关机/重启/注销等Windows系统操作.
* **返回值描述:** 返回是否成功

##### 火山.基本.常用功能类.取系统界面缩放比例

* **类型:** `全局方法`
* **名称:** `取系统界面缩放比例`
* **返回值数据类型:** `小数`
* **参数:**
	* `窗口句柄` (`变整数`, 默认值: `0`): 如果窗口句柄不为0,将返回该窗口当前所处显示器的DPI,否则将返回桌面窗口所处显示器的DPI.
* **特性:**
	* `静态`
* **描述:** 返回所指定显示器在Windows系统中设置的界面缩放比例(DPI)

##### 火山.基本.常用功能类.注册文件关联

* **类型:** `全局方法`
* **名称:** `注册文件关联`
* **参数:**
	* `欲关联的应用程序` (`文本型`): 提供欲关联的应用程序文件名(例如: "C:\MyApp\MyApp.exe"),为空文本表示使用当前程序.
	* `欲注册的扩展名` (`文本型`): 提供欲注册文件的扩展名(例如: ".txt"),需要以句点开始,不能为空文本.
	* `欲注册的键值` (`文本型`): 提供欲注册文件的扩展名在注册表中的对应键值(例如: "txtfile"),不能为空文本.
	* `图标所处文件名` (`文本型`): 提供被注册文件类型图标所处的文件名,为空文本表示使用当前程序.
	* `图标索引位置` (`整数`): 提供图标在"图标所处文件名"所指定文件的图标资源中的索引位置,为小于-1的负值表示为ID,不能等于-1.
	* `文件类型描述` (`文本型`, 默认值: `""`): 提供文件类型的描述文本
* **特性:**
	* `静态`
* **描述:** 将所指定后缀类型的文件注册关联到所指定的EXE文件

##### 火山.基本.常用功能类.取屏幕坐标颜色

* **类型:** `全局方法`
* **名称:** `取屏幕坐标颜色`
* **返回值数据类型:** `整数`
* **参数:**
	* `横坐标` (`整数`)
	* `纵坐标` (`整数`)
* **特性:**
	* `静态`
* **描述:** 返回屏幕上所指定位置处的颜色值

##### 火山.基本.常用功能类.为子窗口

* **类型:** `全局方法`
* **名称:** `为子窗口`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `父窗口句柄` (`变整数`): 提供欲检测父窗口的句柄
	* `子窗口句柄` (`变整数`): 提供欲检测子窗口的句柄
* **特性:**
	* `静态`
* **描述:** 返回"子窗口句柄"所对应窗口是否为"父窗口句柄"所对应窗口的子窗口

##### 火山.基本.常用功能类.全局信息框

* **类型:** `全局方法`
* **名称:** `全局信息框`
* **返回值数据类型:** `返回按钮类型`
* **参数:**
	* `提示信息` (`文本型`): 提供具体的提示文本
	* `按钮` (`整数`, 默认值: `0`): 由"信息框按钮"类中的各组常量值相加后的值,具体请见该类中的说明.
	* `窗口标题` (`文本型`, 默认值: `"信息:"`): 指定显示在信息框标题栏中的文本
	* `父窗口句柄` (`变整数`, 默认值: `0`): 提供父窗口的窗口句柄值,为0表示使用默认父窗口.
* **特性:**
	* `静态`
* **描述:** 显示一个信息框,等待用户单击按钮.
* **返回值描述:** 返回一个值告诉用户单击哪一个按钮. 如果信息框有"取消"按钮,则按下 ESC 键与单击"取消"按钮的效果相同.
* **相关例程:** [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-演示dll-sampledll-main](#vol-演示dll-sampledll-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main)

##### 火山.基本.常用功能类.全局询问信息框

* **类型:** `全局方法`
* **名称:** `全局询问信息框`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `询问信息` (`文本型`): 提供具体的询问提示文本
	* `窗口标题` (`文本型`, 默认值: `"询问:"`): 指定显示在信息框标题栏中的文本
	* `父窗口句柄` (`变整数`, 默认值: `0`): 提供父窗口的窗口句柄值,为0表示使用默认父窗口.
* **特性:**
	* `静态`
* **描述:** 用户点击"是"按钮将返回真,点击"否"按钮将返回假.

##### 火山.基本.常用功能类.全局错误信息框

* **类型:** `全局方法`
* **名称:** `全局错误信息框`
* **参数:**
	* `提示信息` (`文本型`): 提供具体的提示文本
	* `窗口标题` (`文本型`, 默认值: `"错误:"`): 指定显示在信息框标题栏中的文本
	* `父窗口句柄` (`变整数`, 默认值: `0`): 提供父窗口的窗口句柄值,为0表示使用默认父窗口.
* **特性:**
	* `静态`

##### 火山.基本.常用功能类.全局警告信息框

* **类型:** `全局方法`
* **名称:** `全局警告信息框`
* **参数:**
	* `提示信息` (`文本型`): 提供具体的提示文本
	* `窗口标题` (`文本型`, 默认值: `"警告:"`): 指定显示在信息框标题栏中的文本
	* `父窗口句柄` (`变整数`, 默认值: `0`): 提供父窗口的窗口句柄值,为0表示使用默认父窗口.
* **特性:**
	* `静态`

##### 火山.基本.常用功能类.显示鼠标

* **类型:** `全局方法`
* **名称:** `显示鼠标`
* **参数:**
	* `是否显示` (`逻辑型`): 注意: 每显示一次,内部计数会加一,每隐藏一次,内部计数会减一,只有当内部计数值大于等于0时,鼠标光标才会被显示.
* **特性:**
	* `静态`
* **描述:** 显示或隐藏鼠标光标.
* **相关例程:** [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main)

##### 火山.基本.常用功能类.取屏幕DPI

* **类型:** `全局方法`
* **名称:** `取屏幕DPI`
* **返回值数据类型:** `小数`
* **特性:**
	* `静态`
* **描述:** 返回系统主屏幕的DPI比例值(相对基准96 DPI). 注意本方法的返回值受到"关注屏幕DPI"方法的影响.

##### 火山.基本.常用功能类.乘于屏幕DPI

* **类型:** `全局方法`
* **名称:** `乘于屏幕DPI`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲使用尺寸值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 将指定尺寸值乘于系统主屏幕DPI比例值(相对基准96 DPI)后返回结果值. 注意本方法的返回值受到"关注屏幕DPI"方法的影响.
* **相关例程:** [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main)

##### 火山.基本.常用功能类.除于屏幕DPI

* **类型:** `全局方法`
* **名称:** `除于屏幕DPI`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲使用尺寸值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 将指定尺寸值除于系统主屏幕DPI比例值(相对基准96 DPI)后返回结果值. 注意本方法的返回值受到"关注屏幕DPI"方法的影响.

##### 火山.基本.常用功能类.关注屏幕DPI

* **类型:** `全局方法`
* **名称:** `关注屏幕DPI`
* **参数:**
	* `是否关注` (`逻辑型`): 为真则关注系统默认显示器的DPI,此时获取屏幕DPI将得到正确的缩放比例. 为假表示不关注,此时获取屏幕DPI将始终得到固定值1.
* **特性:**
	* `静态`
* **描述:** 设置本程序是否关注系统默认显示器的DPI(缩放比例)

##### 火山.基本.常用功能类.选择目录

* **类型:** `全局方法`
* **名称:** `选择目录`
* **返回值数据类型:** `文本型`
* **参数:**
	* `父窗口句柄` (`变整数`, 默认值: `0`): 提供所打开对话框的父窗口句柄,为0表示无.
* **特性:**
	* `静态`
* **描述:** 打开对话框选择所指定的目录,成功返回所选择目录,失败或用户取消关闭对话框则返回空文本. 注意: 本方法要求操作系统版本最低为 Windows Vista, 不支持 WinXP.

---

#### 火山.基本.鼠标等待器

* **类型:** `类`
* **名称:** `鼠标等待器`
* **文档分类:** `常用功能`
* **描述:** 当建立此类的对象实例时,会将鼠标形状自动设置为沙漏形,用作在即将长时间执行程序前提示用户. 当该对象实例超出其作用区域被销毁时,会自动把鼠标形状恢复到先前形状.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.鼠标等待器.恢复鼠标

* **类型:** `方法`
* **名称:** `恢复鼠标`
* **描述:** 用作在本对象实例被销毁前提前恢复鼠标的先前形状

---

#### 火山.基本.控制台程序运行结果

* **类型:** `类`
* **名称:** `控制台程序运行结果`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `控制台操作.辅助类`

##### 火山.基本.控制台程序运行结果.成功

* **类型:** `成员常量`
* **名称:** `成功`
* **数据类型:** `控制台程序运行结果`
* **描述:** 运行成功

##### 火山.基本.控制台程序运行结果.失败

* **类型:** `成员常量`
* **名称:** `失败`
* **数据类型:** `控制台程序运行结果`
* **描述:** 运行失败

##### 火山.基本.控制台程序运行结果.超时

* **类型:** `成员常量`
* **名称:** `超时`
* **数据类型:** `控制台程序运行结果`
* **描述:** 超出最大等待时间

---

#### 火山.基本.控制台程序编码类型

* **类型:** `类`
* **名称:** `控制台程序编码类型`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `控制台操作.辅助类`
* **描述:** 指定控制台程序运行时所输出文本(标准输出/错误输出)的编码类型

##### 火山.基本.控制台程序编码类型.多字节

* **类型:** `成员常量`
* **名称:** `多字节`
* **数据类型:** `控制台程序编码类型`

##### 火山.基本.控制台程序编码类型.UTF8

* **类型:** `成员常量`
* **名称:** `UTF8`
* **数据类型:** `控制台程序编码类型`

---

#### 火山.基本.控制台程序输出方向

* **类型:** `类`
* **名称:** `控制台程序输出方向`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `控制台操作.辅助类`
* **相关例程:** [vol-接口封装-impl_interface-main](#vol-接口封装-impl_interface-main), [vol-本地整数数据类型-native_int_data_type-main](#vol-本地整数数据类型-native_int_data_type-main), [vol-控制台程序-console_demo-main](#vol-控制台程序-console_demo-main), [vol-mfc控制台程序-mfc_console-main](#vol-mfc控制台程序-mfc_console-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-条码检测-barcode_detection-main](#vol-条码检测-barcode_detection-main), [vol-目标跟踪-target_tracking-main](#vol-目标跟踪-target_tracking-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main)

##### 火山.基本.控制台程序输出方向.标准输出设备

* **类型:** `成员常量`
* **名称:** `标准输出设备`
* **数据类型:** `控制台程序输出方向`
* **初始值:** `1`
* **相关例程:** [vol-接口封装-impl_interface-main](#vol-接口封装-impl_interface-main), [vol-本地整数数据类型-native_int_data_type-main](#vol-本地整数数据类型-native_int_data_type-main), [vol-控制台程序-console_demo-main](#vol-控制台程序-console_demo-main), [vol-mfc控制台程序-mfc_console-main](#vol-mfc控制台程序-mfc_console-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-条码检测-barcode_detection-main](#vol-条码检测-barcode_detection-main)

##### 火山.基本.控制台程序输出方向.错误输出设备

* **类型:** `成员常量`
* **名称:** `错误输出设备`
* **数据类型:** `控制台程序输出方向`
* **初始值:** `2`
* **相关例程:** [vol-目标跟踪-target_tracking-main](#vol-目标跟踪-target_tracking-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main)

---

#### 火山.基本.控制台操作类

* **类型:** `类`
* **名称:** `控制台操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `控制台操作`
* **相关例程:** [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-接口封装-impl_interface-main](#vol-接口封装-impl_interface-main), [vol-本地整数数据类型-native_int_data_type-main](#vol-本地整数数据类型-native_int_data_type-main), [vol-控制台程序-console_demo-main](#vol-控制台程序-console_demo-main), [vol-mfc控制台程序-mfc_console-main](#vol-mfc控制台程序-mfc_console-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-条码检测-barcode_detection-main](#vol-条码检测-barcode_detection-main), [vol-目标跟踪-target_tracking-main](#vol-目标跟踪-target_tracking-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main)

##### 火山.基本.控制台操作类.运行控制台程序

* **类型:** `全局方法`
* **名称:** `运行控制台程序`
* **返回值数据类型:** `控制台程序运行结果`
* **参数:**
	* `欲运行的命令行` (`文本型`): 提供所具体运行的命令行文本
	* `标准输出内容结果` (`文本型`, 默认值: `空对象`): 如果不为空对象,控制台程序在运行期间输出到标准输出设备的所有内容将被存放到此参数中返回.
	* `错误输出内容结果` (`文本型`, 默认值: `空对象`): 如果不为空对象,控制台程序在运行期间输出到标准错误设备的所有内容将被存放到此参数中返回. 提供本参数时,可以与"标准输出内容结果"参数提供同一文本变量,此时标准错误输出文本将附加在该变量后面.
	* `返回值结果` (`整数类`, 默认值: `空对象`): 如果不为空对象,则控制台程序的运行结果值将存放到此参数中返回.
	* `工作目录` (`文本型`, 默认值: `空对象`): 指定所运行命令行的工作目录,为空文本表示自动从所提供的命令行中获取,为空对象则使用本程序的当前目录.
	* `最长等待时间` (`整数`, 默认值: `0`): 等待命令行运行结束的最大等待毫秒数,为0表示无限等待.
	* `是否删除所有空行` (`逻辑型`, 默认值: `假`): 是否自动删除在"标准输出内容结果"和"错误输出内容结果"中所返回文本中的所有空白行
	* `输出编码类型` (`控制台程序编码类型`, 默认值: `控制台程序编码类型.多字节`): 提供所运行控制台程序标准和错误输出内容的编码格式,方法将据此来将这些内容转换存储进所提供的结果文本参数中.
* **特性:**
	* `静态`
* **描述:** 运行指定的控制台程序(不会打开控制台窗口),返回具体运行结果.

##### 火山.基本.控制台操作类.标准输出

* **类型:** `全局方法`
* **名称:** `标准输出`
* **参数:**
	* `输出方向` (`控制台程序输出方向`, 默认值: `控制台程序输出方向.标准输出设备`): 提供内容所输出到的设备
	* `欲输出内容` (`通用基本型`)
* **特性:**
	* `静态`
* **描述:** 在标准输出设备或标准错误设备上输出指定的内容. 注意本方法只能在控制台程序中使用.
* **相关例程:** [vol-接口封装-impl_interface-main](#vol-接口封装-impl_interface-main), [vol-控制台程序-console_demo-main](#vol-控制台程序-console_demo-main), [vol-mfc控制台程序-mfc_console-main](#vol-mfc控制台程序-mfc_console-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-目标跟踪-target_tracking-main](#vol-目标跟踪-target_tracking-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main)

##### 火山.基本.控制台操作类.标准输出行

* **类型:** `全局方法`
* **名称:** `标准输出行`
* **参数:**
	* `输出方向` (`控制台程序输出方向`, 默认值: `控制台程序输出方向.标准输出设备`): 提供内容所输出到的设备
	* `欲输出内容` (`通用基本型`)
* **特性:**
	* `静态`
* **描述:** 在标准输出设备或标准错误设备上输出一行指定的内容. 注意本方法只能在控制台程序中使用.
* **相关例程:** [vol-接口封装-impl_interface-main](#vol-接口封装-impl_interface-main), [vol-本地整数数据类型-native_int_data_type-main](#vol-本地整数数据类型-native_int_data_type-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-条码检测-barcode_detection-main](#vol-条码检测-barcode_detection-main)

##### 火山.基本.控制台操作类.标准输入

* **类型:** `全局方法`
* **名称:** `标准输入`
* **返回值数据类型:** `文本型`
* **参数:**
	* `是否回显` (`逻辑型`, 默认值: `真`): 决定输入时是否显示所输入字符
* **特性:**
	* `静态`
* **描述:** 在标准输入设备上请求输入最多包含2048个字符的一行文本,返回用户所输入的内容. 注意本方法只能在控制台程序中使用.
* **相关例程:** [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-控制台程序-console_demo-main](#vol-控制台程序-console_demo-main), [vol-mfc控制台程序-mfc_console-main](#vol-mfc控制台程序-mfc_console-main), [vol-条码检测-barcode_detection-main](#vol-条码检测-barcode_detection-main), [vol-目标跟踪-target_tracking-main](#vol-目标跟踪-target_tracking-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main)

##### 火山.基本.控制台操作类.标准输入字符

* **类型:** `全局方法`
* **名称:** `标准输入字符`
* **返回值数据类型:** `字符`
* **参数:**
	* `是否回显` (`逻辑型`, 默认值: `真`): 指定是否回显所输入的字符
* **特性:**
	* `静态`
* **描述:** 在标准输入设备上请求输入并返回一个字符. 注意本方法只能在控制台程序中使用.
* **相关例程:** [vol-接口封装-impl_interface-main](#vol-接口封装-impl_interface-main), [vol-本地整数数据类型-native_int_data_type-main](#vol-本地整数数据类型-native_int_data_type-main), [vol-控制台程序-console_demo-main](#vol-控制台程序-console_demo-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

---

#### 火山.基本.环境存取类

* **类型:** `类`
* **名称:** `环境存取类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `环境存取`
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览框扩展-webview2_extensions-main](#vol-edge浏览框扩展-webview2_extensions-main), [vol-edge浏览框自定义菜单-webview2_contextmenu-main](#vol-edge浏览框自定义菜单-webview2_contextmenu-main), [vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main](#vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main), [vol-位图处理-adv_bitmap-main](#vol-位图处理-adv_bitmap-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-程序崩溃回调-breakpad-main](#vol-程序崩溃回调-breakpad-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-密码管理-pw-main](#vol-密码管理-pw-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-rar文件解压-unrar-main](#vol-rar文件解压-unrar-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.环境存取类.取命令行

* **类型:** `全局方法`
* **名称:** `取命令行`
* **返回值数据类型:** `整数`
* **参数:**
	* `命令行文本返回数组` (`文本数组类`): 本数组用作存放所获取的命令行参数,其中原有内容将被清除.
* **特性:**
	* `静态`
* **描述:** 取出在启动程序时附加在其可执行文件名后面的所有以空格分隔的命令行文本参数
* **返回值描述:** 返回所填写到"命令行文本返回数组"参数中的成员数目
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

##### 火山.基本.环境存取类.取运行目录

* **类型:** `全局方法`
* **名称:** `取运行目录`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回当前被执行程序文件所处的目录. 注意: 所返回目录路径必定以路径字符结束,如: "c:\app\".
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览框扩展-webview2_extensions-main](#vol-edge浏览框扩展-webview2_extensions-main), [vol-edge浏览框自定义菜单-webview2_contextmenu-main](#vol-edge浏览框自定义菜单-webview2_contextmenu-main), [vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main](#vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main), [vol-位图处理-adv_bitmap-main](#vol-位图处理-adv_bitmap-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-程序崩溃回调-breakpad-main](#vol-程序崩溃回调-breakpad-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-密码管理-pw-main](#vol-密码管理-pw-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-rar文件解压-unrar-main](#vol-rar文件解压-unrar-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.环境存取类.取模块目录

* **类型:** `全局方法`
* **名称:** `取模块目录`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回当前被载入程序模块文件所处的目录. 与"取运行目录"相比,如果本程序为DLL文件,前者返回载入该DLL的EXE文件所处目录,本方法返回DLL文件自身所处目录. 注意: 所返回目录路径必定以路径字符结束,如: "c:\app\".

##### 火山.基本.环境存取类.取执行文件名

* **类型:** `全局方法`
* **名称:** `取执行文件名`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回当前被执行程序文件的名称
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main)

##### 火山.基本.环境存取类.读环境变量

* **类型:** `全局方法`
* **名称:** `读环境变量`
* **返回值数据类型:** `文本型`
* **参数:**
	* `环境变量名称` (`文本型`): 提供所欲获取其值的环境变量名称
* **特性:**
	* `静态`
* **描述:** 返回所指定操作系统环境变量的值,如不存在则返回空文本.

##### 火山.基本.环境存取类.写环境变量

* **类型:** `全局方法`
* **名称:** `写环境变量`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `环境变量名称` (`文本型`): 提供所欲设置其值的环境变量名称
	* `所欲设置的值` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 设置所指定操作系统环境变量的值,返回是否成功.

---

#### 火山.基本.目录删除模式

* **类型:** `类`
* **名称:** `目录删除模式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `磁盘操作.辅助类`

##### 火山.基本.目录删除模式.全部删除

* **类型:** `成员常量`
* **名称:** `全部删除`
* **数据类型:** `目录删除模式`
* **描述:** 删除所指定目录及其中的所有内容(包括所有直接或间接子目录)

##### 火山.基本.目录删除模式.仅删除文件

* **类型:** `成员常量`
* **名称:** `仅删除文件`
* **数据类型:** `目录删除模式`
* **描述:** 仅删除所指定目录(包括所有直接或间接子目录)中的所有文件

##### 火山.基本.目录删除模式.保留自身

* **类型:** `成员常量`
* **名称:** `保留自身`
* **数据类型:** `目录删除模式`
* **描述:** 删除所指定目录(包括所有直接或间接子目录)中的所有内容,但是不删除所指定目录本身.

---

#### 火山.基本.文件覆盖模式

* **类型:** `类`
* **名称:** `文件覆盖模式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `磁盘操作.辅助类`

##### 火山.基本.文件覆盖模式.覆盖

* **类型:** `成员常量`
* **名称:** `覆盖`
* **数据类型:** `文件覆盖模式`
* **描述:** 如果所欲复制到的文件已经存在,则将其覆盖.

##### 火山.基本.文件覆盖模式.忽略

* **类型:** `成员常量`
* **名称:** `忽略`
* **数据类型:** `文件覆盖模式`
* **描述:** 如果所欲复制到的文件已经存在,则跳过不复制.

##### 火山.基本.文件覆盖模式.快速

* **类型:** `成员常量`
* **名称:** `快速`
* **数据类型:** `文件覆盖模式`
* **描述:** 如果所欲复制到的文件已经存在且其尺寸和最后修改时间与源文件一致,则跳过不复制,否则将其覆盖.

##### 火山.基本.文件覆盖模式.报错

* **类型:** `成员常量`
* **名称:** `报错`
* **数据类型:** `文件覆盖模式`
* **描述:** 如果所欲复制到的文件已经存在,则返回复制失败.

---

#### 火山.基本.磁盘操作类

* **类型:** `类`
* **名称:** `磁盘操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `磁盘操作`
* **相关例程:** [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main)

##### 火山.基本.磁盘操作类.取磁盘总空间

* **类型:** `全局方法`
* **名称:** `取磁盘总空间`
* **返回值数据类型:** `长整数`
* **参数:**
	* `盘符字符` (`字符`, 默认值: `'\0'`): 提供所欲取其空间尺寸的盘符字符(如'C','D'等).如果为'\0',表示为当前驱动器.
* **特性:**
	* `静态`
* **描述:** 返回以1024 字节（KB）为单位的指定磁盘全部空间. 如果失败,返回-1.

##### 火山.基本.磁盘操作类.取磁盘剩余空间

* **类型:** `全局方法`
* **名称:** `取磁盘剩余空间`
* **返回值数据类型:** `长整数`
* **参数:**
	* `盘符字符` (`字符`, 默认值: `'\0'`): 提供所欲取其空间尺寸的盘符字符(如'C','D'等).如果为'\0',表示为当前驱动器.
* **特性:**
	* `静态`
* **描述:** 返回以1024 字节（KB）为单位的指定磁盘剩余可用空间. 如果失败,返回-1.

##### 火山.基本.磁盘操作类.取磁盘卷标

* **类型:** `全局方法`
* **名称:** `取磁盘卷标`
* **返回值数据类型:** `文本型`
* **参数:**
	* `盘符字符` (`字符`, 默认值: `'\0'`): 提供所欲取其卷标文本的盘符字符(如'C','D'等).如果为'\0',表示为当前驱动器.
* **特性:**
	* `静态`
* **描述:** 成功返回指定磁盘的卷标文本,失败返回空文本.

##### 火山.基本.磁盘操作类.置磁盘卷标

* **类型:** `全局方法`
* **名称:** `置磁盘卷标`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `盘符字符` (`字符`, 默认值: `'\0'`): 提供所设置其卷标的盘符字符(如'C','D'等).如果为'\0',表示为当前驱动器.
	* `所欲设置的卷标文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 设置指定磁盘的卷标文本.成功返回真,失败返回假.

##### 火山.基本.磁盘操作类.取磁盘序列号

* **类型:** `全局方法`
* **名称:** `取磁盘序列号`
* **返回值数据类型:** `整数`
* **参数:**
	* `盘符字符` (`字符`, 默认值: `'\0'`): 提供所欲取其序列号的盘符字符(如'C','D'等).如果为'\0',表示为当前驱动器.
* **特性:**
	* `静态`
* **描述:** 成功返回指定磁盘的序列号值,失败返回-1.

##### 火山.基本.磁盘操作类.改变驱动器

* **类型:** `全局方法`
* **名称:** `改变驱动器`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `盘符字符` (`字符`): 提供所欲改变驱动器的盘符字符(如'C','D'等)
* **特性:**
	* `静态`
* **描述:** 改变当前的缺省驱动器,返回是否成功.

##### 火山.基本.磁盘操作类.改变目录

* **类型:** `全局方法`
* **名称:** `改变目录`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲改变到的目录` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 改变现行目录位置,返回是否成功.

##### 火山.基本.磁盘操作类.取当前目录

* **类型:** `全局方法`
* **名称:** `取当前目录`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回现行目录位置

##### 火山.基本.磁盘操作类.创建目录

* **类型:** `全局方法`
* **名称:** `创建目录`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲创建的目录` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 创建所指定目录,返回是否成功. 注意: 所提供路径内的中间目录如果不存在,将会自动创建.
* **相关例程:** [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main)

##### 火山.基本.磁盘操作类.删除目录

* **类型:** `全局方法`
* **名称:** `删除目录`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲删除的目录` (`文本型`)
	* `删除模式` (`目录删除模式`)
	* `仅检测文件删除失败` (`逻辑型`, 默认值: `假`): 指定是否仅当删除文件失败时才会出错返回(即允许目录删除失败)
* **特性:**
	* `静态`
* **描述:** 删除所指定目录,返回是否成功. 由于本方法会自动删除所有直接/间接子目录,请务必谨慎使用本命令.

##### 火山.基本.磁盘操作类.文件尺寸和时间是否相同

* **类型:** `全局方法`
* **名称:** `文件尺寸和时间是否相同`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `文件名1` (`文本型`)
	* `文件名2` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定的两个文件是否均存在且文件尺寸和最后修改时间都一致

##### 火山.基本.磁盘操作类.复制文件

* **类型:** `全局方法`
* **名称:** `复制文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `被复制文件的名称` (`文本型`): 指定被复制文件的名称,必须已经存在.
	* `复制到文件的名称` (`文本型`): 指定所欲复制到文件的名称,如果该文件所处目录尚不存在,则自动将其创建.
	* `覆盖模式` (`文件覆盖模式`, 默认值: `文件覆盖模式.覆盖`): 指定具体的复制覆盖模式
* **特性:**
	* `静态`
* **描述:** 将所指定的文件复制到另一位置,返回是否成功.

##### 火山.基本.磁盘操作类.复制目录

* **类型:** `全局方法`
* **名称:** `复制目录`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `源目录名称` (`文本型`): 提供所欲复制的源目录名称,该目录必须已经存在.
	* `目的目录名称` (`文本型`): 提供欲复制到的目的目录名称,该目录必须已经存在.
	* `所欲复制文件` (`文本型`, 默认值: `""`): 提供所欲复制文件的匹配名称容,支持使用多字符 (*) 和单字符 (?) 通配符. 如果为空文本,则默认为"*.*".
	* `覆盖模式` (`文件覆盖模式`, 默认值: `文件覆盖模式.覆盖`): 提供目录中所有文件的具体复制覆盖模式
	* `是否复制子目录内容` (`逻辑型`, 默认值: `假`): 指定是否递归复制源目录中的所有直接/间接子目录,如果本参数值为真,注意复制目的目录中的这些子目录不需要一定存在,复制时如不存在会自动创建.
	* `复制出错记录数组` (`文本数组类`, 默认值: `空对象`): 如果不为空对象,则将所有复制失败的源文件和目的文件名加入进去(每两个成员为一个记录).
* **特性:**
	* `静态`
* **描述:** 将所指定源目录中的所有匹配文件复制到目标目录中去.
* **返回值描述:** 全部复制成功返回真,存在文件/目录复制失败则返回假. 也就是说: 复制过程会一定完成,并不会因为某个文件复制失败而就中途退出.

##### 火山.基本.磁盘操作类.移动文件

* **类型:** `全局方法`
* **名称:** `移动文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `被移动文件的名称` (`文本型`): 指定被移动文件的名称,必须已经存在.
	* `所欲移动到位置` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定的文件移动到另一位置,返回是否成功.

##### 火山.基本.磁盘操作类.删除文件

* **类型:** `全局方法`
* **名称:** `删除文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲删除文件的名称` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 删除所指定的文件,返回是否成功.

##### 火山.基本.磁盘操作类.文件更名

* **类型:** `全局方法`
* **名称:** `文件更名`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲更名的文件或目录名` (`文本型`)
	* `欲更改到的文件或目录名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 重新命名一个文件或目录,返回是否成功.

##### 火山.基本.磁盘操作类.文件是否存在

* **类型:** `全局方法`
* **名称:** `文件是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检测的文件或目录名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定的文件或目录是否存在
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.磁盘操作类.取文件时间

* **类型:** `全局方法`
* **名称:** `取文件时间`
* **返回值数据类型:** `小数`
* **参数:**
	* `所欲检测的文件或目录名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回指定文件或目录被创建或最后修改后的日期和时间,如果该文件不存在,将返回"数值范围.最小日期时间值"常量值(100年1月1日),可以使用"为最小时间"方法进行判断.

##### 火山.基本.磁盘操作类.取文件尺寸

* **类型:** `全局方法`
* **名称:** `取文件尺寸`
* **返回值数据类型:** `长整数`
* **参数:**
	* `所欲取长度的文件名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定文件的尺寸,单位字节,如果所指定文件不存在则返回-1.

##### 火山.基本.磁盘操作类.取文件属性

* **类型:** `全局方法`
* **名称:** `取文件属性`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲检测的文件名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定文件的属性值,如果所指定文件不存在则返回-1. 所返回属性值可以通过使用"位与"关键字与"文件属性"类中的相关常量值进行比较来判断某属性是否被置位.

##### 火山.基本.磁盘操作类.置文件属性

* **类型:** `全局方法`
* **名称:** `置文件属性`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲设置属性的文件名` (`文本型`)
	* `所欲设置的属性值` (`整数`): 参数值可以为"文件属性"类中各个常量值的和,用作同时指定多个匹配属性.
* **特性:**
	* `静态`
* **描述:** 设置所指定文件的属性,返回是否成功.

##### 火山.基本.磁盘操作类.取临时文件名

* **类型:** `全局方法`
* **名称:** `取临时文件名`
* **返回值数据类型:** `文本型`
* **参数:**
	* `目录名` (`文本型`, 默认值: `""`): 提供所欲处理的目录名,为空文本表示使用系统的标准临时目录.
* **特性:**
	* `静态`
* **描述:** 返回一个在指定目录中确定不存在的后缀为".tmp"的全路径文件名称

##### 火山.基本.磁盘操作类.读入文件

* **类型:** `全局方法`
* **名称:** `读入文件`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲读取文件名` (`文本型`): 提供所欲读取文件的路径名称
	* `所欲读取数据尺寸` (`整数`, 默认值: `-1`): 提供所欲读取数据的尺寸,为-1表示全部读取.
* **特性:**
	* `静态`
* **描述:** 从所指定路径文件中读入指定尺寸的数据,返回所实际读入的数据.
* **相关例程:** [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main)

##### 火山.基本.磁盘操作类.写到文件

* **类型:** `全局方法`
* **名称:** `写到文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲写到文件的名称` (`文本型`)
	* `字节集数据` (`字节集类`): 提供所欲写出的字节集数据
	* `所欲写出数据尺寸` (`整数`, 默认值: `-1`): 提供所欲写出数据的尺寸,为-1表示全部写出.
* **特性:**
	* `静态`
* **描述:** 将所指定的字节集数据写出到所指定名称的文件,文件中的原有内容将被覆盖,返回是否成功.
* **相关例程:** [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-位图处理-adv_bitmap-main](#vol-位图处理-adv_bitmap-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main)

##### 火山.基本.磁盘操作类.为绝对路径

* **类型:** `全局方法`
* **名称:** `为绝对路径`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检测的路径` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定路径是否为绝对路径

##### 火山.基本.磁盘操作类.到相对路径文件名

* **类型:** `全局方法`
* **名称:** `到相对路径文件名`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的绝对路径文件名` (`文本型`): 提供所欲转换的绝对路径文件名
	* `所基于的绝对路径` (`文本型`): 所提供的绝对路径文件名将被转换到基于此目录的相对路径文件名
	* `结果相对路径文件名` (`文本型`): 用作存放所转换后的相对路径文件名
* **特性:**
	* `静态`
* **描述:** 将所指定的绝对路径文件名转换为基于所指定路径的相对路径文件名
* **返回值描述:** 返回所转换后的相对路径文件名

##### 火山.基本.磁盘操作类.到相对路径

* **类型:** `全局方法`
* **名称:** `到相对路径`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的绝对路径` (`文本型`): 提供所欲转换的绝对路径
	* `所基于的绝对路径` (`文本型`): 所提供的绝对路径将被转换到基于此目录的相对路径
	* `结果相对路径` (`文本型`): 用作存放所转换后的相对路径
* **特性:**
	* `静态`
* **描述:** 将所指定的绝对路径转换为基于所指定路径的相对路径
* **返回值描述:** 返回所转换后的相对路径

##### 火山.基本.磁盘操作类.到绝对路径

* **类型:** `全局方法`
* **名称:** `到绝对路径`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的相对路径` (`文本型`): 提供所欲转换的相对路径
	* `结果路径` (`文本型`): 用作存放所转换后的绝对路径
* **特性:**
	* `静态`
* **描述:** 根据现行目录建立所指定路径的绝对路径
* **返回值描述:** 返回所转换后的绝对路径

##### 火山.基本.磁盘操作类.连接路径

* **类型:** `全局方法`
* **名称:** `连接路径`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲连接的路径1` (`文本型`)
	* `所欲连接的路径2` (`文本型`)
	* `连接结果路径` (`文本型`): 用作存放连接后的结果路径
* **特性:**
	* `静态`
* **描述:** 将两个路径连接起来,返回连接后的结果路径.
* **返回值描述:** 返回连接结果路径

##### 火山.基本.磁盘操作类.取文件名后缀

* **类型:** `全局方法`
* **名称:** `取文件名后缀`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲取后缀的文件名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定文件名的后缀名称(注意不以'.'字符开头),如果不存在则返回空文本.

##### 火山.基本.磁盘操作类.改变文件名后缀

* **类型:** `全局方法`
* **名称:** `改变文件名后缀`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所改变后缀的文件名` (`文本型`)
	* `所改变到的后缀` (`文本型`): 提供所改变到的后缀名称(注意不以'.'字符开头)
* **特性:**
	* `静态`
* **描述:** 改变所指定文件名的后缀名称,然后将其返回.

##### 火山.基本.磁盘操作类.取文件名路径

* **类型:** `全局方法`
* **名称:** `取文件名路径`
* **返回值数据类型:** `文本型`
* **参数:**
	* `欲取其路径的文件名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 如所指定文件名中存在路径部分,将其返回,否则返回空文本.

##### 火山.基本.磁盘操作类.取文件名无路径部分

* **类型:** `全局方法`
* **名称:** `取文件名无路径部分`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所处理的文件名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回所指定文件名的无路径部分
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main)

##### 火山.基本.磁盘操作类.浏览选中文件

* **类型:** `全局方法`
* **名称:** `浏览选中文件`
* **参数:**
	* `所欲选中的文件名` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 调用资源管理器打开指定文件所处的文件夹并将其选中
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main)

---

#### 火山.基本.文件属性

* **类型:** `类`
* **名称:** `文件属性`
* **文档分类:** `磁盘操作.辅助类`
* **描述:** 提供文件的各种属性值

##### 火山.基本.文件属性.存档文件

* **类型:** `成员常量`
* **名称:** `存档文件`
* **数据类型:** `整数`

##### 火山.基本.文件属性.子目录

* **类型:** `成员常量`
* **名称:** `子目录`
* **数据类型:** `整数`

##### 火山.基本.文件属性.隐藏文件

* **类型:** `成员常量`
* **名称:** `隐藏文件`
* **数据类型:** `整数`

##### 火山.基本.文件属性.通常文件

* **类型:** `成员常量`
* **名称:** `通常文件`
* **数据类型:** `整数`

##### 火山.基本.文件属性.只读文件

* **类型:** `成员常量`
* **名称:** `只读文件`
* **数据类型:** `整数`

##### 火山.基本.文件属性.系统文件

* **类型:** `成员常量`
* **名称:** `系统文件`
* **数据类型:** `整数`

##### 火山.基本.文件属性.临时文件

* **类型:** `成员常量`
* **名称:** `临时文件`
* **数据类型:** `整数`

---

#### 火山.基本.文件查找句柄类

* **类型:** `类`
* **名称:** `文件查找句柄类`
* **特性:**
	* `未公开`(无法在所处包外部使用,其中的内容只能通过此类的继承类对外提供)
	* `抽象类`(禁止直接定义其实例变量)
* **文档分类:** `磁盘操作.辅助类`

##### 火山.基本.文件查找句柄类.查找句柄

* **类型:** `成员变量`
* **名称:** `查找句柄`
* **数据类型:** `变整数`

##### 火山.基本.文件查找句柄类.关闭

* **类型:** `方法`
* **名称:** `关闭`

---

#### 火山.基本.文件查找类

* **类型:** `类`
* **名称:** `文件查找类`
* **模板基础类:** `参考对象模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文件查找句柄类`
* **文档分类:** `磁盘操作`
* **描述:** 用作支持查找所指定名称的文件. 参考数据中记录当前文件搜寻句柄值,为0表示无. 之所以将文件搜寻句柄值放在参考数据中,是为了支持本对象的复制对象与本对象共享同一句柄.
* **相关例程:** [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main)

##### 火山.基本.文件查找类.找到文件

* **类型:** `事件定义方法`
* **名称:** `找到文件`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲寻找文件的属性` (`整数`): 调用"寻找文件"所提供的"欲寻找文件的属性"参数值
	* `当前文件名称` (`文本型`): 提供当前所找到的文件或目录的名称
	* `当前文件属性` (`整数`): 提供当前所找到的文件或目录的属性,为"文件属性"类中各个常量值的组合,可以使用"位与"关键字分别判断.
* **描述:** 每当找到任何一个文件或目录,在进行"欲寻找文件的属性"参数值所指定的属性匹配检查之前,就会发送此事件.
* **返回值描述:** 事件处理方法返回1表示认可此文件并将其返回,返回0表示不进行任何处理.

##### 火山.基本.文件查找类.寻找文件

* **类型:** `方法`
* **名称:** `寻找文件`
* **返回值数据类型:** `文本型`
* **参数:**
	* `欲寻找文件` (`文本型`): 第一次调用本方法时,本参数内容不能为空,其中支持使用多字符 (*) 和单字符 (?) 通配符,在第一次调用以后如果想继续得到其它匹配的文件名,再一次调用本方法且为本参数提供空文本内容. 查找过程中,"."和".."子目录将会被始终跳过.
	* `欲寻找文件的属性` (`整数`, 默认值: `-1`): 参数值可以为"文件属性"类中各个常量值的和,用作同时指定多个匹配属性.凡是文件具有本参数中所指定的任一属性,则认为其通过匹配.如果为-1,则匹配除子目录外的所有文件.
	* `欲跳过文件的属性` (`整数`, 默认值: `6`): 参数值可以为"文件属性"类中各个常量值的和,用作同时指定多个匹配属性.凡是文件具有本参数中所指定的任一属性,则认为其未通过匹配(将其跳过). 本参数优先级在"欲寻找文件的属性"参数及"找到文件"事件之前. 默认值6等于"文件属性.系统文件 + 文件属性.隐藏文件".
* **描述:** 寻找所指定名称的文件
* **返回值描述:** 成功返回所找到的文件名或目录名,未找到则返回空文本.一旦返回值为空文本,再次调用本方法时,就必须指定非空"欲寻找文件"参数值.寻找过程中随时可以使用一个新的非空"欲寻找文件"参数值来启动新的文件寻找.
* **相关例程:** [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main)

##### 火山.基本.文件查找类.停止寻找文件

* **类型:** `方法`
* **名称:** `停止寻找文件`
* **描述:** 如果先前启动了文件寻找,调用本方法可以停止寻找. 本方法调用不是必需的,本类对象被清理时会自动停止寻找,但是调用本方法可以提前清理相关所占用的资源.

---

#### 火山.基本.文件打开方式

* **类型:** `类`
* **名称:** `文件打开方式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `文件读写.辅助类`
* **描述:** 提供文件的各种打开方式
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件打开方式.读入

* **类型:** `成员常量`
* **名称:** `读入`
* **数据类型:** `文件打开方式`
* **初始值:** `1`
* **描述:** 从指定文件读入数据,如果该文件不存在则失败.

##### 火山.基本.文件打开方式.写出

* **类型:** `成员常量`
* **名称:** `写出`
* **数据类型:** `文件打开方式`
* **初始值:** `2`
* **描述:** 写出数据到指定文件,如果该文件不存在则失败.

##### 火山.基本.文件打开方式.读写

* **类型:** `成员常量`
* **名称:** `读写`
* **数据类型:** `文件打开方式`
* **初始值:** `3`
* **描述:** 从文件中读入数据或者写出数据到文件,如果该文件不存在则失败.
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件打开方式.重写

* **类型:** `成员常量`
* **名称:** `重写`
* **数据类型:** `文件打开方式`
* **初始值:** `4`
* **描述:** 写出数据到指定文件.如果该文件不存在则先创建一个新文件,如果已经存在就先清除其中的所有数据.

##### 火山.基本.文件打开方式.改写

* **类型:** `成员常量`
* **名称:** `改写`
* **数据类型:** `文件打开方式`
* **初始值:** `5`
* **描述:** 写出数据到指定文件.如果该文件不存在则创建一个新文件,如果已经存在就直接打开.
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main)

##### 火山.基本.文件打开方式.改读

* **类型:** `成员常量`
* **名称:** `改读`
* **数据类型:** `文件打开方式`
* **初始值:** `6`
* **描述:** 从文件中读入数据或者写出数据到文件.如果该文件不存在则创建一个新文件,如果已经存在就直接打开.

---

#### 火山.基本.文件共享方式

* **类型:** `类`
* **名称:** `文件共享方式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `文件读写.辅助类`
* **描述:** 提供文件在进程之间的各种共享方式
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件共享方式.无限制

* **类型:** `成员常量`
* **名称:** `无限制`
* **数据类型:** `文件共享方式`
* **初始值:** `1`
* **描述:** 允许其它进程任意读写此文件
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件共享方式.禁止读

* **类型:** `成员常量`
* **名称:** `禁止读`
* **数据类型:** `文件共享方式`
* **初始值:** `2`
* **描述:** 禁止其它进程读此文件

##### 火山.基本.文件共享方式.禁止写

* **类型:** `成员常量`
* **名称:** `禁止写`
* **数据类型:** `文件共享方式`
* **初始值:** `3`
* **描述:** 禁止其它进程写此文件

##### 火山.基本.文件共享方式.禁止读写

* **类型:** `成员常量`
* **名称:** `禁止读写`
* **数据类型:** `文件共享方式`
* **初始值:** `4`
* **描述:** 禁止其它进程读写此文件

---

#### 火山.基本.文件基准位置

* **类型:** `类`
* **名称:** `文件基准位置`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `文件读写.辅助类`
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件基准位置.文件首

* **类型:** `成员常量`
* **名称:** `文件首`
* **数据类型:** `文件基准位置`
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件基准位置.文件尾

* **类型:** `成员常量`
* **名称:** `文件尾`
* **数据类型:** `文件基准位置`

##### 火山.基本.文件基准位置.现行位置

* **类型:** `成员常量`
* **名称:** `现行位置`
* **数据类型:** `文件基准位置`

---

#### 火山.基本.文件读写句柄类

* **类型:** `类`
* **名称:** `文件读写句柄类`
* **特性:**
	* `未公开`(无法在所处包外部使用,其中的内容只能通过此类的继承类对外提供)
	* `抽象类`(禁止直接定义其实例变量)
* **文档分类:** `文件读写.辅助类`

##### 火山.基本.文件读写句柄类.文件句柄

* **类型:** `成员变量`
* **名称:** `文件句柄`
* **数据类型:** `变整数`

##### 火山.基本.文件读写句柄类.关闭

* **类型:** `方法`
* **名称:** `关闭`

---

#### 火山.基本.文件读写类

* **类型:** `类`
* **名称:** `文件读写类`
* **模板基础类:** `参考对象模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文件读写句柄类`
* **文档分类:** `文件读写`
* **描述:** 用作支持读写所指定名称的文件. 参考数据中记录当前文件被打开后的句柄值,为0表示无. 之所以将文件句柄值放在参考数据中,是为了支持本对象的复制对象与本对象共享同一句柄.
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件读写类.是否已打开

* **类型:** `方法`
* **名称:** `是否已打开`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回是否已经打开了文件
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main)

##### 火山.基本.文件读写类.取文件句柄

* **类型:** `方法`
* **名称:** `取文件句柄`
* **返回值数据类型:** `变整数`
* **描述:** 如果当前已经打开了文件,返回其句柄值,否则返回0.

##### 火山.基本.文件读写类.打开文件

* **类型:** `方法`
* **名称:** `打开文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲打开的文件名称` (`文本型`)
	* `打开方式` (`文件打开方式`, 默认值: `文件打开方式.读写`): 提供文件的具体打开方式
	* `共享方式` (`文件共享方式`, 默认值: `文件共享方式.无限制`): 指定限制其它进程操作此文件的方式
* **描述:** 打开所指定的文件,以对文件进行读写操作,返回是否打开成功. 先前被打开的文件将被自动关闭.
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件读写类.关闭文件

* **类型:** `方法`
* **名称:** `关闭文件`
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件读写类.锁住文件

* **类型:** `方法`
* **名称:** `锁住文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲加锁数据的偏移位置` (`长整数`): 指定欲加锁区域在文件中的偏移位置
	* `欲加锁数据的尺寸` (`长整数`): 指定欲加锁区域的尺寸,单位字节.
	* `加锁重试时间` (`整数`, 默认值: `0`): 本参数指定加锁失败后反复进行重试的毫秒数.为0表示一旦失败立即返回,为-1则反复进行重试直到加锁成功为止.
* **描述:** 在有若干个进程访问同一个文件的环境中,使用本方法可以拒绝其它进程对被打开文件中的某个区域进行读写访问. 文件必须已经被打开,返回是否成功.

##### 火山.基本.文件读写类.解锁文件

* **类型:** `方法`
* **名称:** `解锁文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲解锁数据的偏移位置` (`长整数`): 指定欲解锁区域在文件中的偏移位置
	* `欲解锁数据的尺寸` (`长整数`): 指定欲解锁区域的尺寸,单位字节.
* **描述:** 解除由"锁住文件"命令对文件所进行的锁定,返回是否成功. 注意: 本方法调用时所提供的参数值必须与调用"锁住文件"方法时所提供的参数值完全一致.

##### 火山.基本.文件读写类.移动读写位置

* **类型:** `方法`
* **名称:** `移动读写位置`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `基准移动位置` (`文件基准位置`, 默认值: `文件基准位置.文件首`): 指定从文件中开始移动的基准位置
	* `移动距离` (`长整数`): 指定相对于起始移动位置的移动尺寸,单位字节.
* **描述:** 设置下一次读或写操作的位置,返回是否成功.
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件读写类.移到文件首

* **类型:** `方法`
* **名称:** `移到文件首`
* **返回值数据类型:** `逻辑型`
* **描述:** 设置下一次读或写操作的位置到文件首部,返回是否成功.

##### 火山.基本.文件读写类.移到文件尾

* **类型:** `方法`
* **名称:** `移到文件尾`
* **返回值数据类型:** `逻辑型`
* **描述:** 设置下一次读或写操作的位置到文件尾部,返回是否成功.
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main)

##### 火山.基本.文件读写类.读入字节集

* **类型:** `方法`
* **名称:** `读入字节集`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `欲读入数据的尺寸` (`整数`)
* **描述:** 从文件中当前读写位置读取并返回一段字节集数据,实际读入长度(即所返回字节集的尺寸)可能会小于欲读入长度. 如果读入失败,将返回一个空字节集并且自动将当前文件读写位置移到文件尾部.

##### 火山.基本.文件读写类.写出字节集

* **类型:** `方法`
* **名称:** `写出字节集`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲写出的字节集数据` (`字节集类`)
* **描述:** 写出一个字节集数据到文件中当前读写位置处,返回是否成功.
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.文件读写类.读入文本

* **类型:** `方法`
* **名称:** `读入文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `欲读入的最多字符数` (`整数`, 默认值: `-1`): 指定欲读入文本数据的最多字符数目. 注意:如果是UTF-16编码,一个字符将占用两个字节. 如果为-1,则读入文件中当前读写位置后的所有文本.
	* `文本编码` (`文本编码类型`, 默认值: `文本编码类型.UTF16`): 提供欲读入文本数据的字符集编码格式
* **描述:** 从文件中当前读写位置读取并返回一段文本数据,实际读入长度(即返回文本的尺寸)可能会小于欲读入长度.如果该数据中存在字符值0或26(文本结束标志),将仅返回该字符之前的数据(后续读写将跳过该字符).如果读入失败,将返回一个空文本(注意正常情况下也可能返回空文本)并且自动将当前文件读写位置移到文件尾部.

##### 火山.基本.文件读写类.写出文本

* **类型:** `方法`
* **名称:** `写出文本`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲写出的文本` (`文本型`)
	* `是否写出结束零` (`逻辑型`, 默认值: `假`): 指定是否在所写出文本后添加写出一个'\0'字符
	* `文本编码` (`文本编码类型`, 默认值: `文本编码类型.UTF16`): 提供写出前欲将文本转换到的字符集编码格式
* **描述:** 写出一段文本数据到文件中当前读写位置处,返回是否成功.

##### 火山.基本.文件读写类.读入一行

* **类型:** `方法`
* **名称:** `读入一行`
* **返回值数据类型:** `文本型`
* **参数:**
	* `文本编码` (`文本编码类型`, 默认值: `文本编码类型.UTF16`): 提供欲读入文本数据的字符集编码格式
* **描述:** 从文件中当前读写位置读取并返回一行文本数据,行末的回车及换行符将被抛弃. 如果读入失败,将返回一个空文本(注意正常情况下也可能返回空文本)并且自动将当前文件读写位置移到文件尾部.

##### 火山.基本.文件读写类.写文本行

* **类型:** `方法`
* **名称:** `写文本行`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲写出的文本` (`文本型`)
	* `文本编码` (`文本编码类型`, 默认值: `文本编码类型.UTF16`): 提供写出前欲将文本转换到的字符集编码格式
* **描述:** 写出一段文本数据并附加"\r\n"回车换行文本到文件中当前读写位置处,返回是否成功.

##### 火山.基本.文件读写类.读入数据

* **类型:** `方法`
* **名称:** `读入数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所读入数据的存储变量` (`通用非文本基本型(需求:可写入变量)`): 所读入数据将存放到此变量中,所读入数据的尺寸将由此变量的存储空间尺寸决定.
* **描述:** 从文件中当前读写位置读取并返回指定类型的数据,如果读入成功,返回真,否则将返回假并且自动将当前文件读写位置移到文件尾部.

##### 火山.基本.文件读写类.写出数据

* **类型:** `方法`
* **名称:** `写出数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲写出的数据` (`通用非文本基本型`): 如欲明确指定其数据类型,可以使用强制类型转换操作符.
* **描述:** 将所指定数据写出到文件中当前读写位置,返回是否成功.

##### 火山.基本.文件读写类.读入数组数据

* **类型:** `方法`
* **名称:** `读入数组数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所读入数据的存储变量` (`通用非文本基本型数组(需求:可写入变量)`): 所读入数据将存放到此数组变量中,所读入数据的尺寸将由此变量的存储空间尺寸决定.
* **描述:** 从文件中当前读写位置读取并返回指定类型的数组数据,如果读入成功,返回真,否则将返回假并且自动将当前文件读写位置移到文件尾部.

##### 火山.基本.文件读写类.写出数组数据

* **类型:** `方法`
* **名称:** `写出数组数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲写出的数组` (`通用非文本基本型数组`): 所写出数据的尺寸将由此数组变量的存储空间尺寸决定
* **描述:** 将所指定数组数据写出到文件中当前读写位置,返回是否成功.

##### 火山.基本.文件读写类.是否在文件尾

* **类型:** `方法`
* **名称:** `是否在文件尾`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `是否为判断文本已读完` (`逻辑型`, 默认值: `假`): 如果本参数值为真而且下一即将读入的字符值为'\0'或26(文本结束标志)或者当前读写位置已处于文件数据的尾部,方法将返回真.
	* `文本编码` (`文本编码类型`, 默认值: `文本编码类型.UTF16`): 提供欲检查文本数据的字符集编码格式,仅当"是否为判断文本已读完"参数值为真时有效.
* **描述:** 返回当前读写位置是否已经处于文件数据的尾部

##### 火山.基本.文件读写类.取读写位置

* **类型:** `方法`
* **名称:** `取读写位置`
* **返回值数据类型:** `长整数`
* **描述:** 返回当前被打开文件的当前读/写位置,位置值从0开始. 如果当前尚未打开文件或失败,将返回-1.

##### 火山.基本.文件读写类.取文件长度

* **类型:** `方法`
* **名称:** `取文件长度`
* **返回值数据类型:** `长整数`
* **描述:** 返回当前被打开文件的长度,单位为字节. 如果当前尚未打开文件或失败,将返回-1.
* **相关例程:** [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main)

##### 火山.基本.文件读写类.置文件尾

* **类型:** `方法`
* **名称:** `置文件尾`
* **返回值数据类型:** `逻辑型`
* **描述:** 针对一个打开的文件,将当前文件读写位置设为文件末尾.

---

#### 火山.基本.驱动通信类

* **类型:** `类`
* **名称:** `驱动通信类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `驱动通信`

##### 火山.基本.驱动通信类.驱动通信

* **类型:** `全局方法`
* **名称:** `驱动通信`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `控制码` (`整数`): 控制码必须大于等于0x800,小于0x800为系统保留使用, 默认METHOD_BUFFERED缓冲区方式通信,必须与驱动里创建设备时设置的通信方式一致,通信方式不同则传入的缓冲区在驱动里的地址保存不同
	* `输入数据` (`字节集类`): 提供输入数据
	* `输出缓冲区` (`变整数`): 输出数据的缓冲区地址指针,确保内存地址有效,如果驱动未验证确保地址有效性,则会蓝屏.
	* `输出缓冲区尺寸` (`整数`): 提供输出缓冲区的尺寸
	* `符号名` (`文本型`): 驱动里通过IoCreateSymbolicLink创建的符号名格式为 L"\\??\\符号名" , 应用层调用格式为 "\\\\.\\符号名"  符号名必须与驱动里创建的一致
* **特性:**
	* `静态`
* **描述:** 与所指定驱动进行通信,返回是否成功.

##### 火山.基本.驱动通信类.加载驱动

* **类型:** `全局方法`
* **名称:** `加载驱动`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `驱动文件路径` (`文本型`)
	* `服务名` (`文本型`): 用于服务数据库标记和创建服务,如果系统已经存在则会直接打开服务.
* **特性:**
	* `静态`
* **描述:** 加载所指定的驱动,返回是否成功.

##### 火山.基本.驱动通信类.卸载驱动

* **类型:** `全局方法`
* **名称:** `卸载驱动`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `服务名` (`文本型`): 必须与调用"加载驱动"方法时所传入的服务名一致
* **特性:**
	* `静态`
* **描述:** 卸载所指定的驱动,返回是否成功.

---

#### 火山.基本.GUID类

* **类型:** `类`
* **名称:** `GUID类`
* **文档分类:** `常用功能`
* **描述:** 用作生成及管理GUID(全局唯一标识符). 提示: 对比两个本类对象中的GUID是否相等,使用"对象内容是否相同"方法进行比较即可.

##### 火山.基本.GUID类.创建

* **类型:** `方法`
* **名称:** `创建`
* **返回值数据类型:** `逻辑型`
* **描述:** 创建一个GUID(全局唯一标识符)并填入本对象,返回是否成功.

##### 火山.基本.GUID类.从文本创建

* **类型:** `方法`
* **名称:** `从文本创建`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `GUID文本` (`文本型`): 提供所欲转换的文本格式的GUID,格式类似: "{bdfff072-497b-407b-a8f2-450d6e7b6827}"
* **描述:** 从所指定的GUID文本创建对应的GUID并填入本对象中,返回是否成功.

##### 火山.基本.GUID类.从字节集创建

* **类型:** `方法`
* **名称:** `从字节集创建`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `GUID字节集` (`字节集类`): 提供所欲转换的字节集格式的GUID,该字节集应由本类的"取字节集"方法返回.
* **描述:** 从所指定的GUID字节集创建对应的GUID并填入本对象中,返回是否成功.

##### 火山.基本.GUID类.取文本

* **类型:** `方法`
* **名称:** `取文本`
* **返回值数据类型:** `文本型`
* **描述:** 返回本对象中所保存GUID对应的文本,所返回文本格式类似: "{bdfff072-497b-407b-a8f2-450d6e7b6827}"

##### 火山.基本.GUID类.取字节集

* **类型:** `方法`
* **名称:** `取字节集`
* **返回值数据类型:** `字节集类`
* **描述:** 返回本对象中所保存GUID对应的字节集数据

---

#### 火山.基本.通用哈希表模板类

* **类型:** `类`
* **名称:** `通用哈希表模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 哈希表处理类. 模板类型1: 关键字数据类型 模板类型2: 值数据类型

##### 火山.基本.通用哈希表模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应值` (`模板类型2`): 提供关键字所对应的值
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则其所对应的先前值数据将被覆盖.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.通用哈希表模板类.唯一性插入

* **类型:** `方法`
* **名称:** `唯一性插入`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应值` (`模板类型2`): 提供关键字所对应的值
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则返回失败.
* **返回值描述:** 所欲插入关键字如果不存在,则成功返回真,否则返回假.

##### 火山.基本.通用哈希表模板类.取值

* **类型:** `方法`
* **名称:** `取值`
* **返回值数据类型:** `模板类型2`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 返回所指定关键字在本哈希表中所对应的值,如果该关键字不存在,将新建一个空值并将其插入哈希表中后返回.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.通用哈希表模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本哈希表中已有键值对成员的数目
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.通用哈希表模板类.是否存在

* **类型:** `方法`
* **名称:** `是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 返回所指定的关键字是否已经存在
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.通用哈希表模板类.删除

* **类型:** `方法`
* **名称:** `删除`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 删除所指定的键值对,返回是否存在所指定的关键字.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.通用哈希表模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **描述:** 清除本哈希表中的所有内容

##### 火山.基本.通用哈希表模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的哈希表` (`通用哈希表模板类`)
* **描述:** 交换两个哈希表中的数据

##### 火山.基本.通用哈希表模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本哈希表是否为空

##### 火山.基本.通用哈希表模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来正向枚举本哈希表中的每一个成员,在循环中可以调用"取枚举关键字"/"取枚举值"方法来获取当前所枚举到键值对的关键字及其对应值.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.通用哈希表模板类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来逆向枚举本哈希表中的每一个成员,在循环中可以调用"取枚举关键字"/"取枚举值"方法来获取当前所枚举到键值对的关键字及其对应值.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.通用哈希表模板类.取枚举关键字

* **类型:** `方法`
* **名称:** `取枚举关键字`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.通用哈希表模板类.枚举循环), [逆向枚举循环](#火山.基本.通用哈希表模板类.逆向枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的关键字,如果有多层本类或本类继承类的"枚举循环"/"逆向枚举循环"嵌套,本方法将返回最近层"枚举循环"/"逆向枚举循环"所枚举到键值对成员的关键字.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.通用哈希表模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型2`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.通用哈希表模板类.枚举循环), [逆向枚举循环](#火山.基本.通用哈希表模板类.逆向枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的值,如果有多层本类或本类继承类的"枚举循环"/"逆向枚举循环"嵌套,本方法将返回最近层"枚举循环"/"逆向枚举循环"所枚举到键值对成员的值.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.通用哈希表模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.整数到整数哈希表

* **类型:** `类`
* **名称:** `整数到整数哈希表`
* **模板基础类:** `通用哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`; `模板类型2` -> `整数`
* **文档分类:** `数据处理.哈希表`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.整数到文本哈希表

* **类型:** `类`
* **名称:** `整数到文本哈希表`
* **模板基础类:** `通用哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`; `模板类型2` -> `文本型`
* **文档分类:** `数据处理.哈希表`
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.文本到文本哈希表

* **类型:** `类`
* **名称:** `文本到文本哈希表`
* **模板基础类:** `通用哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`; `模板类型2` -> `文本型`
* **文档分类:** `数据处理.哈希表`
* **相关例程:** [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

---

#### 火山.基本.文本到整数哈希表

* **类型:** `类`
* **名称:** `文本到整数哈希表`
* **模板基础类:** `通用哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`; `模板类型2` -> `整数`
* **文档分类:** `数据处理.哈希表`

---

#### 火山.基本.对象哈希表模板类

* **类型:** `类`
* **名称:** `对象哈希表模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 值数据类型为对象类的哈希表处理类. 模板类型1: 关键字数据类型

##### 火山.基本.对象哈希表模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应对象` (`对象类`): 提供关键字所对应的火山类对象,类库将会创建一个新的同实际数据类型对象然后将其内容复制进去后插入哈希表.
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则其所对应的先前值数据将被覆盖.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象哈希表模板类.唯一性插入

* **类型:** `方法`
* **名称:** `唯一性插入`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应对象` (`对象类`): 提供关键字所对应的火山类对象,类库将会创建一个新的同实际数据类型对象然后将其内容复制进去后插入哈希表.
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则返回失败.
* **返回值描述:** 所欲插入关键字如果不存在,则成功返回真,否则返回假.

##### 火山.基本.对象哈希表模板类.插入新对象

* **类型:** `方法`
* **名称:** `插入新对象`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应对象类` (`对象类(需求:数据类型)`): 提供关键字所对应对象的火山类数据类型,类库将会创建一个新的该数据类型对象然后将其插入哈希表.
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则其所对应的先前值数据将被覆盖.

##### 火山.基本.对象哈希表模板类.唯一性插入新对象

* **类型:** `方法`
* **名称:** `唯一性插入新对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应对象类` (`对象类(需求:数据类型)`): 提供关键字所对应对象的火山类数据类型,类库将会创建一个新的该数据类型对象然后将其插入哈希表.
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则返回失败.
* **返回值描述:** 所欲插入关键字如果不存在,则成功返回真,否则返回假.

##### 火山.基本.对象哈希表模板类.取值

* **类型:** `方法`
* **名称:** `取值`
* **返回值数据类型:** `对象类`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 返回所指定关键字在本哈希表中所对应类对象的参考,如果该关键字不存在,将新建一个数据类型为"对象类"的空对象(其"是否为空对象"方法返回真)并将其插入哈希表中后返回. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 ((对象实际数据类型)哈希表1.取值 (关键字)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的哈希表中保存的对象.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象哈希表模板类.取指定类型对象

* **类型:** `方法`
* **名称:** `取指定类型对象`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取对象的数据类型,如果在哈希表中不存在所指定的关键字或其对应的火山对象实例不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **描述:** 返回所指定关键字在本哈希表中所对应类对象的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (哈希表1.取指定类型对象 (关键字, 对象实际数据类型)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.对象哈希表模板类.匹配指定类

* **类型:** `方法`
* **名称:** `匹配指定类`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `所检查的类型` (`对象类(需求:数据类型)`): 提供所欲检查是否匹配的类数据类型
* **描述:** 返回所指定关键字在本哈希表中是否存在及所对应类对象的 实际数据类型是否匹配所指定的类(为其或其继承类).

##### 火山.基本.对象哈希表模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本哈希表中已有键值对成员的数目
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.对象哈希表模板类.是否存在

* **类型:** `方法`
* **名称:** `是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 返回所指定的关键字是否已经存在

##### 火山.基本.对象哈希表模板类.删除

* **类型:** `方法`
* **名称:** `删除`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 删除所指定的键值对,返回是否存在所指定的关键字.

##### 火山.基本.对象哈希表模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **描述:** 清除本哈希表中的所有内容

##### 火山.基本.对象哈希表模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的哈希表` (`对象哈希表模板类`)
* **描述:** 交换两个哈希表中的数据

##### 火山.基本.对象哈希表模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本哈希表是否为空

##### 火山.基本.对象哈希表模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来正向枚举本哈希表中的每一个成员,在循环中可以调用"取枚举关键字"/"取枚举值"方法来获取当前所枚举到键值对的关键字及其对应值.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.对象哈希表模板类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来逆向枚举本哈希表中的每一个成员,在循环中可以调用"取枚举关键字"/"取枚举值"方法来获取当前所枚举到键值对的关键字及其对应值.

##### 火山.基本.对象哈希表模板类.取枚举关键字

* **类型:** `方法`
* **名称:** `取枚举关键字`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象哈希表模板类.枚举循环), [逆向枚举循环](#火山.基本.对象哈希表模板类.逆向枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的关键字,如果有多层本类或本类继承类的"枚举循环"/"逆向枚举循环"嵌套,本方法将返回最近层"枚举循环"/"逆向枚举循环"所枚举到键值对成员的关键字.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.对象哈希表模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `对象类`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象哈希表模板类.枚举循环), [逆向枚举循环](#火山.基本.对象哈希表模板类.逆向枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的值,如果有多层本类或本类继承类的"枚举循环"/"逆向枚举循环"嵌套,本方法将返回最近层"枚举循环"/"逆向枚举循环"所枚举到键值对成员的值.

##### 火山.基本.对象哈希表模板类.取指定类型枚举值

* **类型:** `方法`
* **名称:** `取指定类型枚举值`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取对象的数据类型,如果当前所枚举到的对象成员不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象哈希表模板类.枚举循环), [逆向枚举循环](#火山.基本.对象哈希表模板类.逆向枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的值,如果有多层本类或本类继承类的"枚举循环"/"逆向枚举循环"嵌套,本方法将返回最近层"枚举循环"/"逆向枚举循环"所枚举到键值对成员的值.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.对象哈希表模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.整数到对象哈希表

* **类型:** `类`
* **名称:** `整数到对象哈希表`
* **模板基础类:** `对象哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`
* **文档分类:** `数据处理.哈希表`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.文本到对象哈希表

* **类型:** `类`
* **名称:** `文本到对象哈希表`
* **模板基础类:** `对象哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`
* **文档分类:** `数据处理.哈希表`
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

---

#### 火山.基本.哈希集模板类

* **类型:** `类`
* **名称:** `哈希集模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `未公开`(无法在所处包外部使用,其中的内容只能通过此类的继承类对外提供)
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 哈希集处理类. 模板类型1: 关键字数据类型

##### 火山.基本.哈希集模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲插入的值` (`模板类型1`)
* **描述:** 插入一个值进哈希集中
* **返回值描述:** 如果所指定值已经存在返回假,否则返回真.
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.哈希集模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本哈希集中已有成员的数目

##### 火山.基本.哈希集模板类.是否存在

* **类型:** `方法`
* **名称:** `是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的值` (`模板类型1`)
* **描述:** 返回所指定的值是否已经存在
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

##### 火山.基本.哈希集模板类.删除

* **类型:** `方法`
* **名称:** `删除`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲删除的值` (`模板类型1`)
* **描述:** 删除所指定的值,返回其是否存在.

##### 火山.基本.哈希集模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **描述:** 清除本哈希集中的所有内容

##### 火山.基本.哈希集模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的哈希集` (`哈希集模板类`)
* **描述:** 交换两个哈希集中的数据

##### 火山.基本.哈希集模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本哈希集是否为空

##### 火山.基本.哈希集模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来正向枚举本哈希集中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值.

##### 火山.基本.哈希集模板类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来逆向枚举本哈希集中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值.

##### 火山.基本.哈希集模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.哈希集模板类.枚举循环), [逆向枚举循环](#火山.基本.哈希集模板类.逆向枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前所枚举到的成员值,如果有多层本类或本类继承类的"枚举循环"/"逆向枚举循环"嵌套,本方法将返回最近层"枚举循环"/"逆向枚举循环"所枚举到的成员值.

##### 火山.基本.哈希集模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.整数哈希集

* **类型:** `类`
* **名称:** `整数哈希集`
* **模板基础类:** `哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.文本哈希集

* **类型:** `类`
* **名称:** `文本哈希集`
* **模板基础类:** `哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`
* **文档分类:** `数据处理.哈希集`
* **相关例程:** [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main)

---

#### 火山.基本.通用队列模板类

* **类型:** `类`
* **名称:** `通用队列模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 通用队列类,用作基本类型填充. 模板类型1: 成员数据类型

##### 火山.基本.通用队列模板类.压入

* **类型:** `方法`
* **名称:** `压入`
* **参数:**
	* `值` (`模板类型1`): 提供所欲添加的成员.
* **描述:** 在当前队列的尾部添加指定成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.通用队列模板类.弹出

* **类型:** `方法`
* **名称:** `弹出`
* **描述:** 删除队列中第一个成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.通用队列模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 判断本队列是否为空队列.

##### 火山.基本.通用队列模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本队列中已有成员的数目.

##### 火山.基本.通用队列模板类.取首成员

* **类型:** `方法`
* **名称:** `取首成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 取出队列中的第一个成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.通用队列模板类.取尾成员

* **类型:** `方法`
* **名称:** `取尾成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 取出队列中最末尾的一个成员.

##### 火山.基本.通用队列模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的队列` (`通用队列模板类`)
* **描述:** 交换两个队列中的数据.

##### 火山.基本.通用队列模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.字节集队列类

* **类型:** `类`
* **名称:** `字节集队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节集类`
* **文档分类:** `数据处理.队列`

---

#### 火山.基本.文本队列类

* **类型:** `类`
* **名称:** `文本队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`
* **文档分类:** `数据处理.队列`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.字节队列类

* **类型:** `类`
* **名称:** `字节队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节`
* **文档分类:** `数据处理.队列`

---

#### 火山.基本.短整数队列类

* **类型:** `类`
* **名称:** `短整数队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `短整数`
* **文档分类:** `数据处理.队列`

---

#### 火山.基本.字符队列类

* **类型:** `类`
* **名称:** `字符队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字符`
* **文档分类:** `数据处理.队列`

---

#### 火山.基本.整数队列类

* **类型:** `类`
* **名称:** `整数队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`
* **文档分类:** `数据处理.队列`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.变整数队列类

* **类型:** `类`
* **名称:** `变整数队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `变整数`
* **文档分类:** `数据处理.队列`

---

#### 火山.基本.长整数队列类

* **类型:** `类`
* **名称:** `长整数队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `长整数`
* **文档分类:** `数据处理.队列`

---

#### 火山.基本.单精度小数队列类

* **类型:** `类`
* **名称:** `单精度小数队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `单精度小数`
* **文档分类:** `数据处理.队列`

---

#### 火山.基本.小数队列类

* **类型:** `类`
* **名称:** `小数队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `小数`
* **文档分类:** `数据处理.队列`

---

#### 火山.基本.逻辑型队列类

* **类型:** `类`
* **名称:** `逻辑型队列类`
* **模板基础类:** `通用队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `逻辑型`
* **文档分类:** `数据处理.队列`

---

#### 火山.基本.对象队列模板类

* **类型:** `类`
* **名称:** `对象队列模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 对象队列类,用作对象类型填充. 模板类型1: 成员数据类型

##### 火山.基本.对象队列模板类.压入

* **类型:** `方法`
* **名称:** `压入`
* **参数:**
	* `值` (`模板类型1`): 提供所欲添加的成员.
* **描述:** 在当前队列的尾部添加指定成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象队列模板类.压入指定类型对象

* **类型:** `方法`
* **名称:** `压入指定类型对象`
* **参数:**
	* `对应对象类` (`对象类(需求:数据类型)`): 提供指定的火山类数据类型,类库将会创建一个新的该数据类型对象然后将其压入本队列的尾部.
* **描述:** 在当前队列的尾部添加一个指定类型的对象元素.

##### 火山.基本.对象队列模板类.弹出

* **类型:** `方法`
* **名称:** `弹出`
* **描述:** 删除队列中第一个成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象队列模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 判断本队列是否为空队列.

##### 火山.基本.对象队列模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本队列中已有成员的数目.

##### 火山.基本.对象队列模板类.取首成员

* **类型:** `方法`
* **名称:** `取首成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 返回本队列中处于队列第一个成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取首成员 ()) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象队列模板类.取指定类型首成员

* **类型:** `方法`
* **名称:** `取指定类型首成员`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取成员对象的数据类型,如果在本队列中火山对象实例不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **描述:** 返回本队列中处于队列第一个成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取首成员 ()) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.

##### 火山.基本.对象队列模板类.取尾成员

* **类型:** `方法`
* **名称:** `取尾成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 返回本队列中处于队列最后一个成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取尾成员 ()) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.

##### 火山.基本.对象队列模板类.取指定类型尾成员

* **类型:** `方法`
* **名称:** `取指定类型尾成员`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取成员对象的数据类型,如果在本队列中火山对象实例不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **描述:** 返回本队列中处于队列最后一个成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取尾成员 ()) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.

##### 火山.基本.对象队列模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的队列` (`对象队列模板类`)
* **描述:** 交换两个队列中的数据.

##### 火山.基本.对象队列模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.对象队列类

* **类型:** `类`
* **名称:** `对象队列类`
* **模板基础类:** `对象队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `对象类`
* **文档分类:** `数据处理.队列`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.通用双端队列模板类

* **类型:** `类`
* **名称:** `通用双端队列模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 通用双端队列类,用作基本类型填充. 模板类型1: 成员数据类型

##### 火山.基本.通用双端队列模板类.压入到首部

* **类型:** `方法`
* **名称:** `压入到首部`
* **参数:**
	* `值` (`模板类型1`): 提供所欲添加的值.
* **描述:** 在本队列的首部添加指定成员.

##### 火山.基本.通用双端队列模板类.压入到尾部

* **类型:** `方法`
* **名称:** `压入到尾部`
* **参数:**
	* `值` (`模板类型1`): 提供所欲添加的值.
* **描述:** 在本队列的尾部添加指定成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.通用双端队列模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **返回值数据类型:** `整数`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于本队列的成员数目.
	* `所欲插入的成员` (`模板类型1`): 提供所欲插入的成员值.
	* `所欲插入的个数` (`整数`, 默认值: `1`): 本次所欲插入该成员的个数.
* **描述:** 插入指定成员到本队列中指定索引位置.
* **返回值描述:** 返回所插入成员在本队列中的索引位置(如插入个数大于1则返回首个插入成员的位置).

##### 火山.基本.通用双端队列模板类.删除

* **类型:** `方法`
* **名称:** `删除`
* **参数:**
	* `删除索引位置` (`整数`): 提供所欲删除的成员索引位置,必须大于等于0且小于等于本队列的成员数目.
* **描述:** 删除本队列中指定索引位置处的成员.

##### 火山.基本.通用双端队列模板类.弹出首部

* **类型:** `方法`
* **名称:** `弹出首部`
* **描述:** 删除本队列中第一个成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.通用双端队列模板类.弹出尾部

* **类型:** `方法`
* **名称:** `弹出尾部`
* **描述:** 删除本队列中最后一个成员.

##### 火山.基本.通用双端队列模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 判断本队列是否为空队列.

##### 火山.基本.通用双端队列模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本队列中已有成员的数目.

##### 火山.基本.通用双端队列模板类.取首成员

* **类型:** `方法`
* **名称:** `取首成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 取出本队列中的第一个成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.通用双端队列模板类.取尾成员

* **类型:** `方法`
* **名称:** `取尾成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 取出本队列中最末尾的一个成员.

##### 火山.基本.通用双端队列模板类.取成员

* **类型:** `方法`
* **名称:** `取成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `索引位置` (`整数`): 提供所欲获取成员在本队列中所处的索引位置.
* **描述:** 取出本队列中的指定索引位置处的成员.

##### 火山.基本.通用双端队列模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的队列` (`通用双端队列模板类`)
* **描述:** 交换两个队列中的数据.

##### 火山.基本.通用双端队列模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来正向枚举本队列中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值.

##### 火山.基本.通用双端队列模板类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来逆向枚举本队列中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值.

##### 火山.基本.通用双端队列模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.通用双端队列模板类.枚举循环), [逆向枚举循环](#火山.基本.通用双端队列模板类.逆向枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前所枚举到的成员值,如果有多层本类或本类继承类的"枚举循环"/"逆向枚举循环"嵌套,本方法将返回最近层"枚举循环"/"逆向枚举循环"所枚举到的成员值.

##### 火山.基本.通用双端队列模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **描述:** 清除本队列中的所有成员内容

##### 火山.基本.通用双端队列模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.字节集双端队列类

* **类型:** `类`
* **名称:** `字节集双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节集类`
* **文档分类:** `数据处理.双端队列`

---

#### 火山.基本.文本双端队列类

* **类型:** `类`
* **名称:** `文本双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`
* **文档分类:** `数据处理.双端队列`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.字节双端队列类

* **类型:** `类`
* **名称:** `字节双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节`
* **文档分类:** `数据处理.双端队列`

---

#### 火山.基本.短整数双端队列类

* **类型:** `类`
* **名称:** `短整数双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `短整数`
* **文档分类:** `数据处理.双端队列`

---

#### 火山.基本.字符双端队列类

* **类型:** `类`
* **名称:** `字符双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字符`
* **文档分类:** `数据处理.双端队列`

---

#### 火山.基本.整数双端队列类

* **类型:** `类`
* **名称:** `整数双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`
* **文档分类:** `数据处理.双端队列`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.变整数双端队列类

* **类型:** `类`
* **名称:** `变整数双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `变整数`
* **文档分类:** `数据处理.双端队列`

---

#### 火山.基本.长整数双端队列类

* **类型:** `类`
* **名称:** `长整数双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `长整数`
* **文档分类:** `数据处理.双端队列`

---

#### 火山.基本.单精度小数双端队列类

* **类型:** `类`
* **名称:** `单精度小数双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `单精度小数`
* **文档分类:** `数据处理.双端队列`

---

#### 火山.基本.小数双端队列类

* **类型:** `类`
* **名称:** `小数双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `小数`
* **文档分类:** `数据处理.双端队列`

---

#### 火山.基本.逻辑型双端队列类

* **类型:** `类`
* **名称:** `逻辑型双端队列类`
* **模板基础类:** `通用双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `逻辑型`
* **文档分类:** `数据处理.双端队列`

---

#### 火山.基本.对象双端队列模板类

* **类型:** `类`
* **名称:** `对象双端队列模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 对象双端队列模板,用作对象类型填充. 模板类型1: 成员数据类型

##### 火山.基本.对象双端队列模板类.压入到首部

* **类型:** `方法`
* **名称:** `压入到首部`
* **参数:**
	* `值` (`模板类型1`): 提供所欲添加的值.
* **描述:** 在本队列的首部添加指定元素.

##### 火山.基本.对象双端队列模板类.压入到尾部

* **类型:** `方法`
* **名称:** `压入到尾部`
* **参数:**
	* `值` (`模板类型1`): 提供所欲添加的值.
* **描述:** 在本队列的尾部添加指定元素.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象双端队列模板类.压入指定类型对象到首部

* **类型:** `方法`
* **名称:** `压入指定类型对象到首部`
* **参数:**
	* `对应对象类` (`对象类(需求:数据类型)`): 提供指定的火山类数据类型,类库将会创建一个新的该数据类型对象然后将其压入本队列的首部.
* **描述:** 在当前队列的首部添加一个指定类型的对象元素.

##### 火山.基本.对象双端队列模板类.压入指定类型对象到尾部

* **类型:** `方法`
* **名称:** `压入指定类型对象到尾部`
* **参数:**
	* `对应对象类` (`对象类(需求:数据类型)`): 提供指定的火山类数据类型,类库将会创建一个新的该数据类型对象然后将其压入本队列的尾部.
* **描述:** 在当前队列的尾部添加一个指定类型的对象元素.

##### 火山.基本.对象双端队列模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **返回值数据类型:** `整数`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于本队列的成员数目.
	* `所欲插入的成员` (`模板类型1`): 提供所欲插入的成员值.
	* `所欲插入的个数` (`整数`, 默认值: `1`): 本次所欲插入该成员的个数.
* **描述:** 插入指定成员到本队列中指定索引位置.
* **返回值描述:** 返回所插入成员在本队列中的索引位置(如插入个数大于1则返回首个插入成员的位置).

##### 火山.基本.对象双端队列模板类.插入指定类型对象

* **类型:** `方法`
* **名称:** `插入指定类型对象`
* **返回值数据类型:** `整数`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于本队列的成员数目.
	* `对应对象类` (`对象类(需求:数据类型)`): 提供指定的火山类数据类型,类库将会创建一个新的该数据类型对象然后将其插入到指定索引位置处.
	* `所欲插入的个数` (`整数`, 默认值: `1`): 本次所欲插入该成员的个数.
* **描述:** 插入一个指定类型的对象到本队列中指定索引位置.
* **返回值描述:** 返回所插入成员在本队列中的索引位置(如插入个数大于1则返回首个插入成员的位置).

##### 火山.基本.对象双端队列模板类.删除

* **类型:** `方法`
* **名称:** `删除`
* **参数:**
	* `删除索引位置` (`整数`): 提供所欲删除的成员索引位置,必须大于等于0且小于等于本队列的成员数目.
* **描述:** 删除本队列中指定索引位置处的成员.

##### 火山.基本.对象双端队列模板类.弹出首部

* **类型:** `方法`
* **名称:** `弹出首部`
* **描述:** 删除本队列中第一个元素.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象双端队列模板类.弹出尾部

* **类型:** `方法`
* **名称:** `弹出尾部`
* **描述:** 删除本队列中最后一个元素.

##### 火山.基本.对象双端队列模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 判断本队列是否为空队列.

##### 火山.基本.对象双端队列模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本队列中已有成员的数目.

##### 火山.基本.对象双端队列模板类.取首成员

* **类型:** `方法`
* **名称:** `取首成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 返回本队列中处于队列第一个成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取首成员 ()) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象双端队列模板类.取指定类型首成员

* **类型:** `方法`
* **名称:** `取指定类型首成员`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取成员对象的数据类型,如果在本队列中火山对象实例不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **描述:** 返回本队列中处于队列第一个成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取指定类型首成员 (类型)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.

##### 火山.基本.对象双端队列模板类.取尾成员

* **类型:** `方法`
* **名称:** `取尾成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 返回本队列中处于队列最后一个成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取尾成员 ()) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.

##### 火山.基本.对象双端队列模板类.取指定类型尾成员

* **类型:** `方法`
* **名称:** `取指定类型尾成员`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取成员对象的数据类型,如果在本队列中火山对象实例不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **描述:** 返回本队列中处于队列最后一个成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取指定类型尾成员 (类型)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.

##### 火山.基本.对象双端队列模板类.取成员

* **类型:** `方法`
* **名称:** `取成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `索引位置` (`整数`): 提供所欲获取成员在本队列中所处的索引位置.
* **描述:** 返回本队列中处于队列指定索引位置处成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取成员 (索引)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.

##### 火山.基本.对象双端队列模板类.取指定类型成员

* **类型:** `方法`
* **名称:** `取指定类型成员`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `索引位置` (`整数`): 提供所欲获取成员在本队列中所处的索引位置.
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取成员对象的数据类型,如果在本队列中火山对象实例不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **描述:** 返回本队列中处于队列指定索引位置处成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取成员 (索引)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.

##### 火山.基本.对象双端队列模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的队列` (`对象双端队列模板类`)
* **描述:** 交换两个队列中的数据.

##### 火山.基本.对象双端队列模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来正向枚举本队列中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值.

##### 火山.基本.对象双端队列模板类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来逆向枚举本队列中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值.

##### 火山.基本.对象双端队列模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象双端队列模板类.枚举循环), [逆向枚举循环](#火山.基本.对象双端队列模板类.逆向枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前所枚举到的成员值,如果有多层本类或本类继承类的"枚举循环"/"逆向枚举循环"嵌套,本方法将返回最近层"枚举循环"/"逆向枚举循环"所枚举到的成员值.

##### 火山.基本.对象双端队列模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **描述:** 清除本队列中的所有内容

##### 火山.基本.对象双端队列模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.对象双端队列类

* **类型:** `类`
* **名称:** `对象双端队列类`
* **模板基础类:** `对象双端队列模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `对象类`
* **文档分类:** `数据处理.双端队列`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.通用栈模板类

* **类型:** `类`
* **名称:** `通用栈模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 通用栈类,用作基本类型填充. 模板类型1: 成员数据类型

##### 火山.基本.通用栈模板类.压入

* **类型:** `方法`
* **名称:** `压入`
* **参数:**
	* `值` (`模板类型1`): 提供所欲添加的成员.
* **描述:** 在当前栈顶添加指定成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.通用栈模板类.弹出

* **类型:** `方法`
* **名称:** `弹出`
* **描述:** 删除栈顶成员.

##### 火山.基本.通用栈模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 判断本栈是否为空栈.

##### 火山.基本.通用栈模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本栈中已有成员的数目.

##### 火山.基本.通用栈模板类.取成员

* **类型:** `方法`
* **名称:** `取成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 取出栈顶成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.通用栈模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的栈` (`通用栈模板类`)
* **描述:** 交换两个栈中的数据.

##### 火山.基本.通用栈模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.字节集栈类

* **类型:** `类`
* **名称:** `字节集栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节集类`
* **文档分类:** `数据处理.栈`

---

#### 火山.基本.文本栈类

* **类型:** `类`
* **名称:** `文本栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`
* **文档分类:** `数据处理.栈`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.字节栈类

* **类型:** `类`
* **名称:** `字节栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节`
* **文档分类:** `数据处理.栈`

---

#### 火山.基本.短整数栈类

* **类型:** `类`
* **名称:** `短整数栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `短整数`
* **文档分类:** `数据处理.栈`

---

#### 火山.基本.字符栈类

* **类型:** `类`
* **名称:** `字符栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字符`
* **文档分类:** `数据处理.栈`

---

#### 火山.基本.整数栈类

* **类型:** `类`
* **名称:** `整数栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`
* **文档分类:** `数据处理.栈`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.变整数栈类

* **类型:** `类`
* **名称:** `变整数栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `变整数`
* **文档分类:** `数据处理.栈`

---

#### 火山.基本.长整数栈类

* **类型:** `类`
* **名称:** `长整数栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `长整数`
* **文档分类:** `数据处理.栈`

---

#### 火山.基本.单精度小数栈类

* **类型:** `类`
* **名称:** `单精度小数栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `单精度小数`
* **文档分类:** `数据处理.栈`

---

#### 火山.基本.小数栈类

* **类型:** `类`
* **名称:** `小数栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `小数`
* **文档分类:** `数据处理.栈`

---

#### 火山.基本.逻辑型栈类

* **类型:** `类`
* **名称:** `逻辑型栈类`
* **模板基础类:** `通用栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `逻辑型`
* **文档分类:** `数据处理.栈`

---

#### 火山.基本.对象栈模板类

* **类型:** `类`
* **名称:** `对象栈模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 对象栈类,用作对象类型填充. 模板类型1: 成员数据类型

##### 火山.基本.对象栈模板类.压入

* **类型:** `方法`
* **名称:** `压入`
* **参数:**
	* `值` (`模板类型1`): 提供所欲添加的成员.
* **描述:** 在当前栈顶添加指定成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象栈模板类.压入指定类型对象

* **类型:** `方法`
* **名称:** `压入指定类型对象`
* **参数:**
	* `对应对象类` (`对象类(需求:数据类型)`): 提供指定的火山类数据类型,类库将会创建一个新的该数据类型对象然后将其压入本栈的顶部.
* **描述:** 在当前栈顶添加一个指定类型的对象成员.

##### 火山.基本.对象栈模板类.弹出

* **类型:** `方法`
* **名称:** `弹出`
* **描述:** 删除栈顶成员.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象栈模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 判断本栈是否为空栈.

##### 火山.基本.对象栈模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本栈中已有成员的数目.

##### 火山.基本.对象栈模板类.取成员

* **类型:** `方法`
* **名称:** `取成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 返回本栈栈顶成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (栈1.取成员 ()) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象栈模板类.取指定类型成员

* **类型:** `方法`
* **名称:** `取指定类型成员`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取成员对象的数据类型,如果在本队列中火山对象实例不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **描述:** 返回本栈栈顶成员的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (队列1.取首成员 ()) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的队列中保存的对象.

##### 火山.基本.对象栈模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的栈` (`对象栈模板类`)
* **描述:** 交换两个栈中的数据.

##### 火山.基本.对象栈模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.对象栈类

* **类型:** `类`
* **名称:** `对象栈类`
* **模板基础类:** `对象栈模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `对象类`
* **文档分类:** `数据处理.栈`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.基本无序哈希表模板类

* **类型:** `类`
* **名称:** `基本无序哈希表模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 无序哈希表处理类. 模板类型1: 关键字数据类型,仅支持非文本型的基本类型. 模板类型2: 值数据类型

##### 火山.基本.基本无序哈希表模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应值` (`模板类型2`): 提供关键字所对应的值
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则其所对应的先前值数据将被覆盖.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.基本无序哈希表模板类.唯一性插入

* **类型:** `方法`
* **名称:** `唯一性插入`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应值` (`模板类型2`): 提供关键字所对应的值
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则返回失败.
* **返回值描述:** 所欲插入关键字如果不存在,则成功返回真,否则返回假.

##### 火山.基本.基本无序哈希表模板类.取值

* **类型:** `方法`
* **名称:** `取值`
* **返回值数据类型:** `模板类型2`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 返回所指定关键字在本哈希表中所对应的值,如果该关键字不存在,将新建一个空值并将其插入哈希表中后返回.
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.基本无序哈希表模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本哈希表中已有键值对成员的数目

##### 火山.基本.基本无序哈希表模板类.是否存在

* **类型:** `方法`
* **名称:** `是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 返回所指定的关键字是否已经存在

##### 火山.基本.基本无序哈希表模板类.删除

* **类型:** `方法`
* **名称:** `删除`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 删除所指定的键值对,返回是否存在所指定的关键字.

##### 火山.基本.基本无序哈希表模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **描述:** 清除本哈希表中的所有内容

##### 火山.基本.基本无序哈希表模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的哈希表` (`基本无序哈希表模板类`)
* **描述:** 交换两个哈希表中的数据

##### 火山.基本.基本无序哈希表模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本哈希表是否为空

##### 火山.基本.基本无序哈希表模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来正向枚举本哈希表中的每一个成员,在循环中可以调用"取枚举关键字"/"取枚举值"方法来获取当前所枚举到键值对的关键字及其对应值.

##### 火山.基本.基本无序哈希表模板类.取枚举关键字

* **类型:** `方法`
* **名称:** `取枚举关键字`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.基本无序哈希表模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的关键字,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回最近层"枚举循环"所枚举到键值对成员的关键字.

##### 火山.基本.基本无序哈希表模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型2`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.基本无序哈希表模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的值,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回最近层"枚举循环"所枚举到键值对成员的值.

##### 火山.基本.基本无序哈希表模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.整数到整数无序哈希表

* **类型:** `类`
* **名称:** `整数到整数无序哈希表`
* **模板基础类:** `基本无序哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`; `模板类型2` -> `整数`
* **文档分类:** `数据处理.无序哈希表`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.整数到文本无序哈希表

* **类型:** `类`
* **名称:** `整数到文本无序哈希表`
* **模板基础类:** `基本无序哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`; `模板类型2` -> `文本型`
* **文档分类:** `数据处理.无序哈希表`
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.对象无序哈希表模板类

* **类型:** `类`
* **名称:** `对象无序哈希表模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 无序哈希表处理类. 模板类型1: 关键字数据类型,仅支持"文本型","字节集类"两种类型实现.

##### 火山.基本.对象无序哈希表模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应对象` (`对象类`): 提供关键字所对应的火山类对象,类库将会创建一个新的同实际数据类型对象然后将其内容复制进去后插入哈希表.
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则其所对应的先前值数据将被覆盖.

##### 火山.基本.对象无序哈希表模板类.唯一性插入

* **类型:** `方法`
* **名称:** `唯一性插入`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应对象` (`对象类`): 提供关键字所对应的火山类对象,类库将会创建一个新的同实际数据类型对象然后将其内容复制进去后插入哈希表.
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则返回失败.
* **返回值描述:** 所欲插入关键字如果不存在,则成功返回真,否则返回假.

##### 火山.基本.对象无序哈希表模板类.插入新对象

* **类型:** `方法`
* **名称:** `插入新对象`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应对象类` (`对象类(需求:数据类型)`): 提供关键字所对应对象的火山类数据类型,类库将会创建一个新的该数据类型对象然后将其插入哈希表.
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则其所对应的先前值数据将被覆盖.

##### 火山.基本.对象无序哈希表模板类.唯一性插入新对象

* **类型:** `方法`
* **名称:** `唯一性插入新对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `对应对象类` (`对象类(需求:数据类型)`): 提供关键字所对应对象的火山类数据类型,类库将会创建一个新的该数据类型对象然后将其插入哈希表.
* **描述:** 插入一个键值对进哈希表中,如果所指定关键字已经存在,则返回失败.
* **返回值描述:** 所欲插入关键字如果不存在,则成功返回真,否则返回假.

##### 火山.基本.对象无序哈希表模板类.取值

* **类型:** `方法`
* **名称:** `取值`
* **返回值数据类型:** `对象类`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 返回所指定关键字在本哈希表中所对应类对象的参考,如果该关键字不存在,将新建一个数据类型为"对象类"的空对象(其"是否为空对象"方法返回真)并将其插入哈希表中后返回. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 ((对象实际数据类型)哈希表1.取值 (关键字)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的哈希表中保存的对象.

##### 火山.基本.对象无序哈希表模板类.取指定类型对象

* **类型:** `方法`
* **名称:** `取指定类型对象`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取对象的数据类型,如果在哈希表中不存在所指定的关键字或其对应的火山对象实例不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **描述:** 返回所指定关键字在本哈希表中所对应类对象的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (哈希表1.取指定类型对象 (关键字, 对象实际数据类型)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.

##### 火山.基本.对象无序哈希表模板类.匹配指定类

* **类型:** `方法`
* **名称:** `匹配指定类`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `所检查的类型` (`对象类(需求:数据类型)`): 提供所欲检查是否匹配的类数据类型
* **描述:** 返回所指定关键字在本哈希表中是否存在及所对应类对象的 实际数据类型是否匹配所指定的类(为其或其继承类).

##### 火山.基本.对象无序哈希表模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本哈希表中已有键值对成员的数目

##### 火山.基本.对象无序哈希表模板类.是否存在

* **类型:** `方法`
* **名称:** `是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 返回所指定的关键字是否已经存在

##### 火山.基本.对象无序哈希表模板类.删除

* **类型:** `方法`
* **名称:** `删除`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **描述:** 删除所指定的键值对,返回是否存在所指定的关键字.

##### 火山.基本.对象无序哈希表模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **描述:** 清除本哈希表中的所有内容

##### 火山.基本.对象无序哈希表模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的哈希表` (`对象无序哈希表模板类`)
* **描述:** 交换两个哈希表中的数据

##### 火山.基本.对象无序哈希表模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本哈希表是否为空

##### 火山.基本.对象无序哈希表模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来正向枚举本哈希表中的每一个成员,在循环中可以调用"取枚举关键字"/"取枚举值"方法来获取当前所枚举到键值对的关键字及其对应值.

##### 火山.基本.对象无序哈希表模板类.取枚举关键字

* **类型:** `方法`
* **名称:** `取枚举关键字`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象无序哈希表模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的关键字,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回最近层"枚举循环"所枚举到键值对成员的关键字.

##### 火山.基本.对象无序哈希表模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `对象类`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象无序哈希表模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的值,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回最近层"枚举循环"所枚举到键值对成员的值.

##### 火山.基本.对象无序哈希表模板类.取指定类型枚举值

* **类型:** `方法`
* **名称:** `取指定类型枚举值`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取对象的数据类型,如果当前所枚举到的对象成员不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象无序哈希表模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的值,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回最近层"枚举循环"所枚举到键值对成员的值.

##### 火山.基本.对象无序哈希表模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.文本到对象无序哈希表

* **类型:** `类`
* **名称:** `文本到对象无序哈希表`
* **模板基础类:** `对象无序哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`
* **文档分类:** `数据处理.无序哈希表`

---

#### 火山.基本.字节集到对象无序哈希表

* **类型:** `类`
* **名称:** `字节集到对象无序哈希表`
* **模板基础类:** `对象无序哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节集类`
* **文档分类:** `数据处理.无序哈希表`

---

#### 火山.基本.通用无序哈希集模板类

* **类型:** `类`
* **名称:** `通用无序哈希集模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 无序哈希集处理类. 模板类型1: 关键字数据类型,仅支持非文本型基本类型实现.

##### 火山.基本.通用无序哈希集模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲插入的值` (`模板类型1`)
* **描述:** 插入一个值进哈希集中.
* **返回值描述:** 如果所指定值已经存在返回假,否则返回真.

##### 火山.基本.通用无序哈希集模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本哈希集中已有成员的数目.

##### 火山.基本.通用无序哈希集模板类.是否存在

* **类型:** `方法`
* **名称:** `是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的值` (`模板类型1`)
* **描述:** 返回所指定的值是否已经存在.

##### 火山.基本.通用无序哈希集模板类.删除

* **类型:** `方法`
* **名称:** `删除`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲删除的值` (`模板类型1`)
* **描述:** 删除所指定的值,返回其是否存在.

##### 火山.基本.通用无序哈希集模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **描述:** 清除本哈希集中的所有内容.

##### 火山.基本.通用无序哈希集模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的哈希集` (`通用无序哈希集模板类`)
* **描述:** 交换两个哈希集中的数据.

##### 火山.基本.通用无序哈希集模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本哈希集是否为空.

##### 火山.基本.通用无序哈希集模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来正向枚举本哈希集中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值.

##### 火山.基本.通用无序哈希集模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.通用无序哈希集模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前所枚举到的成员值,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回最近层"枚举循环"所枚举到的成员值.

##### 火山.基本.通用无序哈希集模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.字节无序哈希集

* **类型:** `类`
* **名称:** `字节无序哈希集`
* **模板基础类:** `通用无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.短整数无序哈希集

* **类型:** `类`
* **名称:** `短整数无序哈希集`
* **模板基础类:** `通用无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `短整数`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.字符无序哈希集

* **类型:** `类`
* **名称:** `字符无序哈希集`
* **模板基础类:** `通用无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字符`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.整数无序哈希集

* **类型:** `类`
* **名称:** `整数无序哈希集`
* **模板基础类:** `通用无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.变整数无序哈希集

* **类型:** `类`
* **名称:** `变整数无序哈希集`
* **模板基础类:** `通用无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `变整数`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.长整数无序哈希集

* **类型:** `类`
* **名称:** `长整数无序哈希集`
* **模板基础类:** `通用无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `长整数`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.单精度小数无序哈希集

* **类型:** `类`
* **名称:** `单精度小数无序哈希集`
* **模板基础类:** `通用无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `单精度小数`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.小数无序哈希集

* **类型:** `类`
* **名称:** `小数无序哈希集`
* **模板基础类:** `通用无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `小数`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.逻辑型无序哈希集

* **类型:** `类`
* **名称:** `逻辑型无序哈希集`
* **模板基础类:** `通用无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `逻辑型`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.对象无序哈希集模板类

* **类型:** `类`
* **名称:** `对象无序哈希集模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.辅助类`
* **描述:** 无序哈希集处理类. 模板类型1: 关键字数据类型,仅支持字节集类和文本型,其他对象类型不可实现

##### 火山.基本.对象无序哈希集模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲插入的值` (`模板类型1`)
* **描述:** 插入一个值进哈希集中.
* **返回值描述:** 如果所指定值已经存在返回假,否则返回真.

##### 火山.基本.对象无序哈希集模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回本哈希集中已有成员的数目.

##### 火山.基本.对象无序哈希集模板类.是否存在

* **类型:** `方法`
* **名称:** `是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的值` (`模板类型1`)
* **描述:** 返回所指定的值是否已经存在.

##### 火山.基本.对象无序哈希集模板类.删除

* **类型:** `方法`
* **名称:** `删除`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲删除的值` (`模板类型1`)
* **描述:** 删除所指定的值,返回其是否存在.

##### 火山.基本.对象无序哈希集模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **描述:** 清除本哈希集中的所有内容.

##### 火山.基本.对象无序哈希集模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `所欲交换的哈希集` (`对象无序哈希集模板类`)
* **描述:** 交换两个哈希集中的数据.

##### 火山.基本.对象无序哈希集模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本哈希集是否为空.

##### 火山.基本.对象无序哈希集模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来正向枚举本哈希集中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值.

##### 火山.基本.对象无序哈希集模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象无序哈希集模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前所枚举到的成员值,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回最近层"枚举循环"所枚举到的成员值.

##### 火山.基本.对象无序哈希集模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.文本无序哈希集

* **类型:** `类`
* **名称:** `文本无序哈希集`
* **模板基础类:** `对象无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.字节集无序哈希集

* **类型:** `类`
* **名称:** `字节集无序哈希集`
* **模板基础类:** `对象无序哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节集类`
* **文档分类:** `数据处理.哈希集`

---

#### 火山.基本.内存映射文件类

* **类型:** `类`
* **名称:** `内存映射文件类`
* **文档分类:** `内存映射文件`
* **描述:** 本类提供内存映射文件创建/读/写操作的支持
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main)

##### 火山.基本.内存映射文件类.创建映射文件

* **类型:** `方法`
* **名称:** `创建映射文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `文件名称` (`文本型`): 欲创建内存映射文件的文件全路径名称.
	* `文件创建方式` (`映射文件创建方式`, 默认值: `映射文件创建方式.创建并覆盖`): 提供'映射文件创建方式'常量,设置是打开一个已经存在的文件还是创建一个新文件.
	* `文件尺寸` (`长整数`, 默认值: `4096`): 欲创建内存映射文件的文件大小,默认4096字节(4K).如果是打开一个已经存在的文件,可以指定该值为0,表示创建的内存映射文件大小和文件本身大小是一致的.
	* `内存映射名称` (`文本型`, 默认值: `""`): 创建内存映射文件的名称,其它进程可以通过该名称打开内存映射文件.该参数可以为空,表示创建一个没有名称的内存映射文件.
* **描述:** 创建内存映射文件
* **返回值描述:** 执行成功返回真,否则返回假.
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main)

##### 火山.基本.内存映射文件类.打开映射文件

* **类型:** `方法`
* **名称:** `打开映射文件`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `内存映射名称` (`文本型`): 其他进程创建的内存映射文件名称
* **描述:** 打开一个其他进程创建的内存映射文件
* **返回值描述:** 执行成功返回真,否则返回假.
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main)

##### 火山.基本.内存映射文件类.映射到内存

* **类型:** `方法`
* **名称:** `映射到内存`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `起始位置` (`长整数`, 默认值: `0`): 映射到内存的文件起始位置.注意该值一定要是系统分配内存的分配粒度.windows的分配粒度是64k(即0x10000),所以该值一定要是64k的倍数,否则会执行出错,起始位置的值从0开始.
	* `映射尺寸` (`整数`, 默认值: `0`): 映射到内存的字节数量,该值等于0代表从起始位置开始文件其余部分全部映射到内存.
* **描述:** 将一个创建完毕或已打开的内存映射文件的全部或一部分映射到进程的内存空间中
* **返回值描述:** 执行成功返回真,否则返回假.
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main)

##### 火山.基本.内存映射文件类.解除映射

* **类型:** `方法`
* **名称:** `解除映射`
* **返回值数据类型:** `逻辑型`
* **描述:** "映射到内存"方法的反操作,将已经映射到内存的文件解除映射. 解除映射后先前所获取的数据指针不能再使用.
* **返回值描述:** 执行成功返回真,否则返回假.

##### 火山.基本.内存映射文件类.读数据

* **类型:** `方法`
* **名称:** `读数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `起始位置` (`整数`, 默认值: `0`): 从已映射内存中读出的数据的起始位置偏移,从0开始.
	* `长度` (`整数`): 从已映射内存中读出数据的长度
	* `数据` (`字节集类`): 提供字节集变量,存放从内存映射文件中读出的数据,作为方法的返回值.
* **描述:** 从已映射内存中读出数据,使用该命令时一定要注意不能超过已映射内存的边界,否则会造成非法内存访问从而异常退出. 执行本方法前必须已经成功调用"映射到内存"方法.
* **返回值描述:** 执行成功返回真,否则返回假.
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main)

##### 火山.基本.内存映射文件类.取数据指针

* **类型:** `方法`
* **名称:** `取数据指针`
* **返回值数据类型:** `变整数`
* **描述:** 取得已映射内存的首地址,用于后续对其进行内存修改和复制操作. 执行本方法前必须已经成功调用"映射到内存"方法.
* **返回值描述:** 执行成功返回数据地址指针,否则返回0.

##### 火山.基本.内存映射文件类.写数据

* **类型:** `方法`
* **名称:** `写数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `起始位置` (`整数`, 默认值: `0`): 已经映射内存中的起始写入偏移位置,从0开始.
	* `数据` (`字节集类`): 欲写入的数据. 注意数据的长度不能超过已映射内存的边界,否则会造成非法内存访问从而异常退出.
* **描述:** 向已映射内存中写入数据. 执行本方法前必须已经成功调用"映射到内存"方法.
* **返回值描述:** 执行成功返回真,否则返回假.
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main)

##### 火山.基本.内存映射文件类.保存映射文件

* **类型:** `方法`
* **名称:** `保存映射文件`
* **返回值数据类型:** `逻辑型`
* **描述:** 将已映射内存中的所有数据都真实写入到对应磁盘文件(调用"创建映射文件"方法时指定)中
* **返回值描述:** 执行成功返回真,否则返回假.

##### 火山.基本.内存映射文件类.写指针数据

* **类型:** `方法`
* **名称:** `写指针数据`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `起始位置` (`整数`, 默认值: `0`): 向已映射内存中写入数据的起始偏移位置,从0开始.
	* `数据指针` (`变整数`): 欲写入数据的指针
	* `数据尺寸` (`整数`): 欲写入的数据的尺寸. 注意不能超过已映射内存的边界,否则会造成非法内存访问从而异常退出.
* **描述:** 向已映射内存中写入数据
* **返回值描述:** 执行成功返回真,否则返回假.

##### 火山.基本.内存映射文件类.关闭映射文件

* **类型:** `方法`
* **名称:** `关闭映射文件`
* **描述:** 关闭并释放已经创建或打开的内存映射文件,关闭后先前所取得的已映射内存指针不可再使用.
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main)

---

#### 火山.基本.映射文件创建方式

* **类型:** `类`
* **名称:** `映射文件创建方式`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `内存映射文件.辅助类`
* **描述:** 提供内存映射文件创建方式常量
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main)

##### 火山.基本.映射文件创建方式.无真实文件

* **类型:** `成员常量`
* **名称:** `无真实文件`
* **数据类型:** `映射文件创建方式`
* **初始值:** `-1`
* **描述:** 不创建真实的磁盘文件,文件只映射在内存中

##### 火山.基本.映射文件创建方式.创建新文件

* **类型:** `成员常量`
* **名称:** `创建新文件`
* **数据类型:** `映射文件创建方式`
* **描述:** 创建文件

##### 火山.基本.映射文件创建方式.创建并覆盖

* **类型:** `成员常量`
* **名称:** `创建并覆盖`
* **数据类型:** `映射文件创建方式`
* **描述:** 创建新的文件并覆盖现有文件
* **相关例程:** [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main)

##### 火山.基本.映射文件创建方式.打开已存在

* **类型:** `成员常量`
* **名称:** `打开已存在`
* **数据类型:** `映射文件创建方式`
* **描述:** 打开已存在的现有文件

##### 火山.基本.映射文件创建方式.打开或创建

* **类型:** `成员常量`
* **名称:** `打开或创建`
* **数据类型:** `映射文件创建方式`
* **描述:** 打开文件如果文件不存在就创建一个新的文件

---

#### 火山.基本.宏操作类

* **类型:** `类`
* **名称:** `宏操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `宏操作`
* **描述:** 提供相关宏操作支持

##### 火山.基本.宏操作类.宏如果

* **类型:** `全局方法`
* **名称:** `宏如果`
* **参数:**
	* `欲检查的宏名` (`文本型(需求:立即数或常量)`): 提供用作检查其是否被定义的宏名称文本,必须为有效的英文名称.
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
	* 本方法调用语句后方必须为以下任一方法的调用语句: [宏否则](#火山.基本.宏操作类.宏否则), [宏默认](#火山.基本.宏操作类.宏默认), [宏结束](#火山.基本.宏操作类.宏结束)
* **描述:** 如果所指定名称的宏被定义,则本地编译器将编译本语句的子语句体内容并跳过所有后续的"宏否则"及"宏默认"判断语句,否则将会忽略此子语句体内容. 本方法后必须跟随"宏否则"/"宏默认"/"宏结束"方法的调用语句.
* **相关例程:** [vol-条件编译项目1-cond_compile1-main](#vol-条件编译项目1-cond_compile1-main)

##### 火山.基本.宏操作类.宏否则

* **类型:** `全局方法`
* **名称:** `宏否则`
* **参数:**
	* `欲检查的宏名` (`文本型(需求:立即数或常量)`): 提供用作检查其是否被定义的宏名称文本,必须为有效的英文名称.
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
	* 本方法调用语句前方必须为以下任一方法的调用语句: [宏如果](#火山.基本.宏操作类.宏如果), [宏否则](#火山.基本.宏操作类.宏否则)
	* 本方法调用语句后方必须为以下任一方法的调用语句: [宏否则](#火山.基本.宏操作类.宏否则), [宏默认](#火山.基本.宏操作类.宏默认), [宏结束](#火山.基本.宏操作类.宏结束)
* **描述:** 如果所指定名称的宏被定义,则本地编译器将编译本语句的子语句体内容并跳过所有后续的"宏否则"及"宏默认"判断语句,否则将会忽略此子语句体内容. 本方法只能位于"宏如果"或"宏否则"方法的调用语句后方,后面必须跟随"宏否则"/"宏默认"/"宏结束"方法的调用语句.
* **相关例程:** [vol-条件编译项目1-cond_compile1-main](#vol-条件编译项目1-cond_compile1-main)

##### 火山.基本.宏操作类.宏默认

* **类型:** `全局方法`
* **名称:** `宏默认`
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体
	* 本方法调用语句前方必须为以下任一方法的调用语句: [宏如果](#火山.基本.宏操作类.宏如果), [宏否则](#火山.基本.宏操作类.宏否则)
	* 本方法调用语句后方必须为以下任一方法的调用语句: [宏结束](#火山.基本.宏操作类.宏结束)
* **描述:** 如果前方所有宏判断语句("宏如果"及"宏否则")中的宏均未被定义,则本地编译器将编译本语句的子语句体内容,否则将会忽略此子语句体内容. 本方法只能位于"宏如果"或"宏否则"方法的调用语句后方,后面必须跟随"宏结束"方法的调用语句.
* **相关例程:** [vol-条件编译项目1-cond_compile1-main](#vol-条件编译项目1-cond_compile1-main)

##### 火山.基本.宏操作类.宏结束

* **类型:** `全局方法`
* **名称:** `宏结束`
* **特性:**
	* `静态`
	* 本方法调用语句前方必须为以下任一方法的调用语句: [宏如果](#火山.基本.宏操作类.宏如果), [宏否则](#火山.基本.宏操作类.宏否则), [宏默认](#火山.基本.宏操作类.宏默认)
* **描述:** 用作标志以"宏如果"方法调用语句开始的整个宏判断结束. 本方法只能位于"宏如果"/"宏否则"/"宏默认"方法的调用语句后方.
* **相关例程:** [vol-条件编译项目1-cond_compile1-main](#vol-条件编译项目1-cond_compile1-main)

---

#### 火山.基本.打印机操作类

* **类型:** `类`
* **名称:** `打印机操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `打印机操作`
* **描述:** 提供打印机操作相关功能

##### 火山.基本.打印机操作类.取默认打印机

* **类型:** `全局方法`
* **名称:** `取默认打印机`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回当前默认打印机的名称

##### 火山.基本.打印机操作类.置默认打印机

* **类型:** `全局方法`
* **名称:** `置默认打印机`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲设置打印机名称` (`文本型`): 提供打印机的名称,如果是远程打印机,请按照"\\远程主机名称\\打印机名称"格式提供.
* **特性:**
	* `静态`
* **描述:** 设置当前默认打印机
* **返回值描述:** 成功返回真,失败返回假.

##### 火山.基本.打印机操作类.取打印机状态

* **类型:** `全局方法`
* **名称:** `取打印机状态`
* **返回值数据类型:** `打印机状态码`
* **参数:**
	* `打印机名称` (`文本型`, 默认值: `""`): 提供所欲获取打印机的名称,为空文本表示为默认打印机.
* **特性:**
	* `静态`
* **描述:** 获取所指定名称打印机的当前状态
* **返回值描述:** 返回对应打印机状态码

##### 火山.基本.打印机操作类.取所有打印机

* **类型:** `全局方法`
* **名称:** `取所有打印机`
* **返回值数据类型:** `整数`
* **参数:**
	* `打印机名称数组` (`文本数组类`): 用作存储所获得的所有打印机名称
	* `是否包括网络打印机` (`逻辑型`, 默认值: `假`): 指定是否获取网络/远程打印机
* **特性:**
	* `静态`
* **描述:** 获取当前所有可用打印机名称
* **返回值描述:** 返回所获取到的打印机名称数目

---

#### 火山.基本.打印机状态码

* **类型:** `类`
* **名称:** `打印机状态码`
* **特性:**
	* `常量类`(对应数据类型: `整数`)
* **文档分类:** `打印机操作.辅助类`
* **描述:** 提供打印机的相关状态码值

##### 火山.基本.打印机状态码.失败

* **类型:** `成员常量`
* **名称:** `失败`
* **数据类型:** `打印机状态码`
* **初始值:** `-1`
* **描述:** 获取打印机状态码失败

##### 火山.基本.打印机状态码.正常

* **类型:** `成员常量`
* **名称:** `正常`
* **数据类型:** `打印机状态码`
* **初始值:** `0`

##### 火山.基本.打印机状态码.忙碌

* **类型:** `成员常量`
* **名称:** `忙碌`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.门被打开

* **类型:** `成员常量`
* **名称:** `门被打开`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.出错

* **类型:** `成员常量`
* **名称:** `出错`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.正在初始化

* **类型:** `成员常量`
* **名称:** `正在初始化`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.正在传输

* **类型:** `成员常量`
* **名称:** `正在传输`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.需手动供纸

* **类型:** `成员常量`
* **名称:** `需手动供纸`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.缺墨

* **类型:** `成员常量`
* **名称:** `缺墨`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.不可用

* **类型:** `成员常量`
* **名称:** `不可用`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.离线

* **类型:** `成员常量`
* **名称:** `离线`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.内存溢出

* **类型:** `成员常量`
* **名称:** `内存溢出`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.输出纸盒已满

* **类型:** `成员常量`
* **名称:** `输出纸盒已满`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.无法打印当前页

* **类型:** `成员常量`
* **名称:** `无法打印当前页`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.卡纸

* **类型:** `成员常量`
* **名称:** `卡纸`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.缺纸

* **类型:** `成员常量`
* **名称:** `缺纸`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.纸张有问题

* **类型:** `成员常量`
* **名称:** `纸张有问题`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.暂停

* **类型:** `成员常量`
* **名称:** `暂停`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.作业删除中

* **类型:** `成员常量`
* **名称:** `作业删除中`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.节能模式

* **类型:** `成员常量`
* **名称:** `节能模式`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.正在打印

* **类型:** `成员常量`
* **名称:** `正在打印`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.正在处理作业

* **类型:** `成员常量`
* **名称:** `正在处理作业`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.未知

* **类型:** `成员常量`
* **名称:** `未知`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.少墨

* **类型:** `成员常量`
* **名称:** `少墨`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.需用户处理

* **类型:** `成员常量`
* **名称:** `需用户处理`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.等待

* **类型:** `成员常量`
* **名称:** `等待`
* **数据类型:** `打印机状态码`

##### 火山.基本.打印机状态码.正在预热

* **类型:** `成员常量`
* **名称:** `正在预热`
* **数据类型:** `打印机状态码`

---

#### 火山.基本.标准数组模板类

* **类型:** `类`
* **名称:** `标准数组模板类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.标准数组`
* **描述:** 本模板类封装了C++标准数组模板类"std::vector"

##### 火山.基本.标准数组模板类.预分配尺寸

* **类型:** `属性写方法`
* **名称:** `预分配尺寸`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `尺寸` (`整数`)
* **特性:**
	* `静态`
* **描述:** 提前为本数组分配指定数目成员的空间,用作支持在后面快速进行成员添加.

##### 火山.基本.标准数组模板类.预分配尺寸

* **类型:** `属性读方法`
* **名称:** `预分配尺寸`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`

##### 火山.基本.标准数组模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.

##### 火山.基本.标准数组模板类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来逆向枚举本数组中的每一个成员,在循环中可以调用"取枚举索引"/"取枚举值"方法来获取当前所枚举索引和对应值. 注意: 不能嵌套使用本循环,否则编译将报错.

##### 火山.基本.标准数组模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.标准数组模板类.枚举循环), [逆向枚举循环](#火山.基本.标准数组模板类.逆向枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到的成员值,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回所处最近层"枚举循环"的枚举成员值.

##### 火山.基本.标准数组模板类.取枚举索引

* **类型:** `方法`
* **名称:** `取枚举索引`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.标准数组模板类.枚举循环), [逆向枚举循环](#火山.基本.标准数组模板类.逆向枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到成员的索引位置,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回所处最近层"枚举循环"枚举到成员的索引位置.

##### 火山.基本.标准数组模板类.取数组指针

* **类型:** `方法`
* **名称:** `取数组指针`
* **返回值数据类型:** `变整数`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 返回当前数组内容的第一个元素的指针. 除非必要且对指针概念有透彻的了解,不要使用本方法.

##### 火山.基本.标准数组模板类.索引是否有效

* **类型:** `方法`
* **名称:** `索引是否有效`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `所欲检查的索引值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 返回所指定的索引值是否大于等于0且小于本数组的成员数

##### 火山.基本.标准数组模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 返回数组中的当前已有成员数目

##### 火山.基本.标准数组模板类.取最大索引

* **类型:** `方法`
* **名称:** `取最大索引`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 返回数组中尾成员的索引位置,如果当前数组为空,则返回-1.

##### 火山.基本.标准数组模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 返回本数组是否为空

##### 火山.基本.标准数组模板类.删除所有成员

* **类型:** `方法`
* **名称:** `删除所有成员`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 删除数组中的当前所有成员

##### 火山.基本.标准数组模板类.重置数组

* **类型:** `方法`
* **名称:** `重置数组`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `欲重置的成员数目` (`整数`)
	* `初始值` (`模板类型1`): 用于提供每个成员的初始值
* **特性:**
	* `静态`
* **描述:** 重置数组中的成员数为所指定的数目

##### 火山.基本.标准数组模板类.重置成员数

* **类型:** `方法`
* **名称:** `重置成员数`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `新成员数` (`整数`)
* **特性:**
	* `静态`
* **描述:** 重置当前数组的成员数量,如果新的成员数小于当前成员数,则多余的成员数会被删除.

##### 火山.基本.标准数组模板类.取成员

* **类型:** `方法`
* **名称:** `取成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
* **特性:**
	* `静态`
* **描述:** 返回所指定索引位置处的成员值

##### 火山.基本.标准数组模板类.置成员值

* **类型:** `方法`
* **名称:** `置成员值`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
	* `所欲设置的值` (`模板类型1`): 提供所欲设置的成员值,先前的值将被覆盖.
* **特性:**
	* `静态`
* **描述:** 设置数组中所指定索引位置处的成员值

##### 火山.基本.标准数组模板类.添加数组

* **类型:** `方法`
* **名称:** `添加数组`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `所欲添加的数组` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 将另一个同类型数组的内容添加到本数组尾部

##### 火山.基本.标准数组模板类.添加部分数组

* **类型:** `方法`
* **名称:** `添加部分数组`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `所欲添加的数组` (`标准数组模板类`)
	* `起始索引位置` (`整数`): 必须大于等于0且加上"所欲添加的成员数"后小于等于"所欲添加的数组"的成员数目
	* `所欲添加的成员数` (`整数`): 必须大于等于0且加上"起始索引位置"后小于等于"所欲添加的数组"的成员数目
* **特性:**
	* `静态`
* **描述:** 将另一个同类型数组内容中的一部分添加到本数组尾部

##### 火山.基本.标准数组模板类.初始化

* **类型:** `方法`
* **名称:** `初始化`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `欲添加成员` (`模板类型1`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 从一系列所提供成员值创建当前对象

##### 火山.基本.标准数组模板类.从数组复制

* **类型:** `方法`
* **名称:** `从数组复制`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `欲复制的数组` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 将另一个同类型数组的内容复制到本数组中

##### 火山.基本.标准数组模板类.加入成员

* **类型:** `方法`
* **名称:** `加入成员`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `欲添加成员` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 将一个所指定类型的成员值加入到本数组的尾部

##### 火山.基本.标准数组模板类.插入成员

* **类型:** `方法`
* **名称:** `插入成员`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入的成员值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 将所指定的成员值插入到所指定的索引位置

##### 火山.基本.标准数组模板类.插入相同成员

* **类型:** `方法`
* **名称:** `插入相同成员`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `插入数量` (`整数`)
	* `所欲插入的成员值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 将所指定的成员值插入到所指定的索引位置

##### 火山.基本.标准数组模板类.插入数组

* **类型:** `方法`
* **名称:** `插入数组`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入的数组` (`标准数组模板类`): 提供所欲插入的数组数据
* **特性:**
	* `静态`
* **描述:** 将另一个同类型数组的内容插入到本数组的指定索引位置

##### 火山.基本.标准数组模板类.删除尾成员

* **类型:** `方法`
* **名称:** `删除尾成员`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 删除数组尾部的单个成员,数组不能为空.

##### 火山.基本.标准数组模板类.删除成员

* **类型:** `方法`
* **名称:** `删除成员`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `删除索引位置` (`整数`): 提供所欲删除成员的索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲删除成员数目` (`整数`, 默认值: `1`): 提供所欲删除成员的数目,必须大于等于0且加上"删除索引位置"参数值后小于等于数组成员数目.
* **特性:**
	* `静态`
* **描述:** 删除数组中指定索引位置处的成员

##### 火山.基本.标准数组模板类.删除到尾部

* **类型:** `方法`
* **名称:** `删除到尾部`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `起始索引位置` (`整数`): 提供所欲删除起始成员的索引位置,必须大于等于0且小于等于数组成员数目.
* **特性:**
	* `静态`
* **描述:** 删除数组中所指定索引位置后(包括该位置)的所有成员

##### 火山.基本.标准数组模板类.查找删除成员

* **类型:** `方法`
* **名称:** `查找删除成员`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `所欲查找成员值` (`模板类型1`): 提供所欲查找并删除的成员值
* **特性:**
	* `静态`
* **描述:** 查找第一个等于所指定值的成员,如果找到则将其删除并返回真,否则返回假.

##### 火山.基本.标准数组模板类.交换成员

* **类型:** `方法`
* **名称:** `交换成员`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `索引位置1` (`整数`): 提供成员1的索引位置,必须大于等于0且小于数组成员数目.
	* `索引位置2` (`整数`): 提供成员2的索引位置,必须大于等于0且小于数组成员数目.
* **特性:**
	* `静态`
* **描述:** 将两个索引位置处的成员值相互交换

##### 火山.基本.标准数组模板类.交换所有成员

* **类型:** `方法`
* **名称:** `交换所有成员`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `欲交换的数组` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 将当前数组的成员和另外一个数组的成员进行交换

##### 火山.基本.标准数组模板类.弹出成员

* **类型:** `方法`
* **名称:** `弹出成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 返回并删除数组尾部的单个成员. 注意: 执行本方法前必须确保数组不为空

##### 火山.基本.标准数组模板类.取首成员

* **类型:** `方法`
* **名称:** `取首成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 取第一个成员

##### 火山.基本.标准数组模板类.取尾成员

* **类型:** `方法`
* **名称:** `取尾成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 返回数组尾部的成员值. 注意: 执行本方法前必须确保数组不为空

##### 火山.基本.标准数组模板类.查找首成员

* **类型:** `方法`
* **名称:** `查找首成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `所欲查找的成员值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 正向查找等于所指定值的第一个成员,找到返回其索引位置,未找到返回-1.

##### 火山.基本.标准数组模板类.成员是否存在

* **类型:** `方法`
* **名称:** `成员是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `所欲查找的成员值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 返回数组中是否存在为所指定值的成员

##### 火山.基本.标准数组模板类.查找尾成员

* **类型:** `方法`
* **名称:** `查找尾成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `所欲查找的成员值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 逆向查找等于所指定值的最后一个成员,找到返回其索引位置,未找到返回-1.

##### 火山.基本.标准数组模板类.替换成员值

* **类型:** `方法`
* **名称:** `替换成员值`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `所欲替换的成员值` (`模板类型1`)
	* `所替换到的成员值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 将所有等于指定值的成员替换为另一个值.

##### 火山.基本.标准数组模板类.取指定成员数量

* **类型:** `方法`
* **名称:** `取指定成员数量`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `欲检查的成员值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 获取指定成员值在数组内的数量

##### 火山.基本.标准数组模板类.排序

* **类型:** `方法`
* **名称:** `排序`
* **参数:**
	* `当前对象` (`标准数组模板类`)
	* `从小到大排序` (`逻辑型`, 默认值: `真`): 为真表示从小到大进行排序,为假表示从大到小进行排序.
* **特性:**
	* `静态`
* **描述:** 对数组中的所有成员进行排序

##### 火山.基本.标准数组模板类.反转顺序

* **类型:** `方法`
* **名称:** `反转顺序`
* **参数:**
	* `当前对象` (`标准数组模板类`)
* **特性:**
	* `静态`
* **描述:** 反转数组顺序,例如: 1,2,3 变 3,2,1

---

#### 火山.基本.文本标准数组类

* **类型:** `类`
* **名称:** `文本标准数组类`
* **模板基础类:** `标准数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`
* **文档分类:** `数据处理.标准数组`

---

#### 火山.基本.整数标准数组类

* **类型:** `类`
* **名称:** `整数标准数组类`
* **模板基础类:** `标准数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`
* **文档分类:** `数据处理.标准数组`

---

#### 火山.基本.小数标准数组类

* **类型:** `类`
* **名称:** `小数标准数组类`
* **模板基础类:** `标准数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `小数`
* **文档分类:** `数据处理.标准数组`

---

#### 火山.基本.逻辑型标准数组类

* **类型:** `类`
* **名称:** `逻辑型标准数组类`
* **模板基础类:** `标准数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `逻辑型`
* **文档分类:** `数据处理.标准数组`

---

#### 火山.基本.标准列表模板类

* **类型:** `类`
* **名称:** `标准列表模板类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.标准列表`
* **描述:** 本模板类封装了C++标准列表模板类"std::list"

##### 火山.基本.标准列表模板类.初始化

* **类型:** `方法`
* **名称:** `初始化`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `欲初始化的成员` (`模板类型1`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 从一个或多个成员初始化当前列表

##### 火山.基本.标准列表模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `当前对象` (`标准列表模板类`)
* **特性:**
	* `静态`
* **描述:** 返回本列表内容是否为空

##### 火山.基本.标准列表模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **参数:**
	* `当前对象` (`标准列表模板类`)
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来枚举本列表中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值

##### 火山.基本.标准列表模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `当前对象` (`标准列表模板类`)
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.标准列表模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前枚举到的成员值,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回所处最近层"枚举循环"的枚举成员值.

##### 火山.基本.标准列表模板类.加入首成员

* **类型:** `方法`
* **名称:** `加入首成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 在本列表的首部插入指定成员

##### 火山.基本.标准列表模板类.加入成员

* **类型:** `方法`
* **名称:** `加入成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 将一个成员值加入到本列表的尾部

##### 火山.基本.标准列表模板类.删除首成员

* **类型:** `方法`
* **名称:** `删除首成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
* **特性:**
	* `静态`
* **描述:** 删除本列表的首成员

##### 火山.基本.标准列表模板类.删除尾成员

* **类型:** `方法`
* **名称:** `删除尾成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
* **特性:**
	* `静态`
* **描述:** 删除本列表的最后一个成员

##### 火山.基本.标准列表模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`标准列表模板类`)
* **特性:**
	* `静态`
* **描述:** 返回本列表中的成员数目

##### 火山.基本.标准列表模板类.插入成员

* **类型:** `方法`
* **名称:** `插入成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `索引位置` (`整数`): 提供欲插入成员的索引位置,必须大于等于0且小于等于列表成员数目.
	* `值` (`模板类型1`): 提供欲插入的成员值
* **特性:**
	* `静态`
* **描述:** 在指定索引位置处插入成员

##### 火山.基本.标准列表模板类.插入多个成员

* **类型:** `方法`
* **名称:** `插入多个成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `索引位置` (`整数`): 提供欲插入成员的索引位置,必须大于等于0且小于等于列表成员数目.
	* `插入数量` (`整数`)
	* `值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 在指定索引位置插入多个相同成员

##### 火山.基本.标准列表模板类.插入列表到首部

* **类型:** `方法`
* **名称:** `插入列表到首部`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `欲插入的列表` (`标准列表模板类`)
* **特性:**
	* `静态`
* **描述:** 插入一个列表到当前列表首部

##### 火山.基本.标准列表模板类.加入列表

* **类型:** `方法`
* **名称:** `加入列表`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `欲添加的列表` (`标准列表模板类`)
* **特性:**
	* `静态`
* **描述:** 将指定列表内容添加到当前列表尾部

##### 火山.基本.标准列表模板类.移动列表到首部

* **类型:** `方法`
* **名称:** `移动列表到首部`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `欲移动的列表` (`标准列表模板类`): 注意: 移动后此列表内容将清空
* **特性:**
	* `静态`
* **描述:** 将指定列表的所有内容移动到本列表首部

##### 火山.基本.标准列表模板类.移动列表到尾部

* **类型:** `方法`
* **名称:** `移动列表到尾部`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `欲移动的列表` (`标准列表模板类`): 注意: 移动后此列表内容将清空
* **特性:**
	* `静态`
* **描述:** 将指定列表的所有内容移动到本列表尾部

##### 火山.基本.标准列表模板类.删除成员

* **类型:** `方法`
* **名称:** `删除成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `起始索引` (`整数`): 提供欲删除成员的起始索引位置,必须大于等于0且小于列表成员数目.
	* `删除成员数量` (`整数`, 默认值: `1`): 提供欲删除成员的数目
* **特性:**
	* `静态`
* **描述:** 删除列表中的成员

##### 火山.基本.标准列表模板类.交换所有成员

* **类型:** `方法`
* **名称:** `交换所有成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `欲交换的列表` (`标准列表模板类`)
* **特性:**
	* `静态`
* **描述:** 将当前列表的内容和另外一个列表的内容进行交换

##### 火山.基本.标准列表模板类.重置成员数

* **类型:** `方法`
* **名称:** `重置成员数`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `新成员数` (`整数`)
* **特性:**
	* `静态`
* **描述:** 重置当前列表的成员数量,如果新的成员数小于当前成员数,则多余的成员数会被删除.

##### 火山.基本.标准列表模板类.重置列表

* **类型:** `方法`
* **名称:** `重置列表`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `新成员数` (`整数`)
	* `初始值` (`模板类型1`): 提供新增成员的初始值
	* `清空内容` (`逻辑型`, 默认值: `真`): 是否清空原有内容
* **特性:**
	* `静态`
* **描述:** 重置当前列表的成员数量,并设置新增成员的初始值.

##### 火山.基本.标准列表模板类.删除所有成员

* **类型:** `方法`
* **名称:** `删除所有成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
* **特性:**
	* `静态`
* **描述:** 删除列表中的当前所有成员

##### 火山.基本.标准列表模板类.删除匹配成员

* **类型:** `方法`
* **名称:** `删除匹配成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `欲删除的值` (`模板类型1`): 列表中所有等于该值的成员都将被删除
* **特性:**
	* `静态`
* **描述:** 删除列表中所有等于指定值的成员

##### 火山.基本.标准列表模板类.删除连续重复成员

* **类型:** `方法`
* **名称:** `删除连续重复成员`
* **参数:**
	* `当前对象` (`标准列表模板类`)
* **特性:**
	* `静态`
* **描述:** 删除列表中所有连续重复的成员,只保留其中的一个.

##### 火山.基本.标准列表模板类.排序合并

* **类型:** `方法`
* **名称:** `排序合并`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `欲合并的列表` (`标准列表模板类`): 合并后本列表将清空
* **特性:**
	* `静态`
* **描述:** 排序两个列表并将两者内容合并到当前列表

##### 火山.基本.标准列表模板类.反转

* **类型:** `方法`
* **名称:** `反转`
* **参数:**
	* `当前对象` (`标准列表模板类`)
* **特性:**
	* `静态`
* **描述:** 反转当前列表中成员的排列顺序

##### 火山.基本.标准列表模板类.排序

* **类型:** `方法`
* **名称:** `排序`
* **参数:**
	* `当前对象` (`标准列表模板类`)
	* `从小到大排序` (`逻辑型`, 默认值: `真`): 为真表示从小到大进行排序,为假表示从大到小进行排序.
* **特性:**
	* `静态`
* **描述:** 对列表中的所有成员进行排序

---

#### 火山.基本.文本标准列表类

* **类型:** `类`
* **名称:** `文本标准列表类`
* **模板基础类:** `标准列表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`
* **文档分类:** `数据处理.标准列表`

---

#### 火山.基本.整数标准列表类

* **类型:** `类`
* **名称:** `整数标准列表类`
* **模板基础类:** `标准列表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`
* **文档分类:** `数据处理.标准列表`

---

#### 火山.基本.小数标准列表类

* **类型:** `类`
* **名称:** `小数标准列表类`
* **模板基础类:** `标准列表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `小数`
* **文档分类:** `数据处理.标准列表`

---

#### 火山.基本.多值哈希表模板类

* **类型:** `类`
* **名称:** `多值哈希表模板类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.多值哈希表`
* **描述:** 本模板类封装了C++标准列表模板类"std::multimap". 多值哈希表模板类: 模板类型1: 关键字 模板类型2: 值本类特点如下: 1. 与通常哈希表不同的是: 本类允许关键字有多个关联值; 2. 内部的元素会根据键自动排序; 3. 插入新元素的速度非常快; 4. 支持高效的查找和删除操作：你可以用关键字来查找元素,或者删除具有某个关键字的所有值.

##### 火山.基本.多值哈希表模板类.初始化

* **类型:** `方法`
* **名称:** `初始化`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
	* `初始列表` (`文本型`): 本参数用作提供数据表中的初始键值对列表的字符串格式. "整数到文本多值哈希表"的"初始列表"例如: "{1,\"火\"},{2,\"山\"},{3,\"软\"}"
* **特性:**
	* `静态`

##### 火山.基本.多值哈希表模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
	* `关键字` (`模板类型1`): 提供关键字
	* `对应值` (`模板类型2`): 提供关键字所对应的值
* **特性:**
	* `静态`
* **描述:** 插入一个键值对进哈希表中,如果指定关键字已经存在,不会将其覆盖,会建立一个新的键值对.

##### 火山.基本.多值哈希表模板类.枚举值

* **类型:** `方法`
* **名称:** `枚举值`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
	* `关键字` (`模板类型1`): 提供欲查找其值的关键字
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 枚举指定关键字所有值. 在本方法的子语句体内调用"取值"方法即可取出对应值.

##### 火山.基本.多值哈希表模板类.取值

* **类型:** `方法`
* **名称:** `取值`
* **返回值数据类型:** `模板类型2`
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举值](#火山.基本.多值哈希表模板类.枚举值)
* **描述:** 只能在本类的"枚举值"语句的子语句体中使用,用作取回当前所枚举到键值对成员的值.

##### 火山.基本.多值哈希表模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来正向枚举本哈希表中的每一个成员,在循环中可以调用"取枚举关键字"/"取枚举值"方法来获取当前所枚举到键值对的关键字及其对应值.

##### 火山.基本.多值哈希表模板类.取枚举关键字

* **类型:** `方法`
* **名称:** `取枚举关键字`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.多值哈希表模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的关键字,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回最近层"枚举循环"所枚举到键值对成员的关键字.

##### 火山.基本.多值哈希表模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型2`
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.多值哈希表模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前所枚举到键值对成员的值,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回最近层"枚举循环"所枚举到键值对成员的值.

##### 火山.基本.多值哈希表模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
* **特性:**
	* `静态`
* **描述:** 返回本哈希表中已有键值对成员的数目

##### 火山.基本.多值哈希表模板类.是否存在

* **类型:** `方法`
* **名称:** `是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **特性:**
	* `静态`
* **描述:** 返回所指定的关键字是否已经存在

##### 火山.基本.多值哈希表模板类.删除所有值

* **类型:** `方法`
* **名称:** `删除所有值`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **特性:**
	* `静态`
* **描述:** 删除指定关键字及其所有关联键值对

##### 火山.基本.多值哈希表模板类.删除首值

* **类型:** `方法`
* **名称:** `删除首值`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
	* `关键字` (`模板类型1`): 提供所对应的关键字
* **特性:**
	* `静态`
* **描述:** 删除指定关键字的第一个关联键值对

##### 火山.基本.多值哈希表模板类.删除指定值

* **类型:** `方法`
* **名称:** `删除指定值`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
	* `关键字` (`模板类型1`): 提供所对应的关键字
	* `值` (`模板类型2`): 提供欲删除的该关键字的值
* **特性:**
	* `静态`
* **描述:** 删除指定关键字的所有指定值

##### 火山.基本.多值哈希表模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
* **特性:**
	* `静态`
* **描述:** 清除本哈希表中的所有内容

##### 火山.基本.多值哈希表模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
	* `所欲交换的哈希表` (`多值哈希表模板类`)
* **特性:**
	* `静态`
* **描述:** 交换两个哈希表中的数据

##### 火山.基本.多值哈希表模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `当前对象` (`多值哈希表模板类`)
* **特性:**
	* `静态`
* **描述:** 返回本哈希表是否为空

---

#### 火山.基本.整数到整数多值哈希表

* **类型:** `类`
* **名称:** `整数到整数多值哈希表`
* **模板基础类:** `多值哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`; `模板类型2` -> `整数`
* **文档分类:** `数据处理.多值哈希表`

---

#### 火山.基本.整数到文本多值哈希表

* **类型:** `类`
* **名称:** `整数到文本多值哈希表`
* **模板基础类:** `多值哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`; `模板类型2` -> `文本型`
* **文档分类:** `数据处理.多值哈希表`

---

#### 火山.基本.文本到文本多值哈希表

* **类型:** `类`
* **名称:** `文本到文本多值哈希表`
* **模板基础类:** `多值哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`; `模板类型2` -> `文本型`
* **文档分类:** `数据处理.多值哈希表`

---

#### 火山.基本.文本到整数多值哈希表

* **类型:** `类`
* **名称:** `文本到整数多值哈希表`
* **模板基础类:** `多值哈希表模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`; `模板类型2` -> `整数`
* **文档分类:** `数据处理.多值哈希表`

---

#### 火山.基本.多值哈希集模板类

* **类型:** `类`
* **名称:** `多值哈希集模板类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数据处理.多值哈希集`
* **描述:** 本模板类封装了C++标准列表模板类"std::multiset",提供了有序的哈希集数据存储支持.

##### 火山.基本.多值哈希集模板类.初始化

* **类型:** `方法`
* **名称:** `初始化`
* **参数:**
	* `当前对象` (`多值哈希集模板类`)
	* `值` (`模板类型1`, `可扩展`)
* **特性:**
	* `静态`
* **描述:** 从一个或多个值初始化当前对象

##### 火山.基本.多值哈希集模板类.插入

* **类型:** `方法`
* **名称:** `插入`
* **参数:**
	* `当前对象` (`多值哈希集模板类`)
	* `所欲插入的值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 插入一个值进哈希集中,允许记录重复的值.

##### 火山.基本.多值哈希集模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`多值哈希集模板类`)
* **特性:**
	* `静态`
* **描述:** 返回本哈希集中已有成员的数目

##### 火山.基本.多值哈希集模板类.是否存在

* **类型:** `方法`
* **名称:** `是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `当前对象` (`多值哈希集模板类`)
	* `所欲检查的值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 返回所指定的值是否已经存在

##### 火山.基本.多值哈希集模板类.删除

* **类型:** `方法`
* **名称:** `删除`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`多值哈希集模板类`)
	* `所欲删除的值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 删除所有满足条件的值,并返回删除的值数量.

##### 火山.基本.多值哈希集模板类.清空

* **类型:** `方法`
* **名称:** `清空`
* **参数:**
	* `当前对象` (`多值哈希集模板类`)
* **特性:**
	* `静态`
* **描述:** 清除本哈希集中的所有内容

##### 火山.基本.多值哈希集模板类.交换

* **类型:** `方法`
* **名称:** `交换`
* **参数:**
	* `当前对象` (`多值哈希集模板类`)
	* `所欲交换的哈希集` (`多值哈希集模板类`)
* **特性:**
	* `静态`
* **描述:** 交换两个哈希集中的数据

##### 火山.基本.多值哈希集模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `当前对象` (`多值哈希集模板类`)
* **特性:**
	* `静态`
* **描述:** 返回本哈希集是否为空

##### 火山.基本.多值哈希集模板类.取指定值数目

* **类型:** `方法`
* **名称:** `取指定值数目`
* **返回值数据类型:** `整数`
* **参数:**
	* `当前对象` (`多值哈希集模板类`)
	* `欲检查的值` (`模板类型1`)
* **特性:**
	* `静态`
* **描述:** 返回指定成员值在本哈希集中的记录数目

##### 火山.基本.多值哈希集模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **参数:**
	* `当前对象` (`多值哈希集模板类`)
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来枚举本列表中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值

##### 火山.基本.多值哈希集模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.多值哈希集模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前枚举到的成员值,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回所处最近层"枚举循环"的枚举成员值.

---

#### 火山.基本.文本多值哈希集类

* **类型:** `类`
* **名称:** `文本多值哈希集类`
* **模板基础类:** `多值哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本型`
* **文档分类:** `数据处理.多值哈希集`

---

#### 火山.基本.整数多值哈希集类

* **类型:** `类`
* **名称:** `整数多值哈希集类`
* **模板基础类:** `多值哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`
* **文档分类:** `数据处理.多值哈希集`

---

#### 火山.基本.小数多值哈希集类

* **类型:** `类`
* **名称:** `小数多值哈希集类`
* **模板基础类:** `多值哈希集模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `小数`
* **文档分类:** `数据处理.多值哈希集`

---

#### 火山.基本.标准文本类

* **类型:** `类`
* **名称:** `标准文本类`
* **文档分类:** `数据处理`
* **描述:** 本类封装了C++标准文本类"std::string".

##### 火山.基本.标准文本类.创建

* **类型:** `方法`
* **名称:** `创建`
* **返回值数据类型:** `标准文本类`
* **参数:**
	* `文本数据` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 基于所指定文本内容创建对应的utf-8编码标准文本数据

##### 火山.基本.标准文本类.取文本

* **类型:** `方法`
* **名称:** `取文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `当前对象` (`标准文本类`)
* **特性:**
	* `静态`
* **描述:** 取回本类对象中的文本内容. 注意: 本方法假设本类对象中文本的编码格式为utf-8.

---

#### 火山.基本.标准宽文本类

* **类型:** `类`
* **名称:** `标准宽文本类`
* **文档分类:** `数据处理`
* **描述:** 本类封装了C++标准宽文本类"std::wstring".

##### 火山.基本.标准宽文本类.创建

* **类型:** `方法`
* **名称:** `创建`
* **返回值数据类型:** `标准宽文本类`
* **参数:**
	* `文本数据` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 基于所指定文本内容创建对应的标准文本数据

##### 火山.基本.标准宽文本类.取文本

* **类型:** `方法`
* **名称:** `取文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `当前对象` (`标准宽文本类`)
* **特性:**
	* `静态`
* **描述:** 取回本类对象中的文本内容

---

#### 火山.基本.基本数组操作类

* **类型:** `类`
* **名称:** `基本数组操作类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **描述:** 本类提供维定义数组的相关操作支持,建议数组数据不要使用维定义数组,使用类库中提供的相关数组类对象更加方便灵活.

##### 火山.基本.基本数组操作类.数组清零

* **类型:** `全局方法`
* **名称:** `数组清零`
* **参数:**
	* `数组变量数据` (`通用数值型数组(需求:可写入变量)`)
* **特性:**
	* `静态`
* **描述:** 将所指定数值型数组变量中的内容全部清零

##### 火山.基本.基本数组操作类.重置逻辑值数组

* **类型:** `全局方法`
* **名称:** `重置逻辑值数组`
* **参数:**
	* `数组变量数据` (`逻辑型 [](需求:可写入变量)`)
* **特性:**
	* `静态`
* **描述:** 将所指定逻辑型数组变量中的内容全部设置为假

##### 火山.基本.基本数组操作类.取数组成员数

* **类型:** `全局方法`
* **名称:** `取数组成员数`
* **返回值数据类型:** `整数`
* **参数:**
	* `数组变量数据` (`通用型数组`)
* **特性:**
	* `静态`
* **描述:** 返回指定数组变量首维的定义维数,对于单维数组来说,就是其成员数目.
* **相关例程:** [vol-表格-grid-main](#vol-表格-grid-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-被调用动态链接库-dll_test-main](#vol-被调用动态链接库-dll_test-main), [vol-调用动态链接库-dll_call-main](#vol-调用动态链接库-dll_call-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.基本数组操作类.整数数组排序

* **类型:** `全局方法`
* **名称:** `整数数组排序`
* **参数:**
	* `所欲排序的数组` (`整数 [](需求:可写入变量)`)
	* `从小到大排序` (`逻辑型`, 默认值: `真`)
* **特性:**
	* `静态`
* **描述:** 将所指定整数数组中的所有成员进行排序

##### 火山.基本.基本数组操作类.小数数组排序

* **类型:** `全局方法`
* **名称:** `小数数组排序`
* **参数:**
	* `所欲排序的数组` (`小数 [](需求:可写入变量)`)
	* `从小到大排序` (`逻辑型`, 默认值: `真`)
* **特性:**
	* `静态`
* **描述:** 将所指定小数数组中的所有成员进行排序

---

#### 火山.基本.基本类型数组模板类

* **类型:** `类`
* **名称:** `基本类型数组模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数组操作.模板类`
* **描述:** 所有基本数据类型(不包括文本型)数组的模版类. 模板类型1: 数组成员的数据类型

##### 火山.基本.基本类型数组模板类.预分配尺寸

* **类型:** `属性读方法`
* **名称:** `预分配尺寸`
* **返回值数据类型:** `整数`
* **描述:** 返回本数组为了快速进行数组成员的添加/删除处理使用的空间分配尺寸,每次数组需要调整其空间大小时,都使用本属性值乘于单个数组成员尺寸作为空间调整基准尺寸.值越大,批量加入/删除数组成员时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.

##### 火山.基本.基本类型数组模板类.预分配尺寸

* **类型:** `属性写方法`
* **名称:** `预分配尺寸`
* **参数:**
	* `所欲设置的预分配尺寸` (`整数`)
* **描述:** 设置本数组为了快速进行数组成员的添加/删除处理使用的空间分配尺寸,每次数组需要调整其空间大小时,都使用本属性值乘于单个数组成员尺寸作为空间调整基准尺寸.值越大,批量加入/删除数组成员时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.

##### 火山.基本.基本类型数组模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.
* **相关例程:** [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main)

##### 火山.基本.基本类型数组模板类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个逆向循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.基本类型数组模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.基本类型数组模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到的成员值,如果有多层本类或本类继承类的循环嵌套,本方法将返回所处最近层循环的枚举成员值.
* **相关例程:** [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.基本类型数组模板类.取枚举索引

* **类型:** `方法`
* **名称:** `取枚举索引`
* **返回值数据类型:** `整数`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.基本类型数组模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到成员的索引位置,如果有多层本类或本类继承类的循环嵌套,本方法将返回所处最近层循环枚举到成员的索引位置.

##### 火山.基本.基本类型数组模板类.取数组指针

* **类型:** `方法`
* **名称:** `取数组指针`
* **返回值数据类型:** `变整数`
* **描述:** 返回当前数组内容的数据指针值. 除非必要且对指针概念有透彻的了解,不要使用本方法.

##### 火山.基本.基本类型数组模板类.添加数组指针内容

* **类型:** `方法`
* **名称:** `添加数组指针内容`
* **参数:**
	* `数组数据指针` (`变整数`): 提供指向为本数组成员数据类型的数组数据指针
	* `所欲添加成员数目` (`整数`): 提供所欲添加的指针所指向地址处的数组成员数目,其数据类型必须为本数组的成员数据类型.因此必须确保指针所指向地址处的尺寸为"本数组成员数据类型尺寸 * 本参数值"的数据内容有效.
* **描述:** 将所指定指针处的数组数据添加到本数组的尾部. 除非必要且对指针概念有透彻的了解,不要使用本方法.

##### 火山.基本.基本类型数组模板类.索引是否有效

* **类型:** `方法`
* **名称:** `索引是否有效`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的索引值` (`整数`)
* **描述:** 返回所指定的索引值是否大于等于0且小于本数组的成员数

##### 火山.基本.基本类型数组模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回数组中的当前已有成员数目
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.基本类型数组模板类.取最大索引

* **类型:** `方法`
* **名称:** `取最大索引`
* **返回值数据类型:** `整数`
* **描述:** 返回数组中尾成员的索引位置

##### 火山.基本.基本类型数组模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本数组是否为空

##### 火山.基本.基本类型数组模板类.删除所有成员

* **类型:** `方法`
* **名称:** `删除所有成员`
* **描述:** 删除数组中的当前所有成员
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main)

##### 火山.基本.基本类型数组模板类.重置数组

* **类型:** `方法`
* **名称:** `重置数组`
* **参数:**
	* `欲重置的成员数目` (`整数`)
	* `是否清零` (`逻辑型`, 默认值: `真`): 如果为真则清零所有成员值. 注意: 如果本参数设置为假且扩充了数组成员数,则新增数组成员值为随机值.
* **描述:** 重置数组中的成员数为所指定的数目
* **相关例程:** [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main)

##### 火山.基本.基本类型数组模板类.清零

* **类型:** `方法`
* **名称:** `清零`
* **描述:** 将数组中的所有成员值清除为零值(如果是逻辑型数组,则清除为假)

##### 火山.基本.基本类型数组模板类.取字节集

* **类型:** `方法`
* **名称:** `取字节集`
* **返回值数据类型:** `字节集类`
* **描述:** 将本数组中的内容以字节集对象的形式返回

##### 火山.基本.基本类型数组模板类.取成员

* **类型:** `方法`
* **名称:** `取成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
* **描述:** 返回所指定索引位置处的成员值
* **相关例程:** [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.基本类型数组模板类.取成员尺寸

* **类型:** `方法`
* **名称:** `取成员尺寸`
* **返回值数据类型:** `整数`
* **描述:** 返回数组中单个成员的数据尺寸,单位字节.

##### 火山.基本.基本类型数组模板类.置成员值

* **类型:** `方法`
* **名称:** `置成员值`
* **参数:**
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
	* `所欲设置的值` (`模板类型1`): 提供所欲设置的成员值,先前的值将被覆盖.
* **描述:** 设置数组中所指定索引位置处的成员值
* **相关例程:** [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main)

##### 火山.基本.基本类型数组模板类.复制到基本数组

* **类型:** `方法`
* **名称:** `复制到基本数组`
* **参数:**
	* `起始复制首成员索引` (`整数`, 默认值: `0`): 提供所欲复制的在本数组对象内的首成员索引位置,参数值必须大于等于0且小于等于本数组对象的成员数.
	* `所欲复制的成员数` (`整数`): 提供所欲复制的本数组对象内成员数目,参数值务必大于等于0且加上"所欲复制的成员数"后小于等于本数组对象的成员数.
	* `所欲复制到的基本数组` (`模板类型1 []`): 提供所欲复制到的对应基本数据类型数组
	* `复制到的首成员索引` (`整数`, 默认值: `0`): 提供所欲复制到的在目标数组内的首成员索引位置,参数值务必大于等于0且加上"所欲复制的成员数"后小于等于"所欲复制到的数组"所定义的成员数.
* **描述:** 将本数组对象的内容复制到对应数据类型的基本数组中

##### 火山.基本.基本类型数组模板类.添加基本数组

* **类型:** `方法`
* **名称:** `添加基本数组`
* **参数:**
	* `所欲添加的基本数组` (`模板类型1 []`): 提供所欲添加其数据的对应基本数据类型数组
	* `首成员索引` (`整数`, 默认值: `0`): 提供所欲添加的首成员在基本数据类型数组中的索引位置,参数值务必大于等于0且加上"所欲添加的成员数"后小于等于"所欲添加的基本数组"的定义成员数.
	* `所欲添加的成员数` (`整数`): 提供所欲添加的基本数据类型数组内的成员数目,参数值务必大于等于0且加上"首成员索引"后小于等于该数组的定义成员数.
* **描述:** 将对应的基本数据类型数组中的指定内容添加到本数组的尾部

##### 火山.基本.基本类型数组模板类.从字节集复制

* **类型:** `方法`
* **名称:** `从字节集复制`
* **参数:**
	* `所欲复制的字节集` (`字节集类`): 用作提供成员数据的字节集数据
	* `起始复制偏移位置` (`整数`): 提供首成员数据在所指定字节集中的偏移位置(单位字节),必须大于等于0.
	* `所欲复制的成员数目` (`整数`): 提供所欲添加的成员数,必须大于等于0,"起始复制偏移位置 + 所欲复制的成员数目 * 单个成员数据尺寸"必须小于等于所指定字节集的尺寸.
* **描述:** 清空本数组的内容后,将所指定字节集中的指定部分内容作为数组成员数据添加到本数组中.

##### 火山.基本.基本类型数组模板类.添加字节集

* **类型:** `方法`
* **名称:** `添加字节集`
* **参数:**
	* `所欲添加的字节集` (`字节集类`): 用作提供成员数据的字节集数据
	* `起始添加偏移位置` (`整数`): 提供首成员数据在所指定字节集中的偏移位置(单位字节),必须大于等于0.
	* `所欲添加的成员数目` (`整数`): 提供所欲添加的成员数,必须大于等于0,"起始添加偏移位置 + 所欲添加的成员数目 * 单个成员数据尺寸"必须小于等于所指定字节集的尺寸.
* **描述:** 将所指定字节集中的指定部分内容作为数组成员数据添加到本数组尾部

##### 火山.基本.基本类型数组模板类.添加数组

* **类型:** `方法`
* **名称:** `添加数组`
* **参数:**
	* `所欲添加的数组` (`基本类型数组模板类`)
* **描述:** 将另一个同类型数组的内容添加到本数组尾部

##### 火山.基本.基本类型数组模板类.添加部分数组

* **类型:** `方法`
* **名称:** `添加部分数组`
* **参数:**
	* `所欲添加的数组` (`基本类型数组模板类`)
	* `起始索引位置` (`整数`): 必须大于等于0且加上"所欲添加的成员数"后小于等于"所欲添加的数组"的成员数目
	* `所欲添加的成员数` (`整数`): 必须大于等于0且加上"起始索引位置"后小于等于"所欲添加的数组"的成员数目
* **描述:** 将另一个同类型数组内容中的一部分添加到本数组尾部

##### 火山.基本.基本类型数组模板类.从数组复制

* **类型:** `方法`
* **名称:** `从数组复制`
* **参数:**
	* `所欲复制的数组` (`基本类型数组模板类`)
* **描述:** 清空本数组的原有内容,将另一个同类型数组的内容添加到本数组中.

##### 火山.基本.基本类型数组模板类.加入空成员

* **类型:** `方法`
* **名称:** `加入空成员`
* **参数:**
	* `所欲加入的零成员数` (`整数`)
* **描述:** 加入所指定数目的值为零(如果是逻辑型数组,则值为假)的成员

##### 火山.基本.基本类型数组模板类.加入成员

* **类型:** `方法`
* **名称:** `加入成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲添加成员值` (`模板类型1`, `可扩展`)
* **描述:** 将一个或多个所指定类型的成员值加入到本数组的尾部
* **返回值描述:** 返回所加入的第一个成员在数组中的记录索引位置
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.基本类型数组模板类.插入成员

* **类型:** `方法`
* **名称:** `插入成员`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入的成员值` (`模板类型1`)
* **描述:** 将所指定的成员值插入到所指定的索引位置
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.基本类型数组模板类.插入字节集

* **类型:** `方法`
* **名称:** `插入字节集`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入的字节集` (`字节集类`): 用作提供成员数据的字节集数据
	* `起始数据偏移位置` (`整数`): 提供首成员数据在所指定字节集中的偏移位置(单位字节),必须大于等于0.
	* `所欲插入的成员数目` (`整数`): 提供所欲插入的成员数,必须大于等于0,"起始数据偏移位置 + 所欲插入的成员数目 * 单个成员数据尺寸"必须小于等于所指定字节集的尺寸.
* **描述:** 将所指定字节集中的成员值内容插入到所指定的索引位置

##### 火山.基本.基本类型数组模板类.插入数组

* **类型:** `方法`
* **名称:** `插入数组`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入的数组` (`基本类型数组模板类`): 提供所欲插入的数组数据
* **描述:** 将另一个同类型数组的内容插入到本数组的所指定索引位置

##### 火山.基本.基本类型数组模板类.插入部分数组

* **类型:** `方法`
* **名称:** `插入部分数组`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入的数组` (`基本类型数组模板类`): 提供所欲插入的数组数据
	* `起始索引位置` (`整数`): 必须大于等于0且加上"所欲插入的成员数"后小于等于"所欲插入的数组"的成员数目
	* `所欲插入的成员数` (`整数`): 必须大于等于0且加上"起始索引位置"后小于等于"所欲插入的数组"的成员数目
* **描述:** 将另一个同类型数组的部分内容插入到本数组的所指定索引位置

##### 火山.基本.基本类型数组模板类.删除成员

* **类型:** `方法`
* **名称:** `删除成员`
* **参数:**
	* `删除索引位置` (`整数`): 提供所欲删除成员的索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲删除成员数目` (`整数`, 默认值: `1`): 提供所欲删除成员的数目,必须大于等于0且加上"删除索引位置"参数值后小于等于数组成员数目.
* **描述:** 删除数组中所指定索引位置处的成员
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main)

##### 火山.基本.基本类型数组模板类.删除到尾部

* **类型:** `方法`
* **名称:** `删除到尾部`
* **参数:**
	* `起始索引位置` (`整数`): 提供所欲删除起始成员的索引位置,必须大于等于0且小于等于数组成员数目.
* **描述:** 删除数组中所指定索引位置后(包括该位置)的所有成员

##### 火山.基本.基本类型数组模板类.查找删除成员

* **类型:** `方法`
* **名称:** `查找删除成员`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲查找成员值` (`模板类型1`): 提供所欲查找并删除的成员值
* **描述:** 查找第一个等于所指定值的成员,如果找到则将其删除并返回真,否则返回假.

##### 火山.基本.基本类型数组模板类.交换成员

* **类型:** `方法`
* **名称:** `交换成员`
* **参数:**
	* `索引位置1` (`整数`): 提供成员1的索引位置,必须大于等于0且小于数组成员数目.
	* `索引位置2` (`整数`): 提供成员2的索引位置,必须大于等于0且小于数组成员数目.
* **描述:** 将两个索引位置处的成员值相互交换

##### 火山.基本.基本类型数组模板类.压入成员

* **类型:** `方法`
* **名称:** `压入成员`
* **参数:**
	* `所欲压入的成员值` (`模板类型1`)
* **描述:** 将所指定的成员值添加到本数组的尾部. 本方法的效果等同于"加入成员".

##### 火山.基本.基本类型数组模板类.弹出成员

* **类型:** `方法`
* **名称:** `弹出成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 返回并删除数组尾部的单个成员. 注意: 执行本方法前必须确保数组不为空
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.基本类型数组模板类.抛弃尾成员

* **类型:** `方法`
* **名称:** `抛弃尾成员`
* **描述:** 删除数组尾部的单个成员

##### 火山.基本.基本类型数组模板类.取尾成员

* **类型:** `方法`
* **名称:** `取尾成员`
* **返回值数据类型:** `模板类型1`
* **描述:** 返回数组尾部的单个成员值. 注意: 执行本方法前必须确保数组不为空

##### 火山.基本.基本类型数组模板类.查找首成员

* **类型:** `方法`
* **名称:** `查找首成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲查找的成员值` (`模板类型1`)
* **描述:** 正向查找等于所指定值的第一个成员,找到返回其索引位置,未找到返回-1.

##### 火山.基本.基本类型数组模板类.所指定值是否存在

* **类型:** `方法`
* **名称:** `所指定值是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲查找的成员值` (`模板类型1`)
* **描述:** 返回数组中是否存在为所指定值的成员

##### 火山.基本.基本类型数组模板类.查找尾成员

* **类型:** `方法`
* **名称:** `查找尾成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲查找的成员值` (`模板类型1`)
* **描述:** 逆向查找等于所指定值的最后一个成员,找到返回其索引位置,未找到返回-1.

##### 火山.基本.基本类型数组模板类.替换成员值

* **类型:** `方法`
* **名称:** `替换成员值`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲替换的成员值` (`模板类型1`)
	* `所替换到的成员值` (`模板类型1`)
* **描述:** 将所有等于指定值的成员替换为另一个值,返回是否至少进行了一次替换操作.

##### 火山.基本.基本类型数组模板类.是否相等

* **类型:** `方法`
* **名称:** `是否相等`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲比较的数组` (`基本类型数组模板类`)
* **描述:** 返回所指定数组的内容是否与本数组相同

##### 火山.基本.基本类型数组模板类.排序

* **类型:** `方法`
* **名称:** `排序`
* **参数:**
	* `从小到大排序` (`逻辑型`, 默认值: `真`): 为真表示从小到大进行排序,为假表示从大到小进行排序.
* **描述:** 对数组中的所有成员进行排序

##### 火山.基本.基本类型数组模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本数组中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本数组中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

##### 火山.基本.基本类型数组模板类.流读入

* **类型:** `方法`
* **名称:** `流读入`
* **参数:**
	* `流对象` (`输入流类`): 提供欲从其中读入本对象数据内容的输入流
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 从所指定的流对象中读入本对象的数据

##### 火山.基本.基本类型数组模板类.流写出

* **类型:** `方法`
* **名称:** `流写出`
* **参数:**
	* `流对象` (`输出流类`): 提供欲将本对象数据内容写出到其中的输出流
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象的数据写入所指定的流对象中

---

#### 火山.基本.基本类型值数组模板类

* **类型:** `类`
* **名称:** `基本类型值数组模板类`
* **基础类:** `基本类型数组模板类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数组操作.模板类`
* **描述:** 使用本模板基础类的数组类将使用值内容复制的方式传递数组数据. 即: 执行类似赋值操作"变量数组1 = 变量数组2"后,变量数组1中将获得变量数组2中的所有数组数据的一个完全独立拷贝,修改变量数组1的内容不会对变量数组2造成影响. 模板类型2: 对应的参考类型数组数据类型

##### 火山.基本.基本类型值数组模板类.取参考数组

* **类型:** `方法`
* **名称:** `取参考数组`
* **参数:**
	* `数据接收数组` (`模板类型2`): 提供用作接收被复制数据的参考类型数组
* **描述:** 将本数组的内容复制到一个对应的参考类型组中

---

#### 火山.基本.字节数组类

* **类型:** `类`
* **名称:** `字节数组类`
* **模板基础类:** `基本类型值数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节`; `模板类型2` -> `字节参考数组类`
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.短整数数组类

* **类型:** `类`
* **名称:** `短整数数组类`
* **模板基础类:** `基本类型值数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `短整数`; `模板类型2` -> `短整数参考数组类`
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.字符数组类

* **类型:** `类`
* **名称:** `字符数组类`
* **模板基础类:** `基本类型值数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字符`; `模板类型2` -> `字符参考数组类`
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.整数数组类

* **类型:** `类`
* **名称:** `整数数组类`
* **模板基础类:** `基本类型值数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`; `模板类型2` -> `整数参考数组类`
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

---

#### 火山.基本.变整数数组类

* **类型:** `类`
* **名称:** `变整数数组类`
* **模板基础类:** `基本类型值数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `变整数`; `模板类型2` -> `变整数参考数组类`
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.长整数数组类

* **类型:** `类`
* **名称:** `长整数数组类`
* **模板基础类:** `基本类型值数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `长整数`; `模板类型2` -> `长整数参考数组类`
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.单精度小数数组类

* **类型:** `类`
* **名称:** `单精度小数数组类`
* **模板基础类:** `基本类型值数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `单精度小数`; `模板类型2` -> `单精度小数参考数组类`

---

#### 火山.基本.小数数组类

* **类型:** `类`
* **名称:** `小数数组类`
* **模板基础类:** `基本类型值数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `小数`; `模板类型2` -> `小数参考数组类`
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

---

#### 火山.基本.逻辑型数组类

* **类型:** `类`
* **名称:** `逻辑型数组类`
* **模板基础类:** `基本类型值数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `逻辑型`; `模板类型2` -> `逻辑型参考数组类`
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.基本类型参考数组模板类

* **类型:** `类`
* **名称:** `基本类型参考数组模板类`
* **基础类:** `基本类型数组模板类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数组操作.模板类`
* **描述:** 使用本模板基础类的数组类将使用参考的方式传递数组数据. 即: 执行类似赋值操作"变量数组1 = 变量数组2"后,变量数组1将与变量数组2指向同一份数组数据,对两个变量进行数组操作将基于同一份实际数组数据. 数组以参考方式赋值要比完全的值内容复制快得多,但是需要了解两种方式的不同性. 需要注意的是: 无论哪种类型的数组,在传递到方法参数上时,均采用参考方式传递. 模板类型2: 对应的值传递类型数组数据类型

##### 火山.基本.基本类型参考数组模板类.取值数组

* **类型:** `方法`
* **名称:** `取值数组`
* **参数:**
	* `数据接收数组` (`模板类型2`): 提供用作接收被复制数据的值传递类型数组
* **描述:** 将本数组的内容复制到一个对应的值传递类型组中

---

#### 火山.基本.字节参考数组类

* **类型:** `类`
* **名称:** `字节参考数组类`
* **模板基础类:** `基本类型参考数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节`; `模板类型2` -> `字节数组类`

---

#### 火山.基本.短整数参考数组类

* **类型:** `类`
* **名称:** `短整数参考数组类`
* **模板基础类:** `基本类型参考数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `短整数`; `模板类型2` -> `短整数数组类`

---

#### 火山.基本.字符参考数组类

* **类型:** `类`
* **名称:** `字符参考数组类`
* **模板基础类:** `基本类型参考数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字符`; `模板类型2` -> `字符数组类`

---

#### 火山.基本.整数参考数组类

* **类型:** `类`
* **名称:** `整数参考数组类`
* **模板基础类:** `基本类型参考数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `整数`; `模板类型2` -> `整数数组类`

---

#### 火山.基本.变整数参考数组类

* **类型:** `类`
* **名称:** `变整数参考数组类`
* **模板基础类:** `基本类型参考数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `变整数`; `模板类型2` -> `变整数数组类`

---

#### 火山.基本.长整数参考数组类

* **类型:** `类`
* **名称:** `长整数参考数组类`
* **模板基础类:** `基本类型参考数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `长整数`; `模板类型2` -> `长整数数组类`

---

#### 火山.基本.单精度小数参考数组类

* **类型:** `类`
* **名称:** `单精度小数参考数组类`
* **模板基础类:** `基本类型参考数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `单精度小数`; `模板类型2` -> `单精度小数数组类`

---

#### 火山.基本.小数参考数组类

* **类型:** `类`
* **名称:** `小数参考数组类`
* **模板基础类:** `基本类型参考数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `小数`; `模板类型2` -> `小数数组类`

---

#### 火山.基本.逻辑型参考数组类

* **类型:** `类`
* **名称:** `逻辑型参考数组类`
* **模板基础类:** `基本类型参考数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `逻辑型`; `模板类型2` -> `逻辑型数组类`

---

#### 火山.基本.文本数组模板类

* **类型:** `类`
* **名称:** `文本数组模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `未公开`(无法在所处包外部使用,其中的内容只能通过此类的继承类对外提供)
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数组操作.模板类`
* **描述:** 用作动态管理文本型数组数据的模板基础类

##### 火山.基本.文本数组模板类.预分配尺寸

* **类型:** `属性读方法`
* **名称:** `预分配尺寸`
* **返回值数据类型:** `整数`
* **描述:** 返回本数组为了快速进行数组成员的添加/删除处理使用的空间分配尺寸,每次数组需要调整其空间大小时,都使用本属性值乘于单个数组成员尺寸作为空间调整基准尺寸.值越大,批量加入/删除数组成员时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.

##### 火山.基本.文本数组模板类.预分配尺寸

* **类型:** `属性写方法`
* **名称:** `预分配尺寸`
* **参数:**
	* `所欲设置的预分配尺寸` (`整数`)
* **描述:** 设置本数组为了快速进行数组成员的添加/删除处理使用的空间分配尺寸,每次数组需要调整其空间大小时,都使用本属性值乘于单个数组成员尺寸作为空间调整基准尺寸.值越大,批量加入/删除数组成员时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.

##### 火山.基本.文本数组模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-邮件发送-send_email-main](#vol-邮件发送-send_email-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-mysql连接池-mysql_connectionpool-main](#vol-mysql连接池-mysql_connectionpool-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main)

##### 火山.基本.文本数组模板类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个逆向循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.

##### 火山.基本.文本数组模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `文本型`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.文本数组模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到的成员值,如果有多层本类或本类继承类的循环嵌套,本方法将返回所处最近层循环的枚举成员值.
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-邮件发送-send_email-main](#vol-邮件发送-send_email-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-mysql连接池-mysql_connectionpool-main](#vol-mysql连接池-mysql_connectionpool-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main)

##### 火山.基本.文本数组模板类.取枚举索引

* **类型:** `方法`
* **名称:** `取枚举索引`
* **返回值数据类型:** `整数`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.文本数组模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到成员的索引位置,如果有多层本类或本类继承类的循环嵌套,本方法将返回所处最近层循环枚举到成员的索引位置.
* **相关例程:** [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main)

##### 火山.基本.文本数组模板类.索引是否有效

* **类型:** `方法`
* **名称:** `索引是否有效`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的索引值` (`整数`)
* **描述:** 返回所指定的索引值是否大于等于0且小于本数组的成员数

##### 火山.基本.文本数组模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回数组中的当前已有成员数目
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-json数据访问-json-main](#vol-json数据访问-json-main), [vol-正则表达式-deelx_regular-main](#vol-正则表达式-deelx_regular-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-邮件发送-send_email-main](#vol-邮件发送-send_email-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.文本数组模板类.取最大索引

* **类型:** `方法`
* **名称:** `取最大索引`
* **返回值数据类型:** `整数`
* **描述:** 返回数组中尾成员的索引位置

##### 火山.基本.文本数组模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本数组是否为空

##### 火山.基本.文本数组模板类.删除所有成员

* **类型:** `方法`
* **名称:** `删除所有成员`
* **描述:** 删除数组中的当前所有成员
* **相关例程:** [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main)

##### 火山.基本.文本数组模板类.取成员

* **类型:** `方法`
* **名称:** `取成员`
* **返回值数据类型:** `文本型`
* **参数:**
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
* **描述:** 返回所指定索引位置处的成员值
* **相关例程:** [vol-表格-grid-main](#vol-表格-grid-main), [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-json数据访问-json-main](#vol-json数据访问-json-main), [vol-正则表达式-deelx_regular-main](#vol-正则表达式-deelx_regular-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-tcp转发-tcp_forward-main](#vol-tcp转发-tcp_forward-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-yolov5目标检测-yolov5-main](#vol-yolov5目标检测-yolov5-main)

##### 火山.基本.文本数组模板类.交换成员

* **类型:** `方法`
* **名称:** `交换成员`
* **参数:**
	* `索引位置1` (`整数`): 提供成员1的索引位置,必须大于等于0且小于数组成员数目.
	* `索引位置2` (`整数`): 提供成员2的索引位置,必须大于等于0且小于数组成员数目.
* **描述:** 将两个索引位置处的成员值相互交换

##### 火山.基本.文本数组模板类.添加数组

* **类型:** `方法`
* **名称:** `添加数组`
* **参数:**
	* `所欲添加的数组` (`文本数组模板类`)
* **描述:** 将另一个文本数组的内容添加到本数组尾部

##### 火山.基本.文本数组模板类.添加数组独有成员

* **类型:** `方法`
* **名称:** `添加数组独有成员`
* **参数:**
	* `所欲添加的数组` (`文本数组模板类`)
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定判断文本是否相等时是否区分英文字母的大小写
* **描述:** 将另一个文本数组中在本数组内不存在的成员添加到本数组尾部

##### 火山.基本.文本数组模板类.对比删除重复成员

* **类型:** `方法`
* **名称:** `对比删除重复成员`
* **参数:**
	* `所欲检查的数组` (`文本数组模板类`): 提供用作检查重复成员的文本数组
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定判断文本是否相等时是否区分英文字母的大小写
* **描述:** 将本数组中在"所欲检查的数组"内已经存在的成员删除掉

##### 火山.基本.文本数组模板类.从数组复制

* **类型:** `方法`
* **名称:** `从数组复制`
* **参数:**
	* `所欲复制的数组` (`文本数组模板类`)
* **描述:** 清空本数组的原有内容,将另一个文本数组的内容添加到本数组中.

##### 火山.基本.文本数组模板类.删除成员

* **类型:** `方法`
* **名称:** `删除成员`
* **参数:**
	* `删除索引位置` (`整数`): 提供所欲删除成员的索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲删除成员数目` (`整数`, 默认值: `1`): 提供所欲删除成员的数目,必须大于等于0且加上"删除索引位置"参数值后小于等于数组成员数目.
* **描述:** 删除数组中所指定索引位置处的成员
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main)

##### 火山.基本.文本数组模板类.查找删除成员

* **类型:** `方法`
* **名称:** `查找删除成员`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲查找文本` (`文本型`): 提供所欲查找并删除的成员值
* **描述:** 查找第一个等于所指定值的成员,如果找到则将其删除并返回真,否则返回假.

##### 火山.基本.文本数组模板类.置成员值

* **类型:** `方法`
* **名称:** `置成员值`
* **参数:**
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
	* `所欲设置的值` (`文本型`): 提供所欲设置的成员值,先前的值将被覆盖.
* **描述:** 设置数组中所指定索引位置处的成员值

##### 火山.基本.文本数组模板类.加入成员

* **类型:** `方法`
* **名称:** `加入成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲添加成员值` (`文本型`, `可扩展`)
* **描述:** 将一个或多个文本值加入到本数组的尾部
* **返回值描述:** 返回所加入的第一个文本值在数组中的记录索引位置
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.文本数组模板类.插入成员

* **类型:** `方法`
* **名称:** `插入成员`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入的成员值` (`文本型`)
* **描述:** 将所指定的成员值插入到所指定的索引位置

##### 火山.基本.文本数组模板类.查找首成员

* **类型:** `方法`
* **名称:** `查找首成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲查找的成员值` (`文本型`)
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定判断文本是否相等时是否区分英文字母的大小写
* **描述:** 正向查找等于所指定值的第一个成员,找到返回其索引位置,未找到返回-1.

##### 火山.基本.文本数组模板类.所指定值是否存在

* **类型:** `方法`
* **名称:** `所指定值是否存在`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲查找的成员值` (`文本型`)
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定判断文本是否相等时是否区分英文字母的大小写
* **描述:** 返回数组中是否存在为所指定值的成员

##### 火山.基本.文本数组模板类.查找尾成员

* **类型:** `方法`
* **名称:** `查找尾成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲查找的成员值` (`文本型`)
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定判断文本是否相等时是否区分英文字母的大小写
* **描述:** 逆向查找等于所指定值的最后一个成员,找到返回其索引位置,未找到返回-1.

##### 火山.基本.文本数组模板类.替换成员值

* **类型:** `方法`
* **名称:** `替换成员值`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲替换的成员值` (`文本型`)
	* `所替换到的成员值` (`文本型`)
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定判断文本是否相等时是否区分英文字母的大小写
* **描述:** 将所有等于指定值的成员替换为另一个值,返回是否至少进行了一次替换操作.

##### 火山.基本.文本数组模板类.是否相等

* **类型:** `方法`
* **名称:** `是否相等`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲比较的数组` (`文本数组模板类`)
	* `是否区分大小写` (`逻辑型`, 默认值: `真`): 指定判断文本是否相等时是否区分英文字母的大小写
* **描述:** 返回所指定数组的内容是否与本数组相同

##### 火山.基本.文本数组模板类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本数组中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本数组中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

##### 火山.基本.文本数组模板类.流读入

* **类型:** `方法`
* **名称:** `流读入`
* **参数:**
	* `流对象` (`输入流类`): 提供欲从其中读入本对象数据内容的输入流
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 从所指定的流对象中读入本对象的数据

##### 火山.基本.文本数组模板类.流写出

* **类型:** `方法`
* **名称:** `流写出`
* **参数:**
	* `流对象` (`输出流类`): 提供欲将本对象数据内容写出到其中的输出流
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象的数据写入所指定的流对象中

---

#### 火山.基本.文本数组类

* **类型:** `类`
* **名称:** `文本数组类`
* **基础类:** `文本数组模板类`
* **描述:** 本文本数组类将使用值内容复制的方式传递数组数据. 即: 执行类似赋值操作"变量数组1 = 变量数组2"后,变量数组1中将获得变量数组2中的所有数组数据的一个完全独立拷贝,修改变量数组1的内容不会对变量数组2造成影响.
* **相关例程:** [vol-表格-grid-main](#vol-表格-grid-main), [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-空对象测试-null_object_test-main](#vol-空对象测试-null_object_test-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-json数据访问-json-main](#vol-json数据访问-json-main), [vol-正则表达式-deelx_regular-main](#vol-正则表达式-deelx_regular-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-tcp转发-tcp_forward-main](#vol-tcp转发-tcp_forward-main), [vol-邮件发送-send_email-main](#vol-邮件发送-send_email-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-mysql连接池-mysql_connectionpool-main](#vol-mysql连接池-mysql_connectionpool-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-yolov5目标检测-yolov5-main](#vol-yolov5目标检测-yolov5-main)

##### 火山.基本.文本数组类.取参考数组

* **类型:** `方法`
* **名称:** `取参考数组`
* **参数:**
	* `数据接收数组` (`文本参考数组类`): 提供用作接收被复制数据的参考类型数组
* **描述:** 将本数组的内容复制到一个对应的参考类型组中

---

#### 火山.基本.文本参考数组类

* **类型:** `类`
* **名称:** `文本参考数组类`
* **基础类:** `文本数组模板类`
* **描述:** 本文本数组类将使用参考的方式传递数组数据. 即: 执行类似赋值操作"变量数组1 = 变量数组2"后,变量数组1将与变量数组2指向同一份数组数据,对两个变量进行数组操作将基于同一份实际数组数据. 数组以参考方式赋值要比完全的值内容复制快得多,但是需要了解两种方式的不同性. 需要注意的是: 无论哪种类型的数组,在传递到方法参数上时,均采用参考方式传递.
* **相关例程:** [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main)

##### 火山.基本.文本参考数组类.取值数组

* **类型:** `方法`
* **名称:** `取值数组`
* **参数:**
	* `数据接收数组` (`文本数组类`): 提供用作接收被复制数据的值传递类型数组
* **描述:** 将本数组的内容复制到一个对应的值传递类型组中

---

#### 火山.基本.文本排序数组类

* **类型:** `类`
* **名称:** `文本排序数组类`
* **基础类:** `扩展对象类`
* **描述:** 用作动态管理文本型数组数据并对其自动排序. 本文本数组类将使用值内容复制的方式传递数组数据. 即: 执行类似赋值操作"变量数组1 = 变量数组2"后,变量数组1中将获得变量数组2中的所有数组数据的一个完全独立拷贝,修改变量数组1的内容不会对变量数组2造成影响. 本数组类中对文本进行比较时区分大小写.
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

##### 火山.基本.文本排序数组类.预分配尺寸

* **类型:** `属性读方法`
* **名称:** `预分配尺寸`
* **返回值数据类型:** `整数`
* **描述:** 返回本数组为了快速进行数组成员的添加/删除处理使用的空间分配尺寸,每次数组需要调整其空间大小时,都使用本属性值乘于单个数组成员尺寸作为空间调整基准尺寸.值越大,批量加入/删除数组成员时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.

##### 火山.基本.文本排序数组类.预分配尺寸

* **类型:** `属性写方法`
* **名称:** `预分配尺寸`
* **参数:**
	* `所欲设置的预分配尺寸` (`整数`)
* **描述:** 设置本数组为了快速进行数组成员的添加/删除处理使用的空间分配尺寸,每次数组需要调整其空间大小时,都使用本属性值乘于单个数组成员尺寸作为空间调整基准尺寸.值越大,批量加入/删除数组成员时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.

##### 火山.基本.文本排序数组类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.

##### 火山.基本.文本排序数组类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个逆向循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.

##### 火山.基本.文本排序数组类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `文本型`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.文本排序数组类.枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到的成员值,如果有多层本类或本类继承类的循环嵌套,本方法将返回所处最近层循环的枚举成员值.

##### 火山.基本.文本排序数组类.取枚举索引

* **类型:** `方法`
* **名称:** `取枚举索引`
* **返回值数据类型:** `整数`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.文本排序数组类.枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到成员的索引位置,如果有多层本类或本类继承类的循环嵌套,本方法将返回所处最近层循环枚举到成员的索引位置.

##### 火山.基本.文本排序数组类.索引是否有效

* **类型:** `方法`
* **名称:** `索引是否有效`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的索引值` (`整数`)
* **描述:** 返回所指定的索引值是否大于等于0且小于本数组的成员数

##### 火山.基本.文本排序数组类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回数组中的当前已有成员数目

##### 火山.基本.文本排序数组类.取最大索引

* **类型:** `方法`
* **名称:** `取最大索引`
* **返回值数据类型:** `整数`
* **描述:** 返回数组中尾成员的索引位置

##### 火山.基本.文本排序数组类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本数组是否为空

##### 火山.基本.文本排序数组类.删除所有成员

* **类型:** `方法`
* **名称:** `删除所有成员`
* **描述:** 删除数组中的当前所有成员

##### 火山.基本.文本排序数组类.删除成员

* **类型:** `方法`
* **名称:** `删除成员`
* **参数:**
	* `删除索引位置` (`整数`): 提供所欲删除成员的索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲删除成员数目` (`整数`, 默认值: `1`): 提供所欲删除成员的数目,必须大于等于0且加上"删除索引位置"参数值后小于等于数组成员数目.
* **描述:** 删除数组中所指定索引位置处的成员

##### 火山.基本.文本排序数组类.取成员

* **类型:** `方法`
* **名称:** `取成员`
* **返回值数据类型:** `文本型`
* **参数:**
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
* **描述:** 返回所指定索引位置处的成员值

##### 火山.基本.文本排序数组类.从数组复制

* **类型:** `方法`
* **名称:** `从数组复制`
* **参数:**
	* `所欲复制的数组` (`文本排序数组类`)
* **描述:** 清空本数组的原有内容,将另一个文本数组的内容添加到本数组中.

##### 火山.基本.文本排序数组类.从无序数组复制

* **类型:** `方法`
* **名称:** `从无序数组复制`
* **参数:**
	* `所欲复制的数组` (`文本数组类`): 提供所欲复制的数组数据内容
* **描述:** 从一个非排序文本数组复制内容,然后将其进行排序.

##### 火山.基本.文本排序数组类.从无序参考数组复制

* **类型:** `方法`
* **名称:** `从无序参考数组复制`
* **参数:**
	* `所欲复制的数组` (`文本参考数组类`): 提供所欲复制的数组数据内容
* **描述:** 从一个非排序文本数组复制内容,然后将其进行排序.

##### 火山.基本.文本排序数组类.从无序数组独有复制

* **类型:** `方法`
* **名称:** `从无序数组独有复制`
* **参数:**
	* `所欲复制的数组` (`文本数组类`): 提供所欲复制的数组数据内容
* **描述:** 从一个非排序文本数组复制内容,然后将其进行排序并删除重复的数组成员.

##### 火山.基本.文本排序数组类.从无序参考数组独有复制

* **类型:** `方法`
* **名称:** `从无序参考数组独有复制`
* **参数:**
	* `所欲复制的数组` (`文本参考数组类`): 提供所欲复制的数组数据内容
* **描述:** 从一个非排序文本数组复制内容,然后将其进行排序并删除重复的数组成员.

##### 火山.基本.文本排序数组类.输出无序数组

* **类型:** `方法`
* **名称:** `输出无序数组`
* **参数:**
	* `所输出到的数组` (`文本数组类`)
* **描述:** 将本对象的数组内容复制到所指定的无序数组中

##### 火山.基本.文本排序数组类.输出参考无序数组

* **类型:** `方法`
* **名称:** `输出参考无序数组`
* **参数:**
	* `所输出到的数组` (`文本参考数组类`)
* **描述:** 将本对象的数组内容复制到所指定的无序参考数组中

##### 火山.基本.文本排序数组类.是否相等

* **类型:** `方法`
* **名称:** `是否相等`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲比较的数组` (`文本排序数组类`)
* **描述:** 返回所指定数组的内容是否与本数组相同. 是否区分英文字母大小写由本文本数组类的继承类具体特性决定.

##### 火山.基本.文本排序数组类.加入成员

* **类型:** `方法`
* **名称:** `加入成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲添加成员值` (`文本型`, `可扩展`)
* **描述:** 将一个或多个文本值加入到本数组中
* **返回值描述:** 返回所加入的文本值在数组中的记录索引位置,具体位置由排序算法决定. 注意: 1.如果本对象实例为"文本独有数组类"或"大小写无关文本独有数组类",则当所欲添加的第一个文本值在数组中已经存在时,将返回-1; 2.如果添加进了新的成员,本方法返回的所加入成员对应的索引位置可能发生改变; 3.如果同时添加了多个文本值,则本方法的返回值没有意义(因为首文本值记录位置可能会被后面加入的文本值改变).
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

##### 火山.基本.文本排序数组类.查找成员

* **类型:** `方法`
* **名称:** `查找成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲查找的成员值` (`文本型`)
* **描述:** 查找等于所指定值的成员,找到返回其索引位置,未找到返回-1. 注意: 1.所找到的可能并非第一个等于该值的成员; 2.如果添加进了新的成员,本方法所返回的成员对应索引位置可能发生改变.

##### 火山.基本.文本排序数组类.查找首成员

* **类型:** `方法`
* **名称:** `查找首成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲查找的成员值` (`文本型`)
* **描述:** 正向查找等于所指定值的第一个成员,找到返回其索引位置,未找到返回-1. 注意: 如果添加进了新的成员,本方法所返回的成员对应索引位置可能发生改变.

##### 火山.基本.文本排序数组类.查找尾成员

* **类型:** `方法`
* **名称:** `查找尾成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲查找的成员值` (`文本型`)
* **描述:** 逆向查找等于所指定值的最后一个成员,找到返回其索引位置,未找到返回-1. 注意: 如果添加进了新的成员,本方法所返回的成员对应索引位置可能发生改变.

##### 火山.基本.文本排序数组类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本数组中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本数组中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

##### 火山.基本.文本排序数组类.流读入

* **类型:** `方法`
* **名称:** `流读入`
* **参数:**
	* `流对象` (`输入流类`): 提供欲从其中读入本对象数据内容的输入流
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 从所指定的流对象中读入本对象的数据

##### 火山.基本.文本排序数组类.流写出

* **类型:** `方法`
* **名称:** `流写出`
* **参数:**
	* `流对象` (`输出流类`): 提供欲将本对象数据内容写出到其中的输出流
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象的数据写入所指定的流对象中

---

#### 火山.基本.大小写无关文本排序数组类

* **类型:** `类`
* **名称:** `大小写无关文本排序数组类`
* **基础类:** `文本排序数组类`
* **描述:** 用作动态管理文本型数组数据并对其自动排序. 本文本数组类将使用值内容复制的方式传递数组数据. 即: 执行类似赋值操作"变量数组1 = 变量数组2"后,变量数组1中将获得变量数组2中的所有数组数据的一个完全独立拷贝,修改变量数组1的内容不会对变量数组2造成影响. 本数组类中对文本进行比较时不区分大小写.

---

#### 火山.基本.文本独有数组类

* **类型:** `类`
* **名称:** `文本独有数组类`
* **基础类:** `文本排序数组类`
* **描述:** 用作动态管理文本型数组数据并对其自动排序,相同的成员在本数组内只能加入一次. 本文本数组类将使用值内容复制的方式传递数组数据. 即: 执行类似赋值操作"变量数组1 = 变量数组2"后,变量数组1中将获得变量数组2中的所有数组数据的一个完全独立拷贝,修改变量数组1的内容不会对变量数组2造成影响. 本数组类中对文本进行比较时区分大小写.
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

##### 火山.基本.文本独有数组类.加入独有成员

* **类型:** `方法`
* **名称:** `加入独有成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲添加成员值` (`文本型`): 提供所欲添加的成员值
	* `所加入成员索引位置` (`整数类`): 如果所欲加入成员值已经存在,则在其中返回现有成员的索引位置,如果不存在,则在其中返回本次所添加到的索引位置.
* **描述:** 将一个所指定类型的成员值加入到本数组中
* **返回值描述:** 返回所加入成员在数组中的记录索引位置,具体位置由排序算法决定. 注意: 如果所欲添加成员值在数组中已经存在时,将返回-1.

---

#### 火山.基本.大小写无关文本独有数组类

* **类型:** `类`
* **名称:** `大小写无关文本独有数组类`
* **基础类:** `文本独有数组类`
* **描述:** 用作动态管理文本型数组数据并对其自动排序,相同的成员在本数组内只能加入一次. 本文本数组类将使用值内容复制的方式传递数组数据. 即: 执行类似赋值操作"变量数组1 = 变量数组2"后,变量数组1中将获得变量数组2中的所有数组数据的一个完全独立拷贝,修改变量数组1的内容不会对变量数组2造成影响. 本数组类中对文本进行比较时不区分大小写.

---

#### 火山.基本.对象数组模板类

* **类型:** `类`
* **名称:** `对象数组模板类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数组操作.模板类`
* **描述:** 用作动态管理数据类型为"对象类"或其继承类的数组数据 模板类型1: 具体的对象类数据类型
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.预分配尺寸

* **类型:** `属性读方法`
* **名称:** `预分配尺寸`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
* **特性:**
	* `静态`
* **描述:** 返回本数组为了快速进行数组成员的添加/删除处理使用的空间分配尺寸,每次数组需要调整其空间大小时,都使用本属性值乘于单个数组成员尺寸作为空间调整基准尺寸.值越大,批量加入/删除数组成员时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.预分配尺寸

* **类型:** `属性写方法`
* **名称:** `预分配尺寸`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲设置的预分配尺寸` (`整数`)
* **特性:**
	* `静态`
* **描述:** 设置本数组为了快速进行数组成员的添加/删除处理使用的空间分配尺寸,每次数组需要调整其空间大小时,都使用本属性值乘于单个数组成员尺寸作为空间调整基准尺寸.值越大,批量加入/删除数组成员时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.对象数组模板类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
* **特性:**
	* `静态`
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个逆向循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.对象数组模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象数组模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到的成员值,如果有多层本类或本类继承类的循环嵌套,本方法将返回所处最近层循环的枚举成员值.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.对象数组模板类.取枚举索引

* **类型:** `方法`
* **名称:** `取枚举索引`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象数组模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到成员的索引位置,如果有多层本类或本类继承类的循环嵌套,本方法将返回所处最近层循环枚举到成员的索引位置.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.对象数组模板类.索引是否有效

* **类型:** `方法`
* **名称:** `索引是否有效`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲检查的索引值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 返回所指定的索引值是否大于等于0且小于本数组的成员数
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
* **特性:**
	* `静态`
* **描述:** 返回数组中的当前已有成员数目
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.对象数组模板类.取最大索引

* **类型:** `方法`
* **名称:** `取最大索引`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
* **特性:**
	* `静态`
* **描述:** 返回数组中尾成员的索引位置
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
* **特性:**
	* `静态`
* **描述:** 返回本数组是否为空
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.删除所有成员

* **类型:** `方法`
* **名称:** `删除所有成员`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
* **特性:**
	* `静态`
* **描述:** 删除数组中的当前所有成员
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.对象数组模板类.取成员

* **类型:** `方法`
* **名称:** `取成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
* **特性:**
	* `静态`
* **描述:** 返回所指定索引位置处成员对象的参考. 注意: 如果所获取对象成员需要动态挂接事件,请按类似以下格式挂接: 挂接事件 ((对象实际数据类型)数组1.取成员 (索引位置)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.对象数组模板类.交换成员

* **类型:** `方法`
* **名称:** `交换成员`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `索引位置1` (`整数`): 提供成员1的索引位置,必须大于等于0且小于数组成员数目.
	* `索引位置2` (`整数`): 提供成员2的索引位置,必须大于等于0且小于数组成员数目.
* **特性:**
	* `静态`
* **描述:** 将两个索引位置处的成员值相互交换
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.添加数组

* **类型:** `方法`
* **名称:** `添加数组`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲添加的数组` (`对象数组模板类`): 提供所欲加入的对象数组
* **特性:**
	* `静态`
* **描述:** 将另一个对象数组的内容添加到本数组尾部
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.从数组复制

* **类型:** `方法`
* **名称:** `从数组复制`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲复制的数组` (`对象数组模板类`): 提供所欲复制到本数组的对象数组
* **特性:**
	* `静态`
* **描述:** 清空本数组的原有内容,将另一个数组数组的内容添加到本数组中. 注: 直接使用赋值操作也可以达到同样的效果.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.删除成员

* **类型:** `方法`
* **名称:** `删除成员`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `删除索引位置` (`整数`): 提供所欲删除成员的索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲删除成员数目` (`整数`, 默认值: `1`): 提供所欲删除成员的数目,必须大于等于0且加上"删除索引位置"参数值后小于等于数组成员数目.
* **特性:**
	* `静态`
* **描述:** 删除数组中所指定索引位置处的成员
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.置成员值

* **类型:** `方法`
* **名称:** `置成员值`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
	* `所欲设置的值` (`模板类型1`): 提供所欲设置的成员值,该对象将被复制一份后覆盖到所指定的索引位置.
* **特性:**
	* `静态`
* **描述:** 设置数组中所指定索引位置处的成员值
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.加入成员

* **类型:** `方法`
* **名称:** `加入成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲添加成员值` (`模板类型1`): 提供所欲加入的对象值,该对象将被复制一份后加入到本数组中.
* **特性:**
	* `静态`
* **描述:** 将所指定的对象复制一份后加入到本数组中,返回所加入成员的索引位置.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.对象数组模板类.加入并返回成员

* **类型:** `方法`
* **名称:** `加入并返回成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲添加成员值` (`模板类型1`): 提供所欲加入的对象值,该对象将被复制一份后加入到本数组中.
* **特性:**
	* `静态`
* **描述:** 将所指定的对象复制一份后加入到本数组中,返回所加入复制对象的参考. 注意: 如果所返回对象成员需要动态挂接事件,请按类似以下格式挂接: 挂接事件 ((对象实际数据类型)数组1.加入并返回成员 (...)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.加入并返回成员2

* **类型:** `方法`
* **名称:** `加入并返回成员2`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲添加成员值` (`模板类型1`): 提供所欲加入的对象值,该对象将被复制一份后加入到本数组中.
	* `所加入索引位置` (`整数类`): 在其中返回所加入新对象在数组中的索引位置
* **特性:**
	* `静态`
* **描述:** 将所指定的对象复制一份后加入到本数组中,返回所加入复制对象的参考. 注意: 如果所返回对象成员需要动态挂接事件,请按类似以下格式挂接: 挂接事件 ((对象实际数据类型)数组1.加入并返回成员2 (...)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.加入新成员

* **类型:** `方法`
* **名称:** `加入新成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲添加对象的类型` (`模板类型1(需求:数据类型)`): 提供所欲新建并加入对象的数据类型
	* `用户标记值` (`变整数`, 默认值: `0`): 提供欲置入到新建对象中的用户标记值
* **特性:**
	* `静态`
* **描述:** 建立所指定类的一个实例对象并将其加入到本数组中,返回所加入成员的索引位置.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.批量加入新成员

* **类型:** `方法`
* **名称:** `批量加入新成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲添加对象的类型` (`模板类型1(需求:数据类型)`): 提供所欲新建并加入对象的数据类型
	* `所欲加入成员的数目` (`整数`, 默认值: `1`): 提供所欲加入的新建对象的数目
	* `用户标记值` (`变整数`, 默认值: `0`): 提供欲置入到新建对象中的用户标记值
* **特性:**
	* `静态`
* **描述:** 建立所指定类的一个或多个实例对象并将其加入到本数组中,返回所加入成员的首索引位置.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.重置数组

* **类型:** `方法`
* **名称:** `重置数组`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲填入对象的类型` (`模板类型1(需求:数据类型)`): 提供所欲填入到被重置数组中的新建对象的数据类型
	* `欲重置的成员数目` (`整数`)
	* `用户标记值` (`变整数`, 默认值: `0`): 提供欲置入到新建对象中的用户标记值
* **特性:**
	* `静态`
* **描述:** 重置数组中的成员数为所指定的数目,并清零所有成员值.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.加入并返回新成员

* **类型:** `方法`
* **名称:** `加入并返回新成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲添加对象的类型` (`模板类型1(需求:数据类型)`): 提供所欲新建并加入对象的数据类型
	* `用户标记值` (`变整数`, 默认值: `0`): 提供欲置入到新建对象中的用户标记值
* **特性:**
	* `静态`
* **描述:** 建立所指定类的一个实例对象并将其加入到本数组中,返回所加入对象的参考. 注意: 如果所创建对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 ((对象数据类型)数组1.加入并返回新成员 (对象数据类型)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.加入并返回新成员2

* **类型:** `方法`
* **名称:** `加入并返回新成员2`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲添加对象的类型` (`模板类型1(需求:数据类型)`): 提供所欲新建并加入对象的数据类型
	* `用户标记值` (`变整数`, 默认值: `0`): 提供欲置入到新建对象中的用户标记值
	* `所加入索引位置` (`整数类`): 在其中返回所加入新对象在数组中的索引位置
* **特性:**
	* `静态`
* **描述:** 建立所指定类的一个实例对象并将其加入到本数组中,返回所加入对象的参考. 注意: 如果所创建对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 ((对象数据类型)数组1.加入并返回新成员2 (对象数据类型, ...)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.插入成员

* **类型:** `方法`
* **名称:** `插入成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入成员值` (`模板类型1`): 提供所欲插入的对象值,该对象将被复制一份后插入到本数组中.
* **特性:**
	* `静态`
* **描述:** 将所指定的对象复制一份后插入到本数组中的指定索引位置,返回所插入复制对象的参考. 注意: 如果所插入对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 ((对象实际数据类型)数组1.插入成员 (...)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.插入新成员

* **类型:** `方法`
* **名称:** `插入新成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入对象的类型` (`模板类型1(需求:数据类型)`): 提供所欲新建并插入对象的数据类型
	* `用户标记值` (`变整数`, 默认值: `0`): 提供欲置入到新建对象中的用户标记值
* **特性:**
	* `静态`
* **描述:** 建立所指定类的一个实例对象并将其插入到本数组中的指定索引位置,返回所插入对象的参考. 注意: 如果所创建对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 ((对象数据类型)数组1.插入新成员 (索引位置, 对象数据类型)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.为指定类

* **类型:** `方法`
* **名称:** `为指定类`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `索引位置` (`整数`): 提供所欲检查成员的索引位置,必须大于等于0且小于数组成员数目.
	* `所检查的类型` (`模板类型1(需求:数据类型)`): 提供所欲检查是否匹配的类数据类型
* **特性:**
	* `静态`
* **描述:** 返回本数组中指定位置处成员对象的实际数据类型是否为所指定的类
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.匹配指定类

* **类型:** `方法`
* **名称:** `匹配指定类`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `索引位置` (`整数`): 提供所欲检查成员的索引位置,必须大于等于0且小于数组成员数目.
	* `所检查的类型` (`模板类型1(需求:数据类型)`): 提供所欲检查是否匹配的类数据类型
* **特性:**
	* `静态`
* **描述:** 返回本数组中指定位置处成员对象的实际数据类型是否匹配所指定的类(为其或其继承类)
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.取指定类型枚举值

* **类型:** `方法`
* **名称:** `取指定类型枚举值`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `所欲获取对象的类型` (`模板类型1(需求:数据类型)`): 提供所欲获取对象的数据类型,如果当前所枚举到的对象成员不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **特性:**
	* `静态`
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.对象数组模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"语句的子语句体中使用,用作取回当前枚举到的指定数据类型的成员值,如果有多层本类或本类继承类的"枚举循环"嵌套,本方法将返回所处最近层"枚举循环"的枚举成员值.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.对象数组模板类.取指定类型成员

* **类型:** `方法`
* **名称:** `取指定类型成员`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲操作的数组` (`对象数组模板类`): 提供所欲操作的对象数组
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
	* `所欲获取对象的类型` (`模板类型1(需求:数据类型)`): 提供所欲获取对象的数据类型,如果数组中指定索引位置处对象不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **特性:**
	* `静态`
* **描述:** 返回所指定索引位置处成员对象的参考. 注意: 如果所获取对象成员需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (数组1.取指定类型成员 (索引位置, 对象实际数据类型)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

---

#### 火山.基本.对象数组类

* **类型:** `类`
* **名称:** `对象数组类`
* **模板基础类:** `对象数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `对象类`
* **描述:** 最基本的对象类数组
* **相关例程:** [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

---

#### 火山.基本.字节集数组类

* **类型:** `类`
* **名称:** `字节集数组类`
* **模板基础类:** `对象数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `字节集类`
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.结构数组模板类

* **类型:** `类`
* **名称:** `结构数组模板类`
* **基础类:** `扩展对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **文档分类:** `数组操作.模板类`
* **描述:** 用作提供对C++结构类对象的数组封装. 模板类型1: 对应的结构类,其必须定义了有效的"@视窗.结构类"属性,且其中不能存在/包含数据类型为文本型的成员.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.数组内容

* **类型:** `成员变量`
* **名称:** `数组内容`
* **数据类型:** `字节集类`
* **描述:** 用作保存具体的数组数据,数据内容为所有C++结构数据成员的顺序排列.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.预分配尺寸

* **类型:** `属性读方法`
* **名称:** `预分配尺寸`
* **返回值数据类型:** `整数`
* **描述:** 返回本数组为了快速进行数组成员的添加/删除处理使用的空间分配尺寸,每次数组需要调整其空间大小时,都使用本属性值乘于单个数组成员尺寸作为空间调整基准尺寸.值越大,批量加入/删除数组成员时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.预分配尺寸

* **类型:** `属性写方法`
* **名称:** `预分配尺寸`
* **参数:**
	* `所欲设置的预分配尺寸` (`整数`)
* **描述:** 设置本数组为了快速进行数组成员的添加/删除处理使用的空间分配尺寸,每次数组需要调整其空间大小时,都使用本属性值乘于单个数组成员尺寸作为空间调整基准尺寸.值越大,批量加入/删除数组成员时所实际需要重分配空间的次数就越少,操作速度越快,但是多余内存占用就越大. 一般情况下无需更改本属性值.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.枚举循环

* **类型:** `方法`
* **名称:** `枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.逆向枚举循环

* **类型:** `方法`
* **名称:** `逆向枚举循环`
* **特性:**
	* 必须为本方法调用语句提供一个子语句体(其中可使用"跳出循环"和"到循环尾"关键字)
* **描述:** 启动一个逆向循环来枚举本数组中的每一个成员,在循环中可以调用"取枚举值"方法来获取当前所枚举到的成员值,调用"取枚举索引"方法来获取当前所枚举到成员的索引位置.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.取枚举值

* **类型:** `方法`
* **名称:** `取枚举值`
* **返回值数据类型:** `模板类型1`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.结构数组模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到的成员值,如果有多层本类或本类继承类的循环嵌套,本方法将返回所处最近层循环的枚举成员值.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.取枚举索引

* **类型:** `方法`
* **名称:** `取枚举索引`
* **返回值数据类型:** `整数`
* **特性:**
	* 本方法调用语句必须位于以下任一方法调用语句的直接或间接子语句体中: [枚举循环](#火山.基本.结构数组模板类.枚举循环)
* **描述:** 只能在本类的"枚举循环"/"逆向枚举循环"语句的子语句体中使用,用作取回当前枚举到成员的索引位置,如果有多层本类或本类继承类的循环嵌套,本方法将返回所处最近层循环枚举到成员的索引位置.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.取数组指针

* **类型:** `方法`
* **名称:** `取数组指针`
* **返回值数据类型:** `变整数`
* **描述:** 返回当前数组内容的数据指针值. 数组数据内容为所有C++结构数据成员的顺序排列.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.取数组数据尺寸

* **类型:** `方法`
* **名称:** `取数组数据尺寸`
* **返回值数据类型:** `整数`
* **描述:** 返回当前数组内容数据的尺寸,单位字节. 数组数据内容为所有C++结构数据成员的顺序排列.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.索引是否有效

* **类型:** `方法`
* **名称:** `索引是否有效`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的索引值` (`整数`)
* **描述:** 返回所指定的索引值是否大于等于0且小于本数组的成员数
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.取成员数

* **类型:** `方法`
* **名称:** `取成员数`
* **返回值数据类型:** `整数`
* **描述:** 返回数组中的当前已有成员数目
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.取最大索引

* **类型:** `方法`
* **名称:** `取最大索引`
* **返回值数据类型:** `整数`
* **描述:** 返回数组中尾成员的索引位置
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本数组是否为空
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.删除所有成员

* **类型:** `方法`
* **名称:** `删除所有成员`
* **描述:** 删除数组中的当前所有成员
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.重置数组

* **类型:** `方法`
* **名称:** `重置数组`
* **参数:**
	* `欲重置的成员数目` (`整数`): 必须大于等于0
* **描述:** 重置数组中的成员数为所指定的数目并将其清零
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.清零

* **类型:** `方法`
* **名称:** `清零`
* **描述:** 将数组中的所有成员值清除为零值
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.取成员

* **类型:** `方法`
* **名称:** `取成员`
* **返回值数据类型:** `模板类型1`
* **参数:**
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
* **描述:** 返回所指定索引位置处的成员值
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.取成员2

* **类型:** `方法`
* **名称:** `取成员2`
* **参数:**
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
	* `结果对象` (`模板类型1`): 用作保存所获得的成员值数据内容
* **描述:** 返回所指定索引位置处的成员值
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.取成员尺寸

* **类型:** `方法`
* **名称:** `取成员尺寸`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回数组中单个成员的数据尺寸,单位字节.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.置成员值

* **类型:** `方法`
* **名称:** `置成员值`
* **参数:**
	* `索引位置` (`整数`): 提供所欲操作成员的索引位置,必须大于等于0且小于数组成员数目.
	* `所欲设置的值` (`模板类型1`): 提供所欲设置的成员值,先前的值将被覆盖.
* **描述:** 设置数组中所指定索引位置处的成员值
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.添加数组

* **类型:** `方法`
* **名称:** `添加数组`
* **参数:**
	* `所欲添加的数组` (`结构数组模板类`)
* **描述:** 将另一个同类型数组的内容添加到本数组尾部
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.添加部分数组

* **类型:** `方法`
* **名称:** `添加部分数组`
* **参数:**
	* `所欲添加的数组` (`结构数组模板类`)
	* `起始索引位置` (`整数`): 必须大于等于0且加上"所欲添加的成员数"后小于等于"所欲添加的数组"的成员数目
	* `所欲添加的成员数` (`整数`): 必须大于等于0且加上"起始索引位置"后小于等于"所欲添加的数组"的成员数目
* **描述:** 将另一个同类型数组内容中的一部分添加到本数组尾部
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.从数组复制

* **类型:** `方法`
* **名称:** `从数组复制`
* **参数:**
	* `所欲复制的数组` (`结构数组模板类`)
* **描述:** 清空本数组的原有内容,将另一个同类型数组的内容复制到本数组中.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.加入空成员

* **类型:** `方法`
* **名称:** `加入空成员`
* **参数:**
	* `所欲加入的零成员数` (`整数`)
* **描述:** 加入所指定数目的值为零的成员
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.加入成员

* **类型:** `方法`
* **名称:** `加入成员`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲添加成员值` (`模板类型1`)
* **描述:** 将成员值加入到本数组的尾部
* **返回值描述:** 返回所加入的成员在数组中的记录索引位置
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.插入成员

* **类型:** `方法`
* **名称:** `插入成员`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入的成员值` (`模板类型1`)
* **描述:** 将所指定的成员值插入到所指定的索引位置
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.插入数组

* **类型:** `方法`
* **名称:** `插入数组`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入的数组` (`结构数组模板类`): 提供所欲插入的数组数据
* **描述:** 将另一个同类型数组的内容插入到本数组的所指定索引位置
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.插入部分数组

* **类型:** `方法`
* **名称:** `插入部分数组`
* **参数:**
	* `插入索引位置` (`整数`): 提供所欲插入的成员索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲插入的数组` (`结构数组模板类`): 提供所欲插入的数组数据
	* `起始索引位置` (`整数`): 必须大于等于0且加上"所欲插入的成员数"后小于等于"所欲插入的数组"的成员数目
	* `所欲插入的成员数` (`整数`): 必须大于等于0且加上"起始索引位置"后小于等于"所欲插入的数组"的成员数目
* **描述:** 将另一个同类型数组的部分内容插入到本数组的所指定索引位置
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.删除成员

* **类型:** `方法`
* **名称:** `删除成员`
* **参数:**
	* `删除索引位置` (`整数`): 提供所欲删除成员的索引位置,必须大于等于0且小于等于数组成员数目.
	* `所欲删除成员数目` (`整数`, 默认值: `1`): 提供所欲删除成员的数目,必须大于等于0且加上"删除索引位置"参数值后小于等于数组成员数目.
* **描述:** 删除数组中所指定索引位置处的成员
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.删除到尾部

* **类型:** `方法`
* **名称:** `删除到尾部`
* **参数:**
	* `起始索引位置` (`整数`): 提供所欲删除起始成员的索引位置,必须大于等于0且小于等于数组成员数目.
* **描述:** 删除数组中所指定索引位置后(包括该位置)的所有成员
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.是否相等

* **类型:** `方法`
* **名称:** `是否相等`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲比较的数组` (`结构数组模板类`)
* **描述:** 返回所指定数组的内容是否与本数组相同
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.流读入

* **类型:** `方法`
* **名称:** `流读入`
* **参数:**
	* `流对象` (`输入流类`): 提供欲从其中读入本对象数据内容的输入流
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 从所指定的流对象中读入本对象的数据
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构数组模板类.流写出

* **类型:** `方法`
* **名称:** `流写出`
* **参数:**
	* `流对象` (`输出流类`): 提供欲将本对象数据内容写出到其中的输出流
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象的数据写入所指定的流对象中
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

---

#### 火山.基本.数值范围

* **类型:** `类`
* **名称:** `数值范围`
* **描述:** 提供各种整数数值类型的最大和最小值
* **相关例程:** [vol-选择夹1-tab_demo-main](#vol-选择夹1-tab_demo-main), [vol-选择夹2-tab_demo-main](#vol-选择夹2-tab_demo-main), [vol-选择夹3-tab_demo3-main](#vol-选择夹3-tab_demo3-main), [vol-对话框-dialog_test-main](#vol-对话框-dialog_test-main), [vol-文件浏览-file_viewer-main](#vol-文件浏览-file_viewer-main), [vol-时钟-timer-main](#vol-时钟-timer-main), [vol-超级列表框-listview-main](#vol-超级列表框-listview-main), [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-树形框-tree_box-main](#vol-树形框-tree_box-main), [vol-超级编辑框-rich_edit-main](#vol-超级编辑框-rich_edit-main), [vol-工具条-tool_bar-main](#vol-工具条-tool_bar-main), [vol-状态条-status_bar-main](#vol-状态条-status_bar-main), [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-表格-grid-main](#vol-表格-grid-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-半透明图片演示-alpha_pic_draw-main](#vol-半透明图片演示-alpha_pic_draw-main), [vol-卷帘式菜单-outbar-main](#vol-卷帘式菜单-outbar-main), [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main), [vol-属性表格-property_grid-main](#vol-属性表格-property_grid-main), [vol-带按钮列表框-vs_list_box-main](#vol-带按钮列表框-vs_list_box-main), [vol-媒体播放器-win_media_player-main](#vol-媒体播放器-win_media_player-main), [vol-设计并处理重叠界面-over_ui-main](#vol-设计并处理重叠界面-over_ui-main), [vol-超级菜单演示-adv_menu-main](#vol-超级菜单演示-adv_menu-main), [vol-窗口组件动态消息过滤-msg_filter-main](#vol-窗口组件动态消息过滤-msg_filter-main), [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览框扩展-webview2_extensions-main](#vol-edge浏览框扩展-webview2_extensions-main), [vol-edge浏览框自定义菜单-webview2_contextmenu-main](#vol-edge浏览框自定义菜单-webview2_contextmenu-main), [vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main](#vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-用户自定义窗口组件-user_control-main](#vol-用户自定义窗口组件-user_control-main), [vol-祖国您好-base_test-main](#vol-祖国您好-base_test-main), [vol-菜单-menu_demo-main](#vol-菜单-menu_demo-main), [vol-打印测试-print_test-main](#vol-打印测试-print_test-main), [vol-空对象测试-null_object_test-main](#vol-空对象测试-null_object_test-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main), [vol-位图处理-adv_bitmap-main](#vol-位图处理-adv_bitmap-main), [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-cximage高级图像处理-cximage-main](#vol-cximage高级图像处理-cximage-main), [vol-程序崩溃回调-breakpad-main](#vol-程序崩溃回调-breakpad-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-系统全局热键-syshotkey-main](#vol-系统全局热键-syshotkey-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-演示exe-sampleexe-main](#vol-演示exe-sampleexe-main), [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-条件编译项目1-cond_compile1-main](#vol-条件编译项目1-cond_compile1-main), [vol-mfc控制台程序-mfc_console-main](#vol-mfc控制台程序-mfc_console-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-调用动态链接库-dll_call-main](#vol-调用动态链接库-dll_call-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-被调用mfc动态链接库-mfc_dll-main](#vol-被调用mfc动态链接库-mfc_dll-main), [vol-一步一步跟我学火山-step_by_step-main](#vol-一步一步跟我学火山-step_by_step-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-密码管理-pw-main](#vol-密码管理-pw-main), [vol-json数据访问-json-main](#vol-json数据访问-json-main), [vol-xml数据访问-xml-main](#vol-xml数据访问-xml-main), [vol-树结构访问-treestruct-main](#vol-树结构访问-treestruct-main), [vol-正则表达式-deelx_regular-main](#vol-正则表达式-deelx_regular-main), [vol-网页解析-html_parser-main](#vol-网页解析-html_parser-main), [vol-高级网页解析-adv_html_parser-main](#vol-高级网页解析-adv_html_parser-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-大整数运算-bnsample-main](#vol-大整数运算-bnsample-main), [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-cron时间表达式-cron-main](#vol-cron时间表达式-cron-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-正则表达式2-regex-main](#vol-正则表达式2-regex-main), [vol-yyjson数据访问-yyjson-main](#vol-yyjson数据访问-yyjson-main), [vol-数学公式计算-math_exp_calc-main](#vol-数学公式计算-math_exp_calc-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-串口通讯-cserialport-main](#vol-串口通讯-cserialport-main), [vol-摄像头操作-directshow-main](#vol-摄像头操作-directshow-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-tcp转发-tcp_forward-main](#vol-tcp转发-tcp_forward-main), [vol-数据报-udp-main](#vol-数据报-udp-main), [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main), [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件发送-send_email-main](#vol-邮件发送-send_email-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-ado-ado_sample-main](#vol-ado-ado_sample-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-redis连接池-redisconnectpool-main](#vol-redis连接池-redisconnectpool-main), [vol-mysql连接池-mysql_connectionpool-main](#vol-mysql连接池-mysql_connectionpool-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-elk微型js引擎-elk_js-main](#vol-elk微型js引擎-elk_js-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-wav播放-wav_play-main](#vol-wav播放-wav_play-main), [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main), [vol-rvm人像抠图-rvm_segmentation-main](#vol-rvm人像抠图-rvm_segmentation-main), [vol-角点检测-corner_detection-main](#vol-角点检测-corner_detection-main), [vol-图像融合-image_fusion-main](#vol-图像融合-image_fusion-main), [vol-形态学运算-morphological-main](#vol-形态学运算-morphological-main), [vol-dnn文本检测-dnn_text_detection_recognition-main](#vol-dnn文本检测-dnn_text_detection_recognition-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.数值范围.最小字节值

* **类型:** `成员常量`
* **名称:** `最小字节值`
* **数据类型:** `整数`

##### 火山.基本.数值范围.最大字节值

* **类型:** `成员常量`
* **名称:** `最大字节值`
* **数据类型:** `整数`

##### 火山.基本.数值范围.最小短整数值

* **类型:** `成员常量`
* **名称:** `最小短整数值`
* **数据类型:** `整数`

##### 火山.基本.数值范围.最大短整数值

* **类型:** `成员常量`
* **名称:** `最大短整数值`
* **数据类型:** `整数`

##### 火山.基本.数值范围.最小字符值

* **类型:** `成员常量`
* **名称:** `最小字符值`
* **数据类型:** `整数`
* **初始值:** `0`

##### 火山.基本.数值范围.最大字符值

* **类型:** `成员常量`
* **名称:** `最大字符值`
* **数据类型:** `整数`

##### 火山.基本.数值范围.最小整数值

* **类型:** `成员常量`
* **名称:** `最小整数值`
* **数据类型:** `整数`
* **相关例程:** [vol-选择夹1-tab_demo-main](#vol-选择夹1-tab_demo-main), [vol-选择夹2-tab_demo-main](#vol-选择夹2-tab_demo-main), [vol-选择夹3-tab_demo3-main](#vol-选择夹3-tab_demo3-main), [vol-对话框-dialog_test-main](#vol-对话框-dialog_test-main), [vol-文件浏览-file_viewer-main](#vol-文件浏览-file_viewer-main), [vol-时钟-timer-main](#vol-时钟-timer-main), [vol-超级列表框-listview-main](#vol-超级列表框-listview-main), [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-树形框-tree_box-main](#vol-树形框-tree_box-main), [vol-超级编辑框-rich_edit-main](#vol-超级编辑框-rich_edit-main), [vol-工具条-tool_bar-main](#vol-工具条-tool_bar-main), [vol-状态条-status_bar-main](#vol-状态条-status_bar-main), [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-表格-grid-main](#vol-表格-grid-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-半透明图片演示-alpha_pic_draw-main](#vol-半透明图片演示-alpha_pic_draw-main), [vol-卷帘式菜单-outbar-main](#vol-卷帘式菜单-outbar-main), [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main), [vol-属性表格-property_grid-main](#vol-属性表格-property_grid-main), [vol-带按钮列表框-vs_list_box-main](#vol-带按钮列表框-vs_list_box-main), [vol-媒体播放器-win_media_player-main](#vol-媒体播放器-win_media_player-main), [vol-设计并处理重叠界面-over_ui-main](#vol-设计并处理重叠界面-over_ui-main), [vol-超级菜单演示-adv_menu-main](#vol-超级菜单演示-adv_menu-main), [vol-窗口组件动态消息过滤-msg_filter-main](#vol-窗口组件动态消息过滤-msg_filter-main), [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览框扩展-webview2_extensions-main](#vol-edge浏览框扩展-webview2_extensions-main), [vol-edge浏览框自定义菜单-webview2_contextmenu-main](#vol-edge浏览框自定义菜单-webview2_contextmenu-main), [vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main](#vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-用户自定义窗口组件-user_control-main](#vol-用户自定义窗口组件-user_control-main), [vol-祖国您好-base_test-main](#vol-祖国您好-base_test-main), [vol-菜单-menu_demo-main](#vol-菜单-menu_demo-main), [vol-打印测试-print_test-main](#vol-打印测试-print_test-main), [vol-空对象测试-null_object_test-main](#vol-空对象测试-null_object_test-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main), [vol-位图处理-adv_bitmap-main](#vol-位图处理-adv_bitmap-main), [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-cximage高级图像处理-cximage-main](#vol-cximage高级图像处理-cximage-main), [vol-程序崩溃回调-breakpad-main](#vol-程序崩溃回调-breakpad-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-系统全局热键-syshotkey-main](#vol-系统全局热键-syshotkey-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-演示exe-sampleexe-main](#vol-演示exe-sampleexe-main), [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-条件编译项目1-cond_compile1-main](#vol-条件编译项目1-cond_compile1-main), [vol-mfc控制台程序-mfc_console-main](#vol-mfc控制台程序-mfc_console-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-调用动态链接库-dll_call-main](#vol-调用动态链接库-dll_call-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-被调用mfc动态链接库-mfc_dll-main](#vol-被调用mfc动态链接库-mfc_dll-main), [vol-一步一步跟我学火山-step_by_step-main](#vol-一步一步跟我学火山-step_by_step-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-密码管理-pw-main](#vol-密码管理-pw-main), [vol-json数据访问-json-main](#vol-json数据访问-json-main), [vol-xml数据访问-xml-main](#vol-xml数据访问-xml-main), [vol-树结构访问-treestruct-main](#vol-树结构访问-treestruct-main), [vol-正则表达式-deelx_regular-main](#vol-正则表达式-deelx_regular-main), [vol-网页解析-html_parser-main](#vol-网页解析-html_parser-main), [vol-高级网页解析-adv_html_parser-main](#vol-高级网页解析-adv_html_parser-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-大整数运算-bnsample-main](#vol-大整数运算-bnsample-main), [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-cron时间表达式-cron-main](#vol-cron时间表达式-cron-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-正则表达式2-regex-main](#vol-正则表达式2-regex-main), [vol-yyjson数据访问-yyjson-main](#vol-yyjson数据访问-yyjson-main), [vol-数学公式计算-math_exp_calc-main](#vol-数学公式计算-math_exp_calc-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-串口通讯-cserialport-main](#vol-串口通讯-cserialport-main), [vol-摄像头操作-directshow-main](#vol-摄像头操作-directshow-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-tcp转发-tcp_forward-main](#vol-tcp转发-tcp_forward-main), [vol-数据报-udp-main](#vol-数据报-udp-main), [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main), [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件发送-send_email-main](#vol-邮件发送-send_email-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-ado-ado_sample-main](#vol-ado-ado_sample-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-redis连接池-redisconnectpool-main](#vol-redis连接池-redisconnectpool-main), [vol-mysql连接池-mysql_connectionpool-main](#vol-mysql连接池-mysql_connectionpool-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-elk微型js引擎-elk_js-main](#vol-elk微型js引擎-elk_js-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-wav播放-wav_play-main](#vol-wav播放-wav_play-main), [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main), [vol-rvm人像抠图-rvm_segmentation-main](#vol-rvm人像抠图-rvm_segmentation-main), [vol-角点检测-corner_detection-main](#vol-角点检测-corner_detection-main), [vol-图像融合-image_fusion-main](#vol-图像融合-image_fusion-main), [vol-形态学运算-morphological-main](#vol-形态学运算-morphological-main), [vol-dnn文本检测-dnn_text_detection_recognition-main](#vol-dnn文本检测-dnn_text_detection_recognition-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.数值范围.最大整数值

* **类型:** `成员常量`
* **名称:** `最大整数值`
* **数据类型:** `整数`
* **相关例程:** [vol-ado-ado_sample-main](#vol-ado-ado_sample-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.数值范围.最小长整数值

* **类型:** `成员常量`
* **名称:** `最小长整数值`
* **数据类型:** `长整数`

##### 火山.基本.数值范围.最大长整数值

* **类型:** `成员常量`
* **名称:** `最大长整数值`
* **数据类型:** `长整数`

##### 火山.基本.数值范围.最小变整数值

* **类型:** `成员常量`
* **名称:** `最小变整数值`
* **数据类型:** `变整数`

##### 火山.基本.数值范围.最大变整数值

* **类型:** `成员常量`
* **名称:** `最大变整数值`
* **数据类型:** `变整数`

##### 火山.基本.数值范围.最小日期时间值

* **类型:** `成员常量`
* **名称:** `最小日期时间值`
* **数据类型:** `小数`
* **描述:** 提供所允许的最小日期时间值(用小数表达),为100年1月1日.

##### 火山.基本.数值范围.最大日期时间值

* **类型:** `成员常量`
* **名称:** `最大日期时间值`
* **数据类型:** `小数`
* **描述:** 提供所允许的最大日期时间值(用小数表达),为9999年1月1日.

---

#### 火山.基本.常数

* **类型:** `类`
* **名称:** `常数`
* **描述:** 提供各种常数值
* **相关例程:** [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.常数.接近零小数值

* **类型:** `成员常量`
* **名称:** `接近零小数值`
* **数据类型:** `小数`
* **描述:** 提供一个无限接近零的小数值,可以用作在进行小数比较操作时使用.

##### 火山.基本.常数.PI

* **类型:** `成员常量`
* **名称:** `PI`
* **数据类型:** `小数`
* **初始值:** `3.14159265358979323846`
* **描述:** 圆周率,圆的周长与直径的比值.
* **相关例程:** [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.常数.E

* **类型:** `成员常量`
* **名称:** `E`
* **数据类型:** `小数`
* **初始值:** `2.7182818284590452354`
* **描述:** 自然常数,自然对数函数的底数,有时被称为欧拉数.

---

#### 火山.基本.矩形类

* **类型:** `类`
* **名称:** `矩形类`
* **基础类:** `扩展对象类`
* **描述:** 用作记录一个矩形数据
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-cximage高级图像处理-cximage-main](#vol-cximage高级图像处理-cximage-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-被调用部件动态链接库-com_dll-main](#vol-被调用部件动态链接库-com_dll-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main)

##### 火山.基本.矩形类.左边

* **类型:** `属性成员变量`
* **名称:** `左边`
* **数据类型:** `整数`
* **相关例程:** [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main)

##### 火山.基本.矩形类.顶边

* **类型:** `属性成员变量`
* **名称:** `顶边`
* **数据类型:** `整数`
* **相关例程:** [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main)

##### 火山.基本.矩形类.右边

* **类型:** `属性成员变量`
* **名称:** `右边`
* **数据类型:** `整数`
* **相关例程:** [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main)

##### 火山.基本.矩形类.底边

* **类型:** `属性成员变量`
* **名称:** `底边`
* **数据类型:** `整数`
* **相关例程:** [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main)

##### 火山.基本.矩形类.位置

* **类型:** `属性读方法`
* **名称:** `位置`
* **返回值数据类型:** `位置类`
* **描述:** 返回本矩形的左上角位置

##### 火山.基本.矩形类.位置

* **类型:** `属性写方法`
* **名称:** `位置`
* **参数:**
	* `所欲设置位置` (`位置类`)
* **描述:** 设置本矩形的左上角位置

##### 火山.基本.矩形类.尺寸

* **类型:** `属性读方法`
* **名称:** `尺寸`
* **返回值数据类型:** `尺寸类`
* **描述:** 返回本矩形的尺寸

##### 火山.基本.矩形类.尺寸

* **类型:** `属性写方法`
* **名称:** `尺寸`
* **参数:**
	* `所欲设置尺寸` (`尺寸类`)
* **描述:** 设置本矩形的尺寸

##### 火山.基本.矩形类.宽度

* **类型:** `属性读方法`
* **名称:** `宽度`
* **返回值数据类型:** `整数`
* **描述:** 返回本矩形的宽度
* **相关例程:** [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main)

##### 火山.基本.矩形类.宽度

* **类型:** `属性写方法`
* **名称:** `宽度`
* **参数:**
	* `所欲设置宽度` (`整数`)
* **描述:** 设置本矩形的宽度
* **相关例程:** [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main)

##### 火山.基本.矩形类.高度

* **类型:** `属性读方法`
* **名称:** `高度`
* **返回值数据类型:** `整数`
* **描述:** 返回本矩形的高度
* **相关例程:** [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main)

##### 火山.基本.矩形类.高度

* **类型:** `属性写方法`
* **名称:** `高度`
* **参数:**
	* `所欲设置高度` (`整数`)
* **描述:** 设置本矩形的高度
* **相关例程:** [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main)

##### 火山.基本.矩形类.到小数矩形

* **类型:** `方法`
* **名称:** `到小数矩形`
* **返回值数据类型:** `小数矩形类`
* **描述:** 将本整数矩形转换为小数矩形

##### 火山.基本.矩形类.清零

* **类型:** `方法`
* **名称:** `清零`

##### 火山.基本.矩形类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本矩形的面积是否为空

##### 火山.基本.矩形类.设置

* **类型:** `方法`
* **名称:** `设置`
* **参数:**
	* `所欲设置左边位置` (`整数`)
	* `所欲设置顶边位置` (`整数`)
	* `所欲设置右边位置` (`整数`)
	* `所欲设置底边位置` (`整数`)
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main)

##### 火山.基本.矩形类.基于位置设置

* **类型:** `方法`
* **名称:** `基于位置设置`
* **参数:**
	* `左上角位置` (`位置类`)
	* `右下角位置` (`位置类`)

##### 火山.基本.矩形类.基于位置和尺寸设置

* **类型:** `方法`
* **名称:** `基于位置和尺寸设置`
* **参数:**
	* `所设置位置` (`位置类`)
	* `所设置尺寸` (`尺寸类`)

##### 火山.基本.矩形类.置左上角位置

* **类型:** `方法`
* **名称:** `置左上角位置`
* **参数:**
	* `所欲设置左边位置` (`整数`)
	* `所欲设置顶边位置` (`整数`)

##### 火山.基本.矩形类.置右下角位置

* **类型:** `方法`
* **名称:** `置右下角位置`
* **参数:**
	* `所欲设置右边位置` (`整数`)
	* `所欲设置底边位置` (`整数`)

##### 火山.基本.矩形类.置尺寸

* **类型:** `方法`
* **名称:** `置尺寸`
* **参数:**
	* `所欲设置的宽度` (`整数`)
	* `所欲设置的高度` (`整数`)
* **相关例程:** [vol-被调用部件动态链接库-com_dll-main](#vol-被调用部件动态链接库-com_dll-main)

##### 火山.基本.矩形类.横向移动

* **类型:** `方法`
* **名称:** `横向移动`
* **参数:**
	* `横向移动距离` (`整数`)

##### 火山.基本.矩形类.纵向移动

* **类型:** `方法`
* **名称:** `纵向移动`
* **参数:**
	* `纵向移动距离` (`整数`)

##### 火山.基本.矩形类.移动

* **类型:** `方法`
* **名称:** `移动`
* **参数:**
	* `横向移动距离` (`整数`)
	* `纵向移动距离` (`整数`)

##### 火山.基本.矩形类.放大

* **类型:** `方法`
* **名称:** `放大`
* **参数:**
	* `横向放大尺寸` (`整数`)
	* `纵向放大尺寸` (`整数`)

##### 火山.基本.矩形类.缩小

* **类型:** `方法`
* **名称:** `缩小`
* **参数:**
	* `横向缩小尺寸` (`整数`)
	* `纵向缩小尺寸` (`整数`)

##### 火山.基本.矩形类.包含指定矩形

* **类型:** `方法`
* **名称:** `包含指定矩形`
* **参数:**
	* `所欲包含的矩形` (`矩形类`)
* **描述:** 扩充本矩形以包含所指定矩形

##### 火山.基本.矩形类.包含指定点

* **类型:** `方法`
* **名称:** `包含指定点`
* **参数:**
	* `所欲包含点横坐标` (`整数`)
	* `所欲包含点纵坐标` (`整数`)
* **描述:** 扩充本矩形以包含所指定点的位置

##### 火山.基本.矩形类.乘于

* **类型:** `方法`
* **名称:** `乘于`
* **参数:**
	* `所欲乘于的值` (`小数`)
* **描述:** 将本矩形的所有成员乘于所指定的值

##### 火山.基本.矩形类.除于

* **类型:** `方法`
* **名称:** `除于`
* **参数:**
	* `所欲除于的值` (`小数`)
* **描述:** 将本矩形的所有成员除于所指定的值

##### 火山.基本.矩形类.取面积

* **类型:** `方法`
* **名称:** `取面积`
* **返回值数据类型:** `整数`
* **描述:** 返回本矩形的面积

##### 火山.基本.矩形类.取中心点

* **类型:** `方法`
* **名称:** `取中心点`
* **返回值数据类型:** `位置类`
* **描述:** 返回本矩形的中心点位置

##### 火山.基本.矩形类.取中心横向位置

* **类型:** `方法`
* **名称:** `取中心横向位置`
* **返回值数据类型:** `整数`
* **描述:** 返回本矩形中心点的横向位置

##### 火山.基本.矩形类.取中心纵向位置

* **类型:** `方法`
* **名称:** `取中心纵向位置`
* **返回值数据类型:** `整数`
* **描述:** 返回本矩形中心点的纵向位置

##### 火山.基本.矩形类.取右下角位置

* **类型:** `方法`
* **名称:** `取右下角位置`
* **返回值数据类型:** `位置类`
* **描述:** 返回本矩形右下角的位置

##### 火山.基本.矩形类.规范化

* **类型:** `方法`
* **名称:** `规范化`
* **描述:** 整理本矩形的各个成员,去除左右边或上下边反转的情况,使其规范化.

##### 火山.基本.矩形类.是否包含指定点

* **类型:** `方法`
* **名称:** `是否包含指定点`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所检测点横坐标` (`整数`)
	* `所检测点纵坐标` (`整数`)
* **描述:** 返回所指定点的位置是否在本矩形中

##### 火山.基本.矩形类.是否位于矩形内部

* **类型:** `方法`
* **名称:** `是否位于矩形内部`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的矩形` (`矩形类`)
* **描述:** 返回本矩形是否完全位于所指定矩形内部

##### 火山.基本.矩形类.是否相交

* **类型:** `方法`
* **名称:** `是否相交`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的矩形` (`矩形类`)
* **描述:** 返回本矩形是否与所指定矩形具有相交部分

##### 火山.基本.矩形类.取相交矩形

* **类型:** `方法`
* **名称:** `取相交矩形`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的矩形` (`矩形类`)
	* `相交结果矩形` (`矩形类`): 本参数用作存储本矩形与所检查矩形的相交部分,如果没有相交,则将被清零.
* **描述:** 返回本矩形是否与所指定矩形具有相交部分并将 相交部分矩形填入所指定参数中

##### 火山.基本.矩形类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.小数矩形类

* **类型:** `类`
* **名称:** `小数矩形类`
* **基础类:** `扩展对象类`
* **描述:** 用作记录一个小数矩形数据

##### 火山.基本.小数矩形类.左边

* **类型:** `属性成员变量`
* **名称:** `左边`
* **数据类型:** `小数`

##### 火山.基本.小数矩形类.顶边

* **类型:** `属性成员变量`
* **名称:** `顶边`
* **数据类型:** `小数`

##### 火山.基本.小数矩形类.右边

* **类型:** `属性成员变量`
* **名称:** `右边`
* **数据类型:** `小数`

##### 火山.基本.小数矩形类.底边

* **类型:** `属性成员变量`
* **名称:** `底边`
* **数据类型:** `小数`

##### 火山.基本.小数矩形类.位置

* **类型:** `属性读方法`
* **名称:** `位置`
* **返回值数据类型:** `小数位置类`
* **描述:** 返回本矩形的左上角位置

##### 火山.基本.小数矩形类.位置

* **类型:** `属性写方法`
* **名称:** `位置`
* **参数:**
	* `所欲设置位置` (`小数位置类`)
* **描述:** 设置本矩形的左上角位置

##### 火山.基本.小数矩形类.尺寸

* **类型:** `属性读方法`
* **名称:** `尺寸`
* **返回值数据类型:** `小数尺寸类`
* **描述:** 返回本矩形的尺寸

##### 火山.基本.小数矩形类.尺寸

* **类型:** `属性写方法`
* **名称:** `尺寸`
* **参数:**
	* `所欲设置尺寸` (`小数尺寸类`)
* **描述:** 设置本矩形的尺寸

##### 火山.基本.小数矩形类.宽度

* **类型:** `属性读方法`
* **名称:** `宽度`
* **返回值数据类型:** `小数`
* **描述:** 返回本矩形的宽度

##### 火山.基本.小数矩形类.宽度

* **类型:** `属性写方法`
* **名称:** `宽度`
* **参数:**
	* `所欲设置宽度` (`小数`)
* **描述:** 设置本矩形的宽度

##### 火山.基本.小数矩形类.高度

* **类型:** `属性读方法`
* **名称:** `高度`
* **返回值数据类型:** `小数`
* **描述:** 返回本矩形的高度

##### 火山.基本.小数矩形类.高度

* **类型:** `属性写方法`
* **名称:** `高度`
* **参数:**
	* `所欲设置高度` (`小数`)
* **描述:** 设置本矩形的高度

##### 火山.基本.小数矩形类.到矩形

* **类型:** `方法`
* **名称:** `到矩形`
* **返回值数据类型:** `矩形类`
* **描述:** 将本小数矩形转换为整数矩形,注意将会存在精度转换误差.

##### 火山.基本.小数矩形类.清零

* **类型:** `方法`
* **名称:** `清零`

##### 火山.基本.小数矩形类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本矩形的面积是否为空

##### 火山.基本.小数矩形类.设置

* **类型:** `方法`
* **名称:** `设置`
* **参数:**
	* `所欲设置左边位置` (`小数`)
	* `所欲设置顶边位置` (`小数`)
	* `所欲设置右边位置` (`小数`)
	* `所欲设置底边位置` (`小数`)

##### 火山.基本.小数矩形类.基于位置设置

* **类型:** `方法`
* **名称:** `基于位置设置`
* **参数:**
	* `左上角位置` (`小数位置类`)
	* `右下角位置` (`小数位置类`)

##### 火山.基本.小数矩形类.基于位置和尺寸设置

* **类型:** `方法`
* **名称:** `基于位置和尺寸设置`
* **参数:**
	* `所设置位置` (`小数位置类`)
	* `所设置尺寸` (`小数尺寸类`)

##### 火山.基本.小数矩形类.置左上角位置

* **类型:** `方法`
* **名称:** `置左上角位置`
* **参数:**
	* `所欲设置左边位置` (`小数`)
	* `所欲设置顶边位置` (`小数`)

##### 火山.基本.小数矩形类.置右下角位置

* **类型:** `方法`
* **名称:** `置右下角位置`
* **参数:**
	* `所欲设置右边位置` (`小数`)
	* `所欲设置底边位置` (`小数`)

##### 火山.基本.小数矩形类.置尺寸

* **类型:** `方法`
* **名称:** `置尺寸`
* **参数:**
	* `所欲设置的宽度` (`小数`)
	* `所欲设置的高度` (`小数`)

##### 火山.基本.小数矩形类.横向移动

* **类型:** `方法`
* **名称:** `横向移动`
* **参数:**
	* `横向移动距离` (`小数`)

##### 火山.基本.小数矩形类.纵向移动

* **类型:** `方法`
* **名称:** `纵向移动`
* **参数:**
	* `纵向移动距离` (`小数`)

##### 火山.基本.小数矩形类.移动

* **类型:** `方法`
* **名称:** `移动`
* **参数:**
	* `横向移动距离` (`小数`)
	* `纵向移动距离` (`小数`)

##### 火山.基本.小数矩形类.放大

* **类型:** `方法`
* **名称:** `放大`
* **参数:**
	* `横向放大尺寸` (`小数`)
	* `纵向放大尺寸` (`小数`)

##### 火山.基本.小数矩形类.缩小

* **类型:** `方法`
* **名称:** `缩小`
* **参数:**
	* `横向缩小尺寸` (`小数`)
	* `纵向缩小尺寸` (`小数`)

##### 火山.基本.小数矩形类.包含指定矩形

* **类型:** `方法`
* **名称:** `包含指定矩形`
* **参数:**
	* `所欲包含的矩形` (`小数矩形类`)
* **描述:** 扩充本矩形以包含所指定矩形

##### 火山.基本.小数矩形类.包含指定点

* **类型:** `方法`
* **名称:** `包含指定点`
* **参数:**
	* `所欲包含点横坐标` (`小数`)
	* `所欲包含点纵坐标` (`小数`)
* **描述:** 扩充本矩形以包含所指定点的位置

##### 火山.基本.小数矩形类.乘于

* **类型:** `方法`
* **名称:** `乘于`
* **参数:**
	* `所欲乘于的值` (`小数`)
* **描述:** 将本矩形的所有成员乘于所指定的值

##### 火山.基本.小数矩形类.除于

* **类型:** `方法`
* **名称:** `除于`
* **参数:**
	* `所欲除于的值` (`小数`)
* **描述:** 将本矩形的所有成员除于所指定的值

##### 火山.基本.小数矩形类.取面积

* **类型:** `方法`
* **名称:** `取面积`
* **返回值数据类型:** `小数`
* **描述:** 返回本矩形的面积

##### 火山.基本.小数矩形类.取中心点

* **类型:** `方法`
* **名称:** `取中心点`
* **返回值数据类型:** `小数位置类`
* **描述:** 返回本矩形的中心点位置

##### 火山.基本.小数矩形类.取中心横向位置

* **类型:** `方法`
* **名称:** `取中心横向位置`
* **返回值数据类型:** `小数`
* **描述:** 返回本矩形中心点的横向位置

##### 火山.基本.小数矩形类.取中心纵向位置

* **类型:** `方法`
* **名称:** `取中心纵向位置`
* **返回值数据类型:** `小数`
* **描述:** 返回本矩形中心点的纵向位置

##### 火山.基本.小数矩形类.取右下角位置

* **类型:** `方法`
* **名称:** `取右下角位置`
* **返回值数据类型:** `小数位置类`
* **描述:** 返回本矩形右下角的位置

##### 火山.基本.小数矩形类.规范化

* **类型:** `方法`
* **名称:** `规范化`
* **描述:** 整理本矩形的各个成员,去除左右边或上下边反转的情况,使其规范化.

##### 火山.基本.小数矩形类.是否包含指定点

* **类型:** `方法`
* **名称:** `是否包含指定点`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所检测点横坐标` (`小数`)
	* `所检测点纵坐标` (`小数`)
* **描述:** 返回所指定点的位置是否在本矩形中

##### 火山.基本.小数矩形类.是否位于矩形内部

* **类型:** `方法`
* **名称:** `是否位于矩形内部`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的矩形` (`小数矩形类`)
* **描述:** 返回本矩形是否完全位于所指定矩形内部

##### 火山.基本.小数矩形类.是否相交

* **类型:** `方法`
* **名称:** `是否相交`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的矩形` (`小数矩形类`)
* **描述:** 返回本矩形是否与所指定矩形具有相交部分

##### 火山.基本.小数矩形类.取相交矩形

* **类型:** `方法`
* **名称:** `取相交矩形`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的矩形` (`小数矩形类`)
	* `相交结果矩形` (`小数矩形类`): 本参数用作存储本矩形与所检查矩形的相交部分,如果没有相交,则将被清零.
* **描述:** 返回本矩形是否与所指定矩形具有相交部分并将 相交部分矩形填入所指定参数中

##### 火山.基本.小数矩形类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.位置类

* **类型:** `类`
* **名称:** `位置类`
* **基础类:** `扩展对象类`
* **描述:** 用作记录一个横纵向位置数据
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.位置类.横向位置

* **类型:** `属性成员变量`
* **名称:** `横向位置`
* **数据类型:** `整数`
* **相关例程:** [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.位置类.纵向位置

* **类型:** `属性成员变量`
* **名称:** `纵向位置`
* **数据类型:** `整数`
* **相关例程:** [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.位置类.到小数位置

* **类型:** `方法`
* **名称:** `到小数位置`
* **返回值数据类型:** `小数位置类`
* **描述:** 将本整数位置转换为小数位置

##### 火山.基本.位置类.清零

* **类型:** `方法`
* **名称:** `清零`

##### 火山.基本.位置类.设置

* **类型:** `方法`
* **名称:** `设置`
* **参数:**
	* `所欲设置的横向位置` (`整数`)
	* `所欲设置的纵向位置` (`整数`)
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main)

##### 火山.基本.位置类.剪切到矩形内

* **类型:** `方法`
* **名称:** `剪切到矩形内`
* **参数:**
	* `用作剪切的矩形` (`矩形类`)
* **描述:** 将本位置剪切到所指定矩形内

##### 火山.基本.位置类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.位置数组类

* **类型:** `类`
* **名称:** `位置数组类`
* **模板基础类:** `对象数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `位置类`

---

#### 火山.基本.小数位置类

* **类型:** `类`
* **名称:** `小数位置类`
* **基础类:** `扩展对象类`
* **描述:** 用作记录一个横纵向小数位置数据

##### 火山.基本.小数位置类.横向位置

* **类型:** `属性成员变量`
* **名称:** `横向位置`
* **数据类型:** `小数`

##### 火山.基本.小数位置类.纵向位置

* **类型:** `属性成员变量`
* **名称:** `纵向位置`
* **数据类型:** `小数`

##### 火山.基本.小数位置类.到位置

* **类型:** `方法`
* **名称:** `到位置`
* **返回值数据类型:** `位置类`
* **描述:** 将本小数位置转换为整数位置,注意将会存在精度转换误差.

##### 火山.基本.小数位置类.清零

* **类型:** `方法`
* **名称:** `清零`

##### 火山.基本.小数位置类.设置

* **类型:** `方法`
* **名称:** `设置`
* **参数:**
	* `所欲设置的横向位置` (`小数`)
	* `所欲设置的纵向位置` (`小数`)

##### 火山.基本.小数位置类.剪切到矩形内

* **类型:** `方法`
* **名称:** `剪切到矩形内`
* **参数:**
	* `用作剪切的矩形` (`小数矩形类`)
* **描述:** 将本位置剪切到所指定矩形内

##### 火山.基本.小数位置类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.尺寸类

* **类型:** `类`
* **名称:** `尺寸类`
* **基础类:** `扩展对象类`
* **描述:** 用作记录一个尺寸数据
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-被调用部件动态链接库-com_dll-main](#vol-被调用部件动态链接库-com_dll-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main)

##### 火山.基本.尺寸类.宽度

* **类型:** `属性成员变量`
* **名称:** `宽度`
* **数据类型:** `整数`
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-被调用部件动态链接库-com_dll-main](#vol-被调用部件动态链接库-com_dll-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main)

##### 火山.基本.尺寸类.高度

* **类型:** `属性成员变量`
* **名称:** `高度`
* **数据类型:** `整数`
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-被调用部件动态链接库-com_dll-main](#vol-被调用部件动态链接库-com_dll-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main)

##### 火山.基本.尺寸类.到小数尺寸

* **类型:** `方法`
* **名称:** `到小数尺寸`
* **返回值数据类型:** `小数尺寸类`
* **描述:** 将本整数尺寸转换为小数尺寸

##### 火山.基本.尺寸类.清零

* **类型:** `方法`
* **名称:** `清零`

##### 火山.基本.尺寸类.设置

* **类型:** `方法`
* **名称:** `设置`
* **参数:**
	* `所欲设置的宽度` (`整数`)
	* `所欲设置的高度` (`整数`)
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

##### 火山.基本.尺寸类.为零尺寸

* **类型:** `方法`
* **名称:** `为零尺寸`
* **返回值数据类型:** `逻辑型`

##### 火山.基本.尺寸类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.小数尺寸类

* **类型:** `类`
* **名称:** `小数尺寸类`
* **基础类:** `扩展对象类`
* **描述:** 用作记录一个小数尺寸数据

##### 火山.基本.小数尺寸类.宽度

* **类型:** `属性成员变量`
* **名称:** `宽度`
* **数据类型:** `小数`

##### 火山.基本.小数尺寸类.高度

* **类型:** `属性成员变量`
* **名称:** `高度`
* **数据类型:** `小数`

##### 火山.基本.小数尺寸类.到尺寸

* **类型:** `方法`
* **名称:** `到尺寸`
* **返回值数据类型:** `尺寸类`
* **描述:** 将本小数尺寸转换为整数尺寸,注意将会存在精度转换误差.

##### 火山.基本.小数尺寸类.清零

* **类型:** `方法`
* **名称:** `清零`

##### 火山.基本.小数尺寸类.设置

* **类型:** `方法`
* **名称:** `设置`
* **参数:**
	* `所欲设置的宽度` (`小数`)
	* `所欲设置的高度` (`小数`)

##### 火山.基本.小数尺寸类.为零尺寸

* **类型:** `方法`
* **名称:** `为零尺寸`
* **返回值数据类型:** `逻辑型`

##### 火山.基本.小数尺寸类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.算术运算类

* **类型:** `类`
* **名称:** `算术运算类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)

##### 火山.基本.算术运算类.小数是否为零

* **类型:** `全局方法`
* **名称:** `小数是否为零`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的小数值` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回所指定的小数是否近似为0. 由于小数值存在精度误差,因此检查小数值是否为0最好不要直接与0进行比较,使用本方法替代.

##### 火山.基本.算术运算类.小数是否相等

* **类型:** `全局方法`
* **名称:** `小数是否相等`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲检查的小数值1` (`小数`)
	* `欲检查的小数值2` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回两个所指定的小数是否近似相等. 由于小数值存在精度误差,因此检查小数值是否相等最好不要直接进行比较,使用本方法替代.
* **相关例程:** [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main)

##### 火山.基本.算术运算类.取较小值

* **类型:** `全局方法`
* **名称:** `取较小值`
* **返回值数据类型:** `调用本方法时为"待比较数值1"参数所提供数据的实际类型`
* **参数:**
	* `待比较数值1` (`通用数值型`)
	* `待比较数值2` (`等于前参数值类型`)
* **特性:**
	* `静态`
* **描述:** 返回两个同类型数值中较小的那个

##### 火山.基本.算术运算类.取较大值

* **类型:** `全局方法`
* **名称:** `取较大值`
* **返回值数据类型:** `调用本方法时为"待比较数值1"参数所提供数据的实际类型`
* **参数:**
	* `待比较数值1` (`通用数值型`)
	* `待比较数值2` (`等于前参数值类型`)
* **特性:**
	* `静态`
* **描述:** 返回两个同类型数值中较大的那个
* **相关例程:** [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.算术运算类.取较小值3

* **类型:** `全局方法`
* **名称:** `取较小值3`
* **返回值数据类型:** `调用本方法时为"待比较数值1"参数所提供数据的实际类型`
* **参数:**
	* `待比较数值1` (`通用数值型`)
	* `待比较数值2` (`等于前参数值类型`)
	* `待比较数值3` (`等于前参数值类型`)
* **特性:**
	* `静态`
* **描述:** 返回三个同类型数值中最小的那个

##### 火山.基本.算术运算类.取较大值3

* **类型:** `全局方法`
* **名称:** `取较大值3`
* **返回值数据类型:** `调用本方法时为"待比较数值1"参数所提供数据的实际类型`
* **参数:**
	* `待比较数值1` (`通用数值型`)
	* `待比较数值2` (`等于前参数值类型`)
	* `待比较数值3` (`等于前参数值类型`)
* **特性:**
	* `静态`
* **描述:** 返回三个同类型数值中最大的那个

##### 火山.基本.算术运算类.剪切值

* **类型:** `全局方法`
* **名称:** `剪切值`
* **返回值数据类型:** `调用本方法时为"待检查数值"参数所提供数据的实际类型`
* **参数:**
	* `待检查数值` (`通用数值型`)
	* `所允许的最小值` (`等于前参数值类型`): 如果所指定数值小于此值,则返回此值.
	* `所允许的最大值` (`等于前参数值类型`): 如果所指定数值大于此值,则返回此值.
* **特性:**
	* `静态`
* **描述:** 如果所指定数值小于所提供的最小值,则返回该最小值,如果所指定数值大于所提供的最大值,则返回该最大值,否则返回该数值本身.

##### 火山.基本.算术运算类.小数整除

* **类型:** `全局方法`
* **名称:** `小数整除`
* **返回值数据类型:** `小数`
* **参数:**
	* `被除数` (`小数`)
	* `除数` (`小数`): 如果除数为0,本方法将返回0.
* **特性:**
	* `静态`
* **描述:** 将两个小数相除,返回其整数部分.

##### 火山.基本.算术运算类.求余数

* **类型:** `全局方法`
* **名称:** `求余数`
* **返回值数据类型:** `小数`
* **参数:**
	* `被除数` (`小数`)
	* `除数` (`小数`): 如果除数为0,本方法将返回0.
* **特性:**
	* `静态`
* **描述:** 将两个小数相除,返回其余数部分.

##### 火山.基本.算术运算类.取符号

* **类型:** `全局方法`
* **名称:** `取符号`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲判断的数值` (`通用数值型`)
* **特性:**
	* `静态`
* **描述:** 返回一个整数,如果小于零,表明给定数值为负,如果等于零,表明给定数值为零,如果大于零,表明给定数值为正.

##### 火山.基本.算术运算类.取整数绝对值

* **类型:** `全局方法`
* **名称:** `取整数绝对值`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲处理的整数值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 返回所指定整数的绝对值
* **相关例程:** [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main)

##### 火山.基本.算术运算类.取长整数绝对值

* **类型:** `全局方法`
* **名称:** `取长整数绝对值`
* **返回值数据类型:** `长整数`
* **参数:**
	* `所欲处理的长整数值` (`长整数`)
* **特性:**
	* `静态`
* **描述:** 返回所指定长整数的绝对值

##### 火山.基本.算术运算类.取小数绝对值

* **类型:** `全局方法`
* **名称:** `取小数绝对值`
* **返回值数据类型:** `小数`
* **参数:**
	* `所欲处理的小数值` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回所指定小数的绝对值
* **相关例程:** [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.算术运算类.取整

* **类型:** `全局方法`
* **名称:** `取整`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲处理的小数值` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个小数的整数部分. 本命令与"小数绝对取整"命令不相同之处为: 如果给定小数为负数,则本方法返回小于或等于该小数的第一个负整数,而"小数绝对取整"方法则会返回大于或等于该小数的第一个负整数. 例如,本命令将 -7.8 转换成 -8, 而"小数绝对取整"命令将 -7.8 转换成 -7 .
* **相关例程:** [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.算术运算类.绝对取整

* **类型:** `全局方法`
* **名称:** `绝对取整`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲处理的小数值` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回一个小数的整数部分. 本方法与"小数取整"命令不相同之处为: 如果给定小数为负数,则本方法返回大于或等于该小数的第一个负整数,而"小数取整"方法则会返回小于或等于该小数的第一个负整数. 例如,本命令将 -7.8 转换成 -7, 而"小数取整"命令将 -7.8 转换成 -8 .

##### 火山.基本.算术运算类.四舍五入

* **类型:** `全局方法`
* **名称:** `四舍五入`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲被四舍五入的值` (`小数`)
	* `被舍入的位置` (`整数`, 默认值: `0`): 如果大于0,表示小数点右边应保留的位数; 如果等于0,表示舍入到整数; 如果小于0,表示小数点左边舍入到的位置. 例如: 四舍五入 (1056.65, 1) 返回 1056.7; 四舍五入 (1056.65, 0) 返回 1057; 四舍五入 (1056.65, -1) 返回 1060.
* **特性:**
	* `静态`
* **描述:** 返回按照指定的方式进行四舍五入运算的结果数值
* **相关例程:** [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-人脸性别识别-gender_recognition-main](#vol-人脸性别识别-gender_recognition-main), [vol-相关性多模板匹配-ncc_matching-main](#vol-相关性多模板匹配-ncc_matching-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.算术运算类.求次方

* **类型:** `全局方法`
* **名称:** `求次方`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求次方数值` (`小数`): 指定欲求其某次方的数值
	* `次方数` (`小数`): 指定对欲求次方数值的运算指数
* **特性:**
	* `静态`
* **描述:** 返回指定数值的指定次方
* **相关例程:** [vol-dnn文本检测-dnn_text_detection_recognition-main](#vol-dnn文本检测-dnn_text_detection_recognition-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.算术运算类.求平方根

* **类型:** `全局方法`
* **名称:** `求平方根`
* **返回值数据类型:** `小数`
* **参数:**
	* `所欲处理的数值` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回指定数值的平方根
* **相关例程:** [vol-dnn文本检测-dnn_text_detection_recognition-main](#vol-dnn文本检测-dnn_text_detection_recognition-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main)

##### 火山.基本.算术运算类.弧度到角度

* **类型:** `全局方法`
* **名称:** `弧度到角度`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲转换的角度值` (`小数`): 以弧度为单位
* **特性:**
	* `静态`
* **描述:** 将所指定以弧度为单位的角度值转换为以度为单位

##### 火山.基本.算术运算类.角度到弧度

* **类型:** `全局方法`
* **名称:** `角度到弧度`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲转换的角度值` (`小数`): 以度为单位
* **特性:**
	* `静态`
* **描述:** 将所指定以度为单位的角度值转换为以弧度为单位

##### 火山.基本.算术运算类.求正弦

* **类型:** `全局方法`
* **名称:** `求正弦`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲进行计算的角` (`小数`): 所使用单位为弧度
* **特性:**
	* `静态`
* **描述:** 返回指定角的正弦值
* **相关例程:** [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.算术运算类.求余弦

* **类型:** `全局方法`
* **名称:** `求余弦`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲进行计算的角` (`小数`): 所使用单位为弧度
* **特性:**
	* `静态`
* **描述:** 返回指定角的余弦值
* **相关例程:** [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.算术运算类.求正切

* **类型:** `全局方法`
* **名称:** `求正切`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲进行计算的角` (`小数`): 所使用单位为弧度
* **特性:**
	* `静态`
* **描述:** 返回指定角的正切值

##### 火山.基本.算术运算类.求反正切

* **类型:** `全局方法`
* **名称:** `求反正切`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲进行计算的角` (`小数`): 所使用单位为弧度
* **特性:**
	* `静态`
* **描述:** 返回指定角的反正切值

##### 火山.基本.算术运算类.求自然对数

* **类型:** `全局方法`
* **名称:** `求自然对数`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求其自然对数的值` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回指定参数的自然对数值. 自然对数是以 E 为底的对数.

##### 火山.基本.算术运算类.求反对数

* **类型:** `全局方法`
* **名称:** `求反对数`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求其反对数的值` (`小数`): 注意如果参数值超过 709.782712893 ,将导致计算溢出.
* **特性:**
	* `静态`
* **描述:** 返回 E（自然对数的底）的某次方

##### 火山.基本.算术运算类.是否运算正确

* **类型:** `全局方法`
* **名称:** `是否运算正确`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲检查的小数值` (`小数`)
* **特性:**
	* `静态`
* **描述:** 对乘/除/求次方/求平方根/求正弦值/求余弦值/求正切值/求反正切值/求自然对数/求反对数 等各种数学运算方法所计算出来的双精度结果数值进行校验,如果该数值正确有效,返回真.如果该数值是运算错误或运算溢出后的结果,返回假.

##### 火山.基本.算术运算类.置随机数种子

* **类型:** `全局方法`
* **名称:** `置随机数种子`
* **参数:**
	* `欲置入的种子数值` (`整数`, 默认值: `0`): 本参数值如果为0,将使用当前计算机系统的时钟毫秒值.
* **特性:**
	* `静态`
* **描述:** 为随机数生成器初始化一个种子值,不同的种子值将导致后续的取随机数系列方法返回不同的随机数系列值. 本方法的调用不是必需的,如果在未调用本方法时调用后续的取随机数系列方法,将自动首先使用一个随机值来初始化种子.
* **相关例程:** [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main)

##### 火山.基本.算术运算类.取随机数

* **类型:** `全局方法`
* **名称:** `取随机数`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲取随机数的最小值` (`整数`, 默认值: `0`)
	* `欲取随机数的最大值` (`整数`, 默认值: `数值范围.最大整数值`): 参数必须大于等于所指定的最小值
* **特性:**
	* `静态`
* **描述:** 返回一个所指定范围内的随机整数值,注意范围两侧的最小和最大值本身被包括在内.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-超级编辑框-rich_edit-main](#vol-超级编辑框-rich_edit-main), [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-ado-ado_sample-main](#vol-ado-ado_sample-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main)

##### 火山.基本.算术运算类.取随机数2

* **类型:** `全局方法`
* **名称:** `取随机数2`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲取随机数的最大值` (`整数`): 参数值必须大于等于0
* **特性:**
	* `静态`
* **描述:** 返回一个在0到所指定值之间(包括两者本身)的随机整数值
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main)

##### 火山.基本.算术运算类.取随机短整数

* **类型:** `全局方法`
* **名称:** `取随机短整数`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回一个在0到32627之间(包括两者本身)的随机整数值

##### 火山.基本.算术运算类.取随机整数

* **类型:** `全局方法`
* **名称:** `取随机整数`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回一个从0到最大整数值之间(包括两者本身)的整数值

##### 火山.基本.算术运算类.取随机小数

* **类型:** `全局方法`
* **名称:** `取随机小数`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲取随机数的最小值` (`小数`, 默认值: `0`)
	* `欲取随机数的最大值` (`小数`): 参数必须大于等于所指定的最小值
* **特性:**
	* `静态`
* **描述:** 返回一个所指定范围内的随机小数值,注意范围两侧的最小和最大值本身被包括在内.

##### 火山.基本.算术运算类.取随机小数2

* **类型:** `全局方法`
* **名称:** `取随机小数2`
* **返回值数据类型:** `小数`
* **特性:**
	* `静态`
* **描述:** 返回一个在0到1之间(包括0和1本身)的小数值

##### 火山.基本.算术运算类.合并整数

* **类型:** `全局方法`
* **名称:** `合并整数`
* **返回值数据类型:** `整数`
* **参数:**
	* `用作合并的整数1` (`整数`)
	* `用作合并的整数2` (`整数`)
* **特性:**
	* `静态`
* **描述:** 将第一个整数的低16位放置到结果整数的低16位,将第二个整数的低16位放置到结果整数的高16位,以此合并成一个整数,并返回合并后的结果.

##### 火山.基本.算术运算类.合并短整数

* **类型:** `全局方法`
* **名称:** `合并短整数`
* **返回值数据类型:** `短整数`
* **参数:**
	* `用作合并的整数1` (`整数`)
	* `用作合并的整数2` (`整数`)
* **特性:**
	* `静态`
* **描述:** 将第一个整数的低8位放置到结果短整数的低8位,将第二个整数的低8位放置到结果短整数的高8位,以此合并成一个短整数,并返回合并后的结果.

##### 火山.基本.算术运算类.求反正切2

* **类型:** `全局方法`
* **名称:** `求反正切2`
* **返回值数据类型:** `小数`
* **参数:**
	* `参数1` (`小数`)
	* `参数2` (`小数`)
* **特性:**
	* `静态`
* **描述:** 返回以弧度表示的 参数1/参数2 的反正切.反正切函数是正切函数的反函数.
* **返回值描述:** 返回单位是弧度

##### 火山.基本.算术运算类.求两直线夹角

* **类型:** `全局方法`
* **名称:** `求两直线夹角`
* **返回值数据类型:** `小数`
* **参数:**
	* `参数1` (`小数`): 直线1的斜率
	* `参数2` (`小数`): 直线2的斜率
* **特性:**
	* `静态`
* **描述:** 返回两直线夹角,采用正切公式计算两直线的夹角.
* **返回值描述:** 返回单位是弧度

##### 火山.基本.算术运算类.是否是2的幂

* **类型:** `全局方法`
* **名称:** `是否是2的幂`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `欲求值的数值` (`整数`)
* **特性:**
	* `静态`
* **描述:** 返回某数是否是2的幂

##### 火山.基本.算术运算类.求双曲正切

* **类型:** `全局方法`
* **名称:** `求双曲正切`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求双曲正切的数值` (`小数`)
* **特性:**
	* `静态`

##### 火山.基本.算术运算类.求反双曲正切

* **类型:** `全局方法`
* **名称:** `求反双曲正切`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反双曲正切的小数` (`小数`): 输入参数必须大于-1且小于1 当输入参数小于等于-1或大于等于1返回0
* **特性:**
	* `静态`
* **描述:** 反双曲正切函数是双曲正切函数的反函数

##### 火山.基本.算术运算类.求双曲余切

* **类型:** `全局方法`
* **名称:** `求双曲余切`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求双曲余切的小数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 双曲余切是双曲函数的其中一种

##### 火山.基本.算术运算类.求反双曲余切

* **类型:** `全局方法`
* **名称:** `求反双曲余切`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反双曲余切的小数` (`小数`): 输入参数必须小于-1或大于1 当输入参数大于等于-1且小于等于1时返回0
* **特性:**
	* `静态`
* **描述:** 反双曲余切函数是双曲余切函数的反函数

##### 火山.基本.算术运算类.求双曲正弦

* **类型:** `全局方法`
* **名称:** `求双曲正弦`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求双曲正弦的数值` (`小数`)
* **特性:**
	* `静态`

##### 火山.基本.算术运算类.求双曲正割

* **类型:** `全局方法`
* **名称:** `求双曲正割`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求双曲正割的小数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 双曲正割是双曲函数的其中一种

##### 火山.基本.算术运算类.求双曲余割

* **类型:** `全局方法`
* **名称:** `求双曲余割`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求双曲余割的小数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 双曲余割是双曲函数的其中一种

##### 火山.基本.算术运算类.求双曲余弦

* **类型:** `全局方法`
* **名称:** `求双曲余弦`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求双曲余弦的数值` (`小数`)
* **特性:**
	* `静态`

##### 火山.基本.算术运算类.求反双曲正弦

* **类型:** `全局方法`
* **名称:** `求反双曲正弦`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反双曲正弦的小数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 反双曲正弦函数是双曲正弦函数的反函数

##### 火山.基本.算术运算类.求反双曲余弦

* **类型:** `全局方法`
* **名称:** `求反双曲余弦`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反双曲余弦的小数` (`小数`): 输入参数必须大于等于1 当输入参数小于1时返回0
* **特性:**
	* `静态`
* **描述:** 反双曲余弦函数是双曲余弦函数的反函数

##### 火山.基本.算术运算类.求反双曲正割

* **类型:** `全局方法`
* **名称:** `求反双曲正割`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反双曲正割的小数` (`小数`): 输入参数必须大于等于0且小于等于1 当输入参数大于1或小于等于0时返回0
* **特性:**
	* `静态`
* **描述:** 反双曲正割是双曲正割函数的反函数

##### 火山.基本.算术运算类.求反双曲余割

* **类型:** `全局方法`
* **名称:** `求反双曲余割`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反双曲余割的小数` (`小数`): 输入参数必须不等于0 当输入参数等于0时返回0
* **特性:**
	* `静态`
* **描述:** 反双曲余割函数是双曲余割函数的反函数

##### 火山.基本.算术运算类.求对数

* **类型:** `全局方法`
* **名称:** `求对数`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求对数的底数` (`小数`)
	* `欲求对数的真数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 如果a的x次方等于N（a>0，且a≠1）,那么数x叫做以a为底N的对数,其中,a叫做对数的底数,N叫做真数

##### 火山.基本.算术运算类.求曲率

* **类型:** `全局方法`
* **名称:** `求曲率`
* **返回值数据类型:** `小数`
* **参数:**
	* `一阶导数` (`小数`)
	* `二阶导数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 曲线的曲率就是针对曲线上某个点的切线方向角对弧长的转动率,通过微分来定义,表明曲线偏离直线的程度

##### 火山.基本.算术运算类.求曲率半径

* **类型:** `全局方法`
* **名称:** `求曲率半径`
* **返回值数据类型:** `小数`
* **参数:**
	* `一阶导数` (`小数`)
	* `二阶导数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 曲率半径是曲率的倒数

##### 火山.基本.算术运算类.求反正割

* **类型:** `全局方法`
* **名称:** `求反正割`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反正割的小数` (`小数`): 输入参数必须大于等于1或小于等于-1
* **特性:**
	* `静态`
* **描述:** 反正割函数是正割函数的反函数

##### 火山.基本.算术运算类.求反余割

* **类型:** `全局方法`
* **名称:** `求反余割`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反余割的小数` (`小数`): 输入参数必须大于等于1或小于等于-1
* **特性:**
	* `静态`
* **描述:** 反余割函数是余割函数的反函数

##### 火山.基本.算术运算类.求反余切

* **类型:** `全局方法`
* **名称:** `求反余切`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反余切的小数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 反余切函数是余切函数的反函数

##### 火山.基本.算术运算类.求正割

* **类型:** `全局方法`
* **名称:** `求正割`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求正割的小数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 在直角三角形中,斜边与某个锐角的邻边的比,叫做该锐角的正割. 正割是余弦的倒数.

##### 火山.基本.算术运算类.求余割

* **类型:** `全局方法`
* **名称:** `求余割`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求余割的小数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 在直角三角形中,斜边与某个锐角的对边的比值,叫做该锐角的余割. 余割是正弦的倒数.

##### 火山.基本.算术运算类.求余切

* **类型:** `全局方法`
* **名称:** `求余切`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求余切的小数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 在直角三角形中,某锐角的相邻直角边和相对直角边的比,叫做该锐角的余切. 余切是正切的倒数.

##### 火山.基本.算术运算类.求反余弦

* **类型:** `全局方法`
* **名称:** `求反余弦`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反余弦的小数` (`小数`): 输入参数必须大于等于-1或小于等于1
* **特性:**
	* `静态`
* **描述:** 反余弦函数为余弦函数的反函数

##### 火山.基本.算术运算类.求反正弦

* **类型:** `全局方法`
* **名称:** `求反正弦`
* **返回值数据类型:** `小数`
* **参数:**
	* `欲求反正弦的小数` (`小数`)
* **特性:**
	* `静态`
* **描述:** 反正弦函数为正弦函数的反函数

##### 火山.基本.算术运算类.求整数最大公因数

* **类型:** `全局方法`
* **名称:** `求整数最大公因数`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲求最大公因数的整数1` (`整数`)
	* `欲求最大公因数的整数2` (`整数`)
* **特性:**
	* `静态`
* **描述:** 如果一个整数同时是几个整数的因数,称这个整数为它们的公因数.公因数中最大的称为最大公因数.

##### 火山.基本.算术运算类.求整数阶乘

* **类型:** `全局方法`
* **名称:** `求整数阶乘`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲求阶乘的整数` (`整数`)
* **特性:**
	* `静态`
* **描述:** 一个正整数的阶乘是所有小于及等于该数的正整数的积

---

#### 火山.基本.数值转换类

* **类型:** `类`
* **名称:** `数值转换类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **文档分类:** `数值转换`
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main)

##### 火山.基本.数值转换类.无符号字节到整数

* **类型:** `全局方法`
* **名称:** `无符号字节到整数`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲转换的字节` (`字节`)
* **特性:**
	* `静态`
* **描述:** 将所指定的字节以无符号的形式转换到整数. 所谓无符号,即转换时忽略掉字节的最高符号位,认为其始终为正数.
* **相关例程:** [vol-被调用动态链接库-dll_test-main](#vol-被调用动态链接库-dll_test-main)

##### 火山.基本.数值转换类.无符号短整数到整数

* **类型:** `全局方法`
* **名称:** `无符号短整数到整数`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲转换的短整数` (`短整数`)
* **特性:**
	* `静态`
* **描述:** 将所指定的短整数以无符号的形式转换到整数. 所谓无符号,即转换时忽略掉短整数的最高符号位,认为其始终为正数.

##### 火山.基本.数值转换类.无符号字符到整数

* **类型:** `全局方法`
* **名称:** `无符号字符到整数`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲转换的字符` (`字符`)
* **特性:**
	* `静态`
* **描述:** 将所指定的字符值以无符号的形式转换到整数. 所谓无符号,即转换时忽略掉字符值的最高符号位,认为其始终为正数.

##### 火山.基本.数值转换类.无符号整数到长整数

* **类型:** `全局方法`
* **名称:** `无符号整数到长整数`
* **返回值数据类型:** `长整数`
* **参数:**
	* `所欲转换的整数` (`整数`)
* **特性:**
	* `静态`
* **描述:** 将所指定的整数以无符号的形式转换到长整数. 所谓无符号,即转换时忽略掉整数的最高符号位,认为其始终为正数.

##### 火山.基本.数值转换类.文本到短整数

* **类型:** `全局方法`
* **名称:** `文本到短整数`
* **返回值数据类型:** `短整数`
* **参数:**
	* `所欲转换的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定文本转换到短整数并返回

##### 火山.基本.数值转换类.文本到整数

* **类型:** `全局方法`
* **名称:** `文本到整数`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲转换的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定文本转换到整数并返回
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-树形框-tree_box-main](#vol-树形框-tree_box-main), [vol-状态条-status_bar-main](#vol-状态条-status_bar-main), [vol-表格-grid-main](#vol-表格-grid-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-tcp转发-tcp_forward-main](#vol-tcp转发-tcp_forward-main), [vol-数据报-udp-main](#vol-数据报-udp-main), [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件发送-send_email-main](#vol-邮件发送-send_email-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-redis连接池-redisconnectpool-main](#vol-redis连接池-redisconnectpool-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-形态学运算-morphological-main](#vol-形态学运算-morphological-main)

##### 火山.基本.数值转换类.文本到长整数

* **类型:** `全局方法`
* **名称:** `文本到长整数`
* **返回值数据类型:** `长整数`
* **参数:**
	* `所欲转换的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定文本转换到长整数并返回
* **相关例程:** [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main)

##### 火山.基本.数值转换类.文本到单精度小数

* **类型:** `全局方法`
* **名称:** `文本到单精度小数`
* **返回值数据类型:** `单精度小数`
* **参数:**
	* `所欲转换的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定文本转换到单精度小数并返回

##### 火山.基本.数值转换类.文本到小数

* **类型:** `全局方法`
* **名称:** `文本到小数`
* **返回值数据类型:** `小数`
* **参数:**
	* `所欲转换的文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定文本转换到小数并返回
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-控制台程序-console_demo-main](#vol-控制台程序-console_demo-main), [vol-mfc控制台程序-mfc_console-main](#vol-mfc控制台程序-mfc_console-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.数值转换类.文本到逻辑值

* **类型:** `全局方法`
* **名称:** `文本到逻辑值`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲转换的文本` (`文本型`): 提供所欲转换到逻辑值的文本内容(其首尾空白文本被忽略),"真"/"true"(不区分大小写)/"1"被转换为逻辑值真,其它文本内容被转换为逻辑值假.
* **特性:**
	* `静态`
* **描述:** 将所指定文本转换到逻辑值并返回
* **相关例程:** [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main)

##### 火山.基本.数值转换类.取十六进制文本

* **类型:** `全局方法`
* **名称:** `取十六进制文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的整数` (`整数`)
	* `所需要的最小宽度` (`整数`, 默认值: `0`): 指定所需求的最小宽度(数字数目),如果有效数值宽度小于该值,则自动在首部加0. 为0表示去除所有的前置'0'数字.
* **特性:**
	* `静态`
* **描述:** 返回所指定整数所对应的十六进制文本
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main)

##### 火山.基本.数值转换类.取长整数十六进制文本

* **类型:** `全局方法`
* **名称:** `取长整数十六进制文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的长整数` (`长整数`)
	* `所需要的最小宽度` (`整数`, 默认值: `0`): 指定所需求的最小宽度(数字数目),如果有效数值宽度小于该值,则自动在首部加0. 为0表示去除所有的前置'0'数字.
* **特性:**
	* `静态`
* **描述:** 返回所指定长整数所对应的十六进制文本

##### 火山.基本.数值转换类.取变整数十六进制文本

* **类型:** `全局方法`
* **名称:** `取变整数十六进制文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的变整数` (`变整数`)
	* `所需要的最小宽度` (`整数`, 默认值: `0`): 指定所需求的最小宽度(数字数目),如果有效数值宽度小于该值,则自动在首部加0. 为0表示去除所有的前置'0'数字.
* **特性:**
	* `静态`
* **描述:** 返回所指定变整数所对应的十六进制文本

##### 火山.基本.数值转换类.数值到大写

* **类型:** `全局方法`
* **名称:** `数值到大写`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的数值` (`小数`): 提供所欲转换的数值,其小数位被舍入到两位.
	* `是否转化为简体` (`逻辑型`, 默认值: `假`): 为真转换为简体,为假则转换为繁体.
* **特性:**
	* `静态`
* **描述:** 将数值转换为简体或繁体的大写形式,返回转换后的文本.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main)

##### 火山.基本.数值转换类.数值到金融

* **类型:** `全局方法`
* **名称:** `数值到金融`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲转换的数值` (`小数`): 提供所欲转换的数值,其小数位被舍入到两位.
	* `是否转化为简体` (`逻辑型`, 默认值: `假`): 为真转换为简体,为假则转换为繁体.
* **特性:**
	* `静态`
* **描述:** 将数值转换为货币的简体或繁体大写形式,返回转换后的文本.

##### 火山.基本.数值转换类.数值到格式文本

* **类型:** `全局方法`
* **名称:** `数值到格式文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `欲转换为文本的数值` (`小数`)
	* `小数保留位数` (`整数`, 默认值: `数值范围.最大整数值`): 如果大于0,表示小数点右边应四舍五入保留的位数; 如果等于0.表示舍入到整数;如果小于0,表示小数点左边舍入到的位置.如果为"数值范围.最大整数值",则保留所有实际存在的小数位. 例如: 数值到格式文本 (66.66, 1, 假) 将返回"66.7"; 数值到格式文本 (66.66, 0, 假)将返回"67";  数值到格式文本 (66.66, -1, 假) 将返回"70".
	* `是否进行千分位分隔` (`逻辑型`, 默认值: `假`): 如果为真,数值文本的每个千分位上都将被自动插入一个逗号进行分隔.
* **特性:**
	* `静态`
* **描述:** 将指定数值转换到所指定的格式化文本后返回
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main)

##### 火山.基本.数值转换类.反转整数字节序

* **类型:** `全局方法`
* **名称:** `反转整数字节序`
* **返回值数据类型:** `整数`
* **参数:**
	* `所欲反转的整数` (`整数`)
* **特性:**
	* `静态`
* **描述:** 将所指定整数的组成字节的顺序反转,返回反转后的结果值.譬如十六进制整数0x12345678,反转后将返回0x78563412. 本命令在与类似Java这样的语言进行数据交互时很有用处.

##### 火山.基本.数值转换类.反转长整数字节序

* **类型:** `全局方法`
* **名称:** `反转长整数字节序`
* **返回值数据类型:** `长整数`
* **参数:**
	* `所欲反转的长整数` (`长整数`)
* **特性:**
	* `静态`
* **描述:** 将所指定长整数的组成字节的顺序反转,返回反转后的结果值.譬如十六进制整数0x12345678,反转后将返回0x78563412. 本命令在与类似Java这样的语言进行数据交互时很有用处.

##### 火山.基本.数值转换类.十六进制文本到整数

* **类型:** `全局方法`
* **名称:** `十六进制文本到整数`
* **返回值数据类型:** `整数`
* **参数:**
	* `十六进制文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定的十六进制文本(可以以"0x"开头)转换为对应的整数值并返回

##### 火山.基本.数值转换类.十六进制文本到长整数

* **类型:** `全局方法`
* **名称:** `十六进制文本到长整数`
* **返回值数据类型:** `长整数`
* **参数:**
	* `十六进制文本` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 将所指定的十六进制文本(可以以"0x"开头)转换为对应的长整数值并返回

---

#### 火山.基本.程序基础类

* **类型:** `类`
* **名称:** `程序基础类`
* **特性:**
	* `抽象类`(禁止直接定义其实例变量)

---

#### 火山.基本.程序类

* **类型:** `类`
* **名称:** `程序类`
* **基础类:** `程序基础类`
* **特性:**
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
	* `抽象类`(禁止直接定义其实例变量)
* **描述:** 用户定义的启动类必须直接或间接以此类作为基础类
* **相关例程:** [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-日志记录-plog-main](#vol-日志记录-plog-main), [vol-接口封装-impl_interface-main](#vol-接口封装-impl_interface-main), [vol-本地整数数据类型-native_int_data_type-main](#vol-本地整数数据类型-native_int_data_type-main), [vol-控制台程序-console_demo-main](#vol-控制台程序-console_demo-main), [vol-mfc控制台程序-mfc_console-main](#vol-mfc控制台程序-mfc_console-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-调用mfc动态链接库-call_mfc_dll-main](#vol-调用mfc动态链接库-call_mfc_dll-main), [vol-调用部件动态链接库-com_dll_caller-main](#vol-调用部件动态链接库-com_dll_caller-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-yaml数据访问-yaml-main](#vol-yaml数据访问-yaml-main), [vol-ado-ado_sample-main](#vol-ado-ado_sample-main), [vol-条码检测-barcode_detection-main](#vol-条码检测-barcode_detection-main), [vol-特征检测与匹配-bfmatcher-main](#vol-特征检测与匹配-bfmatcher-main), [vol-斑点检测-blobs_detection-main](#vol-斑点检测-blobs_detection-main), [vol-图像滤波处理-filter-main](#vol-图像滤波处理-filter-main), [vol-人脸性别识别-gender_recognition-main](#vol-人脸性别识别-gender_recognition-main), [vol-照片上色-image_colour-main](#vol-照片上色-image_colour-main), [vol-相关性多模板匹配-ncc_matching-main](#vol-相关性多模板匹配-ncc_matching-main), [vol-风格迁移-style_migration-main](#vol-风格迁移-style_migration-main), [vol-目标跟踪-target_tracking-main](#vol-目标跟踪-target_tracking-main), [vol-yolop全景驾驶感知-yolop-main](#vol-yolop全景驾驶感知-yolop-main), [vol-yolov5目标检测-yolov5-main](#vol-yolov5目标检测-yolov5-main), [vol-人脸检测与比对-face_detection_than-main](#vol-人脸检测与比对-face_detection_than-main), [vol-轮廓查找-find_contour-main](#vol-轮廓查找-find_contour-main), [vol-灰度直方图-histogram-main](#vol-灰度直方图-histogram-main), [vol-图像二值化-threshold-main](#vol-图像二值化-threshold-main), [vol-dnn目标检测-dnn_objectdetection-main](#vol-dnn目标检测-dnn_objectdetection-main)

##### 火山.基本.程序类.取程序

* **类型:** `全局方法`
* **名称:** `取程序`
* **返回值数据类型:** `启动类`
* **特性:**
	* `静态`
* **描述:** 返回系统自动建立的全局唯一的用户启动类实例对象
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-表格-grid-main](#vol-表格-grid-main), [vol-超级菜单演示-adv_menu-main](#vol-超级菜单演示-adv_menu-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-cximage高级图像处理-cximage-main](#vol-cximage高级图像处理-cximage-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-密码管理-pw-main](#vol-密码管理-pw-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-ado-ado_sample-main](#vol-ado-ado_sample-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main)

##### 火山.基本.程序类.取全局对象

* **类型:** `全局方法`
* **名称:** `取全局对象`
* **返回值数据类型:** `对象类`
* **参数:**
	* `所欲获取对象类型` (`对象类(需求:数据类型)`): 提供所欲获取全局对象的类型
* **特性:**
	* `静态`
* **描述:** 获取指定类型对象类的唯一性全局实例. 如果该类型的全局对象尚不存在,则自动创建一个新对象并记录到系统数组中返回,否则直接返回在系统数组中的已有全局类对象. 本方法支持在多线程环境中运行. 当用户程序退出时,系统将自动释放所有已有的全局对象.

##### 火山.基本.程序类.投递退出消息

* **类型:** `全局方法`
* **名称:** `投递退出消息`
* **参数:**
	* `退出码` (`整数`)
* **特性:**
	* `静态`
* **描述:** 向Windows消息队列发送一个退出消息,通知其退出消息队列处理. 如果使用系统所提供的各种界面库,不需要调用本方法,否则在程序主窗口关闭的时候,需要调用本方法退出消息队列处理,否则程序将不会结束.

##### 火山.基本.程序类.取用户程序名称

* **类型:** `全局方法`
* **名称:** `取用户程序名称`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回在项目设置里面所设置的程序名称

##### 火山.基本.程序类.取用户程序版本号

* **类型:** `全局方法`
* **名称:** `取用户程序版本号`
* **返回值数据类型:** `小数`
* **特性:**
	* `静态`
* **描述:** 返回在项目设置里面所设置的程序版本号

##### 火山.基本.程序类.取用户程序次版本号

* **类型:** `全局方法`
* **名称:** `取用户程序次版本号`
* **返回值数据类型:** `小数`
* **特性:**
	* `静态`
* **描述:** 返回在项目设置里面所设置的程序次版本号

##### 火山.基本.程序类.取用户程序版本名

* **类型:** `全局方法`
* **名称:** `取用户程序版本名`
* **返回值数据类型:** `文本型`
* **特性:**
	* `静态`
* **描述:** 返回在项目设置里面所设置的程序版本名称文本

##### 火山.基本.程序类.取火山平台版本号

* **类型:** `全局方法`
* **名称:** `取火山平台版本号`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回编译此程序时所使用的火山平台版本号

---

#### 火山.基本.窗口程序类

* **类型:** `类`
* **名称:** `窗口程序类`
* **基础类:** `程序类`
* **特性:**
	* `抽象类`(禁止直接定义其实例变量)
* **描述:** 基于窗口的用户程序的启动类可以选择以此类作为基础类
* **相关例程:** [vol-选择夹1-tab_demo-main](#vol-选择夹1-tab_demo-main), [vol-选择夹2-tab_demo-main](#vol-选择夹2-tab_demo-main), [vol-选择夹3-tab_demo3-main](#vol-选择夹3-tab_demo3-main), [vol-对话框-dialog_test-main](#vol-对话框-dialog_test-main), [vol-文件浏览-file_viewer-main](#vol-文件浏览-file_viewer-main), [vol-时钟-timer-main](#vol-时钟-timer-main), [vol-超级列表框-listview-main](#vol-超级列表框-listview-main), [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-树形框-tree_box-main](#vol-树形框-tree_box-main), [vol-超级编辑框-rich_edit-main](#vol-超级编辑框-rich_edit-main), [vol-工具条-tool_bar-main](#vol-工具条-tool_bar-main), [vol-状态条-status_bar-main](#vol-状态条-status_bar-main), [vol-日期框-date_box-main](#vol-日期框-date_box-main), [vol-表格-grid-main](#vol-表格-grid-main), [vol-火花代码编辑框-codeedittext-main](#vol-火花代码编辑框-codeedittext-main), [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main), [vol-半透明图片演示-alpha_pic_draw-main](#vol-半透明图片演示-alpha_pic_draw-main), [vol-卷帘式菜单-outbar-main](#vol-卷帘式菜单-outbar-main), [vol-动画框_打靶-cartoon_box_shooting-main](#vol-动画框_打靶-cartoon_box_shooting-main), [vol-属性表格-property_grid-main](#vol-属性表格-property_grid-main), [vol-带按钮列表框-vs_list_box-main](#vol-带按钮列表框-vs_list_box-main), [vol-媒体播放器-win_media_player-main](#vol-媒体播放器-win_media_player-main), [vol-设计并处理重叠界面-over_ui-main](#vol-设计并处理重叠界面-over_ui-main), [vol-超级菜单演示-adv_menu-main](#vol-超级菜单演示-adv_menu-main), [vol-窗口组件动态消息过滤-msg_filter-main](#vol-窗口组件动态消息过滤-msg_filter-main), [vol-图片组动态修改-change_image_list-main](#vol-图片组动态修改-change_image_list-main), [vol-cef浏览器-cef-main](#vol-cef浏览器-cef-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-edge浏览框扩展-webview2_extensions-main](#vol-edge浏览框扩展-webview2_extensions-main), [vol-edge浏览框自定义菜单-webview2_contextmenu-main](#vol-edge浏览框自定义菜单-webview2_contextmenu-main), [vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main](#vol-edge浏览器屏幕捕获和区域拖动-webview2_drag-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-用户自定义窗口组件-user_control-main](#vol-用户自定义窗口组件-user_control-main), [vol-祖国您好-base_test-main](#vol-祖国您好-base_test-main), [vol-菜单-menu_demo-main](#vol-菜单-menu_demo-main), [vol-打印测试-print_test-main](#vol-打印测试-print_test-main), [vol-空对象测试-null_object_test-main](#vol-空对象测试-null_object_test-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-取可执行文件位数-read_exe_bits-main](#vol-取可执行文件位数-read_exe_bits-main), [vol-位图处理-adv_bitmap-main](#vol-位图处理-adv_bitmap-main), [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-二维码生成-qrencode-main](#vol-二维码生成-qrencode-main), [vol-win10通知-wintoast-main](#vol-win10通知-wintoast-main), [vol-cximage高级图像处理-cximage-main](#vol-cximage高级图像处理-cximage-main), [vol-程序崩溃回调-breakpad-main](#vol-程序崩溃回调-breakpad-main), [vol-调用外部cpp代码-call_cpp-main](#vol-调用外部cpp代码-call_cpp-main), [vol-文本编码转换-libiconv-main](#vol-文本编码转换-libiconv-main), [vol-内存映射文件-filemapping-main](#vol-内存映射文件-filemapping-main), [vol-系统全局热键-syshotkey-main](#vol-系统全局热键-syshotkey-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-任务栏操作-taskbarlist-main](#vol-任务栏操作-taskbarlist-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main), [vol-soundtouch音频处理-soundtouch-main](#vol-soundtouch音频处理-soundtouch-main), [vol-邮件槽-mailslot-main](#vol-邮件槽-mailslot-main), [vol-命名管道-namedpipe-main](#vol-命名管道-namedpipe-main), [vol-内存模块-memorymodule-main](#vol-内存模块-memorymodule-main), [vol-演示exe-sampleexe-main](#vol-演示exe-sampleexe-main), [vol-多线程-muti_thread-main](#vol-多线程-muti_thread-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-条件编译项目1-cond_compile1-main](#vol-条件编译项目1-cond_compile1-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-调用动态链接库-dll_call-main](#vol-调用动态链接库-dll_call-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-一步一步跟我学火山-step_by_step-main](#vol-一步一步跟我学火山-step_by_step-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-密码管理-pw-main](#vol-密码管理-pw-main), [vol-json数据访问-json-main](#vol-json数据访问-json-main), [vol-xml数据访问-xml-main](#vol-xml数据访问-xml-main), [vol-树结构访问-treestruct-main](#vol-树结构访问-treestruct-main), [vol-正则表达式-deelx_regular-main](#vol-正则表达式-deelx_regular-main), [vol-网页解析-html_parser-main](#vol-网页解析-html_parser-main), [vol-高级网页解析-adv_html_parser-main](#vol-高级网页解析-adv_html_parser-main), [vol-openssl数据操作-opensslsample-main](#vol-openssl数据操作-opensslsample-main), [vol-大整数运算-bnsample-main](#vol-大整数运算-bnsample-main), [vol-哈希表-hash_map-main](#vol-哈希表-hash_map-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main), [vol-高性能键值表-mmkv-main](#vol-高性能键值表-mmkv-main), [vol-cron时间表达式-cron-main](#vol-cron时间表达式-cron-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-正则表达式2-regex-main](#vol-正则表达式2-regex-main), [vol-yyjson数据访问-yyjson-main](#vol-yyjson数据访问-yyjson-main), [vol-rar文件解压-unrar-main](#vol-rar文件解压-unrar-main), [vol-数学公式计算-math_exp_calc-main](#vol-数学公式计算-math_exp_calc-main), [vol-markdown解析-markdown-main](#vol-markdown解析-markdown-main), [vol-串口通讯-cserialport-main](#vol-串口通讯-cserialport-main), [vol-摄像头操作-directshow-main](#vol-摄像头操作-directshow-main), [vol-curl网络传输-curlsample-main](#vol-curl网络传输-curlsample-main), [vol-tcp转发-tcp_forward-main](#vol-tcp转发-tcp_forward-main), [vol-数据报-udp-main](#vol-数据报-udp-main), [vol-聊天室客户端-chat_client-main](#vol-聊天室客户端-chat_client-main), [vol-聊天室服务器-chat_server-main](#vol-聊天室服务器-chat_server-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件发送-send_email-main](#vol-邮件发送-send_email-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-跨平台http通讯演示客户端-httpclient-main](#vol-跨平台http通讯演示客户端-httpclient-main), [vol-简单http服务器-http_server-main](#vol-简单http服务器-http_server-main), [vol-简单pack客户端-pack_client-main](#vol-简单pack客户端-pack_client-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull客户端-pull_client-main](#vol-简单pull客户端-pull_client-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp客户端-tcp_client-main](#vol-简单tcp客户端-tcp_client-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-线程池异步任务-threadpool-main](#vol-线程池异步任务-threadpool-main), [vol-简单udp客户端-udp_client-main](#vol-简单udp客户端-udp_client-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-pack文件传送客户端-hp_packfile_client-main](#vol-pack文件传送客户端-hp_packfile_client-main), [vol-pack文件传送服务器-hp_packfile_server-main](#vol-pack文件传送服务器-hp_packfile_server-main), [vol-pull文件传送客户端-hp_pullfile_client-main](#vol-pull文件传送客户端-hp_pullfile_client-main), [vol-pull文件传送服务器-hp_pullfile_server-main](#vol-pull文件传送服务器-hp_pullfile_server-main), [vol-tcp文件传送客户端-hp_tcpfile_client-main](#vol-tcp文件传送客户端-hp_tcpfile_client-main), [vol-tcp文件传送服务器-hp_tcpfile_server-main](#vol-tcp文件传送服务器-hp_tcpfile_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-客户端-client-main](#vol-客户端-client-main), [vol-远程服务聊天室服务器-rpc_chat_server-main](#vol-远程服务聊天室服务器-rpc_chat_server-main), [vol-远程服务聊天室客户端-rpc_chat_client-main](#vol-远程服务聊天室客户端-rpc_chat_client-main), [vol-mysql-mysqlsample-main](#vol-mysql-mysqlsample-main), [vol-sqlite3-sqlite3-main](#vol-sqlite3-sqlite3-main), [vol-redis-redis-main](#vol-redis-redis-main), [vol-redis连接池-redisconnectpool-main](#vol-redis连接池-redisconnectpool-main), [vol-mysql连接池-mysql_connectionpool-main](#vol-mysql连接池-mysql_connectionpool-main), [vol-odbc外部数据库-odbc-main](#vol-odbc外部数据库-odbc-main), [vol-python脚本-python_script-main](#vol-python脚本-python_script-main), [vol-javascript脚本-v8js-main](#vol-javascript脚本-v8js-main), [vol-elk微型js引擎-elk_js-main](#vol-elk微型js引擎-elk_js-main), [vol-阿里云oss-aliyun_oss-main](#vol-阿里云oss-aliyun_oss-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云对象存储自签名服务器-aliyunossserver-main](#vol-阿里云对象存储自签名服务器-aliyunossserver-main), [vol-抖音登陆服务器-douyinserver-main](#vol-抖音登陆服务器-douyinserver-main), [vol-手机号码认证服务器-numbercertification_server-main](#vol-手机号码认证服务器-numbercertification_server-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main), [vol-excel2021-excel2021-main](#vol-excel2021-excel2021-main), [vol-word2021-word2021-main](#vol-word2021-word2021-main), [vol-powerpoint2021-powerpoint2021-main](#vol-powerpoint2021-powerpoint2021-main), [vol-wav播放-wav_play-main](#vol-wav播放-wav_play-main), [vol-音乐播放-sound_player-main](#vol-音乐播放-sound_player-main), [vol-tts语音引擎-w_tts5_4-main](#vol-tts语音引擎-w_tts5_4-main), [vol-rvm人像抠图-rvm_segmentation-main](#vol-rvm人像抠图-rvm_segmentation-main), [vol-角点检测-corner_detection-main](#vol-角点检测-corner_detection-main), [vol-图像融合-image_fusion-main](#vol-图像融合-image_fusion-main), [vol-形态学运算-morphological-main](#vol-形态学运算-morphological-main), [vol-dnn文本检测-dnn_text_detection_recognition-main](#vol-dnn文本检测-dnn_text_detection_recognition-main), [vol-autocad时钟-cad_clock-main](#vol-autocad时钟-cad_clock-main), [vol-cad2024测试-cad_2024_test-main](#vol-cad2024测试-cad_2024_test-main), [vol-autocad2024时钟-cad_clock_2024-main](#vol-autocad2024时钟-cad_clock_2024-main)

##### 火山.基本.窗口程序类.消息过滤

* **类型:** `方法`
* **名称:** `消息过滤`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `窗口句柄` (`变整数`): 提供消息所对应的窗口句柄(HWND)
	* `消息值` (`整数`): 提供消息的具体值
	* `消息参数1` (`变整数`): 提供消息所附带的参数1的值
	* `消息参数2` (`变整数`): 提供消息所附带的参数2的值
	* `消息地址` (`变整数`): 提供消息的具体 MSG* 地址指针,用作备用.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 用户的启动类可以覆盖此方法以过滤处理程序中所有窗口的消息
* **返回值描述:** 返回真表示允许消息继续向后传递并处理,返回假表示取消掉该消息的后续处理.

##### 火山.基本.窗口程序类.空闲

* **类型:** `方法`
* **名称:** `空闲`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `已空闲时间` (`整数`): 提供自系统本次进入空闲状态后到现在所经过的空闲时间,单位为毫秒.用户程序在空闲状态下所进行的大工作量操作最好等到此值较大时进行.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 当系统正处于空闲状态时调用此方法,用户的启动类可以覆盖此方法以做一些后台处理工作.
* **返回值描述:** 返回假,在此次空闲期间系统将不再调用本方法(可以降低 CPU 占用率),返回真则将继续调用.

##### 火山.基本.窗口程序类.即将退出

* **类型:** `方法`
* **名称:** `即将退出`
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 用户的启动类可以覆盖此方法以在窗口程序退出前做一些清理工作

---

#### 火山.基本.动态库程序类

* **类型:** `类`
* **名称:** `动态库程序类`
* **基础类:** `程序类`
* **特性:**
	* `抽象类`(禁止直接定义其实例变量)
* **描述:** 动态链接库用户程序的启动类可以选择以此类作为基础类
* **相关例程:** [vol-演示dll-sampledll-main](#vol-演示dll-sampledll-main), [vol-被调用动态链接库-dll_test-main](#vol-被调用动态链接库-dll_test-main), [vol-被调用mfc动态链接库-mfc_dll-main](#vol-被调用mfc动态链接库-mfc_dll-main), [vol-被调用部件动态链接库-com_dll-main](#vol-被调用部件动态链接库-com_dll-main)

##### 火山.基本.动态库程序类.入口通知

* **类型:** `方法`
* **名称:** `入口通知`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `模块句柄` (`变整数`): 动态库自身的模块句柄
	* `调用原因` (`整数`)
	* `保留指针` (`变整数`)
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 动态库的 DllMain 入口函数通知

##### 火山.基本.动态库程序类.将被卸载

* **类型:** `方法`
* **名称:** `将被卸载`
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 用户的启动类可以覆盖此方法以在动态链接库被卸载前做一些清理工作

---

#### 火山.基本.对象类

* **类型:** `类`
* **名称:** `对象类`
* **特性:**
	* `默认基础类`
	* `全局类`(调用其中的静态方法可以省略类名指定前缀)
* **描述:** 所有火山类的默认基础类,如果某类没有明确指定其基础类,则其基础类为本类.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-miniblink浏览器-mini_blink-main](#vol-miniblink浏览器-mini_blink-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-自定义流程控制-flow_control-main](#vol-自定义流程控制-flow_control-main), [vol-com变体型测试-variant_test-main](#vol-com变体型测试-variant_test-main), [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main), [vol-高性能内存分配-mimolloc-main](#vol-高性能内存分配-mimolloc-main), [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-接口封装-impl_interface-main](#vol-接口封装-impl_interface-main), [vol-线程池-pool_thread-main](#vol-线程池-pool_thread-main), [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-被调用动态链接库-dll_test-main](#vol-被调用动态链接库-dll_test-main), [vol-调用动态链接库-dll_call-main](#vol-调用动态链接库-dll_call-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-被调用部件动态链接库-com_dll-main](#vol-被调用部件动态链接库-com_dll-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-邮件接收-receive_email-main](#vol-邮件接收-receive_email-main), [vol-ftp客户端-ftp-main](#vol-ftp客户端-ftp-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-腾讯云对象存储临时秘钥获取-tencentcos-main](#vol-腾讯云对象存储临时秘钥获取-tencentcos-main), [vol-阿里云短信验证服务器-aliyun_sms_server-main](#vol-阿里云短信验证服务器-aliyun_sms_server-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-百度网盘操作-baidu_netdisk-main](#vol-百度网盘操作-baidu_netdisk-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.对象类.标记值

* **类型:** `属性读方法`
* **名称:** `标记值`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 返回本对象中所设置的用户标记数值
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象类.标记值

* **类型:** `属性写方法`
* **名称:** `标记值`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
	* `所欲设置的标记值` (`变整数`)
* **特性:**
	* `静态`
* **描述:** 设置本对象中的用户标记数值,如果未设置过,其初始值为0.
* **相关例程:** [vol-锐浪报表-grid_report-main](#vol-锐浪报表-grid_report-main), [vol-std数据结构-stl_sample-main](#vol-std数据结构-stl_sample-main)

##### 火山.基本.对象类.为指定对象类

* **类型:** `全局方法`
* **名称:** `为指定对象类`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
	* `所检查的类型` (`对象类(需求:数据类型)`): 提供所欲检查是否匹配的类数据类型
* **特性:**
	* `静态`
* **描述:** 返回本对象的实际数据类型是否为所指定的类

##### 火山.基本.对象类.匹配指定对象类

* **类型:** `全局方法`
* **名称:** `匹配指定对象类`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
	* `所检查的类型` (`对象类(需求:数据类型)`): 提供所欲检查是否匹配的类数据类型
* **特性:**
	* `静态`
* **描述:** 返回本对象的实际数据类型是否匹配所指定的类(为其或其继承类). 注: 调用本方法的效果等同于使用"属于"操作符

##### 火山.基本.对象类.对象类型是否相同

* **类型:** `全局方法`
* **名称:** `对象类型是否相同`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
	* `所欲检查的对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 返回本对象的实际数据类型是否与所指定对象的实际数据类型相同

##### 火山.基本.对象类.对象内容是否相同

* **类型:** `全局方法`
* **名称:** `对象内容是否相同`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
	* `所欲检查的对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 返回本对象的当前运行时实际数据类型及其中的数据内容是否与所指定对象相同. 注: 使用比较操作符对两个对象进行比较时将仅对比这两个对象的地址是否相同,如欲比较两个对象的数据内容是否相同,必须使用本方法.
* **相关例程:** [vol-xml数据访问-xml-main](#vol-xml数据访问-xml-main)

##### 火山.基本.对象类.新建对象

* **类型:** `全局方法`
* **名称:** `新建对象`
* **返回值数据类型:** `调用本方法时为"所欲创建对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲创建对象的类型` (`通用类(需求:数据类型)`): 提供欲新建对象的类数据类型
* **特性:**
	* `静态`
* **描述:** 新建一个指定类数据类型的对象
* **返回值描述:** 返回所新建的对象,其类型由所提供的数据类型决定.
* **相关例程:** [vol-echarts图表-echarts-main](#vol-echarts图表-echarts-main)

##### 火山.基本.对象类.检查复制对象

* **类型:** `全局方法`
* **名称:** `检查复制对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
	* `所欲复制的对象` (`对象类`): 提供所欲复制到本对象的对象,其实际数据类型需要与本对象的实际数据类型匹配(为本对象的实际数据类型或其继承类),否则本方法将失败返回假.
* **特性:**
	* `静态`
* **描述:** 如果所提供欲复制对象的实际数据类型匹配本对象的实际数据类型(为本对象 的实际数据类型或其继承类),则将所指定对象的内容复制到本对象中后返回真,否则失败返回假.
* **返回值描述:** 如数据类型匹配则返回真,否则返回假.

##### 火山.基本.对象类.重置对象内容

* **类型:** `全局方法`
* **名称:** `重置对象内容`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 将本对象的内容重置到初始状态(根据当前实际数据类型)
* **相关例程:** [vol-空对象测试-null_object_test-main](#vol-空对象测试-null_object_test-main)

##### 火山.基本.对象类.重置为空对象

* **类型:** `全局方法`
* **名称:** `重置为空对象`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 将本对象的内容重置到初始状态(根据当前实际数据类型),并设置其"空白对象"标志.
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

##### 火山.基本.对象类.去除空对象标志

* **类型:** `全局方法`
* **名称:** `去除空对象标志`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 去除掉本对象中的"空白对象"标志.

##### 火山.基本.对象类.是否为空对象

* **类型:** `全局方法`
* **名称:** `是否为空对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 返回本对象是否设置了"空白对象"标志

##### 火山.基本.对象类.取空对象

* **类型:** `全局方法`
* **名称:** `取空对象`
* **返回值数据类型:** `调用本方法时为"对象类型"参数所提供数据的实际类型`
* **参数:**
	* `对象类型` (`对象类(需求:数据类型)`): 提供所欲建立的对象类型
* **特性:**
	* `静态`
* **描述:** 返回一个设置了"空白对象"标志的指定类型对象

##### 火山.基本.对象类.取空基本对象

* **类型:** `全局方法`
* **名称:** `取空基本对象`
* **返回值数据类型:** `对象类`
* **特性:**
	* `静态`
* **描述:** 返回一个设置了"空白对象"标志的"对象类"对象

##### 火山.基本.对象类.取对象类输出名

* **类型:** `全局方法`
* **名称:** `取对象类输出名`
* **返回值数据类型:** `文本型`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 返回本对象的类输出名

##### 火山.基本.对象类.取对象类信息

* **类型:** `全局方法`
* **名称:** `取对象类信息`
* **返回值数据类型:** `对象类信息`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 返回本对象的类信息

##### 火山.基本.对象类.取对象自身指针

* **类型:** `全局方法`
* **名称:** `取对象自身指针`
* **返回值数据类型:** `变整数`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 返回本对象的自身地址指针值

##### 火山.基本.对象类.取对象数据

* **类型:** `全局方法`
* **名称:** `取对象数据`
* **返回值数据类型:** `字节集类`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
* **特性:**
	* `静态`
* **描述:** 基于流操作获取本对象中的所有内容数据
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.对象类.置对象数据

* **类型:** `全局方法`
* **名称:** `置对象数据`
* **参数:**
	* `所欲操作的本对象` (`对象类`)
	* `所欲设置的内容数据` (`字节集类`): 本参数用作提供对象内容数据,该数据必须为"取对象数据"方法所返回,否则将导致不可预知的后果.
* **特性:**
	* `静态`
* **描述:** 基于流操作设置本对象中的所有内容数据
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

---

#### 火山.基本.扩展对象类

* **类型:** `类`
* **名称:** `扩展对象类`
* **基础类:** `对象类`
* **描述:** 所有以此类为直接或间接基础类的对象将可以使用一些高级特性
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.扩展对象类.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

##### 火山.基本.扩展对象类.流读入

* **类型:** `方法`
* **名称:** `流读入`
* **参数:**
	* `流对象` (`输入流类`): 提供欲从其中读入本对象数据内容的输入流
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 从所指定的流对象中读入本对象的数据. 请注意以下事项: 1. 一旦定义了"流读入"方法,必须定义对应的"流写出"方法,所读入内容格式与"流写出"方法写出的内容格式必须完全一致; 2. 任何类如果既没有定义"流读入"方法,也没有定义"流写出"方法,编译器会自动建立默认的"流读入"和"流写出"方法,默认方法就是首先调用基础类中的对应方法,然后将本对象中的所有非静态变量成员顺序从流中读入/写出; 3. 继承类中如果覆盖了本方法且基础类中也存在数据需要从流中读入,则必须负责调用基础类中的"流读入"方法,调用格式如: "父对象.流读入 (流对象)"; 4. 如果本方法中的读入操作比较复杂或耗时,在之前最好检查一下流对象当前是否处于出错状态("流对象.是否出错"方法返回真),如果出错则放弃后续的读入操作,以提高运行效率; 5. 在读入过程中一旦发现出错,则需要将对应的错误码写入"流对象.错误码"属性中(流读入出错不需要,会自动写入),以禁止后续的流读入操作. 错误码可以是"流错误码"类中的常量值,也可以是自行定义的错误码值(必须大于0); 6. 流对象一旦处于出错状态(流对象的"错误码"属性值不为"流错误码.无错误"),则后续所有流读入操作都会失败,如果欲再次使用此流对象,需要首先调用其"清除错误"方法清除掉流的出错状态或者将流关闭后再打开.
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

##### 火山.基本.扩展对象类.流写出

* **类型:** `方法`
* **名称:** `流写出`
* **参数:**
	* `流对象` (`输出流类`): 提供欲将本对象数据内容写出到其中的输出流
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象的数据写入所指定的流对象中. 注意: 1. 一旦定义了"流写出"方法,必须定义对应的"流读入"方法,所写出内容格式与"流读入"方法读取的内容格式必须完全一致; 2. 任何类如果既没有定义"流读入"方法,也没有定义"流写出"方法,编译器会自动建立默认的"流读入"和"流写出"方法,默认方法就是首先调用基础类中的对应方法,然后将本对象中的所有非静态变量成员顺序从流中读入/写出; 3. 继承类中如果覆盖了本方法且基础类中也存在数据需要写出到流中,则必须负责调用基础类中的"流写出"方法,调用格式如: "父对象.流写出 (流对象)"; 4. 如果本方法中的写出操作比较复杂或耗时,在之前最好检查一下流对象当前是否处于出错状态("流对象.是否出错"方法返回真),如果出错则放弃后续的写出操作,以提高运行效率; 5. 在写出过程中一旦发现出错,则需要将对应的错误码写入"流对象.错误码"属性中(流写出出错不需要,会自动写入),以禁止后续的流写出操作. 错误码可以是"流错误码"类中的常量值,也可以是自行定义的错误码值(必须大于0); 6. 流对象一旦处于出错状态(流对象的"错误码"属性值不为"流错误码.无错误"),则后续所有流写出操作都会失败,如果欲再次使用此流对象,需要首先调用其"清除错误"方法清除掉流的出错状态或者将流关闭后再打开.
* **相关例程:** [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main)

---

#### 火山.基本.对象包装类

* **类型:** `类`
* **名称:** `对象包装类`
* **描述:** 用作在其中包装一个任意实际数据类型的火山类对象.本类对象之间赋值时,采用参考赋值方式,原对象和被赋值到对象将指向同一个被包装的火山对象实例.
* **相关例程:** [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.对象包装类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作本对象` (`对象包装类`): 提供所欲操作的本对象
* **特性:**
	* `静态`
* **描述:** 返回本对象的内容是否为空

##### 火山.基本.对象包装类.清空

* **类型:** `方法`
* **名称:** `清空`
* **参数:**
	* `所欲操作本对象` (`对象包装类`): 提供所欲操作的本对象
* **特性:**
	* `静态`
* **描述:** 清空本对象的内容

##### 火山.基本.对象包装类.置对象

* **类型:** `方法`
* **名称:** `置对象`
* **返回值数据类型:** `对象类`
* **参数:**
	* `所欲操作本对象` (`对象包装类`): 提供所欲操作的本对象
	* `所欲置入的对象` (`对象类`): 提供所欲置入的对象实例,类库将会创建一个新的同实际数据类型对象然后将其内容复制进去后置入本对象.
* **特性:**
	* `静态`
* **描述:** 置入一个火山对象实例到本对象中
* **返回值描述:** 返回被置入到本对象中的复制对象实例

##### 火山.基本.对象包装类.创建新对象

* **类型:** `方法`
* **名称:** `创建新对象`
* **返回值数据类型:** `调用本方法时为"所欲创建对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲操作本对象` (`对象包装类`): 提供所欲操作的本对象
	* `所欲创建对象的类型` (`对象类(需求:数据类型)`): 提供所欲新建对象的数据类型
* **特性:**
	* `静态`
* **描述:** 创建一个所指定类型的新火山对象实例并置入本对象中
* **返回值描述:** 返回被置入到本对象中的新对象实例

##### 火山.基本.对象包装类.创建新对象2

* **类型:** `方法`
* **名称:** `创建新对象2`
* **返回值数据类型:** `对象类`
* **参数:**
	* `所欲操作本对象` (`对象包装类`): 提供所欲操作的本对象
	* `所欲创建对象的类型` (`对象类信息`): 提供所欲新建对象的数据类型,注意此信息的内容不能为空.
* **特性:**
	* `静态`
* **描述:** 创建一个所指定类型的新火山对象实例并置入本对象中
* **返回值描述:** 返回被置入到本对象中的新对象实例

##### 火山.基本.对象包装类.取对象

* **类型:** `方法`
* **名称:** `取对象`
* **返回值数据类型:** `对象类`
* **参数:**
	* `所欲操作本对象` (`对象包装类`): 提供所欲操作的本对象
* **特性:**
	* `静态`
* **描述:** 返回包装在本对象中火山对象实例的参考,如果本对象的内容为空,则将返回一个数据类型为"对象类"的空对象(其"是否为空对象"方法返回真). 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 ((对象实际数据类型)变量1.取对象 ()) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-高级主线程处理器-main_thread_notice-main](#vol-高级主线程处理器-main_thread_notice-main), [vol-ai对话-ai-main](#vol-ai对话-ai-main)

##### 火山.基本.对象包装类.匹配指定类

* **类型:** `方法`
* **名称:** `匹配指定类`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲操作本对象` (`对象包装类`): 提供所欲操作的本对象
	* `所检查的类型` (`对象类(需求:数据类型)`): 提供所欲检查是否匹配的类数据类型
* **特性:**
	* `静态`
* **描述:** 返回包装在本对象中的火山对象实例的实际数据类型是否匹配所指定的类(为其或其继承类)

##### 火山.基本.对象包装类.取指定类型对象

* **类型:** `方法`
* **名称:** `取指定类型对象`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲操作本对象` (`对象包装类`): 提供所欲操作的本对象
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取对象的数据类型,如果包装在本对象中的火山对象实例不匹配该数据类型(为其或其继承类对象),将返回一个为该数据类型的空对象(其"是否为空对象"方法返回真).
* **特性:**
	* `静态`
* **描述:** 返回包装在本对象中火山对象实例的参考. 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (变量1.取指定类型对象 (对象实际数据类型)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.

##### 火山.基本.对象包装类.对象

* **类型:** `方法`
* **名称:** `对象`
* **返回值数据类型:** `调用本方法时为"所欲获取对象的类型"参数所提供数据的实际类型`
* **参数:**
	* `所欲操作本对象` (`对象包装类`): 提供所欲操作的本对象
	* `所欲获取对象的类型` (`对象类(需求:数据类型)`): 提供所欲获取对象的数据类型,必须确保本对象内容不为空且其中所包装对象匹配该数据类型(即"匹配指定类 (所欲获取对象的类型)"方法调用必须返回真),否则在运行时程序将崩溃(调试运行时会报错).
* **特性:**
	* `静态`
* **描述:** 返回包装在本对象中火山对象实例的参考. 注意: 本方法为"取指定类型对象"的快捷操作版,不会进行各种安全性检查.因此执行本方法前,必须确保本对象内容不为空且其中所包装对象符合所指定的数据类型(即"匹配指定类"方法必须返回真),否则在运行时程序将崩溃(调试运行时会报错). 注意: 如果所获取对象需要动态挂接事件,请按类似以下格式挂接: 挂接事件 (变量1.取指定类型对象 (对象实际数据类型)) 因为火山视窗的赋值操作采用的是值复制方式,所以如果将返回对象赋值到另一个变量后再挂接这个变量的话,将导致事件挂接在一个复制出来的对象上而不是所期望的数组中保存的对象.
* **相关例程:** [vol-mdi多文档应用程序-mdi-main](#vol-mdi多文档应用程序-mdi-main), [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main)

---

#### 火山.基本.对象包装数组类

* **类型:** `类`
* **名称:** `对象包装数组类`
* **模板基础类:** `对象数组模板类`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `对象包装类`
* **描述:** 成员数据类型为"对象包装类"的数组

---

#### 火山.基本.对象类信息

* **类型:** `类`
* **名称:** `对象类信息`
* **基础类:** `扩展对象类`
* **描述:** 用作记录对象的运行时类信息
* **相关例程:** [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main)

##### 火山.基本.对象类信息.获取

* **类型:** `方法`
* **名称:** `获取`
* **返回值数据类型:** `对象类信息`
* **参数:**
	* `所欲置入的对象类` (`对象类(需求:数据类型)`): 该对象类的运行时信息将被置入本对象中
* **特性:**
	* `静态`
* **描述:** 获取并返回所指定类的运行时信息
* **相关例程:** [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main)

##### 火山.基本.对象类信息.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本对象的内容是否为空

##### 火山.基本.对象类信息.置对象类

* **类型:** `方法`
* **名称:** `置对象类`
* **参数:**
	* `所欲置入的对象类` (`对象类(需求:数据类型)`): 该对象类的运行时信息将被置入本对象中
* **描述:** 将所指定类的运行时信息置入本对象中

##### 火山.基本.对象类信息.为指定类

* **类型:** `方法`
* **名称:** `为指定类`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所检查的类型` (`对象类(需求:数据类型)`): 提供所欲检查的类数据类型
* **描述:** 返回本对象中当前所保存的运行时类信息是否为所指定的类

##### 火山.基本.对象类信息.置对象实例类

* **类型:** `方法`
* **名称:** `置对象实例类`
* **参数:**
	* `所欲置入的对象` (`对象类`): 该对象的运行时类信息将被置入本对象中
* **描述:** 将所指定对象的运行时类信息置入本对象中

##### 火山.基本.对象类信息.为指定实例类

* **类型:** `方法`
* **名称:** `为指定实例类`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所检查的对象` (`对象类`): 提供所欲检查的对象实例,将依据此对象的实际数据类型进行检查.
* **描述:** 返回本对象中当前所保存的运行时类信息是否为所指定对象实例的类

##### 火山.基本.对象类信息.创建对象

* **类型:** `方法`
* **名称:** `创建对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所创建的对象` (`对象包装类`): 如果本方法返回真,则所创建的对象实例将保存到此参数中,其中的已有内容将被覆盖.
* **描述:** 根据本对象中当前所保存的运行时类信息创建对应的对象实例,返回是否成功.
* **返回值描述:** 本对象中当前内容为空返回假,否则返回真.
* **相关例程:** [vol-对象包装-object_wrapper-main](#vol-对象包装-object_wrapper-main)

##### 火山.基本.对象类信息.创建指定类型对象

* **类型:** `方法`
* **名称:** `创建指定类型对象`
* **返回值数据类型:** `逻辑型`
* **参数:**
	* `所欲创建对象的类型` (`对象类(需求:数据类型)`): 提供所欲创建对象的数据类型
	* `所创建的对象` (`对象包装类`): 如果本方法返回真,则所创建的对象实例将保存到此参数中,其中的已有内容将被覆盖.
* **描述:** 根据本对象中当前所保存的运行时类信息创建所指定类型的对象实例,返回是否成功.
* **返回值描述:** 如果本对象中当前所保存的运行时类信息为所指定数据类型,返回真,否则返回假.

##### 火山.基本.对象类信息.取展示内容

* **类型:** `方法`
* **名称:** `取展示内容`
* **参数:**
	* `展示内容` (`文本型`): 用作填入本对象中所有数据的展示文本
	* `最大展示数据尺寸` (`整数`): 提供用户所指定的最大允许展示数据尺寸,小于0表示全部展示,等于0表示展示默认尺寸数据.
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 将本对象中的所有数据用文本方式填入到所提供的文本参数中,用作调试或其它场合展示时使用.

---

#### 火山.基本.可设计类

* **类型:** `类`
* **名称:** `可设计类`
* **基础类:** `参考对象类`
* **特性:**
	* `抽象类`(禁止直接定义其实例变量)
* **描述:** 为所有可以在开发环境中启动外部设计器来对类中"取设计内容"方法所返回值进行设计的类的最基础类

##### 火山.基本.可设计类.取设计内容

* **类型:** `方法`
* **名称:** `取设计内容`
* **返回值数据类型:** `文本型`
* **特性:**
	* `虚拟方法`(可在继承类中覆盖)
* **描述:** 用作返回用户所设计的内容文本,在继承类中由对应外部设计器填写其内容,然后由编译器覆盖本方法置入.

---

#### 火山.基本.基本数据封装类

* **类型:** `类`
* **名称:** `基本数据封装类`
* **特性:**
	* `抽象类`(禁止直接定义其实例变量)

---

#### 火山.基本.字节类

* **类型:** `类`
* **名称:** `字节类`
* **基础类:** `基本数据封装类`
* **文档分类:** `基础类.基本数据类型封装类`
* **描述:** 提供对字节基本数据类型的封装,一般用作支持通过方法参数来传递回对应的基本数据类型数据. 由于除开"文本型"以外的基本数据类型参数数据传递均采用值传递方式,因此在被调用方法内部对这些参数值进行修改并不能返回到方法调用方,如果有此类需求,可以通过改用对应的基本数据类型封装类的方式,将值传递转换为参考传递,从而达到将方法内部的修改传递到调用方的要求. 譬如: 假设一个方法需要返回两个整数,但是方法返回值只能返回一个,可以通过定义一个数据类型为"整数类"的参数来返回,因为在方法内部对该参数对象的"值"成员进行更改可以被返回到调用方. 文本型数据本身就是以参考方式进行方法参数数据传递的,因此不需要进行封装.
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

##### 火山.基本.字节类.值

* **类型:** `属性成员变量`
* **名称:** `值`
* **数据类型:** `字节`
* **描述:** 提供所封装的字节基本数据类型值
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.短整数类

* **类型:** `类`
* **名称:** `短整数类`
* **基础类:** `基本数据封装类`
* **文档分类:** `基础类.基本数据类型封装类`
* **描述:** 提供对短整数基本数据类型的封装,一般用作支持通过方法参数来传递回对应的基本数据类型数据. 由于除开"文本型"以外的基本数据类型参数数据传递均采用值传递方式,因此在被调用方法内部对这些参数值进行修改并不能返回到方法调用方,如果有此类需求,可以通过改用对应的基本数据类型封装类的方式,将值传递转换为参考传递,从而达到将方法内部的修改传递到调用方的要求. 譬如: 假设一个方法需要返回两个整数,但是方法返回值只能返回一个,可以通过定义一个数据类型为"整数类"的参数来返回,因为在方法内部对该参数对象的"值"成员进行更改可以被返回到调用方. 文本型数据本身就是以参考方式进行方法参数数据传递的,因此不需要进行封装.
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

##### 火山.基本.短整数类.值

* **类型:** `属性成员变量`
* **名称:** `值`
* **数据类型:** `短整数`
* **描述:** 提供所封装的短整数基本数据类型值
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.字符类

* **类型:** `类`
* **名称:** `字符类`
* **基础类:** `基本数据封装类`
* **文档分类:** `基础类.基本数据类型封装类`
* **描述:** 提供对字符基本数据类型的封装,一般用作支持通过方法参数来传递回对应的基本数据类型数据. 由于除开"文本型"以外的基本数据类型参数数据传递均采用值传递方式,因此在被调用方法内部对这些参数值进行修改并不能返回到方法调用方,如果有此类需求,可以通过改用对应的基本数据类型封装类的方式,将值传递转换为参考传递,从而达到将方法内部的修改传递到调用方的要求. 譬如: 假设一个方法需要返回两个整数,但是方法返回值只能返回一个,可以通过定义一个数据类型为"整数类"的参数来返回,因为在方法内部对该参数对象的"值"成员进行更改可以被返回到调用方. 文本型数据本身就是以参考方式进行方法参数数据传递的,因此不需要进行封装.
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

##### 火山.基本.字符类.值

* **类型:** `属性成员变量`
* **名称:** `值`
* **数据类型:** `字符`
* **描述:** 提供所封装的字符基本数据类型值
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.整数类

* **类型:** `类`
* **名称:** `整数类`
* **基础类:** `基本数据封装类`
* **文档分类:** `基础类.基本数据类型封装类`
* **描述:** 提供对整数基本数据类型的封装,一般用作支持通过方法参数来传递回对应的基本数据类型数据. 由于除开"文本型"以外的基本数据类型参数数据传递均采用值传递方式,因此在被调用方法内部对这些参数值进行修改并不能返回到方法调用方,如果有此类需求,可以通过改用对应的基本数据类型封装类的方式,将值传递转换为参考传递,从而达到将方法内部的修改传递到调用方的要求. 譬如: 假设一个方法需要返回两个整数,但是方法返回值只能返回一个,可以通过定义一个数据类型为"整数类"的参数来返回,因为在方法内部对该参数对象的"值"成员进行更改可以被返回到调用方. 文本型数据本身就是以参考方式进行方法参数数据传递的,因此不需要进行封装.
* **相关例程:** [vol-虚拟超级列表框-virtual_list-main](#vol-虚拟超级列表框-virtual_list-main), [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-飞机大战-aircraft-main](#vol-飞机大战-aircraft-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-简单pack服务器-pack_server-main](#vol-简单pack服务器-pack_server-main), [vol-简单pull服务器-pull_server-main](#vol-简单pull服务器-pull_server-main), [vol-简单tcp服务器-tcp_server-main](#vol-简单tcp服务器-tcp_server-main), [vol-简单udp服务器-udp_server-main](#vol-简单udp服务器-udp_server-main), [vol-服务器-server-main](#vol-服务器-server-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-支付宝支付服务器-alipay_server-main](#vol-支付宝支付服务器-alipay_server-main), [vol-人脸性别识别-gender_recognition-main](#vol-人脸性别识别-gender_recognition-main)

##### 火山.基本.整数类.值

* **类型:** `属性成员变量`
* **名称:** `值`
* **数据类型:** `整数`
* **描述:** 提供所封装的整数基本数据类型值
* **相关例程:** [vol-edge浏览框-webview2_new-main](#vol-edge浏览框-webview2_new-main), [vol-动态创建布局-dynamic_create-main](#vol-动态创建布局-dynamic_create-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-复杂接口api调用-api_call-main](#vol-复杂接口api调用-api_call-main), [vol-对象序列化-objectserialize-main](#vol-对象序列化-objectserialize-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main), [vol-海康威视工业相机-hikrobot-main](#vol-海康威视工业相机-hikrobot-main), [vol-微信支付服务器-wx_server-main](#vol-微信支付服务器-wx_server-main), [vol-人脸性别识别-gender_recognition-main](#vol-人脸性别识别-gender_recognition-main)

---

#### 火山.基本.变整数类

* **类型:** `类`
* **名称:** `变整数类`
* **基础类:** `基本数据封装类`
* **文档分类:** `基础类.基本数据类型封装类`
* **描述:** 提供对变整数基本数据类型的封装,一般用作支持通过方法参数来传递回对应的基本数据类型数据. 由于除开"文本型"以外的基本数据类型参数数据传递均采用值传递方式,因此在被调用方法内部对这些参数值进行修改并不能返回到方法调用方,如果有此类需求,可以通过改用对应的基本数据类型封装类的方式,将值传递转换为参考传递,从而达到将方法内部的修改传递到调用方的要求. 譬如: 假设一个方法需要返回两个整数,但是方法返回值只能返回一个,可以通过定义一个数据类型为"整数类"的参数来返回,因为在方法内部对该参数对象的"值"成员进行更改可以被返回到调用方. 文本型数据本身就是以参考方式进行方法参数数据传递的,因此不需要进行封装.
* **相关例程:** [vol-窗口组件动态消息过滤-msg_filter-main](#vol-窗口组件动态消息过滤-msg_filter-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main)

##### 火山.基本.变整数类.值

* **类型:** `属性成员变量`
* **名称:** `值`
* **数据类型:** `变整数`
* **描述:** 提供所封装的变整数基本数据类型值
* **相关例程:** [vol-窗口组件动态消息过滤-msg_filter-main](#vol-窗口组件动态消息过滤-msg_filter-main), [vol-miniblink浏览器组件-mini_blink_control-main](#vol-miniblink浏览器组件-mini_blink_control-main), [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-硬件及键鼠和钩子操作-syshardwareinfo-main](#vol-硬件及键鼠和钩子操作-syshardwareinfo-main)

---

#### 火山.基本.长整数类

* **类型:** `类`
* **名称:** `长整数类`
* **基础类:** `基本数据封装类`
* **文档分类:** `基础类.基本数据类型封装类`
* **描述:** 提供对长整数基本数据类型的封装,一般用作支持通过方法参数来传递回对应的基本数据类型数据. 由于除开"文本型"以外的基本数据类型参数数据传递均采用值传递方式,因此在被调用方法内部对这些参数值进行修改并不能返回到方法调用方,如果有此类需求,可以通过改用对应的基本数据类型封装类的方式,将值传递转换为参考传递,从而达到将方法内部的修改传递到调用方的要求. 譬如: 假设一个方法需要返回两个整数,但是方法返回值只能返回一个,可以通过定义一个数据类型为"整数类"的参数来返回,因为在方法内部对该参数对象的"值"成员进行更改可以被返回到调用方. 文本型数据本身就是以参考方式进行方法参数数据传递的,因此不需要进行封装.
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

##### 火山.基本.长整数类.值

* **类型:** `属性成员变量`
* **名称:** `值`
* **数据类型:** `长整数`
* **描述:** 提供所封装的长整数基本数据类型值
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main)

---

#### 火山.基本.单精度小数类

* **类型:** `类`
* **名称:** `单精度小数类`
* **基础类:** `基本数据封装类`
* **文档分类:** `基础类.基本数据类型封装类`
* **描述:** 提供对单精度小数基本数据类型的封装,一般用作支持通过方法参数来传递回对应的基本数据类型数据. 由于除开"文本型"以外的基本数据类型参数数据传递均采用值传递方式,因此在被调用方法内部对这些参数值进行修改并不能返回到方法调用方,如果有此类需求,可以通过改用对应的基本数据类型封装类的方式,将值传递转换为参考传递,从而达到将方法内部的修改传递到调用方的要求. 譬如: 假设一个方法需要返回两个整数,但是方法返回值只能返回一个,可以通过定义一个数据类型为"整数类"的参数来返回,因为在方法内部对该参数对象的"值"成员进行更改可以被返回到调用方. 文本型数据本身就是以参考方式进行方法参数数据传递的,因此不需要进行封装.

##### 火山.基本.单精度小数类.值

* **类型:** `属性成员变量`
* **名称:** `值`
* **数据类型:** `单精度小数`
* **描述:** 提供所封装的单精度小数基本数据类型值

---

#### 火山.基本.小数类

* **类型:** `类`
* **名称:** `小数类`
* **基础类:** `基本数据封装类`
* **文档分类:** `基础类.基本数据类型封装类`
* **描述:** 提供对小数基本数据类型的封装,一般用作支持通过方法参数来传递回对应的基本数据类型数据. 由于除开"文本型"以外的基本数据类型参数数据传递均采用值传递方式,因此在被调用方法内部对这些参数值进行修改并不能返回到方法调用方,如果有此类需求,可以通过改用对应的基本数据类型封装类的方式,将值传递转换为参考传递,从而达到将方法内部的修改传递到调用方的要求. 譬如: 假设一个方法需要返回两个整数,但是方法返回值只能返回一个,可以通过定义一个数据类型为"整数类"的参数来返回,因为在方法内部对该参数对象的"值"成员进行更改可以被返回到调用方. 文本型数据本身就是以参考方式进行方法参数数据传递的,因此不需要进行封装.
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-数学公式计算-math_exp_calc-main](#vol-数学公式计算-math_exp_calc-main), [vol-人脸性别识别-gender_recognition-main](#vol-人脸性别识别-gender_recognition-main)

##### 火山.基本.小数类.值

* **类型:** `属性成员变量`
* **名称:** `值`
* **数据类型:** `小数`
* **描述:** 提供所封装的小数基本数据类型值
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-数学公式计算-math_exp_calc-main](#vol-数学公式计算-math_exp_calc-main), [vol-人脸性别识别-gender_recognition-main](#vol-人脸性别识别-gender_recognition-main)

---

#### 火山.基本.逻辑型类

* **类型:** `类`
* **名称:** `逻辑型类`
* **基础类:** `基本数据封装类`
* **文档分类:** `基础类.基本数据类型封装类`
* **描述:** 提供对逻辑型基本数据类型的封装,一般用作支持通过方法参数来传递回对应的基本数据类型数据. 由于除开"文本型"以外的基本数据类型参数数据传递均采用值传递方式,因此在被调用方法内部对这些参数值进行修改并不能返回到方法调用方,如果有此类需求,可以通过改用对应的基本数据类型封装类的方式,将值传递转换为参考传递,从而达到将方法内部的修改传递到调用方的要求. 譬如: 假设一个方法需要返回两个整数,但是方法返回值只能返回一个,可以通过定义一个数据类型为"整数类"的参数来返回,因为在方法内部对该参数对象的"值"成员进行更改可以被返回到调用方. 文本型数据本身就是以参考方式进行方法参数数据传递的,因此不需要进行封装.
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-照片上色-image_colour-main](#vol-照片上色-image_colour-main), [vol-风格迁移-style_migration-main](#vol-风格迁移-style_migration-main), [vol-yolov5目标检测-yolov5-main](#vol-yolov5目标检测-yolov5-main)

##### 火山.基本.逻辑型类.值

* **类型:** `属性成员变量`
* **名称:** `值`
* **数据类型:** `逻辑型`
* **描述:** 提供所封装的逻辑型基本数据类型值
* **相关例程:** [vol-调试输出测试-debug_out-main](#vol-调试输出测试-debug_out-main), [vol-照片上色-image_colour-main](#vol-照片上色-image_colour-main), [vol-风格迁移-style_migration-main](#vol-风格迁移-style_migration-main)

---

#### 火山.基本.扩展整数型模板

* **类型:** `类`
* **名称:** `扩展整数型模板`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **描述:** 用作支持扩展C++基本整数值数据类型. 注意: 本类已经废弃,请直接以火山基本整数数据类型的方式使用本地数值数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.扩展整数型模板.到变整数

* **类型:** `方法`
* **名称:** `到变整数`
* **返回值数据类型:** `变整数`
* **参数:**
	* `欲操作本对象` (`扩展整数型模板`)
* **特性:**
	* `静态`
	* `废弃警告`
* **描述:** 将本数据类型值转换到变整数后返回. 注意: 本方法已经废弃,请直接以火山基本整数数据类型的方式使用本地数值数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.扩展整数型模板.到整数

* **类型:** `方法`
* **名称:** `到整数`
* **返回值数据类型:** `整数`
* **参数:**
	* `欲操作本对象` (`扩展整数型模板`)
* **特性:**
	* `静态`
	* `废弃警告`
* **描述:** 将本数据类型值转换到整数后返回. 注意: 本方法已经废弃,请直接以火山基本整数数据类型的方式使用本地数值数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.扩展整数型模板.来自

* **类型:** `方法`
* **名称:** `来自`
* **返回值数据类型:** `扩展整数型模板`
* **参数:**
	* `欲转换整数值` (`通用整数型`)
* **特性:**
	* `静态`
	* `废弃警告`
* **描述:** 将指定整数值转换为本数据类型值后返回. 注意: 本方法已经废弃,请直接以火山基本整数数据类型的方式使用本地数值数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.扩展整数型模板.零值

* **类型:** `方法`
* **名称:** `零值`
* **返回值数据类型:** `扩展整数型模板`
* **特性:**
	* `静态`
	* `废弃警告`
* **描述:** 将零值转换为本数据类型值后返回. 注意: 本方法已经废弃,请直接以火山基本整数数据类型的方式使用本地数值数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

---

#### 火山.基本.无符号字节

* **类型:** `类`
* **名称:** `无符号字节`
* **模板基础类:** `扩展整数型模板`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `无符号字节`
* **描述:** 提示: 本地数值数据类型的使用方式等同于火山基本整数数据类型.
* **相关例程:** [vol-本地整数数据类型-native_int_data_type-main](#vol-本地整数数据类型-native_int_data_type-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

---

#### 火山.基本.无符号短整数

* **类型:** `类`
* **名称:** `无符号短整数`
* **模板基础类:** `扩展整数型模板`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `无符号短整数`
* **描述:** 提示: 本地数值数据类型的使用方式等同于火山基本整数数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

---

#### 火山.基本.无符号整数

* **类型:** `类`
* **名称:** `无符号整数`
* **模板基础类:** `扩展整数型模板`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `无符号整数`
* **描述:** 提示: 本地数值数据类型的使用方式等同于火山基本整数数据类型.
* **相关例程:** [vol-本地整数数据类型-native_int_data_type-main](#vol-本地整数数据类型-native_int_data_type-main), [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

---

#### 火山.基本.通用指针

* **类型:** `类`
* **名称:** `通用指针`
* **模板基础类:** `扩展整数型模板`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `通用指针`
* **描述:** 提示: 本地数值数据类型的使用方式等同于火山基本整数数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

---

#### 火山.基本.文本指针

* **类型:** `类`
* **名称:** `文本指针`
* **模板基础类:** `扩展整数型模板`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `文本指针`
* **描述:** 对应可修改的文本数据指针. 提示: 本地数值数据类型的使用方式等同于火山基本整数数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.文本指针.获取

* **类型:** `方法`
* **名称:** `获取`
* **返回值数据类型:** `文本指针`
* **参数:**
	* `文本数据` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回指定文本所对应的本类指针
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.文本指针.取指针

* **类型:** `方法`
* **名称:** `取指针`
* **返回值数据类型:** `通用指针`
* **参数:**
	* `欲操作本对象` (`文本指针`)
* **特性:**
	* `静态`
* **描述:** 取回本类指针对应的通用指针. 注意本方法已经废弃,请直接使用强制转换操作: (通用指针)本类对象

##### 火山.基本.文本指针.取文本

* **类型:** `方法`
* **名称:** `取文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `欲操作本对象` (`文本指针`)
* **特性:**
	* `静态`
* **描述:** 取回本类指针对应的Unicode文本内容
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

---

#### 火山.基本.常量文本指针

* **类型:** `类`
* **名称:** `常量文本指针`
* **模板基础类:** `扩展整数型模板`
* **特性:**
	* `模板实现类`. 其直接/间接继承的模板基础类中的模板数据类型将按下表进行替换: `模板类型1` -> `常量文本指针`
* **描述:** 对应不可修改的常量文本数据指针. 提示: 本地数值数据类型的使用方式等同于火山基本整数数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.常量文本指针.获取

* **类型:** `方法`
* **名称:** `获取`
* **返回值数据类型:** `常量文本指针`
* **参数:**
	* `文本数据` (`文本型`)
* **特性:**
	* `静态`
* **描述:** 返回指定文本所对应的本类指针

##### 火山.基本.常量文本指针.取指针

* **类型:** `方法`
* **名称:** `取指针`
* **返回值数据类型:** `通用指针`
* **参数:**
	* `欲操作本对象` (`常量文本指针`)
* **特性:**
	* `静态`
* **描述:** 取回本类指针对应的通用指针. 注意本方法已经废弃,请直接使用强制转换操作: (通用指针)本类对象

##### 火山.基本.常量文本指针.取文本

* **类型:** `方法`
* **名称:** `取文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `欲操作本对象` (`常量文本指针`)
* **特性:**
	* `静态`
* **描述:** 取回本类指针对应的Unicode文本内容

---

#### 火山.基本.多字节文本指针

* **类型:** `类`
* **名称:** `多字节文本指针`
* **描述:** 对应可修改的多字节文本数据指针. 提示: 本地数值数据类型的使用方式等同于火山基本整数数据类型.

##### 火山.基本.多字节文本指针.取文本

* **类型:** `方法`
* **名称:** `取文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `欲操作本对象` (`多字节文本指针`)
* **特性:**
	* `静态`
* **描述:** 取回本类指针对应的多字节文本内容

---

#### 火山.基本.多字节常量文本指针

* **类型:** `类`
* **名称:** `多字节常量文本指针`
* **描述:** 对应不可修改的多字节文本数据指针. 提示: 本地数值数据类型的使用方式等同于火山基本整数数据类型.

##### 火山.基本.多字节常量文本指针.取文本

* **类型:** `方法`
* **名称:** `取文本`
* **返回值数据类型:** `文本型`
* **参数:**
	* `欲操作本对象` (`多字节常量文本指针`)
* **特性:**
	* `静态`
* **描述:** 取回本类指针对应的多字节文本内容

---

#### 火山.基本.无符号长整数

* **类型:** `类`
* **名称:** `无符号长整数`
* **描述:** 提示: 本地数值数据类型的使用方式等同于火山基本整数数据类型.

##### 火山.基本.无符号长整数.到长整数

* **类型:** `方法`
* **名称:** `到长整数`
* **返回值数据类型:** `长整数`
* **参数:**
	* `欲操作本对象` (`无符号长整数`)
* **特性:**
	* `静态`
* **描述:** 将本数据类型值转换到长整数后返回. 注意本方法已经废弃,请直接使用强制转换操作: (长整数)本类对象

##### 火山.基本.无符号长整数.来自

* **类型:** `方法`
* **名称:** `来自`
* **返回值数据类型:** `无符号长整数`
* **参数:**
	* `欲转换整数值` (`通用整数型`)
* **特性:**
	* `静态`
* **描述:** 将指定整数值转换为本数据类型值后返回. 注意本方法已经废弃,请直接使用强制转换操作: (无符号长整数)欲转换整数值

---

#### 火山.基本.本地结构指针模板

* **类型:** `类`
* **名称:** `本地结构指针模板`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **描述:** 用作支持C++结构指针的基础模板类
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.本地结构指针模板.创建

* **类型:** `方法`
* **名称:** `创建`
* **返回值数据类型:** `本地结构指针模板`
* **特性:**
	* `静态`
* **描述:** 创建并返回一个本类指针,注意不使用后必须调用销毁命令将其销毁. 注意: 使用本模板类方法时,所对应的C++结构指针别名必须以'*'字符结束,或者以"P"/"P_"/"LP"/"LP_"这几类文本开头,譬如别名为 xxx 结构的指针, 可以使用"Pxxx" / "LPxxx" / "P_xxx" / "LP_xxx" / "xxx*"别名,否则将无法正确取得结构指针所对应的结构数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.本地结构指针模板.销毁

* **类型:** `方法`
* **名称:** `销毁`
* **参数:**
	* `指针值` (`本地结构指针模板`)
* **特性:**
	* `静态`
* **描述:** 销毁先前调用"创建"方法所创建的本类指针
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.本地结构指针模板.取数据尺寸

* **类型:** `方法`
* **名称:** `取数据尺寸`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回本类指针所指向结构数据的尺寸. 注意: 使用本模板类方法时,所对应的C++结构指针别名必须以'*'字符结束,或者以"P"/"P_"/"LP"/"LP_"这几类文本开头,譬如别名为 xxx 结构的指针, 可以使用"Pxxx" / "LPxxx" / "P_xxx" / "LP_xxx" / "xxx*"别名,否则将无法正确取得结构指针所对应的结构数据类型.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.本地结构指针模板.取指针

* **类型:** `方法`
* **名称:** `取指针`
* **返回值数据类型:** `通用指针`
* **参数:**
	* `欲操作本对象` (`本地结构指针模板`)
* **特性:**
	* `静态`
* **描述:** 取回本类指针对应的通用指针
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.本地结构指针模板.取变整数指针

* **类型:** `方法`
* **名称:** `取变整数指针`
* **返回值数据类型:** `变整数`
* **参数:**
	* `欲操作本对象` (`本地结构指针模板`)
* **特性:**
	* `静态`
* **描述:** 将本数据类型值转换到变整数后返回
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.本地结构指针模板.来自变整数

* **类型:** `方法`
* **名称:** `来自变整数`
* **返回值数据类型:** `本地结构指针模板`
* **参数:**
	* `欲转换整数值` (`通用整数型`)
* **特性:**
	* `静态`
* **描述:** 将指定整数值转换为本数据类型值后返回
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.本地结构指针模板.空指针

* **类型:** `方法`
* **名称:** `空指针`
* **返回值数据类型:** `本地结构指针模板`
* **特性:**
	* `静态`
* **描述:** 将NULL指针值转换为本数据类型值后返回
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

---

#### 火山.基本.本地结构模板

* **类型:** `类`
* **名称:** `本地结构模板`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **描述:** 用作支持C++本地结构的基础模板类
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.本地结构模板.取尺寸

* **类型:** `方法`
* **名称:** `取尺寸`
* **返回值数据类型:** `整数`
* **特性:**
	* `静态`
* **描述:** 返回结构数据的尺寸
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.本地结构模板.取地址

* **类型:** `方法`
* **名称:** `取地址`
* **返回值数据类型:** `通用指针`
* **参数:**
	* `欲操作本对象` (`本地结构模板`)
* **特性:**
	* `静态`
* **描述:** 返回本结构地址对应的通用指针
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.本地结构模板.取变整数地址

* **类型:** `方法`
* **名称:** `取变整数地址`
* **返回值数据类型:** `变整数`
* **参数:**
	* `欲操作本对象` (`本地结构模板`)
* **特性:**
	* `静态`
* **描述:** 返回本结构地址指针对应的变整数
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

---

#### 火山.基本.事件接收器

* **类型:** `类`
* **名称:** `事件接收器`
* **描述:** 用作挂接到一个"事件发送器"对象以接收其所发送的事件,本类对象被销毁时将自动断开与所挂接到"事件发送器"对象之间的连接.
* **相关例程:** [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main)

##### 火山.基本.事件接收器.接收到事件

* **类型:** `事件定义方法`
* **名称:** `接收到事件`
* **返回值数据类型:** `整数`
* **参数:**
	* `事件参数` (`COM变体型数组类`): 提供事件的所有参数数据
	* `事件返回值` (`COM变体型`): 仅用作输出. 事件处理完毕后如果需要返回数据,请将所欲返回数据值填入到此参数变量中.
	* `事件附加对象` (`对象类`): 为调用"事件发送器"对象的"发送事件"方法时所提供的"事件附加对象"参数值
	* `事件附加值` (`变整数`): 为调用"事件发送器"对象的"发送事件"方法时所提供的"事件附加值"参数值
* **描述:** 当本对象接收到来自所挂接"事件发送器"对象的事件时,本事件被发送.
* **返回值描述:** 事件处理方法返回值将返回到所挂接"事件发送器"对象的"发送事件"方法
* **相关例程:** [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main)

---

#### 火山.基本.事件发送器

* **类型:** `类`
* **名称:** `事件发送器`
* **描述:** 用作向已经挂接到本对象的"事件接收器"对象发送事件,发送事件时不用考虑该接收器对象是否还存在,所挂接的"事件接收器"对象被销毁时将自动断开与本对象之间的连接.
* **相关例程:** [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main)

##### 火山.基本.事件发送器.挂接

* **类型:** `方法`
* **名称:** `挂接`
* **参数:**
	* `所欲挂接的接收器` (`事件接收器`): 提供所欲挂接到本对象的"事件接收器"对象
* **描述:** 将所指定的"事件接收器"对象挂接到本对象,先前的挂接将被覆盖.
* **相关例程:** [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main)

##### 火山.基本.事件发送器.取消挂接

* **类型:** `方法`
* **名称:** `取消挂接`
* **描述:** 取消当前已经挂接进来的"事件接收器"对象. 除非必要不用显式调用本方法取消挂接,所挂接的"事件接收器"对象被销毁时将自动取消挂接.

##### 火山.基本.事件发送器.是否已挂接

* **类型:** `方法`
* **名称:** `是否已挂接`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回当前是否已经挂接了"事件接收器"对象

##### 火山.基本.事件发送器.发送事件

* **类型:** `方法`
* **名称:** `发送事件`
* **返回值数据类型:** `整数`
* **参数:**
	* `事件参数` (`COM变体型数组类`, 默认值: `空对象`): 提供事件的所有参数数据
	* `事件返回值` (`COM变体型`, 默认值: `空对象`): 用作接收用户处理事件后的返回数据
	* `事件附加对象` (`对象类`, 默认值: `空对象`): 用作提供事件的"事件附加对象"参数值
	* `事件附加值` (`变整数`, 默认值: `0`): 用作提供事件的"事件附加值"参数值
* **描述:** 向所挂接的"事件接收器"对象发送事件
* **返回值描述:** 如果本对象上挂接有"事件接收器"对象,本方法将返回该对象的"接收到事件"事件方法的返回值,否则返回0.
* **相关例程:** [vol-跨对象发送接收事件-object_event-main](#vol-跨对象发送接收事件-object_event-main)

---

#### 火山.基本.参考对象类

* **类型:** `类`
* **名称:** `参考对象类`
* **描述:** 用作保存参考型数据的基础类

---

#### 火山.基本.参考对象模板类

* **类型:** `类`
* **名称:** `参考对象模板类`
* **基础类:** `参考对象类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **描述:** 支持保存一个具有指定类型参考型数据的模板基础类. 模板类型1: 所欲保存的参考型数据的数据类型(可以是任意除数组外的数据类型,包括对象类). 提示: 可以使用为对象类的模板类型1,以支持在该类销毁时自动调用"类_清理"方法进行相关清理工作.

##### 火山.基本.参考对象模板类.参考数据

* **类型:** `属性读方法`
* **名称:** `参考数据`
* **返回值数据类型:** `模板类型1`
* **描述:** 返回当前所参考到的数据,可以直接对本属性所返回数据中的成员值进行修改,注意将会影响所有参考到该数据的对象实例.

##### 火山.基本.参考对象模板类.参考数据

* **类型:** `属性写方法`
* **名称:** `参考数据`
* **参数:**
	* `所欲设置的数据` (`模板类型1`)
* **描述:** 设置当前所参考到的数据,注意将会影响所有参考到该数据的对象实例.

---

#### 火山.基本.指针类

* **类型:** `类`
* **名称:** `指针类`
* **描述:** 由于火山视窗程序没有支持参考型变量,特提供本类用作支持通过指针对其它基本数据类型或对象实例数据进行访问,以间接达到参考型变量的效果. 由于是指针操作,使用本类务必仔细小心,避免程序出错.
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.指针类.指针

* **类型:** `成员变量`
* **名称:** `指针`
* **数据类型:** `变整数`

##### 火山.基本.指针类.置指针

* **类型:** `方法`
* **名称:** `置指针`
* **参数:**
	* `所指向的数据` (`所有类型`): 该数据的地址指针将被置入本对象中,以后可以通过"读"/"写"方法访问.
* **描述:** 设置本对象中指针所指向的数据内容
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.指针类.读

* **类型:** `方法`
* **名称:** `读`
* **返回值数据类型:** `调用本方法时为"指针数据类型"参数所提供数据的实际类型`
* **参数:**
	* `指针数据类型` (`所有类型(需求:数据类型)`): 提供所欲读出数据的数据类型,必须与调用"置指针"方法所提供数据的数据类型匹配. 匹配的意思是: 1. 如果调用"置指针"方法所提供数据的数据类型为基本数据类型,则必须相同; 2. 如果调用"置指针"方法所提供数据的数据类型为类,则可以为该类或该类的基础类.
* **描述:** 返回先前通过"置指针"方法所提供的数据指针内容,对该内容进行操作等同于对指针内容进行操作. 调用本方法前必须满足以下前提: 1. 必须已经通过调用"置指针"方法置入了有效且为指定数据类型(由"欲获取数据类型"参数指定)的数据指针; 2. "置指针"方法所置入指针指向的数据必须确保有效存在. 如果不能保证以上事项,调用本方法程序将崩溃.
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main), [vol-winhttp-winhttp5_1-main](#vol-winhttp-winhttp5_1-main)

##### 火山.基本.指针类.写

* **类型:** `方法`
* **名称:** `写`
* **参数:**
	* `指针数据类型` (`所有类型(需求:数据类型)`): 必须与调用"置指针"方法所提供数据的数据类型相同
	* `欲写入数据` (`所有类型`): 提供所欲写入的数据,必须与调用"置指针"方法所提供数据的数据类型相同或匹配.
* **描述:** 将指定数据写入先前通过"置指针"方法所提供的数据指针中. 调用本方法前必须满足以下前提: 1. 必须已经通过调用"置指针"方法置入了有效且为指定数据类型(由"欲写入数据"参数提供)的数据指针; 2. "置指针"方法所置入指针指向的数据必须确保有效存在. 如果不能保证以上事项,调用本方法程序将崩溃.
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main)

##### 火山.基本.指针类.清除

* **类型:** `方法`
* **名称:** `清除`
* **描述:** 清除本对象中所指向的数据指针

##### 火山.基本.指针类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本对象中是否不存在"置指针"方法所置入的指针

---

#### 火山.基本.指针模板类

* **类型:** `类`
* **名称:** `指针模板类`
* **特性:**
	* `模板基础类`(只能通过定义模板实现类替换掉其中的模板数据类型后才能使用)
* **描述:** 由于火山视窗程序没有支持参考型变量,特提供本类用作支持通过指针对其它基本数据类型或对象实例数据进行访问,以间接达到参考型变量的效果. 由于是指针操作,使用本类务必仔细小心,避免程序出错. 模板类型1: 所欲操作数据的类型
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main)

##### 火山.基本.指针模板类.指针

* **类型:** `成员变量`
* **名称:** `指针`
* **数据类型:** `变整数`
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main)

##### 火山.基本.指针模板类.置指针

* **类型:** `方法`
* **名称:** `置指针`
* **参数:**
	* `所指向的数据` (`模板类型1`): 该数据的地址指针将被置入本对象中,以后可以通过"读"/"写"方法访问.
* **描述:** 设置本对象中指针所指向的数据内容
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main)

##### 火山.基本.指针模板类.读

* **类型:** `方法`
* **名称:** `读`
* **返回值数据类型:** `模板类型1`
* **描述:** 返回先前通过"置指针"方法所提供的数据指针内容,对该内容进行操作等同于对指针内容进行操作. 调用本方法前必须满足以下前提: 1. 必须已经通过调用"置指针"方法置入了有效的数据指针; 2. "置指针"方法所置入指针指向的数据必须确保有效存在. 如果不能保证以上事项,调用本方法程序将崩溃.
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main)

##### 火山.基本.指针模板类.写

* **类型:** `方法`
* **名称:** `写`
* **参数:**
	* `欲写入数据` (`模板类型1`): 提供所欲写入的数据
* **描述:** 将指定数据写入先前通过"置指针"方法所提供的数据指针中. 调用本方法前必须满足以下前提: 1. 必须已经通过调用"置指针"方法置入了有效的数据指针; 2. "置指针"方法所置入指针指向的数据必须确保有效存在. 如果不能保证以上事项,调用本方法程序将崩溃.
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main)

##### 火山.基本.指针模板类.清除

* **类型:** `方法`
* **名称:** `清除`
* **描述:** 清除本对象中所指向的数据指针
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main)

##### 火山.基本.指针模板类.是否为空

* **类型:** `方法`
* **名称:** `是否为空`
* **返回值数据类型:** `逻辑型`
* **描述:** 返回本对象中是否不存在"置指针"方法所置入的指针
* **相关例程:** [vol-指针类-pointer_class-main](#vol-指针类-pointer_class-main)

---

#### 火山.基本.结构基础类

* **类型:** `类`
* **名称:** `结构基础类`
* **特性:**
	* `抽象类`(禁止直接定义其实例变量)
* **描述:** 本类可以在封装C++结构时作为其基础类,用作提供一些基本的操作功能. 注意: 本类唯一可以使用的位置为作为使用 DECLARE_STRUCT_CLASS 宏进行结构封装的类的基础类.
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构基础类.取结构指针

* **类型:** `方法`
* **名称:** `取结构指针`
* **返回值数据类型:** `变整数`
* **描述:** 返回继承类中所封装C++结构的指针地址
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构基础类.取结构尺寸

* **类型:** `方法`
* **名称:** `取结构尺寸`
* **返回值数据类型:** `整数`
* **描述:** 返回继承类中所封装C++结构的尺寸
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

##### 火山.基本.结构基础类.取结构字节集

* **类型:** `方法`
* **名称:** `取结构字节集`
* **返回值数据类型:** `字节集类`
* **描述:** 返回继承类中所封装C++结构所对应的字节集数据
* **相关例程:** [vol-结构封装示例-struct_wrapper-main](#vol-结构封装示例-struct_wrapper-main)

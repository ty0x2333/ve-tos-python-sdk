TOS SDK for Python 版本记录
===========================

Version 2.5.7
-------------
- 增加：签名接口解除最大7天限制

Version 2.5.6
-------------
- 增加：listv2默认返回owner信息

Version 2.5.5
-------------
- 修复：不支持枚举类型，添加默认unknown枚举值

Version 2.5.4
-------------
- 修复：删除resumable_copy_object中etag校验

Version 2.5.3
-------------
- 修复：上传对象时不支持大小为0的流

Version 2.5.2
-------------
- 修复：upload_file和put_object_from_file不支持空文件问题

Version 2.5.0
-------------
- 增加：桶跨区域复制相关接口
- 增加：桶多版本相关接口
- 增加：桶配置静态网站相关接口
- 增加：桶事件通知相关接口
- 增加：自定义域名相关接口
- 增加：断点续传复制接口
- 增加：目录分享签名接口
- 增加：列举对象v2接口
- 增加：获取桶元数据添加az字段
- 修复：追加写对象必填pre_crc问题

Version 2.4.2
-------------
- 增加：upload_file 和 download_file 支持加密
- 增加：自定义域名预签名
Version 2.4.1
-------------
- 增加：ListObjectsType2 接口
- 增加：桶生命周期相关接口
- 增加：桶策略相关接口
- 增加：桶存储类型相关接口
- 增加：桶CORS相关接口
- 增加: 桶镜像回源相关接口
- 增加: 桶ACL相关接口
- 增加: 对象标签相关接口
- 增加: fetch 相关接口
- 修复: copy 相关接口校验 etag
Version 2.3.4
-------------
- 修复：download_file 缺陷
- 修复：proxy 支持 https

Version 2.3.3
-------------
- 修复：删除不必要依赖

Version 2.3.2
-------------
- 修复：开启DNS缓存后，重复包装创建tcp连接问题
- 修复：部分字段类型

Version 2.3.1
-------------
- 修复：put_object_from_file 参数类型注解错误问题
- 修复：upload_part_copy 参数类型注解错误问题

Version 2.3.0
-------------
- 增加：断点续传下载功能
- 增加：客户端 CRC 校验功能
- 增加：客户端 DNS 缓存功能
- 增加：客户端断流校验功能
- 增加：进度条共功能
- 增加: 日志功能
- 增加: 上传下载客户端限速功能
- 改变：统一异常错误定义
- 增加：Proxy 功能

Version 2.1.0
-------------
- 改变：对齐各语言 SDK 使用接口与初始化客户端参数
- 增加：断点传输续传功能
- 增加：v2.1.0 相关unittest
- 改变：修改 User-Agent 命名规范
- 增加：v2.1.0 使用示例

Version 1.0.0
-------------
- 基于requests库构建 TOS Python SDK
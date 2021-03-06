# Node.js
## 第三方库
* 文件处理
  * [fs-extra](https://github.com/jprichardson/node-fs-extra) 文件操作工具库。支持给不存在的文件夹，文件写内容。
* [Yargs](https://www.npmjs.com/package/yargs) 解析命令行的参数。
* 语义化 SQL 字符串(SQL generation)
  * schemaless(不需要建表的Schema，就能生成SQL)
    * [squel](https://github.com/hiddentao/squel) [文档](https://hiddentao.com/squel/api.html)
    * [SQL query builder](https://github.com/dresende/node-sql-query)
  * schema
    * [knex](https://github.com/tgriesser/knex)
* ORM
  * [sequelize](https://github.com/sequelize/sequelize)
  * [typeorm](https://github.com/typeorm/typeorm)
  * [bookshelf](https://github.com/bookshelf/bookshelf)
  * [objection.js](https://github.com/Vincit/objection.js/) 轻量级ORM，基于 knex。
* [node acl](https://github.com/OptimalBits/node_acl) 接口权限。
* [parameter](https://github.com/node-modules/parameter) 参数验证。
* 测试
  * [Mocha](https://mochajs.org/) 测试框架。
  * [power-assert](https://github.com/power-assert-js/power-assert) 断言库。
  * [SuperTest](https://github.com/visionmedia/supertest) 测试 HTTP 接口的断言工具库。

## 微服务
可以理解成商城，写的微服务的代码是上面的商品，由微服务框架来提供 路由，验证，写日志，限流等等功能。

库：
* [Kong](https://github.com/Kong/kong)
* [notadd](https://github.com/notadd/notadd) 基于 [nest](https://github.com/nestjs/nest)。

## Demo
* [爬取页面](crawler)



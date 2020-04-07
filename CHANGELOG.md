# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.5.2](https://github.com/daixijun/ansible-role-mysql/compare/v1.5.1...v1.5.2) (2020-04-07)


### Bug Fixes

* **molecule:** 修复软链接造成的 playbook_dir 路径错误的问题 ([1289445](https://github.com/daixijun/ansible-role-mysql/commit/1289445faf4543a8edcc52c06d363c3243cea1b7))
* 修复mysql安装目录权限问题 ([cf5bccc](https://github.com/daixijun/ansible-role-mysql/commit/cf5bccc0950d9ad949bc1a02cff55f1747c2c49f))

### [1.5.1](https://github.com/daixijun/ansible-role-mysql/compare/v1.5.0...v1.5.1) (2020-03-30)


### Bug Fixes

* 增加mysql包下载超时为300秒 ([e636af4](https://github.com/daixijun/ansible-role-mysql/commit/e636af4af3fc043ede83008734762d33d8f4f938))

## [1.5.0](https://github.com/daixijun/ansible-role-mysql/compare/v1.4.0...v1.5.0) (2020-03-27)


### Features

* 添加mysql相关命令到系统PATH环境变量 ([7c1edb9](https://github.com/daixijun/ansible-role-mysql/commit/7c1edb952e54fa50017159dca9b64cd29a57ed5d))
* **mgr:** mgr 添加ssl 支持 ([ba5fffc](https://github.com/daixijun/ansible-role-mysql/commit/ba5fffc480a6cafc90b3efff743b017b2be04150))
* add ssl support ([6fb8c78](https://github.com/daixijun/ansible-role-mysql/commit/6fb8c78f429c5faf6f819daf3c49b8c138d7b830))
* 添加 mysql_sql_mode 变量，用于自定义sql_mode，默认值保持和官方一致 ([454aa4a](https://github.com/daixijun/ansible-role-mysql/commit/454aa4a79a07e72f3dba2b9fcab29a608a0855bc))


### Bug Fixes

* 移除ssl相关配置,因为默认就已经开启并全自动生成证书 ([5936998](https://github.com/daixijun/ansible-role-mysql/commit/5936998125be19f161441ad70d66777cf428561e))
* **mgr:** 修复MGR实例重启 ([885ba73](https://github.com/daixijun/ansible-role-mysql/commit/885ba73ad76d7d9bd4cc4b9154625e74af04a06f))

## [1.4.0](https://github.com/daixijun/ansible-role-mysql/compare/v1.3.1...v1.4.0) (2020-02-27)


### Features

* 添加 mysql_interface 变量用于在多网卡环境中指定集群间通信IP ([92a43ef](https://github.com/daixijun/ansible-role-mysql/commit/92a43ef202c3f2ea95ce81092a49542b79bb09bb))
* 添加 mysql_query 模块用于代替部分命令行执行sql的任务 ([275fc34](https://github.com/daixijun/ansible-role-mysql/commit/275fc3499f04f4e772cb04e7730c9eceb6f3a14e))


### Bug Fixes

* **master_slave:** 隐藏部分日志信息 ([8da5365](https://github.com/daixijun/ansible-role-mysql/commit/8da53657c66a7bc0c21ad60ea6f03024f0074a20))
* **mgr:** 隐藏部分日志 ([2bafabe](https://github.com/daixijun/ansible-role-mysql/commit/2bafabeac99331d856e0ef1267519012df15ee0a))

### [1.3.1](https://github.com/daixijun/ansible-role-mysql/compare/v1.3.0...v1.3.1) (2020-01-05)


### Bug Fixes

* 修复master-slave判断错误 ([7acb25e](https://github.com/daixijun/ansible-role-mysql/commit/7acb25e52b132f756a7ecbc2ff124d5ca4c6280f))

## [1.3.0](https://github.com/daixijun/ansible-role-mysql/compare/v1.2.0...v1.3.0) (2020-01-04)


### Features

* 修改db与user创建逻辑 ([6623851](https://github.com/daixijun/ansible-role-mysql/commit/66238512e5dc8cd7319c2ac5f55dc148eb01ed35))

## [1.2.0](https://github.com/daixijun/ansible-role-mysql/compare/v1.1.5...v1.2.0) (2020-01-03)


### Features

* 修改安装包下载方式 ([27effc3](https://github.com/daixijun/ansible-role-mysql/commit/27effc36a6211f0cd8f9c9029c813fcc5d64761d))

### [1.1.5](https://github.com/daixijun/ansible-role-mysql/compare/v1.1.4...v1.1.5) (2020-01-03)


### Bug Fixes

* 安装包已经存在或者下载成功后执行解压操作 ([be5aaf6](https://github.com/daixijun/ansible-role-mysql/commit/be5aaf6629c6b909d7a8ef3692798e91b711d7e4))

### [1.1.4](https://github.com/daixijun/ansible-role-mysql/compare/v1.1.3...v1.1.4) (2019-12-11)


### Bug Fixes

* 修复check模式下初始化的问题 ([9d20605](https://github.com/daixijun/ansible-role-mysql/commit/9d20605a2b349cbed949b49ea16e23cd7e6843a6))

### [1.1.3](https://github.com/daixijun/ansible-role-mysql/compare/v1.1.2...v1.1.3) (2019-12-11)


### Bug Fixes

* 修复check模式下need_to_initialize变量未定义的问题 ([221756d](https://github.com/daixijun/ansible-role-mysql/commit/221756d3abb5cd202267bcea8fdb8ee0766838ad))

### [1.1.2](https://github.com/daixijun/ansible-role-mysql/compare/v1.1.1...v1.1.2) (2019-12-05)


### Bug Fixes

* 修复删除的系统版本my.cnf路径 ([c363074](https://github.com/daixijun/ansible-role-mysql/commit/c363074c22bc07e2dc151f37863028c29f154c48))

### [1.1.1](https://github.com/daixijun/ansible-role-mysql/compare/v1.1.0...v1.1.1) (2019-12-04)


### Bug Fixes

* 修复 PyMySQL 依赖 cryptography 模块的问题 ([15f4c5c](https://github.com/daixijun/ansible-role-mysql/commit/15f4c5c1c9eb9a951962a9b3f9237ffbf18fda2e))
* 取消移除 mariadb-libs 包 ([67adc4e](https://github.com/daixijun/ansible-role-mysql/commit/67adc4e667144e168a22f2f5a4d8ad89b6c4a10f))

## [1.1.0](https://github.com/daixijun/ansible-role-mysql/compare/v1.0.0...v1.1.0) (2019-12-04)


### Features

* 修改 mysql 下载方式 ([1d11148](https://github.com/daixijun/ansible-role-mysql/commit/1d11148ee40cf142805932d9bfb83ed7c42b3c6d))
* 修改安装包下载流程 ([e74e999](https://github.com/daixijun/ansible-role-mysql/commit/e74e99952b9222560e0456b4a4ad63d305f528b7))
* 添加 -vv 时显示slave状态信息 ([2655533](https://github.com/daixijun/ansible-role-mysql/commit/2655533ceab4622be0803f214eb843c73fcc70ea))

## 1.0.0 (2019-12-02)


### Features

* 添加 Master-Slave 主从同步支持 ([7c3f142](https://github.com/daixijun/ansible-role-mysql/commit/7c3f142106fff7070818c45b05e1f6f61b0a4165))


### Bug Fixes

* change master-slave Converge ([a903dd5](https://github.com/daixijun/ansible-role-mysql/commit/a903dd5db31e5b14e790cace5d5c584f4c2ef4cc))
* fix ansible-lint  Don't compare to empty string ([e4ac4d0](https://github.com/daixijun/ansible-role-mysql/commit/e4ac4d0bd9658b4a3c16593f06245bf8599c3036))
* 禁用部分任务的日志输出(可能包含敏感信息) ([785944e](https://github.com/daixijun/ansible-role-mysql/commit/785944e7e5f8cdad3d77f7814c084f5a8f03fdda))

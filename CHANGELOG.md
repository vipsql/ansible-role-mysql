# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

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

# 部署帮助文档

## 一、相关仓库
[基准仓库](https://github.com/CL-a11y/uCore-x86-32-base-v2)

[文档仓库](https://github.com/CL-a11y/uCore-x86-32-doc)

[实验参考答案仓库](https://github.com/LearningOS/uCore-x86-32-answer)

[自动测试脚本仓库](https://github.com/CL-a11y/uCore-x86-32-test)

[codespace开发环境配置脚本仓库](https://github.com/CL-a11y/uCore-x86-32-conf)

## 二、github classroom部署说明

[github classroom部署说明](./classroom.md)

## 三、说明

在基准仓库中执行自动测试和环境配置需要从自动测试脚本仓库和codespace开发环境配置脚本仓库中拉取.

基准仓库中lab1实验在lab1分支下,以此类推.

自动测试脚本仓库中测试脚本都在main分支下. lab1测试脚本命名为lab1.sh,以此类推

codespace开发环境配置脚本在Makefile中, 执行命令为 make codespaces_setenv

统计分析页面生成,参考[https://github.com/os2edu/classroom-grading-template](https://github.com/os2edu/classroom-grading-template)仓库下的README.md文档.

[在线文档访问入口](https://ucore-x86-classroom-test.github.io/doc_test/)


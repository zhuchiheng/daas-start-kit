


# 快速体验

## 获取本项目

中国大陆
```
git clone https://gitee.com/doublechaintech/daas-start-kit.git
```
中国大陆以外
```
git clone https://github.com/doublechaintech/daas-start-kit.git
```
## 利用示例的模型文件示例生成所有代码

系统支持windows，Mac和Linux


Windows下
```
> cd daas-start-kit
> .\gencode.bat .\bank.xml all
```
Linux&MacOS下
```
> cd daas-start-kit
> ./gencode.sh bank.xml all
```

生成的代码在bizui（React+Ant Design前端）, bizcore(Java后端）

## 请注意！匿名用户的模型文件最多在root下面有10个节点，包含root节点本身注册用户暂时没有限制

```
<root>
  <od1 />
  <od2 />
  <od3 />
  <od4 />
  <od5 />
  <od6 />
  <od7 />
  <od8 />
  <od9 />
  <od10 />
  <od11 message="超过10个对于匿名用户不合法，od代表一个领域对象"/>
</root>
```
注册地址在这里 https://daas.doublechaintech.com/daas/daasService/registration/

# 深入学习DaaS

针对Daas start kit，我们提供了以下三份手册

## [DaaS Start Kit 环境配置与准备](https://docs.qq.com/doc/DTklDV2dNd0RBdEds)

在daas start kit 环境配置与准备文档中，我们描述了如何快速使用 dass start kit 工具包生成代码。

## [DaaS 概要与建模](https://docs.qq.com/doc/DTnBhWU5tVXZoZHpj)

在 daas 概要与建模文档中，我们详细的描述了如何编写daas start kit工具包能够处理的XML 文件以及使用XML文件建模的高级特性。

## [DaaS 开发指南](https://docs.qq.com/doc/DTkxKYnhKV0R2amxr)

在 daas 开发指南文档中，描述了如何使用daas start kit 开发Java部分的定制化代码。

# Bolt.Diy服务实例部署文档

## 概述
![img.png](img.png)
Bolt.diy是 Bolt.new 的官方开源版本，Bolt.new是一个AI驱动的Web开发Agent, 支持直接从浏览器编写Prompt，运行，编辑和部署全栈应用程序, 而无需本地设置。Bolt.diy有以下优势
- 支持多种大模型，包括OpenAI， Anthropic, Ollama, OpenRouter, Gemini, LMStudio, Mistral, xAI, HuggingFace， DeepSeek、OpenAILike等。
- 支持将代码恢复到以前的版本
- 支持在Prompt中添加图片
- 支持将项目下载到本地
- 支持Docker快速部署
- 支持集成的terminal,方便页面调试
- 有活跃的社区支持

## 计费说明

Bolt.diy在计算巢上的费用主要涉及：

- 所选vCPU与内存规格
- 系统盘类型及容量
- 公网带宽

计费方式包括：

- 按量付费（小时）
- 包年包月

百炼模型调用费用:
当您首次开通百炼时，平台会自动为您发放各模型的新人专属免费额度，详情请看[百炼新人免费额度](https://help.aliyun.com/zh/model-studio/new-free-quota?spm=5176.24779694.console-base_help.dexternal.6ab44d22erpR17#view-quota)。


## 部署架构
部署架构采用ECS(云服务器)单机部署
![img_1.png](img_1.png)`(部署概述内容)`

## 部署流程

### 部署步骤


### 验证结果

`(验证结果内容)`

```
eg:

1. 查看服务实例。服务实例创建成功后，部署时间大约需要2分钟。部署完成后，页面上可以看到对应的服务实例。 
2. 通过服务实例访问TuGraph。进入到对应的服务实例后，可以在页面上获取到web、rpc、ssh共3种使用方式。
```

### 使用说明

`(服务使用说明内容)`

```
eg:

请访问Demo官网了解如何使用：[使用文档](https://www.aliyun.com)
```

## 问题排查

`(服务使用说明内容)`

```
eg:

请访问[Demo的问题排查链接](https://www.aliyun.com)获取帮助。
```

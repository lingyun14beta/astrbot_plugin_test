# astrbot_plugin_test

AstrBot 插件。

## 安装

将本插件放入 AstrBot 的 `data/plugins/` 目录下。

## 配置

通过 AstrBot WebUI 的插件配置面板进行配置。

## 目录结构

参考 [AstrBot 插件开发文档](https://docs.astrbot.app/dev/star/plugin-new.html)：

```
astrbot_plugin_test/
  main.py          # 插件入口
  metadata.yaml    # 插件元数据
  _conf_schema.json # 配置 Schema（可选）
  requirements.txt  # 依赖列表（可选）
```

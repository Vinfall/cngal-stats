# CnGal Stats

WIP CnGal Statistics Visualization Demo.

## TODO

- `真实Id` -> `index`, rm `Id`
- datasette-dashboards

## 启动

[CnGal 资料站数据汇总][data] 页面下载数据：导出数据 -> CSV -> 保存，重复保存每一项数据到本项目目录。

```sh
# 安装命令行依赖
mise install
# 安装额外的 datasette 依赖
mise run install
# 自动初始化/重建数据库并启动
mise run serve
```

访问 <http://127.0.0.1:8001/cngal> 即可。

## 卸载

```sh
# 删除数据库
mise clean
# 卸载 mise
# 手动删除见 https://mise.jdx.dev/installing-mise.html#uninstalling
mise implode
# 删除本项目
cd ..
rm -rf cngal-stats
```

[data]: https://www.cngal.org/data

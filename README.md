# 说明
覆盖 Home Assistant 地图面板的同名文件，适用版本 0.57.0及以上。

如果你是通过虚拟环境安装 HA 的，如 All-in-one，那么路径为：

```
/srv/homeassistant/homeassistant_venv/lib/python3.5/site-packages/hass_frontend/panels
```

之后，替换上级文件夹（`/srv/homeassistant/homeassistant_venv/lib/python3.5/site-packages/hass_frontend`）中 `__init__.py`内 `"panels/ha-panel-map.html"`的 md5 值。

**注意路径中 python 3.x 为所安装的 python 版本号，请自行填写选择 3.5 或 3.6。**

更多 Home Assistant 的教程和经验欢迎浏览我的博客：

[http://cxlwill.cn](http://cxlwill.cn)

    


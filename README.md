
Upgrade [old package](https://github.com/Lexfoxer/Leaflet.WMTS) for package builders .

# Leaflet.WMTS vue2

## 描述 

原有基础上修改适用geoserver的版本


## 安装

```html
npm install wgis.leaflet.wmts.vue2;
```


### 使用案例
 
```js 
//图
    var satelliteLayer= L.tileLayer.wmts(
            "http://127.0.0.1:8080/geoserver/gwc/service/wmts",
            {
              layer: 'topp:beijing',//规定的图层名
              style: "",//使用样式
              tilematrixset: "mercator",//比例尺集EPSG:3857
              format: 'image/png',
              tileSize: 256,
              attribution: "<a href='https://github.com/pengge/wgis.leaflet.wmts.vue2'>GitHub </a>&copy; "
            }
    );
```

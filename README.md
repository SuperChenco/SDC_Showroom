# 曜之岩 SDC 外墙材料虚拟展厅

基于 Three.js 的外墙材料搭配预览。页面按约 8 × 6 m 建筑立面与 455 × 1010 mm 花色源图制作；每张源花色沿板材长边重复 3 次，组成 455 × 3030 mm 板材。

## 本地运行

在仓库根目录启动静态 HTTP 服务：

```powershell
python -m http.server 8089 --bind 127.0.0.1
```

打开 <http://127.0.0.1:8089/>。请通过 HTTP 打开页面，避免浏览器对 `file://` 本地贴图的限制。

## 文件

- `index.html`：GitHub Pages 首页
- `virtual-exterior-showroom.html`：展厅页面
- `Pattens/_sourceTiles/`：按实际源花色尺寸裁切出的轻量贴图
- `Pattens/_thumbs/`：产品选择面板缩略图

原始产品照片没有纳入仓库。

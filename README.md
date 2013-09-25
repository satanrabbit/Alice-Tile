# tile

---

// 基于alice规范的Tile通用样式

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/tile.css">

### 默认

````html
<div class="ui-tile">
	<div class="ui-tile-title">通知公告</div>
    <div class="ui-tile-main">
        <div class="ui-tile-icon "> <i class="ui-tile-icon-bus">.</i></div>
        <div class="ui-tile-content">
            <div style="margin:20px 10px;line-height:32px;font-size:16px;font-weight:400;">
                报修与服务预约
            </div>
        </div>
    </div>
    <div class="ui-tile-bar">
    &emsp;设施、设备故障报修与维修服务预约
    </div>
</div>
````

### 示例一 无title

````html
<div class="ui-tile">
    <div class="ui-tile-main">
        <div class="ui-tile-icon "> <i class="ui-tile-icon-bus">.</i></div>
        <div class="ui-tile-content">
            <div style="margin:20px 10px;line-height:32px;font-size:16px;font-weight:400;">
                报修与服务预约
            </div>
        </div>
    </div>
    <div class="ui-tile-bar">
    &emsp;设施、设备故障报修与维修服务预约
    </div>
</div>
````

### 示例二 无底部bar

````html
<div class="ui-tile">	
	<div class="ui-tile-title">通知公告</div>
    <div class="ui-tile-main">
        <div class="ui-tile-icon "> <i class="ui-tile-icon-bus">.</i></div>
        <div class="ui-tile-content">
            <div style="margin:20px 10px;line-height:32px;font-size:16px;font-weight:400;">
                报修与服务预约
            </div>
        </div>
    </div>
</div>
````
### 示例三 只有tile-main

````html
<div class="ui-tile ui-tile-main-only">
    <div class="ui-tile-main">
        <div class="ui-tile-icon "> <i class="ui-tile-icon-bus">.</i></div>
        <div class="ui-tile-content">
            <div style="margin:20px 10px;line-height:32px;font-size:16px;font-weight:400;">
                报修与服务预约
            </div>
        </div>
    </div>
</div>
````
### 示例四 无tile-icon

````html
<div class="ui-tile ui-tile-icon-none">
    <div class="ui-tile-title">通知公告</div>
    <div class="ui-tile-main">
        <div class="ui-tile-icon "> <i class="ui-tile-icon-bus">.</i></div>
        <div class="ui-tile-content">
            <div style="margin:20px 10px;line-height:32px;font-size:16px;font-weight:400;">
                报修与服务预约
            </div>
        </div>
    </div>
</div>
````
### 示例五 自定义tile width

````html
<div class="ui-tile" style="width:400px;">
    <div class="ui-tile-title">通知公告</div>
    <div class="ui-tile-main">
        <div class="ui-tile-icon "> <i class="ui-tile-icon-bus">.</i></div>
        <div class="ui-tile-content">
            <div style="margin:20px 10px;line-height:32px;font-size:16px;font-weight:400; background-color:#09f;">
                报修与服务预约报修与服务预约报修与服务预约报修与服务预约报修与服务预约
            </div>
        </div>
    </div>
</div>
````

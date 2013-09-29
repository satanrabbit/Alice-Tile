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
        <div class="ui-tile-icon "> <i class="iconfont" title="银行卡">&#xe809;</i></div>
        <div class="ui-tile-content">
            <div style="margin:20px 10px;line-height:32px;font-size:16px;font-weight:400;">
                报修与服务预约
            </div>
        </div>
    </div>
    <div class="ui-tile-bar">
    &emsp;设施、设备故障报修与维修服务
    <div class="ui-tile-bar-tip">15</div>
</div>
````

### 示例一 无title

````html
<div class="ui-tile">
    <div class="ui-tile-main">
        <div class="ui-tile-icon "><i class="iconfont" title="银行卡">&#xe81e;</i></div>
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
<div class="ui-tile ui-tile-color-amethyst  ">	
	<div class="ui-tile-title">通知公告</div>
    <div class="ui-tile-main">
        <div class="ui-tile-icon "> <i class="iconfont" title="银行卡">&#xE81c;</i></div>
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
        <div class="ui-tile-icon "> <i class="iconfont" title="银行卡">&#xe802;</i></div>
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
        <div class="ui-tile-icon "> <i class="iconfont" title="银行卡">&#xe806;</i></div>
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
        <div class="ui-tile-icon "> <i class="iconfont" title="银行卡">&#xe828;</i></div>
        <div class="ui-tile-content">
            <div style="margin: 10px;line-height:32px;font-size:16px;font-weight:400;  ">
                报修与服务预约报修与服务预约报修与服务预约报修与服务预约报修与服务预约
            </div>
        </div>
    </div>
</div>
````
### 示例六 tile title 位于左侧 ui-tile-color-midnight-blue 

  title 位于左侧时，为考虑整体布局效果，不显示bar

````html
<div class="ui-tile  ui-tile-title-left" >
    <div class="ui-tile-title">通知公告</div>
    <div class="ui-tile-main">
        <div class="ui-tile-icon ui-tile-icon-bus"> <i class="iconfont" title="盾牌-阳">&#xe816;</i></div>
        <div class="ui-tile-content">
            <div style="margin:20px 10px;line-height:32px;font-size:16px;font-weight:400;  ">
                报修与服务预约
            </div>
        </div>
    </div>
    <div class="ui-tile-bar">
    &emsp;设施、设备故障报修与维修服务预约
    </div>
</div>
````
### 示例七 主题 

  title 位于左侧时，为考虑整体布局效果，不显示bar

````html
<div class="ui-tile  ui-tile-title-left ui-tile-color-midnight-blue " >
    <div class="ui-tile-title">通知公告</div>
    <div class="ui-tile-main" style="background-color:#ccc;">
        <div class="ui-tile-icon ui-tile-icon-bus"> <i class="iconfont" title="盾牌-阳">&#xe818;</i></div>
        <div class="ui-tile-content">
            <div style="margin:20px 10px;line-height:32px;font-size:16px;font-weight:400;  ">
                报修与服务预约
            </div>
        </div>
    </div>
    <div class="ui-tile-bar">
    &emsp;设施、设备故障报修与维修服务预约
    </div>
</div>
````

````html
<div class="ui-tile  ui-tile-title-left ui-tile-color-amethyst" >
    <div class="ui-tile-title">通知公告</div>
    <div class="ui-tile-main">
        <div class="ui-tile-icon ui-tile-icon-bus"> <i class="iconfont" title="盾牌-阳">&#xe806;</i></div>
        <div class="ui-tile-content">
            <div style="margin:20px 10px;line-height:32px;font-size:16px;font-weight:400;  ">
                报修与服务预约
            </div>
        </div>
    </div>
    <div class="ui-tile-bar">
    &emsp;设施、设备故障报修与维修服务预约
    </div>
</div>
````

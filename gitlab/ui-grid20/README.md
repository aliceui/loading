# ui-grid20
---

990像素定宽20栅格布局。

---


##使用说明
.ui-grid-row

表示一行，用于包裹.ui-grid20-{{number}}。一行内的栅格数不要超过 20。

.ui-grid-{{number}}

表示区域跨越了多少列。数字从 1 到 20，例如ui-grid-18。

    <div class="ui-grid20-row">
        <div class="ui-grid20-5">ui-grid-5</div>
        <div class="ui-grid20-10">ui-grid-10</div>
        <div class="ui-grid20-5">ui-grid-5</div>
    </div>



## 演示

    <link type="text/css" rel="stylesheet" media="screen" href="src/ui-grid20.css">
    <style>
    .wrapper {
        width: 990px;
        margin: 30px auto 0;
    }
    .ui-grid20-row div {
        background: #5DBB73;
        box-shadow: 0 1px 0 #4FAA65 inset, 0 -1px 0 #4FAA65 inset, 1px 0 0 #4FAA65 inset, -1px 0 0 #4FAA65 inset;
        transition-duration: 0.3s;
        text-align: center;
        padding: 3px 0;
    }
    .ui-grid20-row div:hover {
        background: #72DD8D;
    }
    </style>
    
    <div class="wrapper">
    
        <div class="ui-grid20-row">
            <div class="ui-grid20-20">ui-grid20-20</div>
        </div>
        
        <div class="ui-grid20-row">
            <div class="ui-grid20-10">ui-grid20-10</div>
            <div class="ui-grid20-10">ui-grid20-10</div>
        </div>
        
        <div class="ui-grid20-row">
            <div class="ui-grid20-5">ui-grid20-5</div>
            <div class="ui-grid20-10">ui-grid20-10</div>
            <div class="ui-grid20-5">ui-grid20-5</div>
        </div>
        
        <div class="ui-grid20-row">
            <div class="ui-grid20-16">ui-grid20-16</div>
            <div class="ui-grid20-4">ui-grid20-4</div>
        </div>
    
    </div>

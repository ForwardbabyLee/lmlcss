# lmlcss

    /*显示成盒子模式*/
        display: -webkit-flex; /* Chrome 21+, Safari 6.1+, iOS Safari 7+, Opera 15/16 */
        display: -moz-flex; /* Firefox 18+ */
        display: flex; /* Chrome 29+, Firefox 22+, IE 11+, Opera 12.1/17/18, Android 4.4+ */
        display: -ms-flexbox; /* IE 10 */
        display: flexbox;
        display: box;
        display: -moz-box; /* Firefox 17- */
        display: -webkit-box; /* Chrome 4+, Safari 3.1, iOS Safari 3.2+ */

        -webkit-box-align: center;/*垂直居中*/
        -moz-box-align: center;
        box-align: center;

        -webkit-box-pack:center;/*水平居中*/
        -moz-box-pack:center;
        box-pack:center;
        
     /*一、当文本溢出，显示省略号*/
        .test {
        text-overflow: ellipsis;
        overflow:hidden;
        white-space:nowrap;

        width: 180px;
        background: #999;
        color:red;
      }
      /*二、当光标浮动到元素是那个，显示全文本*/
      .test:hover {
          text-overflow:inherit;
          overflow:visible;
      }
        
        
<h4><span style="color:#f45;">看点1:</span>nav的父元素.box添加属性{float: left;position:relative;left:-50%;},如果float:right,则left:50%;</h4>
<h4><span style="color:#f45;">看点2:</span>.box的父元素.box添加属性{float: left;position:relative;left:50%;},如果float:right,则left:-50%;</h4>

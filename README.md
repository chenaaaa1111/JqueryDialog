# JqueryDialog
Jquery自定义弹框组件
一个简单的自定义弹框，需要依赖jQuery 和frozen.css
算是他们的一个小插件
使用方式
css:
    <link rel="stylesheet" href="http://i.gtimg.cn/vipstyle/frozenui/2.0.0/css/frozen.css">
js:
//路径根据项目路径而定
 <script type="text/javascript" src="js/lib.js"></script>
 
    <script type="text/javascript">
        showPromise('haha',function(){
                alert('弹窗关闭')
        });
        showDialog({msg:'HELLO WORLS',
            makeSure:function(res){
            console.log('123');
            },
            cancen:function(){
                alert(66)
            }

    })

    </script>

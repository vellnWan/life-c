--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

前言:  

>初学者，水平比较菜，大家多包涵。  
    
>发这个项目的目的是想我的microsoft e5账户安全续约，但是我学c和python的代码实在没啥价值，就挑了一个我看来有点用的发了。  
    
>本文是基于按键精灵看广告白嫖起点每天50章节卡奖励的小脚本。  
    
>之前尝试过基于python写一个自动看广告的程序，但是写到一半发现对于初学者来讲使用代码捕捉要素还是有点麻烦（我太菜了），最后想起了当年用按键精灵游戏挂机刷钱，于是选择了按键精灵来完成。  
    
>后面可能还会发基于python的看广告程序（优点是不需要下载脚本精灵，缺点是我还没写出来，如果我的e5账户一直活着的话它应该有机会和大家见面hhh）。  
    
>好的，闲话就到这里，接下来附上最重要的按键精灵的官网，大家可以根据自己的需求自行下载，网上关于他的教程还是比较全面的，大家也可以去小破站学学然后就可以自己写一个自定义用途的脚本了。  

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

按键精灵官网：  
    http://www.anjian.com  

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

使用说明：  
>本脚本适用于pc端，安卓端因为我没有使用需求所以没做，有需要的朋友可以自己做一个hhh；  
>每个设备的显示器不同，所以具体坐标会有所区别，大家可以自行修改（特别简单）；  
>8.0那个文件是在界面“我”直接点击的，3.0那个是8.0结束之后看3个广告得10点章节卡的脚本；  
>3.0和8.0没写在一起是因为起点现在有设备观看限制，大家应该都懂hhh；  
>使用脚本之前建议先开启起点pc端全屏模式，避免每次白嫖的时候还得调整坐标；  

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

脚本内容（8.0）：  

>MoveTo 691, 416     //福利中心坐标  
>Delay 55            //休眠时间  
>LeftClick 1         //左键点击次数  
>Delay 2555          //进入福利中心休眠时间（根据自己的电脑进入速度和网速自行调整）  
>For 8               //循环次数  
	>>MoveTo 928, 560   //移动到看广告按钮坐标  
	>>Delay 55  
	>>LeftClick 1  
	>>MoveTo 662, 81    //移动到左上角退出按钮坐标  
	>>Delay 16943       //等待广告播放完毕时间，可根据网速自行调整  
	>>LeftClick 1  
	>>MoveTo 928, 720   //这个广告看完后确认按钮  
	>>Delay 555  
	>>LeftClick 1  
	>>Delay 555  
>Next                 //循环结束  

>3.0的内容和8.0差不多，我就不写注释了，大家可以直接下载两个文件然后自行修改  
>上面休眠时间的单位是毫秒，大家可以根据自己的网速自行修改，坐标的话按键精灵里面有一个抓抓可以获取坐标  

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    

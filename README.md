
    Charlin出框架的目标：简单、易用、实用、高度封装、绝对解耦！

# CoreAleetViewManagerVC
####高度集成AlertView/ActionSheet,真的只需要一句代码！



##框架特性：<br />
>1.一句代码搞定，定义和接收数据，一句话，不再有烦人的代理模式，不需要！<br />
>2.集成AlertView、ActionSheet,两个东西集成后调用同一句代码。真正的高度集成！<br />
>3.参数数组化，正常传数组会导致一些问题，本框架已经处理。<br />
>4.已经处理系统版本兼容问题，多线程问题，请放心使用！<br />
>5.直接一句代码即可使用，不需要记录任何成员变量，真正的绿色无嵌入使用。<br />
>6.已经严管了控制器的生命周期，视图消失会自动释放。不用担心内存问题。<br />

<br /><br />

##使用示例
    //显示并处理一个alertView
    [CoreAleetViewManagerVC showWithAleetViewType:CoreAleetViewTypeUIAlertView inController:self title:@"标题" message:@"描述" cancelButtonTitle:@"取消" destructiveButtonTitle:@"毁灭" otherButtonTitles:@[@"其他1",@"其他2"] clickedButtonBlock:^(NSInteger index) {
        NSLog(@"%i",index);
    }];


<br /><br />

-----
    CoreAleetViewManagerVC 高度集成AlertView/ActionSheet,真的只需要一句代码！
-----

<br /><br />




#### 版权说明 RIGHTS <br />
作品说明：本框架由iOS开发攻城狮Charlin制作。<br />
作品时间： 2015.03.03 18:07<br />

#### 关于Chariln INTRODUCE <br />
作者简介：Charlin-四川成都华西都市报旗下华西都市网络有限公司技术部iOS工程师！<br /><br />


#### 联系方式 CONTACT <br />
Q    Q：1761904945（请注明缘由）<br />
Mail：1761904945@qq.com<br />

# HACursor

## Introduction:
## Presentation:
## Usage:
#### 代码例子:其中（必选）为必须设置的属性，其余可根据需要来设置

    HACursor *cursor = [[HACursor alloc]init];
    cursor.frame = CGRectMake(0, 20, self.view.width, 45);
    
    //需要管理的scrollView （必选！！）
    cursor.rootScrollView = scrollView;
    //显示的标题栏的标题（必选！！）
    cursor.titles = self.titles; 
    //需要管理的子页面（必选！！）
    cursor.pageViews = self.pageViews;
    
    //设置标题普通状态下的颜色
    cursor.titleNormalColor = [UIColor whiteColor];
    //设置标题选中状态下的颜色
    cursor.titleSelectedColor = [UIColor redColor];
    //是否需要显示排序的按钮
    cursor.showSortbutton = YES;
    //设置背景颜色
    cursor.backgroundColor = [UIColor yellowColor];
    //设置最小化的字体
    cursor.minFontSize = 10.0;
    //设置最大化的字体
    cursor.maxFontSize = 30.0;
    //设置是否需要渐变字体的大小
    cursor.isGraduallyChangFont = NO;
    //设置是否需要渐变字体的颜色
    cursor.isGraduallyChangColor = NO;
    [self.view addSubview:cursor];
## Requirement:
* iOS7.0以上
* Xcode 6

## 侧滑面板（对ViewGroup的自定义）
* 应用场景: 扩展主面板的功能
* 功能实现:
> 1. ViewDragHelper: Google2013年IO大会提出的,
>  解决界面控件拖拽移动问题. (v4包下)
> 2. mTouchSlop 最小敏感范围, 值越小, 越敏感

* 伴随动画:
> 1. 左面板: 缩放动画, 平移动画, 透明度动画
> 2. 主面板: 缩放动画
> 3. 背景动画: 亮度变化 (颜色变化)

* 状态监听\触摸优化:
> 1. 设置并更新状态
> 2. 触摸优化: 重写ViewGroup里onInterceptTouchEvent和onTouchEvent

Github  大牛
Jake Wharton  
nineoldandroids.jar  属性动画
ActionBarSherlock  

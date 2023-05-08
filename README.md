# ZBWWidgetRotationKit
iOS 动态组件实现工具  组件旋转
使用：
将ZBWWidgetRotationKit.framework 拉进项目  引用 import ZBWWidgetRotationKit
ZBWWidgetRotationView(content: testView(), speedType: 0)
testView 是你创建view 这个函数可以让view旋转起来   testView旋转速度 0：与秒针一致  1：与分针一致 2：与时针一致
注意：
实现的api是高版本xcode废弃的，以此实现旋转组件是否会被苹果特殊“优待“，还没测试过~ 此实现只为自己娱乐

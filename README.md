# bubble
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![Badge](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu/#/zh_CN)
一个聊天气泡组件

## 用法
#### 1.在 pubspec.yaml 中添加依赖
```
dependencies:
  plugin1:
    git:
      url: https://github.com/yah0130/bubble.git
```
#### 2.使用
```dart
Bubble(
  color: Colors.purple,
  child: Text(
    "你6666",
    style: TextStyle(color: Colors.white),
  ),
)
```
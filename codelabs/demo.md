summary: 备份
id: first_codelab
categories: Android
tags: android
status: Published
authors: Nthily
Feedback Link: https://github.com/Nthily

# 小试牛刀

## 标题
```kotlin
class MainActivity : ComponentActivity() {

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContent {
            ColumnDemo()
        }
    }
}

@Composable
fun ColumnDemo() {
    Column(){
        Text("你好呀")
        Text("我正在使用 Android Studio")
        Text("现在是晚上")
    }
}
```
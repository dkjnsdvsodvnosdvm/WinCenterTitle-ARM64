# WinCenterTitle-ARM64
这里是放置未完工的ARM64版的WinCenterTitle
### TODO
1.解决WinCenterTitle的显示BUG

2.添加WinCenterTitle对arm64的支持（已完成）

3.能够Hook到由WindowBlinds11渲染的窗口边框上面，而没有边框模糊效果溢出
## 一些事
WinCenterTitle.exe是ARM64文件，WinCenterTitleLibrary.dll是ARM64EC文件（主要因为库基本上是X64）

还有，这些文件是基于22000的SDK,但实际上，它并不兼容22000的DWM。或许拿21390的DWM来替换22000的DWM，就可能让它正常工作（或许21390的DWM根本不兼容22000，或者WinCenterTitle干脆兼容不了21390的DWM）

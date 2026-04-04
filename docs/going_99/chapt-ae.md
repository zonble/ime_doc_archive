# 附錄 E、語音介面呼叫範例

## 1. C 語言範例

```c
#include "gospkapi.h"

void WinMain(int argc, char **argv)
{
    openGoingIME();
    goingSpeakOutText("一隻隻可愛的小花貓");
    sleep(3);
    closeGoingIME();
}

 note: 程式需連結 gospkapi.lib
```

## 2. Visual Basic 語言範例

>

```vb
Declare Function goingSpeakOutText% Lib "c:\GOING32\gospkapi" (ByVal prompt$)
Declare Function openGoingIME% Lib "c:\GOING32\gospkapi" ()
Declare Function closeGoingIME% Lib "c:\GOING32\gospkapi" ()

Private Sub Command1_Click()
    openGoingIME
End Sub

Private Sub Command2_Click()
    goingSpeakOutText("一隻隻可愛的小花貓")
End Sub

Private Sub Command3_Click()
    closeGoingIME
End Sub
```

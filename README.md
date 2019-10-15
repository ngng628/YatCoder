﻿# YatCoder
競技プログラミング（プログラミングコンテスト）のコードを、Siv3D スタイルで書けるライブラリ

**対応コンパイラ:** C++14 (GCC 5.4.1)

**ライセンス:** CC0 1.0 Universal

## 機能

### 1. インクルードされるヘッダ

`# include <bits/stdc++.h>`

### 2. 数値型

| 名前       | 説明              |
|----------|-----------------|
| int8     | 8-bit 符号付き整数型   |
| int16    | 16-bit 符号付き整数型  |
| int32    | 32-bit 符号付き整数型  |
| int64    | 64-bit 符号付き整数型  |
| int128   | 128-bit 符号付き整数型 |
| uint8    | 8-bit 符号なし整数型   |
| uint16   | 16-bit 符号なし整数型  |
| uint32   | 32-bit 符号なし整数型  |
| uint64   | 64-bit 符号なし整数型  |
| uint128  | 128-bit 符号なし整数型 |
| float32  | 単精度浮動小数点数型      |
| float64  | 倍精度浮動小数点数型      |
| float128 | 四倍精度浮動小数点数型     |

```C++
# include "YatCoder.hpp"

int main()
{
    uint8 a = 0b0101;
    int32 b = -200;
    uint64 c = 1234567890123;
    int128 d = int128(1) << 100; // 1267650600228229401496703205376
    uint128 e = uint128(-1); // 340282366920938463463374607431768211455
    float32 f = 3.14f;
    float64 g = 3.14;
    float128 h = 3.14L;
}
```

🚧🚧🚧


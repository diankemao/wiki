# Swow

> ⚠️ 預覽版本, 非生產可用

**Swow是一個使用PHP和C編寫的高性能網絡通信引擎**, 它致力於使用最小C核心及多數PHP代碼以支持PHP高性能編程

## ⚡️ 特點

+ 主要功能使用PHP實現, 核心部分使用純C實現
+ 最小核心原則, 類Opcache擴展, 為PHP提供高性能的IO引擎
+ 跨平台, 支持所有主流操作系統
+ 可選的Composer安裝
+ 支持主協程, 無需創建協程即可使用
+ 支持協程中斷, kill協程等特性
+ 可編程的搶佔式協程調度功能
+ 線程安全
+ 支持在所有SAPI下運行
+ 使用異常機制而不是錯誤碼

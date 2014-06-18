WRK
===

## 簡介
Git:[WRK](https://github.com/wg/wrk)

這是一套簡單的壓力測試工具

Base on Lua


## 如何開始


1. 安裝Lua 
   ```
   $ brew install lua
   ```
2. Make
   ```
   $ cd wrk
   $ make 
   ```
3. 執行
   ```
    $ ./wrk -c 6 -t 5 -d 30s -s wrk-scripts/post_data_api.lua http://localhost:5000/review/api/data/
   ```

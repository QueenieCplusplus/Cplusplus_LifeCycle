# Cplusplus_LifeCycle
物件的生命週期

__________________

stactic obj 靜態物件 (全域變數或是類別或方法中的 static 物件)

僅會被創建一次，也僅會被初始化一次，存活時間直到程式 end 為止。
在程式執行期間，靜態物件的位址不會變更。
然而，靜態物件在 mulit-threads 使用時，要特別注意使用 lock 避免資源競奪。

__________________

free store 自由空間 (new 出來的物件)

__________________

temp obj 暫存物件

__________________

automatic obj 自動型物件 (local 變數)

TBD...尚未完成。

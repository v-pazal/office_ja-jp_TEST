
# TaskRequestItem.BeforeAttachmentWriteToTempFile 事件 (Outlook)

将与父对象的实例相关的附件写到临时文件前发生。


## 语法

 _表达式_. **BeforeAttachmentWriteToTempFile**( ** _Attachment_**, ** _Cancel_** )

 _表达式_ 一个表示 **TaskRequestItem** 对象的变量。


### 参数



|**名称**|**必需/可选**|**数据类型**|**说明**|
|:-----|:-----|:-----|:-----|
| _Attachment_|必需|**[Attachment](3e11582b-ac90-0948-bc37-506570bb287b.md)**|**附件** 以进行写入。|
| _Cancel_|必需|**Boolean**|设置为 **True** 以取消操作;否则，设置为 **False** 以允许写入 **附件** 。|

## 另请参阅


#### 概念


[TaskRequestItem 对象](2908a28a-634c-e786-aa53-f3e32038b727.md)
#### 其他资源


[TaskRequestItem 对象成员](d43114ee-be91-ff02-3424-525da2cf3a50.md)
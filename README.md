# 五笔091输入方案〔Rime-wubi091〕
1. This is a Chinese input method based on Rime input engine<br>
2. `wubi091.schema.yaml` is the configuration file<br>
  `wubi091.dict.yaml` is the charactor encoding list<br>
  `wubi091.extended.dict.yaml` is the phrase list<br>
  `weasel.custom.yaml` is the Candidate frame skin file<br>
3. To personalise, follow instructions in `wubi091.schema.yaml`<br>
****
1. 本方案为基于Rime输入法引擎的中文五笔输入方案<br>
2. `wubi091.schema.yaml`为方案配置文档<br>
   `wubi091.dict.yaml`为词库及编码列表<br>
   `wubi091.extended.dict.yaml`为自定义词库<br>
   `weasel.custom.yaml`为候选框皮肤<br>
3. 如需更改默认配置，请按照`wubi091.schema.yaml`中注释进行<br>
# 使用方法〔How to use〕
1. Download [Rime](https://rime.im/)<br>
2. Clone or download the schema files from this repository, relocate the files to Rime's user folder:<br>
`MacOS X`: ~/Library/Rime<br>
`Windows`: User_Direction\AppData\Roaming\Rime<br>
3. Add<br>
```
patch:
  schema_list:
    - {schema: wubi091}
```
   to `default.custom.yaml` in Rime's user folder.<br>
4. Deploy. Then press control+` and choose wubi091 to start to use.<br>
****  
1. 下载[中州韵输入法引擎](https://rime.im/)<br>
2. 复制或下载此中档案，将下载的文件放入【用户文件夹】：<br>
`MacOS X`: ~/Library/Rime (鼠须管状态栏选单中的「用户文档…」)<br>
`Windows`: User_Direction\AppData\Roaming\Rime (开始→所有程序→小狼毫输入法→用户文件夹)<br>
3. 在default.custom.yaml中加入：<br>
```
patch:
  schema_list:
    - {schema: wubi091}
```
4. 重新部署后用Control+` 或 F4 (仅Windows) 叫出〔方案选单〕，选中「091五笔」。<br>
# 其他信息
*  编码方案作者：行走的风景  
*  点儿词库作者：晓览  
*  点儿词库版本：2002无emoji
*  整理及上传者：aLIEz
*  联系邮箱：807303359@qq.com
*  如有侵权，请即联系删除
****

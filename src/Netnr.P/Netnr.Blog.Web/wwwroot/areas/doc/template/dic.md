﻿### SysUser

用户表，储存用户信息

|字段|类型|主键|自增|不为空|默认值|注释|
|----|----|:-----:|:-----:|:-----:|:-----:|-----|
|uid |int |YES |  |YES | | |
|username |varchar(20) | | | | |用户名 |
|password |varchar(50) | | | | |密码 |
|name  |varchar(15) | | | | |昵称 |
|reg_time |datetime | | | | |注册时间 |

---

### SysRole

角色表，储存角色信息

|字段|类型|主键|自增|不为空|默认值|注释|
|----|----|:-----:|:-----:|:-----:|:-----:|-----|
|rid |int |YES |  |YES | | |
|rname |varchar(20) | | | | |角色名 |
# robocon_note

# 萝卜坑表设计

## 位置表
| id | BigInt | 自增id |
| --- | --- | --- |
| tid | BigInt | 坑id |
| lid | Integer | 楼牌号id |
| fid | Integer | 楼层数id |

## 楼表
| id | Integer | 自增id |
| --- | --- | --- |
| lid | Interger | 楼id |
| info | varchar(1024) | 楼信息说明 |

## 楼层表 
| id | Integer | 自增id |
| --- | --- | --- |
| fid | Interger | 楼层数id |
| lid | Interger | 楼id |
| info | varchar(1024) | 楼层信息说明 |

## 坑表
| id | BigInt |自增id |
| --- | --- | --- |
| tid | BigInt | 坑id |
| status | Integer | 0：开 1：关 |
| gender | Integer | 0：男 1：女|

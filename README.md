# Discord 赛博经济模组核心
1. 本模组的全部命令应该只有服主和技术组能够使用。
2. 本模组只负责记录所有成员（包括虚拟实体）拥有物品。
3. 为某人添加物体，需要调用下面命令，其中num为浮点数:
```/core give @id @item @num```
4. 将某人的物品给另一个人。
```/core transport @sender_id @reciver_id @item @num```
5. 输出某个人拥有的全部物品。
```/core print @id```
6. 输出数据库（高风险操作）
```/core output_dataset```
7. 设置数据库（高风险操作）
```/core set_dataset```
8. 添加核心操作权限
```/core add_root @id```
9. 删除核心操作权限
```/core remove_root @id```
10. 展示核心操作权限
```/core show_root_members```
## C++版球球大作战
### 游戏说明：
游戏为《球球大作战》的精简版与抽象版。<br><br>玩家操控一个小球，小球可以吃散落在四周的食物；除了玩家操控的小球外，
还有 2 个自动移动的小球，它们也可以吃食物。小球吃了食物后会长大，但是所有小球最大
的大小是有限制的。此外，屏幕的随机位置还会出现 5 个刺球，玩家的小球被扎到就会死
亡，但是自动的小球撞到刺球没有事。
如果玩家的球比自动的球大，那么玩家就可以把自动的球吃掉，自动的球随后会自动生
成。游戏的目标是吃掉更多的小球，玩家吃掉的小球数最后会显示在控制台上，这就是玩家
的得分。
所以，向着更高的分数冲刺吧！
### 依赖
用到的图形库为ACLLib。这是一个windows系统下的图形库，所以跨平台性不是很好。
### 设计
![image](https://user-images.githubusercontent.com/68995451/144999617-72192fbd-b133-44cb-ab34-73d343b10a38.png)
### 运行：
$ `make run`
### 运行截图
![image](https://user-images.githubusercontent.com/68995451/145000491-d1d276c6-8d9f-42f6-b480-14d021d4f05a.png)

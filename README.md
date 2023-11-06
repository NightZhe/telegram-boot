# telegram-boot
## 假设机器人名称是my_bot。

## 1-将机器人添加到组中。
# 转到组，单击组名称，单击添加成员，在搜索框中搜索您的机器人，如下所示：@my_bot，选择您的机器人并单击添加。

## 2-向机器人发送虚拟消息。

# 您可以使用此示例：/my_id @my_bot

# 我尝试了一些消息，但并非所有消息都有效。上面的示例工作正常。也许消息应该以 / 开头）

## 3- 转到以下网址： 

# https://api.telegram.org/botXXX:YYYY/getUpdates
# 复制
# 将 XXX:YYYY 替换为您的机器人令牌，如：

# https://api.telegram.org/bot123456789:jbd78sadvbdy63d37gda37bd8/getUpdates
# 复制
## 4- 查找 "chat":{"id":-zzzzzzzzzz，-zzzzzzzzzz 是您的聊天 ID（带有负号）。
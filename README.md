# 文件说明

1. 1.Trajectory tracking.ipynb为用户轨迹追踪代码 http://localhost:8877/notebooks/phone_project_1/Code%20Folder/1.Trajectory%20tracking.ipynb

2. 文件2是判断新入网和新离网代码。

3. 3.Get Frequency.ipynb是获取用户频率的代码  https://github.com/Miki123-gif/phone_project/blob/master/Code%20Folder/3.Get%20Frequency.ipynb

4. 4.time person.ipynb 指定时间进入某地的代码 https://github.com/Miki123-gif/phone_project/blob/master/Code%20Folder/4.time%20person.ipynb

其中文件4是获取某时间进入某地的人群，需要改进下，代码实现的只是某天进过某地的人群。因为可能要改进数据结构，所以这里先等老师回复再修改代码。如果真要实现，可以字典的键是小时，值再嵌套字典，然后获得每个仪器的用户。由于pandas时间切片，获得的是每个时间段，每天的人群。这里我们实现了两层循环。最后只要再外面再加一层循环，即对一天24小时时间切片即可。

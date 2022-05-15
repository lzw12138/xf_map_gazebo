<<<<<<< HEAD
# gazebo地图导入

1、终端打开gazebo，选择左上方的Edit->Model Editor

2、点击custom shapes下面的add，找到map的对应路径，选择xf_map.dae。

3、将地图放置在gazebo环境中，并且点击左上的Model 将static选中。

4、ctrl + s保存文件 路径自己选择，退出gazebo

5、打开4中保存的路径，打开文件夹中的model.sdf，删除

```
        <material>
          <lighting>1</lighting>
          <script>
            <uri>file://media/materials/scripts/gazebo.material</uri>
            <name>Gazebo/Grey</name>
          </script>
        </material>
```

6、重新打开gazebo，点击Insert 找到4中保存路径的文件，添加地图

7、将地图位置调整后保存world文件即可。若底部贴图较为模糊，可以删除gazebo中自带的ground_plane。

8、若想修改地图的位置，参考下面的资料

## 地图由blender制作 参考资料如下

https://www.bilibili.com/video/BV1rT4y1P7HN?spm_id_from=333.337.search-card.all.click

https://blog.csdn.net/qq_48427527/article/details/120312499?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522165260080016782388044596%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=165260080016782388044596&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-120312499-null-null.142^v9^control,157^v4^control&utm_term=blender+%E9%9B%B7%E8%BE%BE&spm=1018.2226.3001.4187



=======
# xf_map_gazebo
gazebo地图仿真
>>>>>>> 0c649a63d82f9920e9d4c9090ccc49dc0bfbc1b2

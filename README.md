1.变量名命名规范 ：

http://zh-google-styleguide.readthedocs.org/en/latest/google-cpp-styleguide/naming/

补充：
所有Activity类统一后缀名是Activity
所有的类中的变量：必须跟所实现的功能有关系，例如bbmInformationItem这种，所有的适配器类后缀名是Adapter，适配器用到的实体统一后缀名Item，
类的命名规范一定要反映用途
每一个函数必须有注释，注明函数的用途

2：注意事项
跟网络有关的一定要判断网络状态，能够处理用户突然掉线的情况，一定不能在主线程处理，推荐Handler处理
  
跟发布有关的要保存到本地的数据库中，然后把你们设计的本地数据库格式，数据库名称传到github上，
轻量级的用SharePredfences

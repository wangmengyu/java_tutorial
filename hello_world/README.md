编译.java文件,生成.class文件的命令：
javac /home/wangmengyu/work/code/java_tutorial/hello_world/HelloWorldApp.java

运行：
cd  /home/wangmengyu/work/code/java_tutorial/hello_world/
java HelloWorldApp 

每个java项目需要有main入口方法,并且需要一个字符串数组作为参数
public static main(String[] args);

命令行参数的传递：它的作用是不用重新编译,
java HelloWorldApp arg1 arg2 

类的修饰尽量public static, 不要用 static public


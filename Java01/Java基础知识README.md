# Java基础知识

目标：以前是用word文档记录知识点，现在准备把他们放到github上。

---

**类**

1，开闭原则:对修改关闭，对扩展开放。

抽象类： 包含抽象方法的类，abstratc类只关心操作，但不关心这些操作的具体实现细节。

接  口； Java不支持多继承，用interface 接口名字来声明一个接口。
		接口中只有抽象方法, 无普通方法，一定是public abstract修饰。接口中所有常量一定是public, abstract。
	    接口中只有常量，无普通变量，所有常量一定是public final 。
		
上转型：老虎是哺乳动物，Tiger extends A ;  Animal a = new Tiger(); 
		![Image text](https://github.com/raoyaoiau/Java/blob/master/images/class01.png)
		
接口回调：interface A{};  Class B implements A ;  A a = new B();
        接口回调很像上转型。

多态：通过上转型和接口回调可以实现多态，并且接口优于抽象类，当然函数重载也是多态。
		              
super
![Image text](https://github.com/raoyaoiau/Java/blob/master/images/class02.png)

final 字面意思final是”最后的“， 修饰类，类不可以被继承，如String类； 修饰变量，则变为常量； 修饰方法，则方法不可以被重写。

重写和重载的区别？

---


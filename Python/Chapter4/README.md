## 第四章 变量与运算符

    1.变量
        1.定义
            Python 中的变量不需要声明。每个变量在使用前都必须赋值，变量赋值以后该变量才会被创建。在 Python 中，变量就是变量，它没有类型，我们所说的"类型"是变量所指的内存中对象的类型。
            等号（=）用来给变量赋值。
            等号（=）运算符左边是一个变量名,等号（=）运算符右边是存储在变量中的值。
    
        2.多个变量赋值
            a=b=c=1
            a,b,c=1,2,'wkl'
    
        3.变量命名规则
            1.字母、数字、下划线
            2.首字母不能使数字
            3.系统关键字，不能用在变量名中，保留关键字
                 如：ant if import
                 不建议使用type
            4.变量名区分大小写
    
        4.值类型与引用类型
             1.值类型(int,str,tuple)
                   a=1
                   b=a
                   a=3
    
             2.引用类型(list set dict)
                   a=[1,2,3]
                   b=a
                   a[0]='1'
    
                   id()获取变量内存地址
    2.运算符
        1.算数运算符
        +   -   *   /   //  %   **
    
        2.赋值运算符
        =   +=  *=  /=  //= %=  **=
    
        3.比较运算符
        ==  !=  >   <   >=  <=
    
        4.逻辑运算符
        操作boolean类型
        and     or      not
        与      或      非
        5.成员运算符
        in      not in
    
        6.身份运算符
        取值与内存地址相同
        is      is not
    
        7.位运算符(把数字当做二进制进行运算)
        & ：按位与
        | ：按位或
        ^ ：按位异或
        - ：按位去反
        << ：左移动
        >> ：右移动
    
    3.如何判断变量的值、身份与类型
        a=1
        type(a)==int
    
        isinstance判断变量的类型
        isinstance(a,int)
    
        isinstance(a,(int,str,float))
    
    对象的三个特征
        id、value、type
    
        ==、is、isinstance
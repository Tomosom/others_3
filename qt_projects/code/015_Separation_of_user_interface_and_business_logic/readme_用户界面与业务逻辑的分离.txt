用户界面与业务逻辑的分离

1. 界面和逻辑
    基本程序架构一般包含:
    - 用户界面模块(UI)
        接收用户输入及呈现数据
    - 业务逻辑模块(Business Logic)
        根据用户需求处理数据
        
2. 基本设计原则
    功能模块之间需要进行解耦
    核心思想:强内聚,弱耦合
    - 每个模块应该只实现单一的功能
    - 模块内部的字模块只为整体的单一功能而存在
    - 模块之间通过约定好的接口进行交互

3. 参考 <<计算器应用程序的整体架构.PNG>>

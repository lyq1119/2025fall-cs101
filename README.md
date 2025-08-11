# 2025fall-cs101: DS Alog （计算概论）

Updated 2010 GMT+8 Aug 10 2025

2025 summer, Complied by Hongfei Yan  
https://github.com/GMyhf/2025fall-cs101/



> 在我们的计算机基础课程中，涵盖的内容包括计算概论（简称“计概”）、数据结构与算法（简称“数算”），以及AI知识介绍。对于AI部分，我们会涉及到一个概览性的介绍、神经网络的关键算法，并通过实战示例来加深理解，甚至从零开始构建大型模型的方法也会有所涉猎。无论你遇到任何相关的问题，都可以在相关课程群里提出。
>
> 我主要负责讲解计算概论B和数据结构与算法B的课程内容。不过，群内也有同学之前已经完成了计算概论A和数据结构与算法A的学习。欢迎大家一起交流学习经验！




## 1 题解 & 教材

https://github.com/GMyhf/2020fall-cs101/blob/main/2020fall_cs101.openjudge.cn_problems.md    
https://github.com/GMyhf/2024fall-cs101/blob/main/2024fall_LeetCode_problems.md  
https://github.com/GMyhf/2020fall-cs101/blob/main/2020fall_Codeforces_problems.md  
https://github.com/GMyhf/2024spring-cs201/blob/main/sunnywhy_problems.md

Book_my_flight_2025spring    
计算机科学导论（第4版）  
语法教材：Python 3教程，https://www.runoob.com/python3/python3-tutorial.html  
或者 Python编程：从入门到实践（第3版）  

算法笔记.胡凡 曾磊  
算法图解  
算法基础与在线实践  
算法导论 第3版  (Thmos.H.Cormen ,Charles E. Leiserson etc.)

AI教材：从零构建大模型 Build a Large Language Model (From Scratch) (Sebastian Raschka)  


## 2 计概B-11班 上课、机考和笔试

上课时间：1-16周 每周 周二 7-9节（15:10-18:00），上课地点：理教207（425座位）

机考时间：第16周周四 7-8节 上机，2025年12月25日 15:08-17:00, 在6号（6A 44台、6B 44台机器）、7号（109台）机房  
笔试时间：周二，2026年1月6日 下午 14:00-16:00

数算总评规划：期末机考1小时52分钟包含6个题目，AC5或者AC6尽量确保获得优秀评级；如果AC0，即使笔试满分，总评最高也只能达到84；如果AC4，笔试成绩较高，在不超优秀率限制的前提下，仍有机会被评定为优秀。

> 北大信息门户，`课表查询`、`课程介绍`
>
> 或者 课程查询，https://dean.pku.edu.cn/service/web/courseSearch.php

## 3 暑假可以开始预习

⚠️：秋季课程Python为主，如果同学坚持C++也可以。

访问“小北智学”平台（zx.pku.edu.cn），找到“计算概论B”课程卡片（计算机学院 闫宏飞），点击并加入课程，即可开启问答式自学之旅。

本课程配备专属知识库，涵盖教材、课件、题解等内容，方便具备一定编程基础的同学自主学习。在学习过程中，遇到任何与课程相关的问题，均可随时向AI助教提问，例如：“详细总结知识库内容”，“课程内容是什么”，“课程大纲有哪些”等。
 如需进一步的人工指导，请发送邮件至：yanhf@pku.edu.cn。

编程部分学习建议，为帮助同学们夯实基础、提升算法思维与问题解决能力，建议按照以下步骤进行练习：

1. 优先完成 LeetCode 热题 100 - 14 - 15（不包括 链表14个、二叉树15个）  
   https://leetcode.cn/studyplan/top-100-liked/
   通过刷题提升常用算法与数据结构的熟练度。
2. 完成课程组精选200余道题目，帮助同学们夯实基础、提升算法思维与问题解决能力。请访问  http://cs101.openjudge.cn， 首次使用需要注册账号并登录，点击"加入"按钮加入"cs101"小组（仅需操作一次）。加入后，点击 “<mark>计算思维算法实践</mark>”即可查看题目列表。题目按难度分为三类：E（Easy 简单），M（Medium 中等），T（Tough 挑战）。
   建议完成全部Easy和Medium题，并积极挑战部分 Tough题。

查阅往年笔试题目，了解笔试风格与重点，做好充分准备：
https://github.com/GMyhf/2024fall-cs101/blob/main/written_exam/written_exam_20241210.md



## 在课程衔接群发布的信息



- VS Code写Python相对容易配置。有同学问到 VS Code写C++程序，我在mac机器上试通了，如上“Writing_First_C++_Program_in_VSCode_on_Mac.pdf”。源文件在  https://github.com/GMyhf/2025fall-cs101/blob/main/Writing_First_C%2B%2B_Program_in_VS-Code_on_Mac.md

  > 24-CYK 计概课前准备，https://github.com/Usercyk/cs101/blob/master/Notes/Preparation.md
  >
  > 写Python，建议使用PyCharm。因为机房VS Code 不好用，很大一个问题是插件太多。

- 计算概论课前任务：盲打技能训练与打字测试，https://github.com/GMyhf/2025fall-cs101/blob/main/question1_before_class.md

- O365（含teams）账号申请链接：https://www.wjx.cn/vm/Y5XwfHD.aspx#     服务邮箱gteams@pku.edu.cn，教师教学发展中心，2025年2月3日

- 阅读《图灵和ACM图灵奖 纪念计算机诞生70周年 1966-2015 第5版 (吴鹤龄，崔林, 吴鹤龄 (19375-), 吴鹤龄, 1937-) 》，《IEEE计算机先驱奖：1980-2006计算机科学与技术中的发明史》

- 同学们在假期里观看一部电影：《模仿游戏》（The Imitation Game 2015）。这部影片讲述了计算机科学奠基人艾伦·图灵破解二战密码的故事。通过了解图灵的生平与贡献，可以更好地理解“图灵机”这一核心概念。同时，这也有助于大家理解“图灵测试”等现代人工智能中的关键术语。


- 如果在校外，开了VPN，https://its.pku.edu.cn/service_1_vpn_client.jsp

  有北大id，应该可以使用 云计算实验平台，https://clab.pku.edu.cn

- `20250218_VM_Shell_LLMs.md` 是上学期 数据结构与算法 课程的一个课件。准备选课 计算概论 的同学，可以跳过其中的编程题目，熟悉其他内容。https://github.com/GMyhf/2025spring-cs201/blob/main/20250218_VM_Shell_LLMs.md

- 北京大学正版软件，https://software.pku.edu.cn/index.html

  此外，在本课程中，我们推荐使用 Markdown 编辑器 Typora（官网：https://typoraio.cn ）来进行文档编写和笔记整理。Typora 操作简洁、所见即所得，非常适合初学者和技术写作。

  Typora 的正版授权价格为 89 元，可激活 3 台设备（购买页面：https://lizhi.shop/products/typora ）。往年也曾出现过优惠价（如 80 元），也有同学选择三人合买的方式分摊费用。

  当然，也可以选择免费替代工具，如 Obsidian等。虽然 Word 也可以使用，但在代码和公式排版方面，体验相对较差。

- 有信息学竞赛基础的同学，可以考虑同时选 计算概论、数据结构与算法。这两门课内容差异较大，没有基础的，还是建议第2学期再选数算。

- 新生同学，可以邀请其他没有在群里的新生同学加入我们的衔接课程群。因为大家通常都是第1学期选课 计算概论，很多同学第2学期选课 数据结构与算法。

- 科学上网。可能需要北大学长提供的Clash（最好用更现代的clash-verge），请自己取用。

  https://189854.xyz/verify/

  https://blog.189854.xyz/blog/walless/2023/11/04/clash.html

  > 最好用更现代的clash-verge

- 北京大学计算机基础科学与开发手册，https://github.com/ZangXuanyi/getting-started-handout
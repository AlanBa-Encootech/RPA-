# 工作包4
## 联合开发

联合开发应满足的基本功能：
* 设计器/编辑器支持主流程和子流程功能
* 设计器/编辑器支持导入流程到目前正在开发的流程中

联合开发可支持的高阶功能：
* 支持多人在线编辑
## 版本管理
版本管理应满足的基本功能：
* 可以查看不同版本的更新时间
* 可以在统一流程中的不同版本中进行切换

版本管理可支持的高阶功能：
* 支持流程版本回滚

## 调试模式
调试模式应满足的基本功能：
* 支持对流程打断点功能
* 支持断点处显示变量值
* 支持逐步调试
* 一个流程中支持多个断点进行调试
* 可以对单个组件单独调试

调试模式可支持的高阶功能：
* 可以在设计器/编辑器进行条件断点的设置
* 可以自动在流程报错处打断点




# 工作包6

## 日志记录

**日志用来记录机器人流程操作，运行状态等，是一个RPA产品体系中重要的组成部分**

日志记录应满足的基本功能：
* 支持可以在机器人端查看机器人执行时候的每个步骤的日志
* 支持在服务端查看每个机器人运行的日志
* * 支持记录机器人成功或者失败的日志
* 支持查看流程运行次数的日志
* 支持按照部门/角色运行机器人的日志

日志记录可支持的高阶功能：
* 支持查看机器人执行时流程时，对被操作对象的日志记录
* 支持流程在执行失败的节点日志
* 支持日志实时回传服务端
## 人机协作
**人机协作能力在RPA产品体系中是必不可少的一环**

人机协作应满足的基本功能：
* 支持手动触发机器人
* 支持远程调度机器人
* 支持移动端机器人
* 支持在流程运行期间可以让人工输入必要信息/确认后执行后续环节

人机协作可支持的高阶功能：
* 支持通过检测用户触发了不同的界面动作之后，自动执行相应流程

## 队列和并发
**对队列和并发的相关描述**

队列和并发应满足的基本功能：
* 支持将多个机器人归属到一个工作组中
* 支持将多个任务分发给一个机器人，进行队列运行
* 支持将多个任务分发给一个工作组中，工作组中的所有机器人对接收到的任务进行队列执行
* 支持最高100个机器人并发

队列和并发可支持的高阶功能:
* 支持最高500个机器人并发
## 动态适应
**对动态适应的相关描述**

动态适应应满足的基本功能：
* 支持机器人的流程可以在相同操作系统下，不同终端中进行自适配

动态适应可支持的高阶功能:
* 支持机器人的流程支持对不同的运行环境进行自适配
* 支持流程可以对不同分辨率的运行终端进行自适配
* 支持机器人在不同语言的终端进行自适配
## 异常处置
异常处置应满足的基本功能：
* 支持对已知报错步骤的容错能力
* 支持对未知报错的容错能力
* 支持对发生未知的报错情况不影响流程运行
* 支持在异常发生时，可以使用邮件的形式通知相关人员
* 支持在异常发生时，可以使用电话，短信，微信等终端通知相关人员

异常处置可支持的高阶功能:
* 支持在异常发生时，支持流程数据回滚，保证数据的完整性
* 在异常发生后，再次运行流程时候，支持对上次异常发生之后的流程的接连运行，保证流程完整性
* 支持在流程执行异常，可以自动调动其他机器人完成流程。





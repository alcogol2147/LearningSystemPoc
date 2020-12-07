# LearningSystemPoc
- [LearningSystemPoc](#learningsystempoc)
  - [实施计划](#实施计划)
  - [原型业务需求(删减可能)](#原型业务需求删减可能)
  - [相应技术分析](#相应技术分析)
  - [成本估算](#成本估算)
## 实施计划
- sprint 1

    周期：2020/12/4-2021/1/14

    范围：pending

    目标：需求，技术选型，架构==>PPT

## 原型业务需求(删减可能)
- 入力部分
    - ①登录
    - ②具有导航功能的主页面（分为两个部分）
      - 考试
        - 考试形式（客观选择题，代码实操）
        - 角色（受试者，考官，管理员）
      - 学习
        - 学习形式（文字阅读，弹幕视频，实际操作）
    - ③利用状况监视
      - 考试
        - 基于不同试题难易度以及受试者能力，对于试题进行统计学偏差值的判定。可能实现的目的：1.出题者方面定量评价，2.判定是否认真答题，3.运气成分
      - 学习
        - 视频观看的时长
        - 视频反复回倒 
- 通信
  - 页面展示部分:http
  - 源码编译部分:socket
  - 视频播放:流媒体协议RTMP(Real Time Messaging Protocol)
- 处理
  - 单点登录
  - 权限控制
  - 实时编译沙箱
  - 流媒体服务处理

## 相应技术分析
## 成本估算
# 汽车租借信息系统
采用C/S模式实现一个汽车租借信息系统。完成用户、车辆、经手员工、租借情况、车辆损毁情况、交通违规罚款等信息的管理。

功能：
 - 实现不同权限的浏览和更新
 - 能够根据车辆使用情况计算押金退还金额
 - 能查询客户的租借历史记录，并进行信誉度评价，进行会员制和非会员制的客户管理
 - 能够管理车辆报修信息
 - 能够生成租借公司的日、月、年财务报表，报表支持导出
 - 能够生成备份文件

 ## Dependence
 - 界面主体为Swing组件，由BeautyEye进行优化视图。
 - MySQL作为数据库后台。
 - JFreeChart绘制统计图。

 ## Note
 - 约束在Java层实现。

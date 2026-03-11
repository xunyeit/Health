## <font style="color:#000000;">产品定位</font>
**<font style="color:#000000;">一款专注于家庭健康指标管理的轻量化工具类小程序，支持家庭成员体重、血压、血糖、血脂、血尿酸等核心健康指标的录入、存储、智能判定与趋势分析，帮助用户实时掌握家人健康状况，为家庭健康管理提供数据支撑。</font>**

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">一、项目概述</font>
### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">1.1 核心需求</font>
1. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">便捷录入家庭成员多项健康指标，建立完整的家庭健康数据档案</font>
2. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">快速获取指标是否正常的判定结果，及时发现异常情况</font>
3. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">直观查看健康指标的长期变化趋势，辅助调整健康管理方案</font>
4. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">方便地管理和共享家庭健康数据，便于就医时向医生提供参考</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">1.2 产品价值</font>
<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">通过轻量化、低成本的方式，解决家庭健康指标记录分散、判定不专业、趋势难追踪的问题，让家庭健康管理更高效、更科学，降低慢性疾病恶化风险。</font>

---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">二、功能需求</font>
### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">2.1 多指标智能录入</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">手动输入：体重、血脂（总胆固醇 / 甘油三酯等）、血压（收缩压 / 舒张压）、血糖（空腹 / 餐后）、血尿酸</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">快速选择：支持保存常用数值组合，一键录入</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">批量录入：一次记录多人或多日数据</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">2.2 健康状态智能判断</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">根据医学标准自动标注异常值（偏高 / 偏低 / 正常）</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">分级提醒：区分轻度 / 中度 / 重度异常（如用颜色区分）</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">异常解读：提供简明的医学解释与建议</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">2.3 多角色家庭成员管理</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">添加 / 编辑家庭成员（可设置头像、昵称、关系）</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">为不同成员设置个性化健康指标范围（如年龄、病史差异）</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">2.4 数据可视化与分析</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">趋势图表：支持按日 / 周 / 月 / 年查看指标变化曲线</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">多指标对比图表</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">健康报告：</font>
    - <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">周期报告：生成周 / 月健康总结</font>
    - <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">异常统计：高发异常时段</font>

---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">三、系统架构与技术栈</font>
### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">3.1 整体架构</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">前后端分离架构，独立开发，符合主流开发模式</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">Maven 多模块管理，插件化开发，方便安装、卸载、升级，降低耦合</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">业务模块与 API 抽离，模块之间便捷引用</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">数据库设计精巧，字段规范、易于扩展</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">3.2 前端技术</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">基础：Vue3 + Vite</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">UI 框架：Ant Design Vue</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">网络：统一网络框架、API 接口拦截框架</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">运行环境：Node.js ≥16</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">3.3 后端技术</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">基础框架：SpringBoot3</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">数据层：MybatisPlus</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">缓存：Redis</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">权限认证：SaToken</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">数据库：支持 MySQL、Oracle、SQLServer、PGSQL 及达梦、人大金仓等国产数据库</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">中间件：支持中创、宝蓝德、东方通等</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">环境：JDK17、Maven、Lombok</font>

---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">四、系统特性</font>
### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">4.1 功能特性</font>
1. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">完善的系统基础功能，避免重复造轮子</font>
2. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">文件上传：支持本地、阿里云、腾讯云、MINIO</font>
3. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">消息发送：支持本地 / 阿里云 / 腾讯云邮件、短信</font>
4. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">账号体系：B、C 端双账号认证，会话治理独立</font>
5. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">日志审计：登录日志、操作日志、异常日志</font>
6. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">系统监控：会话监控、数据源监控、系统监控</font>
7. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">基础能力：组织机构、权限管理、定时任务、系统配置</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">4.2 安全特性</font>
1. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">支持登录认证、权限认证、单点登录、三方登录、OAuth2.0</font>
2. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">增强 RBAC 权限设计，按钮级别细粒度授权</font>
3. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">API 接口注解式、路由拦截式鉴权</font>
4. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">独创数据范围机制，接口可配置不同数据范围</font>
5. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">限流防抖、防重复提交</font>
6. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">国密算法加密传输与存储（密码、手机号、身份证等）</font>
7. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">操作日志 SM2 完整性保护，满足等保审计</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">4.3 界面特性</font>
1. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">视觉清新简洁，操作友好</font>
2. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">支持暗黑模式、经典菜单、双排菜单、多页签、目录坞、主题切换</font>
3. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">精细化交互设计，上手成本低</font>

---

## <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">五、部署与运维环境</font>
### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">5.1 操作系统</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">支持 Windows、Linux、国产操作系统</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">推荐：Centos 7.6</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">5.2 服务器配置</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">最低配置：2 核 2G 100GB 3M 带宽</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">推荐配置：2 核 4G 100GB 5M 带宽</font>

### <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">5.3 软件版本</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">Node.js：14.x</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">Java：1.8</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">MySQL：5.7</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">Redis：6.2.8</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">文件存储：阿里云 OSS（可替换其他存储）</font>

## <font style="color:#000000;background-color:rgba(0, 0, 0, 0);">联系交流</font>
公司官网：[https://www.xunyeit.com](https://www.xunyeit.com)

案例库：[https://cms.xunyeit.com/](https://cms.xunyeit.com/)

交流微信：


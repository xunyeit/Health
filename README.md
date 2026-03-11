## <font style="color:rgb(31, 35, 40);">产品定位</font>
**<font style="color:rgb(31, 35, 40);">第一款专注于家庭健康指标管理的轻量化工具类小程序，支持家庭成员体重、血糖、血压、血脂、血尿酸等核心健康指标的录入、存储、智能判定与趋势分析，帮助用户实时掌握健康状况，为家庭健康管理提供数据支撑。</font>****<font style="color:rgb(31, 35, 40);">  
</font>**<!-- 这是一张图片，ocr 内容为： -->
![](https://camo.githubusercontent.com/3c1c7e6e542bc82dc643a6bf46a821eacc2e4415f9d04140855482921d05c398/68747470733a2f2f63646e2e6e6c61726b2e636f6d2f79757175652f302f323032362f706e672f32313438373033382f313737333230313431393330382d66383664653330372d666233332d346337312d616263302d6435306264363730373734312e706e67)

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773209761230-bf2dd291-ccea-4ba0-8fde-eb6871b2ce59.png)

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773209804153-e53f0431-cfff-4539-9fa0-2515f7ec6609.png)

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773209819175-5084400e-bbc8-4fdd-bf84-ca0e2062261a.png)

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773209848267-1658c4fa-e4ea-485f-946e-76224f272bb6.png)

## <font style="color:rgb(31, 35, 40);">一、项目概述</font>
### <font style="color:rgb(31, 35, 40);">1.1 核心需求</font>
1. <font style="color:rgb(31, 35, 40);">方便录入家庭成员健康指标，建立完整的家庭健康数据档案</font>
2. <font style="color:rgb(31, 35, 40);">快速获取指标是否正常的判定结果，及时发现异常情况</font>
3. <font style="color:rgb(31, 35, 40);">洞察查看健康指标的长期变化趋势，辅助调整健康管理方案</font>
4. <font style="color:rgb(31, 35, 40);">方便地管理和共享家庭健康数据，其实就医时向医生提供参考</font>

### <font style="color:rgb(31, 35, 40);">1.2 产品价值</font>
<font style="color:rgb(31, 35, 40);">通过轻量化、聚焦的方式，解决家庭健康指标记录分散、判定不专业、趋势难以追踪的问题，让家庭健康管理更、更科学，降低慢性病患病风险。</font>

---

## <font style="color:rgb(31, 35, 40);">二、功能需求</font>
### <font style="color:rgb(31, 35, 40);">2.1 多指标智能录入</font>
+ <font style="color:rgb(31, 35, 40);">手动输入：体重、血脂（总胆固醇 / 甘油三酯等）、血糖（收缩压 / 舒张压）、血糖（空腹 / 餐后）、血尿酸</font>
+ <font style="color:rgb(31, 35, 40);">快速选择：支持保存常用数值组合，一键录入</font>
+ <font style="color:rgb(31, 35, 40);">批量录入：一次记录双胞胎的日常数据</font>

### <font style="color:rgb(31, 35, 40);">2.2 健康状态智能判断</font>
+ <font style="color:rgb(31, 35, 40);">根据医学标准自动标注异常值（偏高/偏低/正常）</font>
+ <font style="color:rgb(31, 35, 40);">分级提醒：区分 / 中度 / 重度异常（如用颜色区分）</font>
+ <font style="color:rgb(31, 35, 40);">异常阅读：提供简明的医学解释与建议</font>

### <font style="color:rgb(31, 35, 40);">2.3 多角色家庭成员管理</font>
+ <font style="color:rgb(31, 35, 40);">添加 / 编辑家庭成员（可设置头像、昵称、关系）</font>
+ <font style="color:rgb(31, 35, 40);">为不同成员设置个性化健康指标范围（如年龄、疾病史差异）</font>

### <font style="color:rgb(31, 35, 40);">2.4 数据可视化与分析</font>
+ <font style="color:rgb(31, 35, 40);">趋势图表：支持按日/周/月/年查看指标变化曲线</font>
+ <font style="color:rgb(31, 35, 40);">多指标图表</font>
+ <font style="color:rgb(31, 35, 40);">健康报告：</font>
    - <font style="color:rgb(31, 35, 40);">生命周期报告：生成周/月健康总结</font>
    - <font style="color:rgb(31, 35, 40);">异常统计：高发异常</font>

---

## <font style="color:rgb(31, 35, 40);">三、系统架构与技术栈</font>
### <font style="color:rgb(31, 35, 40);">3.1 整体架构</font>
+ <font style="color:rgb(31, 35, 40);">前架构师分离架构，独立开发，符合主流开发模式</font>
+ <font style="color:rgb(31, 35, 40);">Maven多模块管理，插件化开发，方便安装、卸载、升级，取消连接</font>
+ <font style="color:rgb(31, 35, 40);">业务模块与API抽离，模块之间便捷引用</font>
+ <font style="color:rgb(31, 35, 40);">数据库设计精巧，字段规范、易于扩展</font>

### <font style="color:rgb(31, 35, 40);">3.2前端技术</font>
+ <font style="color:rgb(31, 35, 40);">基础：Vue3 + Vite</font>
+ <font style="color:rgb(31, 35, 40);">UI框架：Ant Design Vue</font>
+ <font style="color:rgb(31, 35, 40);">网络：统一网络框架、API接口拦截框架</font>
+ <font style="color:rgb(31, 35, 40);">运行环境：Node.js ≥16</font>

### <font style="color:rgb(31, 35, 40);">3.3 通话技术</font>
+ <font style="color:rgb(31, 35, 40);">基础框架：SpringBoot3</font>
+ <font style="color:rgb(31, 35, 40);">数据层：MybatisPlus</font>
+ <font style="color:rgb(31, 35, 40);">服务器：Redis</font>
+ <font style="color:rgb(31, 35, 40);">权限认证：SaToken</font>
+ <font style="color:rgb(31, 35, 40);">数据库：支持MySQL、Oracle、SQLServer、PGSQL及达梦、人大金仓等国产数据库</font>
+ <font style="color:rgb(31, 35, 40);">中间件：支持中创、宝蓝德、东方通等</font>
+ <font style="color:rgb(31, 35, 40);">环境：JDK17、Maven、Lombok</font>

---

## <font style="color:rgb(31, 35, 40);">四、系统特性</font>
### <font style="color:rgb(31, 35, 40);">4.1 功能特性</font>
1. <font style="color:rgb(31, 35, 40);">完善的系统基础功能，避免重复造轮子</font>
2. <font style="color:rgb(31, 35, 40);">文件上传：支持本地、阿里云、腾讯云、MINIO</font>
3. <font style="color:rgb(31, 35, 40);">消息发送：支持本地/阿里云/腾讯云邮件、短信</font>
4. <font style="color:rgb(31, 35, 40);">账号体系：B、C端双账号认证，会话治理独立</font>
5. <font style="color:rgb(31, 35, 40);">审计登录日志、操作日志、异常日志</font>
6. <font style="color:rgb(31, 35, 40);">系统监控：会话监控、数据源监控、系统监控</font>
7. <font style="color:rgb(31, 35, 40);">基础能力：组织机构、权限管理、定时任务、系统配置</font>

### <font style="color:rgb(31, 35, 40);">4.2 安全特性</font>
1. <font style="color:rgb(31, 35, 40);">支持登录认证、权限认证、单点登录、三方登录、OAuth2.0</font>
2. <font style="color:rgb(31, 35, 40);">增强RBAC权限设计，按钮级别细粒度授权</font>
3. <font style="color:rgb(31, 35, 40);">API接口注解方式、路由拦截方式鉴权</font>
4. <font style="color:rgb(31, 35, 40);">独创数据范围机制，接口可配置不同数据范围</font>
5. <font style="color:rgb(31, 35, 40);">限流防、防抖重复工作</font>
6. <font style="color:rgb(31, 35, 40);">国密算法加密传输与存储（密码、手机号、身份证等）</font>
7. <font style="color:rgb(31, 35, 40);">操作日志 SM2 遗产保护，满足审计等保障</font>

### <font style="color:rgb(31, 35, 40);">4.3 界面特性</font>
1. <font style="color:rgb(31, 35, 40);">美观简洁，操作友好</font>
2. <font style="color:rgb(31, 35, 40);">支持暗黑模式、经典菜单、双排菜单、多页签、目录坞、主题切换</font>
3. <font style="color:rgb(31, 35, 40);">精细化交互设计，前期成本低</font>

---

## <font style="color:rgb(31, 35, 40);">五、部署与运维环境</font>
### <font style="color:rgb(31, 35, 40);">5.1 操作系统</font>
+ <font style="color:rgb(31, 35, 40);">支持Windows、Linux、国产操作系统</font>
+ <font style="color:rgb(31, 35, 40);">推荐：Centos 7.6</font>

### <font style="color:rgb(31, 35, 40);">5.2 服务器配置</font>
+ <font style="color:rgb(31, 35, 40);">最低配置：2核2G 100GB 3M带宽</font>
+ <font style="color:rgb(31, 35, 40);">推荐配置：2核4G 100GB 5M带宽</font>

### <font style="color:rgb(31, 35, 40);">5.3 软件版本</font>
+ <font style="color:rgb(31, 35, 40);">Node.js：14.x</font>
+ <font style="color:rgb(31, 35, 40);">Java：1.8</font>
+ <font style="color:rgb(31, 35, 40);">MySQL：5.7</font>
+ <font style="color:rgb(31, 35, 40);">Redis：6.2.8</font>
+ <font style="color:rgb(31, 35, 40);">文件存储：阿里云 OSS（可替换其他存储）</font>

<font style="color:rgb(31, 35, 40);"></font>

<font style="color:rgb(31, 35, 40);">联系交流</font>

<font style="color:rgb(31, 35, 40);">公司官网：</font>[https://www.xunyeit.com](https://www.xunyeit.com)

<font style="color:rgb(31, 35, 40);">案例库：</font>[https://cms.xunyeit.com/](https://cms.xunyeit.com/)

<font style="color:rgb(31, 35, 40);">交流微信：</font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/35238927/1773209901730-a30b487b-e14a-49f8-8d0b-759596e63446.png)


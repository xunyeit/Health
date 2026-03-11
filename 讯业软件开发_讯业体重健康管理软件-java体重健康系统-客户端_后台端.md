<h2 id="0304bced"><font style="color:#000000;">产品定位</font></h2>
**<font style="color:#000000;">一款专注于家庭健康指标管理的轻量化工具类小程序，支持家庭成员体重、血压、血糖、血脂、血尿酸等核心健康指标的录入、存储、智能判定与趋势分析，帮助用户实时掌握家人健康状况，为家庭健康管理提供数据支撑。</font>**

<h2 id="1a0889fb"><font style="color:#000000;">目标用户</font></h2>
+ **<font style="color:#000000;">核心用户：关注家人健康的家庭主妇/主夫、中老年人（需子女协助操作）、有慢性疾病（高血压、糖尿病等）患者的家庭</font>**
+ **<font style="color:#000000;">次要用户：医护人员（用于辅助跟踪患者家庭健康数据）、健康管理爱好者</font>**

<h2 id="a54a06a9"><font style="color:#000000;">核心需求</font></h2>
**<font style="color:#000000;">便捷录入家庭成员多项健康指标，建立完整的家庭健康数据档案</font>**

**<font style="color:#000000;">快速获取指标是否正常的判定结果，及时发现异常情况</font>**

**<font style="color:#000000;">直观查看健康指标的长期变化趋势，辅助调整健康管理方案</font>**

**<font style="color:#000000;">方便地管理和共享家庭健康数据，便于就医时向医生提供参考</font>**

<h2 id="de3800ce"><font style="color:#000000;">产品价值</font></h2>
**<font style="color:#000000;">通过轻量化、低成本的方式，解决家庭健康指标记录分散、判定不专业、趋势难追踪的问题，让家庭健康管理更高效、更科学，降低慢性疾病恶化风险。</font>**

<h2 id="dd31beba"><font style="color:#000000;">功能需求</font></h2>
**<font style="color:#000000;">多指标智能录入</font>**

**<font style="color:#000000;">手动输入：体重、血脂（总胆固醇/甘油三酯等）、血压（收缩压/舒张压）、血糖（空腹/餐后）、血尿酸</font>**

**<font style="color:#000000;">快速选择：支持保存常用数值组合，一键录入</font>**

**<font style="color:#000000;">批量录入：一次记录多人或多日数据</font>**

**<font style="color:#000000;">健康状态智能判断</font>**

**<font style="color:#000000;">根据医学标准自动标注异常值（偏高/偏低/正常）</font>**

**<font style="color:#000000;">分级提醒：区分轻度/中度/重度异常（如用颜色区分）</font>**

**<font style="color:#000000;">异常解读：提供简明的医学解释与建议</font>**

**<font style="color:#000000;">多角色家庭成员管理</font>**

**<font style="color:#000000;">添加/编辑家庭成员（可设置头像、昵称、关系）</font>**

**<font style="color:#000000;">为不同成员设置个性化健康指标范围（如年龄、病史差异）</font>**

**<font style="color:#000000;">数据可视化与分析</font>**

**<font style="color:#000000;">趋势图表</font>**

**<font style="color:#000000;">支持按日/周/月/年查看指标变化曲线</font>**

**<font style="color:#000000;">多指标对比图表</font>**

**<font style="color:#000000;">健康报告</font>**

**<font style="color:#000000;">周期报告：生成周/月健康总结</font>**

**<font style="color:#000000;">异常统计：高发异常时段</font>**

<font style="color:#000000;"></font>

<h2 id="75f3c580"><font style="color:#000000;">运维环境</font></h2>
<h2 id="8888e42a"><font style="color:#000000;">前端环境</font></h2>
| **<font style="color:#000000;">插件</font>** | **<font style="color:#000000;">版本</font>** | **<font style="color:#000000;">用途</font>** |
| --- | --- | --- |
| **<font style="color:#000000;">node.js</font>** | **<font style="color:#000000;">≥16</font>** | **<font style="color:#000000;">JavaScript运行环境</font>** |


<h2 id="d08fce1b"><font style="color:#000000;">后端环境</font></h2>
| **<font style="color:#000000;">插件</font>** | **<font style="color:#000000;">版本</font>** | **<font style="color:#000000;">用途</font>** |
| --- | --- | --- |
| **<font style="color:#000000;">jdk</font>** | **<font style="color:#000000;">17</font>** | **<font style="color:#000000;">Java环境</font>** |
| **<font style="color:#000000;">lombok</font>** | **<font style="color:#000000;">idea默认</font>** | **<font style="color:#000000;">代码简化插件</font>** |
| **<font style="color:#000000;">maven</font>** | **<font style="color:#000000;">最新版</font>** | **<font style="color:#000000;">包管理工具</font>** |
| **<font style="color:#000000;">redis</font>** | **<font style="color:#000000;">最新版</font>** | **<font style="color:#000000;">缓存库</font>** |
| **<font style="color:#000000;">mysql</font>** | **<font style="color:#000000;">8.0 / 5.7</font>** | **<font style="color:#000000;">数据库</font>** |


<h2 id="77af2939"><font style="color:#000000;">架构特点</font></h2>
<h3 id="ec0ef4cd"><font style="color:rgb(89, 93, 105);">架构特性</font></h3>
+ **<font style="color:#000000;">前后端分离架构，独立开发，符合主流开发模式</font>**
+ **<font style="color:#000000;">前端以Vue3+Vite为主技术，AntdV为UI界面框架</font>**
+ **<font style="color:#000000;">后端SpringBoot3为基础，MybatisPlus为数据操作框架，Redis为缓存框架</font>**
+ **<font style="color:#000000;">Maven多模块管理，插件化开发，方便安装、卸载、升级，降低耦合</font>**
+ **<font style="color:#000000;">业务模块与API抽离，模块之间便捷引用</font>**
+ **<font style="color:#000000;">数据库设计精巧，字段规范、易于扩展</font>**
+ **<font style="color:#000000;">支持国产密码算法加解密，等保测评国产项目无压力</font>**
+ **<font style="color:#000000;">支持MYSQL、ORACLE、SQLSERVER、PGSQL等主流标准结构式数据库</font>**
+ **<font style="color:#000000;">支持达梦、人大金仓、南大通用、九有、瀚高、虚谷数据库等国产数据库</font>**
+ **<font style="color:#000000;">支持中创、宝蓝德、东方通等中间件</font>**
+ **<font style="color:#000000;">支持Windows、Linux操作系统、国产操作系统部署</font>**

<h3 id="48ab146a"><font style="color:#000000;">功能特性</font></h3>
+ **<font style="color:#000000;">完善的系统基础功能，满足使用需求，避免重复造轮子</font>**
+ **<font style="color:#000000;">支持本地文件、阿里云文件、腾讯云文件、MINIO文件上传</font>**
+ **<font style="color:#000000;">支持本地邮件、阿里云邮件、腾讯云邮件发送</font>**
+ **<font style="color:#000000;">支持阿里云短信、腾讯云短信发送</font>**
+ **<font style="color:#000000;">B、C端双账号认证体系，会话治理各自独立</font>**
+ **<font style="color:#000000;">完善的登录日志、操作日志、异常日志等审计功能</font>**
+ **<font style="color:#000000;">完善的会话监控、数据源监控、系统监控等必备监控功能</font>**
+ **<font style="color:#000000;">支持组织机构、权限管理、定时任务、系统配置等基础功能</font>**

<h3 id="91730e32"><font style="color:#000000;">安全特性</font></h3>
+ **<font style="color:#000000;">采用SaToken轻量级 Java 权限认证框架，功能强大、学习成本低</font>**
+ **<font style="color:#000000;">支持登录认证、权限认证、单点登录、三方登录、OAuth2.0等认证模式</font>**
+ **<font style="color:#000000;">增强的RBAC权限设计，资源于接口独立授权，更加灵活</font>**
+ **<font style="color:#000000;">支持按钮级别细粒度独立授权，界面按钮动态展示</font>**
+ **<font style="color:#000000;">支持API接口注解式、路由拦截式鉴权，防止越界访问</font>**
+ **<font style="color:#000000;">独创的数据范围机制，每个接口都可以配置不同数据范围</font>**
+ **<font style="color:#000000;">支持限流防抖，防重复提交，有效阻止脏数据产生</font>**
+ **<font style="color:#000000;">密码、手机、身份证号等使用国密算法加密传输、加密存储，数据更安全</font>**
+ **<font style="color:#000000;">操作日志使用SM2进行完整性保护，满足安全审计要求</font>**

<h3 id="1f7607bd"><font style="color:#000000;">界面特性</font></h3>
+ **<font style="color:#000000;">Vue3 + Vite为基础，AntdV为界面UI框架，视觉风格清新简洁</font>**
+ **<font style="color:#000000;">精细化设计，注重界面的每一处细节，操作轻松友好</font>**
+ **<font style="color:#000000;">暗黑风格、经典菜单、双排菜单、多页签、目录坞、主题切换等功能应有尽有</font>**
+ **<font style="color:#000000;">统一的网络框架、API接口拦截框架，拿来即可上手</font>**

<font style="color:#000000;"></font>

<h2 id="75f3c580-1"><font style="color:#000000;">运维环境</font></h2>
+ **<font style="color:#000000;">全系列系统服务器。推荐使用 Centos 7.6</font>**
+ **<font style="color:#000000;">2 核 2 G 100MB 3M带宽 为最低配置，建议 2 核 4G 100Mb 5M带宽。</font>**
+ **<font style="color:#000000;">Node.js 14x</font>**
+ **<font style="color:#000000;">Java1.8</font>**
+ **<font style="color:#000000;">Mysql 5.7</font>**
+ **<font style="color:#000000;">Redis 6.2.8</font>**
+ **<font style="color:#000000;">阿里云 OSS – 可更换其它。  
  
</font>**

<h2 id="25f9c7fa"><font style="color:#000000;background-color:rgba(0, 0, 0, 0);">联系交流</font></h2>
**<font style="color:#000000;">公司官网：</font>**[**<font style="color:#000000;">https://www.xunyeit.com</font>**](https://www.xunyeit.com)

**<font style="color:#000000;">案例库：</font>**[**<font style="color:#000000;">https://cms.xunyeit.com/</font>**](https://cms.xunyeit.com/)

**<font style="color:#000000;">交流微信：</font>**


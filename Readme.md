## Ego项目自评

从5月13号正式开始写Ego项目算起，截至今日是12天。在这12天的学习中，我从老师们的教学视频中学习到很多知识与技巧，但更多的是发现自己的不足。
我从以下几个方面做一个小结：
1. 项目功能实现表
2. 持续改进
3. 自我评价 


### 1. 项目功能实现表
#### 首页
- 顶部tab
    - 有选中效果[√]
    - hover动画效果[√]
- 顶部搜索可用
	- 搜索非空进行搜索操作[√]
	- 回车和点击图标都可进行搜索操作[√]
- 登录后顶部展示用户信息
    - 用户名很长…显示[√]
    - hover出现下拉列表[√]
    - 点击”退出登录”退出，跳转到首页[√]
- 轮播图
    - 图片垂直剧中[√]
    - 图片5s切换（500ms淡入淡出）[√]
    - 点击指示器定位到指定图片[√]
    - hover上去轮播停止，hover退出轮播继续[√]
- 明日之星
    - 列表展示正确[√]
    - 未登录时，点击关注，弹出登录弹窗[√]
    - 已登录时，关注和取消关注功能可用[√]
- 其他效果显示正确
    - 侧边热门话题2行显示，文字太多直接截断[√]

#### 登录
- 数据验证
    - 手机号非空，11位数字[√]
    - 密码非空[√]
    - 验证失败，相应输入框变红[√]
- 登录
    - 登录功能可用[√]
    - 登录成功后，如果在首页，首页的明日之星列表需要刷新数据[√]
    - 登录不成功，显示错误[√]
- 点击立即注册，关闭登录弹窗，弹出注册弹窗[x]
- 点击关闭图标，弹窗关闭[√]

#### 注册
- 级联选择器可用
    - 地区数据正确[x]
    - 生日数据，大小月30/31日，闰年2月29日数据正确[x]
- 验证码
    - 验证码显示正确[x]
    - 点击验证码更新[x]
- 表单验证
    - 手机号非空，11位数字[x]
    - 昵称中文英文数字均可，至少8个字符[x]
    - 密码长度6-16位字符[x]
    - 验证失败，相应输入框变红[x]
- 注册
    - 注册功能可用[x]
    - 注册成功关闭注册弹窗，打开登录弹窗[x]
    - 注册不成功，显示错误[x]

#### 我的作品
- 年龄、星座、城市名计算正确。[√]
- 作品列表加载正常，加载列表期间要显示loading图标，没有作品时有文案提示。[√]
- 分页功能正常可用。分页的具体逻辑请参见《我的作品-分页》课程的讲解。


#### 上传作品
- 表单元素行为正常：
    - 作品分类按钮组状态互斥[x]
    - 权限设置按钮组状态互斥[x]
    - 作品授权的模拟下拉菜单[x]
- 图片上传功能可用：
    - 图片可以批量上传[x]
    - 上传过程中要有表示整体进度的进度条[x]
    - 上传完后可以即时预览[x]
    - 单张图片的大小小于1MB[x]
    - 每次最多选择10张图片，超过10张要有弹窗提示[x]
    - 设置封面功能正常[x]
    - 开始上传后，上传按钮变为不可点击，视觉上表显为灰色[x]
- 标签组件功能可用：
    - 加载系统推荐标签[x]
    - 标签可删除[x]
    - 标签可添加[x]
- 表单可正常提交
    - 不丢失任何数据信息[x]
    - 提交前需要检查作品名称是否为空[x]


#### 从页面的层面来看
- 首页：视觉和功能完成度较高，注册框的部分功能还没实现（级联选择器）。
- 作品列表页：视觉和功能完成度高。
- 作品创建页面：没有完成····

### 持续改进
1. 将没有做完的静态页面和功能做完；
2. 将项目中涉及到的组件（级联选择器、分页器等）剥离出来，并结合测试课程与持续改进课程中的知识，封装成可复用的组件；
3. 结合NEC代码规范改善CSS的代码质量。

### 小评
之前只写过功能比较单一的页面，当第一次尝试写有大量交互和功能的页面时，完全错误的预估代码量、完成时间、BUG及修复BUG的耗时，这也就导致上传页面没有按时完成。
在不能使用框架情况下，自己对DOM操作、表单、ajax相关知识还是很生疏，后期需要多看看《JS高级程序设计》，夯实基础。
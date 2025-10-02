# GitHub 协作常见问题

## 关于协作者(Collaborator)和关注(Follow)

### 问：如果我邀请某人作为协作者，会显示他关注了我的仓库吗？

**答：不会。** 邀请某人作为协作者和他们关注你的仓库是两个完全独立的操作：

#### 协作者 (Collaborator)
- **权限访问**：协作者被授予仓库的直接访问权限（读、写或管理员权限）
- **目的**：允许团队成员直接向仓库推送代码、审查 PR、管理 Issues 等
- **显示位置**：在仓库的 Settings → Collaborators 页面中显示
- **通知**：被邀请的人会收到协作邀请通知
- **操作方式**：仓库所有者或管理员在 Settings 中手动邀请

#### 关注仓库 (Watch/Follow)
- **信息订阅**：用户选择接收仓库的更新通知
- **目的**：关注感兴趣的项目，了解最新动态
- **显示位置**：
  - 在仓库页面的 Watch/Unwatch 按钮
  - 在用户的个人资料中的 "Repositories" 标签下可以看到他们关注(watching)的仓库
- **通知**：根据用户的 Watch 设置接收不同级别的通知
- **操作方式**：用户自行点击仓库的 "Watch" 按钮

#### Star (给星标)
- **表达认可**：用户给仓库点赞，表示喜欢或收藏
- **显示位置**：
  - 在仓库页面的 Star/Unstar 按钮
  - 在用户的个人资料中的 "Stars" 标签下可以看到他们标星的所有仓库
- **作用**：帮助发现优秀项目，也是项目受欢迎程度的指标
- **操作方式**：用户自行点击仓库的 "Star" 按钮

### 关键要点

1. **独立操作**：成为协作者不会自动让用户关注或给仓库加星
2. **手动选择**：用户需要自己决定是否要 Watch 或 Star 一个仓库
3. **不同目的**：
   - 协作者 = 工作权限
   - Watch = 接收更新通知
   - Star = 收藏和点赞

### 最佳实践建议

如果你邀请了协作者，建议：
1. 邀请后提醒他们可以选择 Watch 仓库以接收更新通知
2. 如果你希望协作者给项目加星，可以礼貌地建议（但不要强制要求）
3. 在团队协作时，建议所有成员至少设置为 "Watch" 模式，以便及时收到重要更新

## 其他常见问题

### 问：如何邀请协作者？

1. 进入你的仓库页面
2. 点击 "Settings" 标签
3. 在左侧菜单中选择 "Collaborators and teams"
4. 点击 "Add people" 按钮
5. 输入用户名或邮箱
6. 选择权限级别（Read, Write, Admin）
7. 发送邀请

### 问：协作者权限有哪些级别？

- **Read**：可以查看和克隆仓库，提交 Issue 和 PR
- **Write**：除 Read 权限外，还可以直接推送代码
- **Admin**：拥有完全控制权，包括删除仓库、管理设置等

### 问：如何查看谁 Watch 或 Star 了我的仓库？

- **查看 Stars**：在仓库页面点击 "Star" 旁边的数字
- **查看 Watchers**：在仓库页面点击 "Watch" 旁边的数字
- **限制**：只能看到公开关注的用户列表

### 问：我应该 Watch 还是 Star 一个项目？

- **Watch**：如果你想持续关注项目进展，接收更新通知
- **Star**：如果你觉得项目有价值，想收藏以后查看，或想支持项目作者

## 相关资源

- [GitHub 官方文档 - 协作者](https://docs.github.com/cn/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository)
- [GitHub 官方文档 - Watch 仓库](https://docs.github.com/cn/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/configuring-notifications)
- [GitHub 官方文档 - Star 仓库](https://docs.github.com/cn/get-started/exploring-projects-on-github/saving-repositories-with-stars)

---

**注意**：本文档旨在帮助贡献者理解 GitHub 的基本协作功能。更多详细信息请参考 GitHub 官方文档。

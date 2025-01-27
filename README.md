# Chinese Name Generator

一个智能化的英文转中文姓名推荐系统，为外国友人提供富有文化内涵和个性化的中文名字选择。

## 功能特点

1. 智能名字生成
   - 支持英文名到中文名的智能转换
   - 基于音译规则和文化内涵生成名字
   - 每次提供3个独特的名字方案
   - 确保音韵和谐、寓意优美

2. 文化解读
   - 提供每个字的详细释义
   - 解释名字的整体寓意
   - 包含相关的文化背景
   - 说明名字暗含的性格特质

3. 用户体验
   - 简洁直观的界面设计
   - 响应式布局，支持各种设备
   - 实时生成和展示结果
   - 支持一键清除重置

## 使用说明

1. 输入英文名
   - 支持名/姓+名格式
   - 不区分大小写
   - 自动处理特殊字符

2. 生成名字
   - 点击"Generate Names"按钮
   - 或按回车键生成
   - 系统会生成3个推荐方案

3. 查看结果
   - 每个推荐方案包含：
     * 中文名字
     * 拼音注音
     * 字义解释
     * 文化内涵
     * 性格特征

4. 重置
   - 点击"Clear"按钮清除
   - 重新开始新的生成

## 技术实现

1. 本地数据库
   - 丰富的字库资源
   - 完善的音译规则
   - 详细的文化解读
   - 智能的组合规则

2. 算法特点
   - 智能音节分析
   - 音韵和谐评估
   - 文化适配检查
   - 禁忌组合过滤

3. 预留扩展
   - AI 接口集成准备
   - 文化解读增强
   - 个性化推荐
   - 多语言支持

## 开发计划

1. 第一阶段（当前）
   - [x] 基础功能实现
   - [x] 本地数据库建设
   - [x] 核心算法优化
   - [x] 界面交互完善

2. 第二阶段
   - [ ] AI 接口集成
   - [ ] 文化解读深化
   - [ ] 用户反馈系统
   - [ ] 性能优化

## 本地运行

1. 环境要求
   - 现代浏览器
   - Python 3.x（用于本地服务器）

2. 启动步骤
   ```bash
   # 进入项目目录
   cd path/to/chinese-name-generator

   # 启动本地服务器
   python3 -m http.server 8000

   # 访问地址
   http://localhost:8000
   ```

## 注意事项

1. 名字生成
   - 确保输入英文名规范
   - 建议使用常见英文名
   - 支持2-3个字的中文名

2. 文化解读
   - 解读基于传统文化
   - 含义仅供参考
   - 可根据个人喜好选择

## 贡献指南

欢迎贡献代码或提供建议：
1. Fork 项目
2. 创建特性分支
3. 提交变更
4. 发起 Pull Request

## 许可证

MIT License 
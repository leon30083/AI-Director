# 更新日志

## [0.1.0] - 2024-03-20

### 添加
- 初始化项目结构
- 创建基础配置文件
  - `.cursorrules` - 基础工作规则
  - `video-creation-rules.md` - AI视频创作规则
  - `个性化流程信息.md` - 用户工作流程说明

### 新增功能
- 建立提示词管理系统
  - 创建 `/prompts` 目录结构
  - 设置FLUX提示词模板
  - 设置混元视频提示词模板
  - 建立提示词分类系统

### 文档
- 完善项目说明文档
- 创建提示词模板文档
  - `/prompts/flux/character.md` - 人物提示词模板
  - `/prompts/flux/scene.md` - 场景提示词模板
  - `/prompts/flux/style.md` - 风格提示词模板
  - `/prompts/hunyuan/transition.md` - 转场提示词模板
  - `/prompts/hunyuan/movement.md` - 运动提示词模板
  - `/prompts/hunyuan/effect.md` - 特效提示词模板

### 工作流程
- 确定AI视频创作的四个主要步骤：
  1. 需求分析与故事构思
  2. AI关键帧制作
  3. AI视频生成
  4. 剪映后期处理

### 工具集成
- ComfyUI工作流程规范
- 剪映使用规范
- FLUX模型应用规范
- 混元视频模型应用规范

## 待办事项
- [ ] 收集和整理FLUX优秀提示词
- [ ] 收集和整理混元视频优秀提示词
- [ ] 建立提示词效果案例库
- [ ] 完善工具使用教程
- [ ] 优化工作流程文档

## 计划中的功能
1. 提示词自动优化系统
2. 效果参考案例库
3. 常见问题解决方案库
4. 视频风格模板库

## [0.1.1] - 2024-03-20

### 添加
- 完善提示词模板系统
  - 创建 FLUX 提示词模板
    - `/prompts/flux/character.md` - 人物提示词模板
    - `/prompts/flux/scene.md` - 场景提示词模板
    - `/prompts/flux/style.md` - 风格提示词模板
  - 创建混元视频提示词模板
    - `/prompts/hunyuan/transition.md` - 转场提示词模板
    - `/prompts/hunyuan/movement.md` - 运动提示词模板
    - `/prompts/hunyuan/effect.md` - 特效提示词模板

### 优化
- 完善提示词模板的文档结构
- 添加详细的参数说明
- 增加实用的示例
- 补充注意事项说明

## [0.1.2] - 2024-03-20

### 优化
- 完善提示词模板的中文支持
  - 添加中英文对照说明
  - 增加参数中文解释
  - 补充中文示例
  - 添加详细的参数对照表

### 重构
- 调整目录结构
  - `/prompts` → `/提示词模板`
  - `/flux` → `/FLUX模型`
  - `/hunyuan` → `/混元模型`
- 重命名模板文件
  - `character.md` → `人物提示词.md`
  - `scene.md` → `场景提示词.md`
  - `style.md` → `风格提示词.md`
  - `transition.md` → `转场提示词.md`
  - `movement.md` → `运镜提示词.md`
  - `effect.md` → `特效提示词.md`

## [0.1.3] - 2024-03-20

### 删除
- 移除英文版提示词模板文件
  - 删除 `/prompts/flux/` 目录下的英文文件
  - 删除 `/prompts/hunyuan/` 目录下的英文文件
- 清理冗余目录结构

### 优化
- 统一使用中文版提示词模板
- 保留英文参考示例和对照表

---
本项目由 AI进化论-花生 创建维护 
[Uploading README.md…]()
# Vue3 图片画廊应用

这是一个基于Vue3的图片画廊应用，包含图片分类、预览、编辑和上传功能。

## 功能特性

- 📷 图片分类浏览
- 🔍 大图预览功能
- ✏️ 图片信息编辑（标题、描述、分类、标签）
- 🎨 基础滤镜效果（灰度、复古、模糊、亮度、对比度）
- 📤 本地图片上传
- 🖼️ 响应式设计，支持网格和列表视图
- ⚡ 图片懒加载优化

## 技术栈

- Vue 3 - 前端框架
- Pinia - 状态管理
- Vue Router - 路由管理
- 纯CSS - 样式设计
- Font Awesome - 图标库



## 项目结构
image-gallery1/
├── public/ # 静态资源
├── src/
│ ├── assets/ # 图片、样式资源
│ ├── components/ # 可复用组件
│ │ ├── ImagePreviewModal.vue # 图片预览模态框
│ │ ├── ImageEditModal.vue # 图片编辑模态框
│ │ └── ImageUploadModal.vue # 图片上传模态框
│ ├── stores/ # Pinia状态管理
│ │ └── imageStore.js # 图片数据状态
│ ├── views/ # 页面组件
│ │ └── Home.vue # 首页
│ ├── App.vue # 根组件
│ └── main.js # 入口文件
├── README.md # 项目说明
└── package.json # 项目配置


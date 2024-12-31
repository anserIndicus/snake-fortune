# 蛇年运势抽卡 - 设计规范

## 色彩系统

### 主色调
- 中国红: #e60012
- 金色: #ffd700
- 银色: #c0c0c0

### 辅助色
- 背景色: #f8f8f8
- 文字色: #333333
- 暗色: #666666

## 卡片设计规范

### 明牌（灵蛇卡）
- 尺寸: 300x450px
- 边框: 2px solid #e60012
- 圆角: 15px
- 主图区域: 居中，占据卡片60%面积
- 标题: 20px, 中国红
- 描述: 14px, 暗色

#### 设计元素
1. 青蛇卡
   - 主色: 青色调 (#00a0e9)
   - 图案: 灵动的青蛇，缠绕竹枝
   
2. 白蛇卡
   - 主色: 白色调 (#ffffff)
   - 图案: 优雅的白蛇，莲花环绕
   
3. 银龙卡
   - 主色: 银色调 (#c0c0c0)
   - 图案: 威严的银龙，云雾缭绕
   
4. 金蟾卡
   - 主色: 金色调 (#ffd700)
   - 图案: 三足金蟾，铜钱衬托
   
5. 如意卡
   - 主色: 红色调 (#e60012)
   - 图案: 如意纹样，祥云环绕
   
6. 同心结卡
   - 主色: 粉色调 (#ffb6c1)
   - 图案: 中国结，双心交织

### 暗牌设计

#### 人造物系列
- 统一使用金属质感
- 细节突出工艺感
- 背景使用低饱和度色调

#### 自然物系列
- 强调自然光影
- 柔和的色彩过渡
- 有机的形态设计

#### 行动系列
- 动态感设计
- 简洁的图形语言
- 象征性的视觉表达

## 布局规范

### 卡片正面布局
```
+------------------+
|     标题区      |
+------------------+
|                  |
|     主图区      |
|                  |
+------------------+
|    描述文字     |
+------------------+
```

### 卡片背面布局
```
+------------------+
|  ●          ●   |
|                  |
|    装饰图案     |
|                  |
|  ●          ●   |
+------------------+
```

## 动画效果

### 卡片翻转
- 持续时间: 0.6s
- 缓动函数: ease-in-out
- 3D效果: perspective(1000px)

### 选中效果
- 上浮距离: 5px
- 阴影加深
- 边框高亮
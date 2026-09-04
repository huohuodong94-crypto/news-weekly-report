# 监控关键词配置

> 初始化状态：**已配置**（2026-09-01）

```yaml
# ══════════════════════════════════════════════════════════
# 监控关键词列表
# ══════════════════════════════════════════════════════════

keywords:
  - name: "空气能热泵 行业动态"
    search_terms: "空气能 热泵 空气源热泵 热泵采暖 热泵热水"
    max_items: 8
  - name: "竞品动态"
    search_terms: "纽恩泰 芬尼 中广欧特斯 四季沐歌 华天成 生能 哈唯"
    max_items: 8
  - name: "政策与招标"
    search_terms: "煤改电 清洁取暖 清洁供暖 招标 采暖季 能效"
    max_items: 8
  - name: "出海与欧洲市场"
    search_terms: "热泵出口 欧洲 EHPA 海外市场"
    max_items: 5

# ══════════════════════════════════════════════════════════
# 报告偏好
# ══════════════════════════════════════════════════════════

preferences:
  language: "zh-CN"
  recency_hours: 24
  recency_hours_soft: 48
  hot_topics_max: 5
  link_check_sample: 5
  empty_keyword_alert_ratio: 0.5
```

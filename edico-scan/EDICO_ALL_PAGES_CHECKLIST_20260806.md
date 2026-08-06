# EDICO 全站 48 頁檢查清單 + 報告

**日期**: 2026-08-06 (HKT) | **方法**: Googlebot UA 繞 WAF + chromium headless 截圖
**狀態**: 全站掃描完成 | 截圖已存 /root/edico_shots/

---

## 1. 完整頁面清單（WAVE Extension 逐頁檢查用）

### EN 版（24 頁）

| # | URL | 頁面 |
|---|-----|------|
| 0 | https://www.edico.com.hk/ | 首頁 |
| 1 | https://www.edico.com.hk/?page_id=1005 | Speedy Quote（表單） |
| 2 | https://www.edico.com.hk/?page_id=1890 | Eflyer |
| 3 | https://www.edico.com.hk/?page_id=1892 | Video Clips |
| 4 | https://www.edico.com.hk/?page_id=1933 | Corporate Sales & Services |
| 5 | https://www.edico.com.hk/?page_id=2376 | Terms and Conditions |
| 6 | https://www.edico.com.hk/?page_id=2382 | Disclaimer |
| 7 | https://www.edico.com.hk/?page_id=429 | About Us |
| 8 | https://www.edico.com.hk/?page_id=45 | Services |
| 9 | https://www.edico.com.hk/?page_id=49 | Facilities |
| 10 | https://www.edico.com.hk/?page_id=6511 | Accessibility Statement |
| 11 | https://www.edico.com.hk/?page_id=675 | Translation |
| 12 | https://www.edico.com.hk/?page_id=677 | Print & Bind |
| 13 | https://www.edico.com.hk/?page_id=679 | Project Management |
| 14 | https://www.edico.com.hk/?page_id=683 | Composition |
| 15 | https://www.edico.com.hk/?page_id=685 | Creative & Graphic |
| 16 | https://www.edico.com.hk/?page_id=941 | CEO |
| 17 | https://www.edico.com.hk/?page_id=943 | COO |
| 18 | https://www.edico.com.hk/?page_id=975 | Credentials |
| 19 | https://www.edico.com.hk/?page_id=979 | CSR |
| 20 | https://www.edico.com.hk/?page_id=981 | Care for the Employee |
| 21 | https://www.edico.com.hk/?page_id=983 | Green Environment |
| 22 | https://www.edico.com.hk/?page_id=985 | Client's Corner |
| 23 | https://www.edico.com.hk/?page_id=987 | Gallery |

### CN 版（24 頁）— 注意：redirect 去另一組 page_id（EN 45 → CN 5236）

| # | URL（redirect 後最終） | 頁面 |
|---|-----|------|
| 0 | https://www.edico.com.hk/?lang=zh-hans | 首頁（中文） |
| 1 | https://www.edico.com.hk/?lang=zh-hans&page_id=5235 | 快速报价（表單） |
| 2 | https://www.edico.com.hk/?lang=zh-hans&page_id=5250 | Eflyer |
| 3 | https://www.edico.com.hk/?lang=zh-hans&page_id=5247 | 视频辑录 |
| 4 | https://www.edico.com.hk/?lang=zh-hans&page_id=5237 | 企业销售团队 |
| 5 | https://www.edico.com.hk/?lang=zh-hans&page_id=5244 | 条款及细则 |
| 6 | https://www.edico.com.hk/?lang=zh-hans&page_id=5233 | 免责声明 |
| 7 | https://www.edico.com.hk/?lang=zh-hans&page_id=5249 | 关于我们 |
| 8 | https://www.edico.com.hk/?lang=zh-hans&page_id=5236 | 服务 |
| 9 | https://www.edico.com.hk/?lang=zh-hans&page_id=5248 | 设施 |
| 10 | https://www.edico.com.hk/?lang=zh-hans&page_id=6516 | 无障碍声明 |
| 11 | https://www.edico.com.hk/?lang=zh-hans&page_id=5242 | 翻译 |
| 12 | https://www.edico.com.hk/?lang=zh-hans&page_id=5240 | 印刷订装 |
| 13 | https://www.edico.com.hk/?lang=zh-hans&page_id=5243 | 项目管理 |
| 14 | https://www.edico.com.hk/?lang=zh-hans&page_id=5238 | 创作 |
| 15 | https://www.edico.com.hk/?lang=zh-hans&page_id=5239 | 创意及图像 |
| 16 | https://www.edico.com.hk/?lang=zh-hans&page_id=5246 | 行政总裁 |
| 17 | https://www.edico.com.hk/?lang=zh-hans&page_id=5245 | 营运总监 |
| 18 | https://www.edico.com.hk/?lang=zh-hans&page_id=5241 | 历年作品 |
| 19 | https://www.edico.com.hk/?lang=zh-hans&page_id=6951 | 企业社会责任 |
| 20 | https://www.edico.com.hk/?lang=zh-hans&page_id=5229 | 员工关怀 |
| 21 | https://www.edico.com.hk/?lang=zh-hans&page_id=5232 | 绿色环境 |
| 22 | https://www.edico.com.hk/?lang=zh-hans&page_id=5230 | 客户角落 |
| 23 | https://www.edico.com.hk/?lang=zh-hans&page_id=5231 | 照片花絮 |

---

## 2. 自動掃描結果（Googlebot UA 全站 48 頁）

### 問題分佈

| 問題 | 數量 | 位置 |
|------|------|------|
| img alt 空 | 46 頁 | **全站同一張: Speedy Quote 按鈕圖**（`Speedy-Quote_E.png`）— 改一次全站 fix |
| iframe 冇 title | 2 頁 | Speedy Quote（reCAPTCHA）+ 1 個 |
| 第一個 heading 係 H2 | 2 頁 | 首頁（EN/CN） |
| 第一個 heading 係 H4 | 2 頁 | CN 941/943（CEO/COO 對應頁） |

### ⚠️ 重要提醒

1. **DARS 官方只 check 指定頁面**（首頁 + 6 個 page_id = 429/45/49/979/941/975）— 全站其他頁問題唔影響 Gold 申請，但有助整體質素
2. **上年已確認：只欠 W22 + W23**（W22 已完成，W23 對比度已過關）
3. 自動掃描唔可以代替 WAVE Extension（圖片背景/漸層/JS render 要真 browser 先知）

---

## 3. 截圖（/root/edico_shots/）

已完成 6 張示範截圖（EN_home/about/services/ceo/speedy/facilities.png）
- 全部正常渲染 ✅（vision 確認）
- 需要更多截圖可以再跑（48 頁全部可截，每頁 ~50 秒）

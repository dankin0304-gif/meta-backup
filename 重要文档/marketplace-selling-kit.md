# Marketplace 卖东西 · 接管准备包

准备时间：2026-11-23（周一）13:30 新西兰时间
背景：Kin 2026-11-23 13:07 问“你可以接管我的 marketplace？帮我卖东西？然后接私信，回复？”主聊天已回：分工是上架稿我准备、价格他定、过目后发布；常规私信直接回；砍价按他给的底价谈；看货取货约好时间地点、实物交接他本人去。并问了第一件卖什么，尚未回复。

## 已核实（2026-11-23 13:30，用 facebook-cli me 实测）
- Facebook 已连接，账号显示名 **Capek Karel**。上架/发帖都会以这个名字出去，发布第一件之前先跟 Kin 确认一次这个名字就是他要用的 Facebook 身份。
- Messenger（私信通道）本次未核实：2026-11-22 的连接器清单里 Messenger 还列在“建议连、待确认”里，不在已连好的 10 个里。接私信之前必须先跑 `/opt/hatch/bin/hatch_messenger_cli check`；若未连接，给 Kin 发 Connect Messenger 链接点一次授权。
- Marketplace 操作以 facebook-cli 为准：`marketplace my-listings` 查自己的上架，`marketplace listing create / edit / publish / delete` 管上架；建草稿走常规权限提示，正式发布会弹出审批卡——即每件上架仍需 Kin 过目确认，符合“不可逆动作先确认”的规矩。

## 时间线（为什么现在动手合算）
- 12 月底搬基督城；收拾行李 12-05/06、12-12/13；买电话卡最后一天 11-30；Serena 预计 11-30 到港、12 月初提车。
- 大件/难卖的先上架（现在到 12 月初约 2 周售卖窗口），赶在 12-05 第一轮收拾之前清掉；小件可拖到 12 月中。
- 闲鱼（tb58931002）也已登录，是中文买家方向的备选渠道，但 Kin 这次问的是 Marketplace，先走 Marketplace。

## 第一件需要 Kin 给的信息（缺一不可，不编造）
1. 品名 + 品牌型号；2. 成色/瑕疵（有瑕疵要拍出来写明）；3. 包含什么（配件、原包装、说明书）；4. 照片（参考 Porte 草稿的拍法：整体、细节、瑕疵各拍）；5. 心理价 + 底价（底价以内我谈，低于底价先问他）；6. 取货方式：自提（Flat Bush 一带，不写门牌号）还是可送。

## 上架模板（英文为主，Marketplace 买家多为英文）
Title: [Brand + Model + key spec] — [condition, e.g. Good condition]
Price: NZ$ ___ (or best offer if Kin agrees)
Description:
- Condition: ___ / Defects: ___ (honest, with photos)
- Includes: ___
- Pickup: Flat Bush, Auckland (exact address only in private message once a time is agreed)
- Payment: cash or bank transfer on collection, before handover
- Reason for selling: moving to Christchurch end of December

## 私信回复口径（常规问题直接回，涉及承诺的先确认）
- “Is this still available?” → “Yes, still available. Pickup in Flat Bush, Auckland. When would you like to view it?”
- 问价/砍价 → 底价以内可谈，低于底价先问 Kin；不口头承诺降价、不承诺留货。
- 约看货 → 只约白天、公共地点或他同意的地点；时间地点先经 Kin 确认再回。
- 付款 → 只认到账，不认截图；先款后货，不接受多付再退差价。
- 绝不做的事：不发验证码、不点买家发来的链接、不把交易挪出平台、不收定金留货（除非 Kin 同意）。

## 防骗红线（按 marketplaces skill）
- 买家索要验证码、要求移出平台付款、付给另一个人、多付要求退款、发付款截图冒充到账——一律停手并报 Kin。
- 家里精确地址不出在公开上架里，只写 Flat Bush / East Auckland；精确地址只在私信里、约好时间后给。
- 交接建议白天、光线好的公共地点，可带人同去；电子产品当面验机。

## 待办（给 delivery）
1. 跑 `hatch_messenger_cli check` 核 Messenger；未连则发连接链接。
2. 等 Kin 回第一件物品信息 + 照片，按模板出上架稿给他过目。
3. 发布后用 `marketplace my-listings` 回读确认已上架，再报他。

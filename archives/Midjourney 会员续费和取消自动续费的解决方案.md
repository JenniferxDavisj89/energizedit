# Midjourney 会员续费和取消自动续费的解决方案

## 问题概述
许多用户在 Midjourney 充值续费时遇到问题，例如无法正常充值或找不到取消自动续费的按钮。这些问题通常会导致错误提示，如 `Error: subscription already active for user: 乱码`，使订阅服务无法正常使用。本文将详细分析这些问题的原因，并提供解决方案。

## 问题原因

### 1. 无法充值续费的原因
Midjourney 的默认会员订阅方式是连续扣款。如果代充的卡在月底没有足够的余额，系统将无法自动扣款，导致续费失败。

### 2. 无法取消自动续费的原因
同样，由于卡内余额不足，系统无法执行自动续费，因此也无法处理取消订阅的请求。

## 解决方案

### 1. 解决无法充值续费的问题
1. 在对话框中输入 `/subscribe` 指令。
2. 登录 Midjourney 邮箱，找到 Discord 的登录确认邮件并点击 `Log in`。
3. 按提示输入号码并登录。
4. 点击 `Manage subscriptions`，进入订阅后台界面。
5. 点击“更新支付方式”，重新填写卡号信息完成订阅，或找到未付款的账单并支付。

### 2. 解决无法取消自动续费的问题
1. 在对话框中输入 `/subscribe` 指令，点击 `Open subscription page`。
2. 点击订阅计划右上角的 `Manage`，在弹出的菜单中点击 `Cancel Plan`。
3. 在 `Billing & Payment` 栏中，选择 `Cancel at end of subscription period`，然后点击 `Confirm Cancellation`。

### 3. 重新订阅已取消的会员
1. 在机器人窗口发送 `/subscribe`，点击 `Open subscription page`。
2. 依次点击 `Manage Sub` -> `Manage` -> `Uncancel Plan` 以重新开启订阅。

👉 [野卡 | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/yeka)

## 注意事项
- 养成习惯，会员开通后立即关闭自动续费，以避免下次找不到续费入口。
- 确保卡内有足够余额，以免续费失败。

通过以上步骤，您可以有效解决 Midjourney 会员续费和取消自动续费的问题。如果您需要更便捷的充值服务，推荐使用[野卡](https://bbtdd.com/yeka)，享受一分钟注册，轻松订阅海外线上服务的便利。
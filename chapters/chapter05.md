# Table of Content
<!-- MarkdownTOC -->

- [期望值的計算方法](#formula)
- [例 1](#example1)
- [例 2](#example2)

<!-- /MarkdownTOC -->

期望值的意思，是長遠來說，平均取得的數值。

# 期望值的計算方法{#formula}
$$
\sum_{\forall i}{} x_iP(x_i)
$$

# 例 1 {#example1}

假設一場遊戲，你勝出的機會是 $$\frac{1}{4}$$，如果你勝出，可獲10元，輸了便要給2元。求完成一場遊戲後你所得金錢的期望值。

ans:
$$
10 \times \frac{1}{4} + (-2)\times \frac{3}{4} = 1
$$

$$\therefore$$ 期望值 = 1

***意思是：*** 長遠來說，你每玩一局，平均每一局可獲取1元

---

# 例 2 {#example2}

袋入面有 20 個白波，15個黑波，5個紅波。抽到白波得1分、黑波4分、紅波8分。求抽一個波可得分的期望值

<!--sec data-title="題解" data-id="eg2ans" data-show=true data-collapse=true ces-->
ans:
$$
1 \times \frac{20}{40} + 2\times \frac{15}{40} + 8 \times \frac{5}{40} = 3
$$

$$\therefore$$ 期望值 = 3

***意思是：*** 長遠來說，你每玩一局，平均每一局可獲取3分

<!-- endsec -->
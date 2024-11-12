# Chaining Selectors

圖片來源：[Katho Mutodo](https://linktr.ee/photobykatho_) 和 [Andrea Piacquadio](https://www.pexels.com/@olly?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)。

在這個練習中，我們提供了一個部分完成的 HTML 文件，你需要配置它。本練習的目的是專注於理解如何鏈接不同的選擇器，而不僅僅是添加屬性。此外，你還將有機會審查你的 HTML 圖片。

我們有兩張圖片需要你來設置樣式，每張圖片都有兩個類別名稱，其中一個類別名稱是共享的。目標是鏈接這兩個元素的選擇器，使每個元素都應用獨特的樣式，儘管使用了共享的類別選擇器。例如，你希望一個同時具有 X 和 Y 的元素有一組樣式，而具有 X 和 Z 的元素則有完全不同的一組樣式。我們還包括了原始圖片，以便你可以看到你將添加的樣式與原始圖片的對比，因此不要對它們添加任何樣式。

你需要為每個元素添加的屬性是：

* 使同時具有 `avatar` 和 `proportioned` 類別的元素寬度為 300 像素，然後給它一個高度，使其保持原來的正方形比例（不要硬編碼高度的像素值！）。
* 使同時具有 `avatar` 和 `distorted` 類別的元素寬度為 200 像素，然後使其高度是寬度的兩倍（這裡你應該硬編碼高度的像素值）。

## 預期結果
![desired outcome](./desired-outcome.png)

### 自我檢查
- 你是否正確鏈接了每個規則的類別選擇器？
- `proportioned` 圖片是否保持其原來的正方形比例？
- `distorted` 圖片是否看起來被壓縮和扭曲？
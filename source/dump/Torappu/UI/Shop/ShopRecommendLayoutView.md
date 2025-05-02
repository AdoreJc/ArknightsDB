# ShopRecommendLayoutView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopRecommendTemplateViewBase _templateView`

- `UIRecommendEvent onClickEvent`


## Methods

- `Void OnClick(Int32)`

- `Void Render(String, List`1, ShopRecommendTemplateViewModelBase)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopRecommendLayoutView : MonoBehaviour
{
	private ShopRecommendItemView[] _itemList; // 0x18
	private ShopRecommendTemplateViewBase _templateView; // 0x20
	public UIRecommendEvent onClickEvent; // 0x28
	private List`1 m_dataList; // 0x30


	// RVA: 0x245b148 VA: 0x7594a73148
	public Void OnClick(Int32 index) { }
	// RVA: 0x245b1d8 VA: 0x7594a731d8
	public Void Render(String tagId, List`1 viewModel, ShopRecommendTemplateViewModelBase templateModel) { }
	// RVA: 0x245b56c VA: 0x7594a7356c
	public Void .ctor() { }
}
```
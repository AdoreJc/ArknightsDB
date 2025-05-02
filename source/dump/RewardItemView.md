# RewardItemView

**Namespace:** ` `


## Fields

- `GameObject _root`

- `Text _textName`

- `Text _textCount`

- `GameObject _panelMax`

- `RectTransform _itemCardContainer`

- `Image _progressCur`

- `Image _progressAdd`

- `UIItemCard m_itemCard`


## Methods

- `Void RenderItem(ItemData, Single)`

- `Void RenderCount(Int32, Int32, Int32)`

- `Void <RenderItem>b__10_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RewardItemView : IHotfixable
{
	private static readonly Color COLOR_ZERO; // 0x0
	private static readonly Color COLOR_OVER_ZERO; // 0x10
	private GameObject _root; // 0x10
	private Text _textName; // 0x18
	private Text _textCount; // 0x20
	private GameObject _panelMax; // 0x28
	private RectTransform _itemCardContainer; // 0x30
	private Image _progressCur; // 0x38
	private Image _progressAdd; // 0x40
	private UIItemCard m_itemCard; // 0x48
	private static DelegateBridge __Hotfix0_RenderItem; // 0x20
	private static DelegateBridge __Hotfix0_RenderCount; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2c6d5f0 VA: 0x75952855f0
	public Void RenderItem(ItemData data, Single itemCardScaleFactor) { }
	// RVA: 0x2c6e61c VA: 0x759528661c
	public Void RenderCount(Int32 currCount, Int32 addCount, Int32 maxCount) { }
	// RVA: 0x2c6f280 VA: 0x7595287280
	public Void .ctor() { }
	// RVA: 0x2c6f300 VA: 0x7595287300
	private static Void .cctor() { }
	// RVA: 0x2c6f364 VA: 0x7595287364
	private Void <RenderItem>b__10_0(Int32 index) { }
}
```
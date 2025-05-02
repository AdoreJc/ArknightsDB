# CarvingMainCardDeskView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingSlotView _slotViewPrefab`

- `UIAnimationLocation _slotSampleCurve`

- `RectTransform _slotContainer`

- `CarvingSlotCardListView _slotCardListView`

- `GameObject _panelSlot`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _CreateSlotViewIfNot()`

- `Void StateOnlyRegisterTutorialGO()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainCardDeskView : DataBinder`1
{
	private CarvingSlotView _slotViewPrefab; // 0x20
	private UIAnimationLocation _slotSampleCurve; // 0x28
	private Single[] _slotSamplePosList; // 0x38
	private RectTransform _slotContainer; // 0x40
	private CarvingSlotCardListView _slotCardListView; // 0x48
	private GameObject _panelSlot; // 0x50
	private List`1 m_slotViews; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private static DelegateBridge __Hotfix0_get_cardSlotList; // 0x0
	private static DelegateBridge __Hotfix0__CreateSlotViewIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_StateOnlyRegisterTutorialGO; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public List`1 cardSlotList { get; }

	// RVA: 0x2d9afd4 VA: 0x75953b2fd4
	public List`1 get_cardSlotList() { }
	// RVA: 0x2d9c0d8 VA: 0x75953b40d8
	private Void _CreateSlotViewIfNot() { }
	// RVA: 0x2d9c650 VA: 0x75953b4650
	public override Void OnValueChanged(CarvingMainProperty property) { }
	// RVA: 0x2d9adf8 VA: 0x75953b2df8
	public Void StateOnlyRegisterTutorialGO() { }
	// RVA: 0x2d9ca94 VA: 0x75953b4a94
	public Void .ctor() { }
}
```
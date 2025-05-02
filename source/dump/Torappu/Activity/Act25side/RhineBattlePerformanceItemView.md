# RhineBattlePerformanceItemView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Act25sideTechType _itemType`

- `Text _itemName`

- `Text _itemDesc`

- `Image _itemLevel1IconUnlock`

- `Image _itemLevel1IconLock`

- `GameObject _itemLevel1IconNew`

- `Image _itemLevel2IconUnlock`

- `Image _itemLevel2IconLock`

- `GameObject _itemLevel2IconNew`

- `GameObject _itemUnlockObj`

- `GameObject _itemLockObj`

- `GameObject _itemRunning`

- `UIPageFinder m_pageFinder`


## Properties

- `Act25sideTechType itemtype`


## Methods

- `Act25sideTechType get_itemtype()`

- `Void Render(RhineBattlePerformanceItemListModel)`

- `Sprite _LoadItemIcon(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class RhineBattlePerformanceItemView : MonoBehaviour, IHotfixable
{
	private Act25sideTechType _itemType; // 0x18
	private Text _itemName; // 0x20
	private Text _itemDesc; // 0x28
	private Image _itemLevel1IconUnlock; // 0x30
	private Image _itemLevel1IconLock; // 0x38
	private GameObject _itemLevel1IconNew; // 0x40
	private Image _itemLevel2IconUnlock; // 0x48
	private Image _itemLevel2IconLock; // 0x50
	private GameObject _itemLevel2IconNew; // 0x58
	private GameObject _itemUnlockObj; // 0x60
	private GameObject _itemLockObj; // 0x68
	private GameObject _itemRunning; // 0x70
	private UIPageFinder m_pageFinder; // 0x78
	private static DelegateBridge __Hotfix0_get_itemtype; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__LoadItemIcon; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Act25sideTechType itemtype { get; }

	// RVA: 0x32863f0 VA: 0x759589e3f0
	public Act25sideTechType get_itemtype() { }
	// RVA: 0x3286458 VA: 0x759589e458
	public Void Render(RhineBattlePerformanceItemListModel itemList) { }
	// RVA: 0x32866e4 VA: 0x759589e6e4
	private Sprite _LoadItemIcon(String itemIconId) { }
	// RVA: 0x3286788 VA: 0x759589e788
	public Void .ctor() { }
}
```
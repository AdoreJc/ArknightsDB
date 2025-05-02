# SandboxV2SquadToolItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2ItemCard _itemCardPrefab`

- `RectTransform _itemContainer`

- `Single _itemScale`

- `Text _textName`

- `Text _textPosition`

- `Text _textTotalCnt`

- `GameObject _normalPartGo`

- `GameObject _emptyPartGo`

- `Image _imgTagBg`

- `Text _textTagName`

- `GameObject _btnBuildGo`

- `GameObject _btnBuildBgGo`

- `UIPageFinder m_pageFinder`

- `SandboxV2ItemCard m_itemCard`

- `Int32 m_index`


## Methods

- `Void set_onToolClick(Action`1)`

- `Void set_onBtnBuildClick(Action`1)`

- `Void Render(Int32, Int32, SandboxV2SquadToolModel, Boolean)`

- `Void EventOnToolClick()`

- `Void EventOnBtnBuild()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadToolItemView : MonoBehaviour, IHotfixable
{
	private SandboxV2ItemCard _itemCardPrefab; // 0x18
	private RectTransform _itemContainer; // 0x20
	private Single _itemScale; // 0x28
	private Text _textName; // 0x30
	private Text _textPosition; // 0x38
	private Text _textTotalCnt; // 0x40
	private GameObject _normalPartGo; // 0x48
	private GameObject _emptyPartGo; // 0x50
	private Image _imgTagBg; // 0x58
	private Text _textTagName; // 0x60
	private GameObject _btnBuildGo; // 0x68
	private GameObject _btnBuildBgGo; // 0x70
	private UIPageFinder m_pageFinder; // 0x78
	private SandboxV2ItemCard m_itemCard; // 0x88
	private Int32 m_index; // 0x90
	private Action`1 <onToolClick>k__BackingField; // 0x98
	private Action`1 <onBtnBuildClick>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_onToolClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onToolClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onBtnBuildClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onBtnBuildClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_EventOnToolClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBtnBuild; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`1 onToolClick { get; set; }
	private Action`1 onBtnBuildClick { get; set; }

	// RVA: 0x261c3b0 VA: 0x7594c343b0
	private Action`1 get_onToolClick() { }
	// RVA: 0x261c418 VA: 0x7594c34418
	public Void set_onToolClick(Action`1 value) { }
	// RVA: 0x261c49c VA: 0x7594c3449c
	private Action`1 get_onBtnBuildClick() { }
	// RVA: 0x261c504 VA: 0x7594c34504
	public Void set_onBtnBuildClick(Action`1 value) { }
	// RVA: 0x261c588 VA: 0x7594c34588
	public Void Render(Int32 index, Int32 capacity, SandboxV2SquadToolModel toolModel, Boolean disableBtnBuild) { }
	// RVA: 0x261c930 VA: 0x7594c34930
	public Void EventOnToolClick() { }
	// RVA: 0x261c9d0 VA: 0x7594c349d0
	public Void EventOnBtnBuild() { }
	// RVA: 0x261ca70 VA: 0x7594c34a70
	public Void .ctor() { }
}
```
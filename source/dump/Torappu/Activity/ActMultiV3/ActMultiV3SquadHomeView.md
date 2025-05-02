# ActMultiV3SquadHomeView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `SimpleLayoutContent _tabList`

- `UIRecycleLayoutGroup _charList`

- `ActMultiV3SquadClassColView _classColPrefab`

- `Single _classColWidth`

- `ActMultiV3SquadCharColView _charColPrefab`

- `Single _charColWidth`

- `Image _imgEffectIcon`

- `GameObject _btnSquadEffectGO`

- `Boolean m_hasInited`

- `ActMultiV3SquadGroupModel m_squadGroupModel`

- `TabListAdapter m_tabListAdapter`

- `CharListAdapter m_charListAdapter`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void _RegisterTutorialGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadHomeView : DataBinder`1
{
	private SimpleLayoutContent _tabList; // 0x20
	private UIRecycleLayoutGroup _charList; // 0x28
	private ActMultiV3SquadClassColView _classColPrefab; // 0x30
	private Single _classColWidth; // 0x38
	private ActMultiV3SquadCharColView _charColPrefab; // 0x40
	private Single _charColWidth; // 0x48
	private Image _imgEffectIcon; // 0x50
	private GameObject _btnSquadEffectGO; // 0x58
	private Boolean m_hasInited; // 0x60
	private ActMultiV3SquadGroupModel m_squadGroupModel; // 0x68
	private TabListAdapter m_tabListAdapter; // 0x70
	private CharListAdapter m_charListAdapter; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31447c0 VA: 0x759575c7c0
	public override Void OnValueChanged(ActMultiV3SquadGroupProp property) { }
	// RVA: 0x31449a4 VA: 0x759575c9a4
	private Void _InitIfNot() { }
	// RVA: 0x3144c38 VA: 0x759575cc38
	private Void _RegisterTutorialGo() { }
	// RVA: 0x3144d24 VA: 0x759575cd24
	public Void .ctor() { }
}
```
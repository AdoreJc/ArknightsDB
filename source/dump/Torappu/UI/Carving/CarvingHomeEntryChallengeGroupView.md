# CarvingHomeEntryChallengeGroupView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `RectTransform _tabContainer`

- `Sequence m_switchAnim`

- `Tween m_enterAnim`

- `Int32 m_cachedIndex`

- `String m_cachedCurrId`

- `String m_cachedTabId`

- `CarvingHomeEntryItemViewModel m_cachedPrevModel`

- `Int32 m_cacheEnterSequence`

- `UIPageFinder m_pageFinder`


## Methods

- `Void OnExit()`

- `Void _ResetItemStatus(String, String)`

- `Void _AppendItemAnim(Sequence, CarvingHomeEntryChallengeTabView, AnimType)`

- `CarvingHomeEntryChallengeTabView _GetItemTab(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingHomeEntryChallengeGroupView : DataBinder`1, IHotfixable
{
	private RectTransform _tabContainer; // 0x20
	private Sequence m_switchAnim; // 0x28
	private Tween m_enterAnim; // 0x30
	private Dictionary`2 m_itemTab; // 0x38
	private Int32 m_cachedIndex; // 0x40
	private String m_cachedCurrId; // 0x48
	private String m_cachedTabId; // 0x50
	private CarvingHomeEntryItemViewModel m_cachedPrevModel; // 0x58
	private Int32 m_cacheEnterSequence; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private static DelegateBridge __Hotfix0_OnExit; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__ResetItemStatus; // 0x10
	private static DelegateBridge __Hotfix0__AppendItemAnim; // 0x18
	private static DelegateBridge __Hotfix0__GetItemTab; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d912bc VA: 0x75953a92bc
	public Void OnExit() { }
	// RVA: 0x2d9135c VA: 0x75953a935c
	public override Void OnValueChanged(CarvingHomeEntryProperty property) { }
	// RVA: 0x2d918bc VA: 0x75953a98bc
	private Void _ResetItemStatus(String currId, String nextId) { }
	// RVA: 0x2d91dac VA: 0x75953a9dac
	private Void _AppendItemAnim(Sequence sequence, CarvingHomeEntryChallengeTabView item, AnimType type) { }
	// RVA: 0x2d91b3c VA: 0x75953a9b3c
	private CarvingHomeEntryChallengeTabView _GetItemTab(String itemId) { }
	// RVA: 0x2d91eb4 VA: 0x75953a9eb4
	public Void .ctor() { }
}
```
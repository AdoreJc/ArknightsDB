# RL04FragmentDetailDialog

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04FragmentDetailView _detailView`

- `RectTransform _panelBackRt`

- `RL04FragmentDetailProperty m_property`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void EventOnBackBtnClicked()`

- `Void _InitIfNot()`

- `Void _EventOnNextBtnClicked()`

- `Void _EventOnPrevBtnClicked()`

- `Void _EventOnUseBtnClicked()`

- `Void _OnUseInspiration(String)`

- `Void _OnUseInspirationProceed(RL04UseInspirationResponse)`

- `Void _EventOnDropBtnClicked()`

- `Void _OnDropFragmentProceed(RL04LoseFragmentResponse)`

- `Void _NotifyDungeonUpdate()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentDetailDialog : UICompDialog`1, IHotfixable
{
	private RL04FragmentDetailView _detailView; // 0x48
	private RectTransform _panelBackRt; // 0x50
	private RL04FragmentDetailProperty m_property; // 0x58
	private Boolean m_hasInited; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__EventOnNextBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0__EventOnPrevBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0__EventOnUseBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnUseInspiration; // 0x38
	private static DelegateBridge __Hotfix0__OnUseInspirationProceed; // 0x40
	private static DelegateBridge __Hotfix0__EventOnDropBtnClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnDropFragmentProceed; // 0x50
	private static DelegateBridge __Hotfix0__NotifyDungeonUpdate; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2b1f830 VA: 0x7595137830
	protected override Void OnInit() { }
	// RVA: 0x2b1fb10 VA: 0x7595137b10
	protected override Void OnRender(Options input) { }
	// RVA: 0x2b1fe64 VA: 0x7595137e64
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x2b1f8a4 VA: 0x75951378a4
	private Void _InitIfNot() { }
	// RVA: 0x2b202d0 VA: 0x75951382d0
	private Void _EventOnNextBtnClicked() { }
	// RVA: 0x2b20410 VA: 0x7595138410
	private Void _EventOnPrevBtnClicked() { }
	// RVA: 0x2b20550 VA: 0x7595138550
	private Void _EventOnUseBtnClicked() { }
	// RVA: 0x2b2082c VA: 0x759513882c
	private Void _OnUseInspiration(String instId) { }
	// RVA: 0x2b20a1c VA: 0x7595138a1c
	private Void _OnUseInspirationProceed(RL04UseInspirationResponse response) { }
	// RVA: 0x2b20e08 VA: 0x7595138e08
	private Void _EventOnDropBtnClicked() { }
	// RVA: 0x2b210a4 VA: 0x75951390a4
	private Void _OnDropFragmentProceed(RL04LoseFragmentResponse response) { }
	// RVA: 0x2b20c20 VA: 0x7595138c20
	private Void _NotifyDungeonUpdate() { }
	// RVA: 0x2b2125c VA: 0x759513925c
	public Void .ctor() { }
	// RVA: 0x2b21394 VA: 0x7595139394
	private Void <>xLuaBaseProxy_OnInit() { }
}
```
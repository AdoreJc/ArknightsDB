# FifthAnnivExploreGroupChooseState

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreGroupChooseView _view`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Int32 m_confirmDialogInst`

- `FifthAnnivExploreGroupChooseStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnConfirmBtnClick()`

- `Void SetSelectHeritage(Boolean)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void _OnSelectGroup(Int32)`

- `Void _OnConfirmGroupChoose()`

- `Void _OpenConfirmDialog()`

- `Void <_OnConfirmGroupChoose>b__16_0(ExploreSelectInitGroupResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreGroupChooseState : PopupFadeState, IValueMsgReceiver, ICompDialogCallBack
{
	public const Int32 SELECT_GROUP; // 0x0
	public const Int32 DIALOG_CONFIRM; // 0x0
	public const Int32 DIALOG_CANCEL; // 0x0
	private FifthAnnivExploreGroupChooseView _view; // 0x70
	private Boolean m_isInited; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private Int32 m_confirmDialogInst; // 0x90
	private FifthAnnivExploreGroupChooseStateBean m_stateBean; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnConfirmBtnClick; // 0x18
	private static DelegateBridge __Hotfix0_SetSelectHeritage; // 0x20
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnSelectGroup; // 0x38
	private static DelegateBridge __Hotfix0__OnConfirmGroupChoose; // 0x40
	private static DelegateBridge __Hotfix0__OpenConfirmDialog; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x291a690 VA: 0x7594f32690
	public override IStateBean GetCacheBean() { }
	// RVA: 0x291a7f8 VA: 0x7594f327f8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x291a938 VA: 0x7594f32938
	protected override Void OnEnter() { }
	// RVA: 0x291a9ac VA: 0x7594f329ac
	public Void OnConfirmBtnClick() { }
	// RVA: 0x291af28 VA: 0x7594f32f28
	public Void SetSelectHeritage(Boolean select) { }
	// RVA: 0x291b088 VA: 0x7594f33088
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x291a700 VA: 0x7594f32700
	private Void _InitIfNot() { }
	// RVA: 0x291a8a8 VA: 0x7594f328a8
	private Void _OnSelectGroup(Int32 position) { }
	// RVA: 0x291ac8c VA: 0x7594f32c8c
	private Void _OnConfirmGroupChoose() { }
	// RVA: 0x291aaf0 VA: 0x7594f32af0
	private Void _OpenConfirmDialog() { }
	// RVA: 0x291b4d8 VA: 0x7594f334d8
	public Void .ctor() { }
	// RVA: 0x291b548 VA: 0x7594f33548
	private Void <_OnConfirmGroupChoose>b__16_0(ExploreSelectInitGroupResponse response) { }
	// RVA: 0x291b62c VA: 0x7594f3362c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```
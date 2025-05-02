# SandboxV2BasementState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2BasementView _basementView`

- `Boolean m_inited`

- `SandboxV2DungeonController m_dungeonController`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void _OnJumpToDungeonState(IStateBean)`

- `Void _OnJumpToNodeStagePreview(IStateBean)`

- `Void _OnJumpToNodeDropDetail(IStateBean)`

- `Void _OnJumpToDungeonSquad(IStateBean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnBasementUpgradeBtnClicked()`

- `Void OnBtnBackClicked()`

- `Void OnMonthBtnClick()`

- `Void _RaiseAVGSignal()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BasementState : SandboxV2TransparentState, IValueMsgReceiver
{
	public const Int32 ON_BASEMENT_UPGRADE; // 0x0
	private SandboxV2BasementView _basementView; // 0x70
	private Boolean m_inited; // 0x78
	private SandboxV2DungeonController m_dungeonController; // 0x80
	private UIPageFinder m_pageFinder; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToDungeonState; // 0x28
	private static DelegateBridge __Hotfix0__OnJumpToNodeStagePreview; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToNodeDropDetail; // 0x38
	private static DelegateBridge __Hotfix0__OnJumpToDungeonSquad; // 0x40
	private static DelegateBridge __Hotfix0_OnMessage; // 0x48
	private static DelegateBridge __Hotfix0__OnBasementUpgradeBtnClicked; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnBackClicked; // 0x58
	private static DelegateBridge __Hotfix0_OnMonthBtnClick; // 0x60
	private static DelegateBridge __Hotfix0__RaiseAVGSignal; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x250b3b8 VA: 0x7594b233b8
	private Void _InitIfNot() { }
	// RVA: 0x250b4ac VA: 0x7594b234ac
	public override IStateBean GetCacheBean() { }
	// RVA: 0x250b510 VA: 0x7594b23510
	protected override Void OnEnter() { }
	// RVA: 0x250b584 VA: 0x7594b23584
	protected override Void OnResume() { }
	// RVA: 0x250b718 VA: 0x7594b23718
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x250b9ec VA: 0x7594b239ec
	private Void _OnJumpToDungeonState(IStateBean stateBean) { }
	// RVA: 0x250bb48 VA: 0x7594b23b48
	private Void _OnJumpToNodeStagePreview(IStateBean stateBean) { }
	// RVA: 0x250bcb8 VA: 0x7594b23cb8
	private Void _OnJumpToNodeDropDetail(IStateBean stateBean) { }
	// RVA: 0x250bf40 VA: 0x7594b23f40
	private Void _OnJumpToDungeonSquad(IStateBean stateBean) { }
	// RVA: 0x250c148 VA: 0x7594b24148
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x250c1ec VA: 0x7594b241ec
	private Void _OnBasementUpgradeBtnClicked() { }
	// RVA: 0x250c40c VA: 0x7594b2440c
	public Void OnBtnBackClicked() { }
	// RVA: 0x250c5bc VA: 0x7594b245bc
	public Void OnMonthBtnClick() { }
	// RVA: 0x250b5f8 VA: 0x7594b235f8
	private Void _RaiseAVGSignal() { }
	// RVA: 0x250ca58 VA: 0x7594b24a58
	public Void .ctor() { }
	// RVA: 0x250cac8 VA: 0x7594b24ac8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x250cad0 VA: 0x7594b24ad0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x250cad8 VA: 0x7594b24ad8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```
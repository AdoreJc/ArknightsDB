# SandboxV2DungeonMonthState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonMonthView _view`

- `SandboxV2DungeonMonthModelProperty m_prop`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _Refresh()`

- `Void _InitIfNot()`

- `Void _LoadFromRuntime(StateRuntime)`

- `Void _OnJumpToNodeStagePreview(IStateBean)`

- `Void _OnJumpToDungeonSquad(IStateBean)`

- `SandboxV2DungeonNodeViewModel _GetCurrentNodeViewModel(SandboxV2DungeonController)`

- `Void _EventOnOpenEnemy()`

- `Void _EventOnOpenMap()`

- `Void _EventOnStartBattle()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonMonthState : PopupFadeState
{
	private SandboxV2DungeonMonthView _view; // 0x70
	private SandboxV2DungeonMonthModelProperty m_prop; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private StateCacheHandler`1 m_runtimeHandler; // 0x90
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x18
	private static DelegateBridge __Hotfix0__Refresh; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__LoadFromRuntime; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToNodeStagePreview; // 0x38
	private static DelegateBridge __Hotfix0__OnJumpToDungeonSquad; // 0x40
	private static DelegateBridge __Hotfix0__GetCurrentNodeViewModel; // 0x48
	private static DelegateBridge __Hotfix0__EventOnOpenEnemy; // 0x50
	private static DelegateBridge __Hotfix0__EventOnOpenMap; // 0x58
	private static DelegateBridge __Hotfix0__EventOnStartBattle; // 0x60
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x2530c98 VA: 0x7594b48c98
	protected override Void OnEnter() { }
	// RVA: 0x2531154 VA: 0x7594b49154
	protected override Void OnResume() { }
	// RVA: 0x25311d8 VA: 0x7594b491d8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x25313cc VA: 0x7594b493cc
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x2530f10 VA: 0x7594b48f10
	private Void _Refresh() { }
	// RVA: 0x2530d38 VA: 0x7594b48d38
	private Void _InitIfNot() { }
	// RVA: 0x25316ec VA: 0x7594b496ec
	private Void _LoadFromRuntime(StateRuntime runtime) { }
	// RVA: 0x25317e4 VA: 0x7594b497e4
	private Void _OnJumpToNodeStagePreview(IStateBean stateBean) { }
	// RVA: 0x2531a58 VA: 0x7594b49a58
	private Void _OnJumpToDungeonSquad(IStateBean stateBean) { }
	// RVA: 0x253194c VA: 0x7594b4994c
	private SandboxV2DungeonNodeViewModel _GetCurrentNodeViewModel(SandboxV2DungeonController controller) { }
	// RVA: 0x2531c80 VA: 0x7594b49c80
	private Void _EventOnOpenEnemy() { }
	// RVA: 0x2531dd4 VA: 0x7594b49dd4
	private Void _EventOnOpenMap() { }
	// RVA: 0x2532034 VA: 0x7594b4a034
	private Void _EventOnStartBattle() { }
	// RVA: 0x2532294 VA: 0x7594b4a294
	public override IStateBean GetCacheBean() { }
	// RVA: 0x25322f8 VA: 0x7594b4a2f8
	public Void .ctor() { }
	// RVA: 0x2532368 VA: 0x7594b4a368
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2532370 VA: 0x7594b4a370
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2532378 VA: 0x7594b4a378
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2532380 VA: 0x7594b4a380
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
}
```
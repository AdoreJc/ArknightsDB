# SandboxResTrap

**Namespace:** `Torappu.Battle`


## Fields

- `String _dropEffect`

- `Int32 m_maxStockCount`

- `Int32 m_curStockCount`

- `SandboxV2RewardCommonConfig m_reward`

- `SandboxGameMode m_gameMode`


## Properties

- `Int32 maxStockCount`

- `Int32 currentStockCount`

- `String rewardItemId`

- `SandboxGameMode sandboxGameMode`

- `Int32 notCollectedCount`


## Methods

- `Int32 get_maxStockCount()`

- `Int32 get_currentStockCount()`

- `String get_rewardItemId()`

- `SandboxGameMode get_sandboxGameMode()`

- `Int32 get_notCollectedCount()`

- `Void DropItems(Int32)`

- `Void RefreshCurrentStock(Int32)`

- `Void <>xLuaBaseProxy_OnInit(Single)`

- `Boolean <>xLuaBaseProxy_SetHpInternal(FP, Boolean, Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SandboxResTrap : Trap
{
	protected String _dropEffect; // 0x4f8
	private Int32 m_maxStockCount; // 0x500
	private Int32 m_curStockCount; // 0x504
	private SandboxV2RewardCommonConfig m_reward; // 0x508
	private SandboxGameMode m_gameMode; // 0x510
	private static DelegateBridge __Hotfix0_get_maxStockCount; // 0x0
	private static DelegateBridge __Hotfix0_get_currentStockCount; // 0x8
	private static DelegateBridge __Hotfix0_get_rewardItemId; // 0x10
	private static DelegateBridge __Hotfix0_get_sandboxGameMode; // 0x18
	private static DelegateBridge __Hotfix0_get_notCollectedCount; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_SetHpInternal; // 0x30
	private static DelegateBridge __Hotfix0_OnBorn; // 0x38
	private static DelegateBridge __Hotfix0_DropItems; // 0x40
	private static DelegateBridge __Hotfix0_RefreshCurrentStock; // 0x48
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Int32 maxStockCount { get; }
	public Int32 currentStockCount { get; }
	public String rewardItemId { get; }
	private SandboxGameMode sandboxGameMode { get; }
	public Int32 notCollectedCount { get; }

	// RVA: 0x1c263c8 VA: 0x759423e3c8
	public Int32 get_maxStockCount() { }
	// RVA: 0x1c26430 VA: 0x759423e430
	public Int32 get_currentStockCount() { }
	// RVA: 0x1c26498 VA: 0x759423e498
	public String get_rewardItemId() { }
	// RVA: 0x1c2650c VA: 0x759423e50c
	private SandboxGameMode get_sandboxGameMode() { }
	// RVA: 0x1c265bc VA: 0x759423e5bc
	public Int32 get_notCollectedCount() { }
	// RVA: 0x1c2665c VA: 0x759423e65c
	protected override Void OnInit(Single initHeight) { }
	// RVA: 0x1c26c20 VA: 0x759423ec20
	protected override Boolean SetHpInternal(FP value, Boolean force, Boolean noSource, Boolean skipReborn) { }
	// RVA: 0x1c26ec4 VA: 0x759423eec4
	protected override Void OnBorn() { }
	// RVA: 0x1c26dfc VA: 0x759423edfc
	public Void DropItems(Int32 count) { }
	// RVA: 0x1c26f88 VA: 0x759423ef88
	public Void RefreshCurrentStock(Int32 count) { }
	// RVA: 0x1c27008 VA: 0x759423f008
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1c2712c VA: 0x759423f12c
	public Void .ctor() { }
	// RVA: 0x1c27198 VA: 0x759423f198
	private Void <>xLuaBaseProxy_OnInit(Single P0) { }
	// RVA: 0x1c2719c VA: 0x759423f19c
	private Boolean <>xLuaBaseProxy_SetHpInternal(FP P0, Boolean P1, Boolean P2, Boolean P3) { }
	// RVA: 0x1c271b0 VA: 0x759423f1b0
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x1c271b8 VA: 0x759423f1b8
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```
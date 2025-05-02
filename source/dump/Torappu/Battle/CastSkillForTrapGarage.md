# CastSkillForTrapGarage

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean m_inAutoMode`

- `Int32 m_requiredCost`


## Properties

- `Int32 requiredCost`


## Methods

- `Int32 get_requiredCost()`

- `Void AutoUseSkill(PlayerSide)`

- `Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide)`

- `Boolean <>xLuaBaseProxy_IsDiscardable()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Boolean <>xLuaBaseProxy_DoCast(FinishCallbackDelegate, PlayerSide)`

- `Boolean <>xLuaBaseProxy_UseSkill(PlayerSide)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CastSkillForTrapGarage : CastSkill
{
	private Boolean m_inAutoMode; // 0x11c
	private Int32 m_requiredCost; // 0x120
	private static DelegateBridge __Hotfix0_get_requiredCost; // 0x0
	private static DelegateBridge __Hotfix0_IsAvailable; // 0x8
	private static DelegateBridge __Hotfix0_IsDiscardable; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_DoCast; // 0x20
	private static DelegateBridge __Hotfix0_UseSkill; // 0x28
	private static DelegateBridge __Hotfix0_AutoUseSkill; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 requiredCost { get; }

	// RVA: 0x40f1598 VA: 0x7596709598
	public Int32 get_requiredCost() { }
	// RVA: 0x40f1600 VA: 0x7596709600
	public override Boolean IsAvailable(PlayerSide operationSide) { }
	// RVA: 0x40f16e4 VA: 0x75967096e4
	public override Boolean IsDiscardable() { }
	// RVA: 0x40f174c VA: 0x759670974c
	public override Void OnInit() { }
	// RVA: 0x40f1850 VA: 0x7596709850
	protected override Boolean DoCast(FinishCallbackDelegate finishCb, PlayerSide operationSide) { }
	// RVA: 0x40f1c14 VA: 0x7596709c14
	public override Boolean UseSkill(PlayerSide operationSide) { }
	// RVA: 0x40f1dc4 VA: 0x7596709dc4
	public Void AutoUseSkill(PlayerSide operationSide) { }
	// RVA: 0x40f1e44 VA: 0x7596709e44
	protected override Void OnTick(FP deltaTime) { }
	// RVA: 0x40f1f84 VA: 0x7596709f84
	public Void .ctor() { }
	// RVA: 0x40f2014 VA: 0x759670a014
	private Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide P0) { }
	// RVA: 0x40f2018 VA: 0x759670a018
	private Boolean <>xLuaBaseProxy_IsDiscardable() { }
	// RVA: 0x40f201c VA: 0x759670a01c
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x40f2020 VA: 0x759670a020
	private Boolean <>xLuaBaseProxy_DoCast(FinishCallbackDelegate P0, PlayerSide P1) { }
	// RVA: 0x40f2024 VA: 0x759670a024
	private Boolean <>xLuaBaseProxy_UseSkill(PlayerSide P0) { }
	// RVA: 0x40f2028 VA: 0x759670a028
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
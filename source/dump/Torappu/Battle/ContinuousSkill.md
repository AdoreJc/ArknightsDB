# ContinuousSkill

**Namespace:** `Torappu.Battle`


## Fields

- `PrecisePeriodicTimer m_spContinuousCostTimer`

- `FP m_spCostPerSpec`


## Methods

- `Void <>xLuaBaseProxy_AssignData(SkillData, Character, Blackboard, Delta)`

- `Boolean <>xLuaBaseProxy_DoCast(FinishCallbackDelegate, PlayerSide)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ContinuousSkill : CastSkill
{
	private const Single DEFAULT_SP_COST_PER_SEC; // 0x0
	private PrecisePeriodicTimer m_spContinuousCostTimer; // 0x120
	private FP m_spCostPerSpec; // 0x128
	private static DelegateBridge __Hotfix0_AssignData; // 0x0
	private static DelegateBridge __Hotfix0_DoCast; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1b6fa00 VA: 0x7594187a00
	public override Void AssignData(SkillData data, Character owner, Blackboard externalBlackboard, Delta modifier) { }
	// RVA: 0x1b6fb4c VA: 0x7594187b4c
	protected override Boolean DoCast(FinishCallbackDelegate finishCb, PlayerSide operationSide) { }
	// RVA: 0x1b6fcd8 VA: 0x7594187cd8
	protected override Void OnTick(FP deltaTime) { }
	// RVA: 0x1b6fed8 VA: 0x7594187ed8
	public Void .ctor() { }
	// RVA: 0x1b6ffb8 VA: 0x7594187fb8
	private Void <>xLuaBaseProxy_AssignData(SkillData P0, Character P1, Blackboard P2, Delta P3) { }
	// RVA: 0x1b6ffc0 VA: 0x7594187fc0
	private Boolean <>xLuaBaseProxy_DoCast(FinishCallbackDelegate P0, PlayerSide P1) { }
	// RVA: 0x1b6ffc8 VA: 0x7594187fc8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```
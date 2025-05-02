# ReplacementSkill

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _cancelIfSearchTargetFailed`

- `Boolean _recoverSpIfTargetDead`

- `TargetSelector _rangeToShow`


## Methods

- `Boolean TryHookSearchTarget(out)`

- `Void _RecoverSp(Int32)`

- `IDrawableRange <>xLuaBaseProxy_get_rangeToShow()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Boolean <>xLuaBaseProxy_DoCast(FinishCallbackDelegate, PlayerSide)`

- `Void <>xLuaBaseProxy_OnCastFinish(Ability, FinishReason, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ReplacementSkill : NextAttackOrCombatSkill, IReplacement
{
	private Boolean _cancelIfSearchTargetFailed; // 0x100
	private Boolean _recoverSpIfTargetDead; // 0x101
	private TargetSelector _rangeToShow; // 0x108
	private static DelegateBridge __Hotfix0_get_rangeToShow; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfToModify; // 0x10
	private static DelegateBridge __Hotfix0_DoCast; // 0x18
	private static DelegateBridge __Hotfix0_ApplyModification; // 0x20
	private static DelegateBridge __Hotfix0_CancelAfterAttack; // 0x28
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x30
	private static DelegateBridge __Hotfix0_TryHookSearchTarget; // 0x38
	private static DelegateBridge __Hotfix0__RecoverSp; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override IDrawableRange rangeToShow { get; }

	// RVA: 0x1b711e4 VA: 0x75941891e4
	public override IDrawableRange get_rangeToShow() { }
	// RVA: 0x1b71298 VA: 0x7594189298
	public override Void OnInit() { }
	// RVA: 0x1b71390 VA: 0x7594189390
	protected override Boolean CheckIfToModify(Ability atkOrCbt, Boolean isCombat) { }
	// RVA: 0x1b71460 VA: 0x7594189460
	protected override Boolean DoCast(FinishCallbackDelegate finishCb, PlayerSide operationSide) { }
	// RVA: 0x1b71570 VA: 0x7594189570
	protected override Void ApplyModification() { }
	// RVA: 0x1b716e4 VA: 0x75941896e4
	protected override Boolean CancelAfterAttack(Ability atkOrCbt, Boolean isCombat, FinishReason reason) { }
	// RVA: 0x1b71818 VA: 0x7594189818
	protected override Void OnCastFinish(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x1b71ac8 VA: 0x7594189ac8
	public Boolean TryHookSearchTarget(out Boolean isFound) { }
	// RVA: 0x1b71928 VA: 0x7594189928
	private Void _RecoverSp(Int32 delta) { }
	// RVA: 0x1b71c44 VA: 0x7594189c44
	public Void .ctor() { }
	// RVA: 0x1b71cb8 VA: 0x7594189cb8
	private IDrawableRange <>xLuaBaseProxy_get_rangeToShow() { }
	// RVA: 0x1b71cbc VA: 0x7594189cbc
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x1b71cc4 VA: 0x7594189cc4
	private Boolean <>xLuaBaseProxy_DoCast(FinishCallbackDelegate P0, PlayerSide P1) { }
	// RVA: 0x1b71cc8 VA: 0x7594189cc8
	private Void <>xLuaBaseProxy_OnCastFinish(Ability P0, FinishReason P1, Boolean P2) { }
}
```
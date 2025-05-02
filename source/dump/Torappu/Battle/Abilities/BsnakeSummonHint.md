# BsnakeSummonHint

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _effectKey`

- `String _cancelBuffKey`

- `Int32 m_cursor`


## Methods

- `Void _InitTilePresetList()`

- `Void _RemoveEffects()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BsnakeSummonHint : AbilityStandard
{
	private String _effectKey; // 0x108
	private String _cancelBuffKey; // 0x110
	private List`1 m_effectList; // 0x118
	private Int32 m_cursor; // 0x120
	private List`1 m_tilePresetList; // 0x128
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x0
	private static DelegateBridge __Hotfix0_get_category; // 0x8
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x10
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x18
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x20
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x28
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x30
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x38
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x40
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x48
	private static DelegateBridge __Hotfix0__InitTilePresetList; // 0x50
	private static DelegateBridge __Hotfix0_DoSetData; // 0x58
	private static DelegateBridge __Hotfix0_DoDetach; // 0x60
	private static DelegateBridge __Hotfix0__RemoveEffects; // 0x68
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x70
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e6d6c4 VA: 0x75944856c4
	public override FP get_cooldown() { }
	// RVA: 0x1e6d754 VA: 0x7594485754
	public override Category get_category() { }
	// RVA: 0x1e6d7bc VA: 0x75944857bc
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e6d824 VA: 0x7594485824
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e6d888 VA: 0x7594485888
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e6d8ec VA: 0x75944858ec
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e6d950 VA: 0x7594485950
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e6d9d0 VA: 0x75944859d0
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e6da48 VA: 0x7594485a48
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e6db0c VA: 0x7594485b0c
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e6dbd0 VA: 0x7594485bd0
	private Void _InitTilePresetList() { }
	// RVA: 0x1e6e0fc VA: 0x75944860fc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e6e1b0 VA: 0x75944861b0
	protected override Void DoDetach() { }
	// RVA: 0x1e6e224 VA: 0x7594486224
	private Void _RemoveEffects() { }
	// RVA: 0x1e6e344 VA: 0x7594486344
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e6e6b8 VA: 0x75944866b8
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e6e7dc VA: 0x75944867dc
	public Void .ctor() { }
	// RVA: 0x1e6e854 VA: 0x7594486854
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e6e87c VA: 0x759448687c
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e6e884 VA: 0x7594486884
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e6e890 VA: 0x7594486890
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```
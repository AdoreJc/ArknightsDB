# FootBallHudPluginTalent

**Namespace:** `Torappu.Battle`


## Fields

- `FootBallHudPlugin m_hudPlugin`

- `FootballEnemy m_footballEnemy`

- `FP m_maxValue`

- `FP m_currentValue`

- `FP m_forceVectorX`

- `FP m_forceVectorY`

- `FP m_frictionFactor`

- `FP m_force`


## Methods

- `Void _OnHudCreated(Object)`

- `Void Reset(Boolean)`

- `Void OnTakeDamage(Entity, FP, FP, FP)`

- `Void OnKnockBack()`

- `Void OnKickByEnemy(Vector2, FP)`

- `Void ModifyKickValue(FP)`

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FootBallHudPluginTalent : UIPluginTalent
{
	private FootBallHudPlugin m_hudPlugin; // 0x60
	private FootballEnemy m_footballEnemy; // 0x68
	private FP m_maxValue; // 0x70
	private FP m_currentValue; // 0x78
	private FP m_forceVectorX; // 0x80
	private FP m_forceVectorY; // 0x88
	private FP m_frictionFactor; // 0x90
	private FP m_force; // 0x98
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_AssignData; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_DoDetach; // 0x18
	private static DelegateBridge __Hotfix0__OnHudCreated; // 0x20
	private static DelegateBridge __Hotfix0_LoadPlugin; // 0x28
	private static DelegateBridge __Hotfix0_Reset; // 0x30
	private static DelegateBridge __Hotfix0_OnTakeDamage; // 0x38
	private static DelegateBridge __Hotfix0_OnKnockBack; // 0x40
	private static DelegateBridge __Hotfix0_OnKickByEnemy; // 0x48
	private static DelegateBridge __Hotfix0_ModifyKickValue; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override PluginType type { get; }

	// RVA: 0x1b83420 VA: 0x759419b420
	public override PluginType get_type() { }
	// RVA: 0x1b83484 VA: 0x759419b484
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b83838 VA: 0x759419b838
	protected override Void DoAttach() { }
	// RVA: 0x1b83938 VA: 0x759419b938
	protected override Void DoDetach() { }
	// RVA: 0x1b83a48 VA: 0x759419ba48
	private Void _OnHudCreated(Object arg) { }
	// RVA: 0x1b83b88 VA: 0x759419bb88
	protected override UnitTalentUIPlugin LoadPlugin(String pluginName) { }
	// RVA: 0x1b8370c VA: 0x759419b70c
	public Void Reset(Boolean resetPlugin) { }
	// RVA: 0x1b83ca4 VA: 0x759419bca4
	public Void OnTakeDamage(Entity source, FP directionX, FP directionY, FP value) { }
	// RVA: 0x1b8407c VA: 0x759419c07c
	public Void OnKnockBack() { }
	// RVA: 0x1b84128 VA: 0x759419c128
	public Void OnKickByEnemy(Vector2 direction, FP forceScale) { }
	// RVA: 0x1b8422c VA: 0x759419c22c
	public Void ModifyKickValue(FP value) { }
	// RVA: 0x1b84330 VA: 0x759419c330
	public Void .ctor() { }
	// RVA: 0x1b843a0 VA: 0x759419c3a0
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
	// RVA: 0x1b843a4 VA: 0x759419c3a4
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b843ac VA: 0x759419c3ac
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```
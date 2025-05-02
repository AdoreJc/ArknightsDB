# BounceEnemyPhysicalFeatureTalent

**Namespace:** `Torappu.Battle`


## Fields

- `BounceEnemyHudPlugin m_hudPlugin`

- `InteractableBounceEnemy m_host`


## Methods

- `Void _OnHudCreated(Object)`

- `Void Reset(Boolean)`

- `Void OnAppliedFinalForce()`

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BounceEnemyPhysicalFeatureTalent : UIPluginTalent
{
	protected BounceEnemyHudPlugin m_hudPlugin; // 0x60
	protected InteractableBounceEnemy m_host; // 0x68
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_AssignData; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_DoDetach; // 0x18
	private static DelegateBridge __Hotfix0__OnHudCreated; // 0x20
	private static DelegateBridge __Hotfix0_LoadPlugin; // 0x28
	private static DelegateBridge __Hotfix0_Reset; // 0x30
	private static DelegateBridge __Hotfix0_UpdateHUD; // 0x38
	private static DelegateBridge __Hotfix0_OnAppliedFinalForce; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override PluginType type { get; }

	// RVA: 0x1b82388 VA: 0x759419a388
	public override PluginType get_type() { }
	// RVA: 0x1b823ec VA: 0x759419a3ec
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b82790 VA: 0x759419a790
	protected override Void DoAttach() { }
	// RVA: 0x1b82890 VA: 0x759419a890
	protected override Void DoDetach() { }
	// RVA: 0x1b829a0 VA: 0x759419a9a0
	protected Void _OnHudCreated(Object arg) { }
	// RVA: 0x1b82b2c VA: 0x759419ab2c
	protected override UnitTalentUIPlugin LoadPlugin(String pluginName) { }
	// RVA: 0x1b826b4 VA: 0x759419a6b4
	public Void Reset(Boolean resetPlugin) { }
	// RVA: 0x1b82c48 VA: 0x759419ac48
	public virtual Void UpdateHUD(UIForceInfo m_cachedForceInfo) { }
	// RVA: 0x1b82d24 VA: 0x759419ad24
	public Void OnAppliedFinalForce() { }
	// RVA: 0x1b82de0 VA: 0x759419ade0
	public Void .ctor() { }
	// RVA: 0x1b82e50 VA: 0x759419ae50
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
	// RVA: 0x1b82e54 VA: 0x759419ae54
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b82e5c VA: 0x759419ae5c
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```
# UpdateHealScaleByTraitData

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _usedToEPHeal`

- `Boolean _applyEPScaleForEPHealNode`

- `Single _defaultValue`

- `Single _defaultEPHealRatioValue`

- `Boolean _overwrite`

- `Single m_healScale`

- `Single m_epHealScale`


## Properties

- `Boolean usedToEPHeal`


## Methods

- `Boolean get_usedToEPHeal()`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnCastStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class UpdateHealScaleByTraitData : Behaviour
{
	private Boolean _usedToEPHeal; // 0x20
	private Boolean _applyEPScaleForEPHealNode; // 0x21
	private Single _defaultValue; // 0x24
	private Single _defaultEPHealRatioValue; // 0x28
	private Boolean _overwrite; // 0x2c
	private Single m_healScale; // 0x30
	private Single m_epHealScale; // 0x34
	private static DelegateBridge __Hotfix0_get_usedToEPHeal; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected Boolean usedToEPHeal { get; }

	// RVA: 0x1ed4f50 VA: 0x75944ecf50
	protected Boolean get_usedToEPHeal() { }
	// RVA: 0x1ed4fb8 VA: 0x75944ecfb8
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed516c VA: 0x75944ed16c
	public override Void OnCastStart() { }
	// RVA: 0x1ed5348 VA: 0x75944ed348
	public Void .ctor() { }
	// RVA: 0x1ed53c4 VA: 0x75944ed3c4
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed53cc VA: 0x75944ed3cc
	private Void <>xLuaBaseProxy_OnCastStart() { }
}
```
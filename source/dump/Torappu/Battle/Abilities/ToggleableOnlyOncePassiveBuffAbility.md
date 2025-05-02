# ToggleableOnlyOncePassiveBuffAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean m_isTriggered`

- `Boolean m_isTriggerFinished`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnToggleChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ToggleableOnlyOncePassiveBuffAbility : ToggleablePassiveBuffAbility
{
	private Boolean m_isTriggered; // 0x130
	private Boolean m_isTriggerFinished; // 0x131
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnToggleChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1e60900 VA: 0x7594478900
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e60a78 VA: 0x7594478a78
	protected override Void OnToggleChanged(Boolean isToggled) { }
	// RVA: 0x1e60b48 VA: 0x7594478b48
	public Void .ctor() { }
	// RVA: 0x1e60c90 VA: 0x7594478c90
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e60cb4 VA: 0x7594478cb4
	private Void <>xLuaBaseProxy_OnToggleChanged(Boolean P0) { }
}
```
# UpdateAttackTimeByHost

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Character m_host`


## Methods

- `Boolean _TryGetHost()`

- `Void _UpdateAtkInternal()`

- `Void <>xLuaBaseProxy_OnAttackTimeChanged(FP)`

- `Void <>xLuaBaseProxy_OnCastStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class UpdateAttackTimeByHost : Behaviour
{
	private Character m_host; // 0x20
	private static DelegateBridge __Hotfix0_OnAttackTimeChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x8
	private static DelegateBridge __Hotfix0__TryGetHost; // 0x10
	private static DelegateBridge __Hotfix0__UpdateAtkInternal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ed4a78 VA: 0x75944eca78
	public override Void OnAttackTimeChanged(FP newValue) { }
	// RVA: 0x1ed4e44 VA: 0x75944ece44
	public override Void OnCastStart() { }
	// RVA: 0x1ed4b20 VA: 0x75944ecb20
	private Boolean _TryGetHost() { }
	// RVA: 0x1ed4d20 VA: 0x75944ecd20
	private Void _UpdateAtkInternal() { }
	// RVA: 0x1ed4ed0 VA: 0x75944eced0
	public Void .ctor() { }
	// RVA: 0x1ed4f40 VA: 0x75944ecf40
	private Void <>xLuaBaseProxy_OnAttackTimeChanged(FP P0) { }
	// RVA: 0x1ed4f48 VA: 0x75944ecf48
	private Void <>xLuaBaseProxy_OnCastStart() { }
}
```
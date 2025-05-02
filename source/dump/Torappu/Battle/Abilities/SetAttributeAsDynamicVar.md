# SetAttributeAsDynamicVar

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `AttributeType _attributeType`

- `String _scaleVar`

- `String _durationKey`

- `Single m_nextEscapeTime`


## Methods

- `Void _UpdateDynamicVar()`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class SetAttributeAsDynamicVar : Behaviour
{
	private AttributeType _attributeType; // 0x20
	private String _scaleVar; // 0x28
	private String _durationKey; // 0x30
	private Single m_nextEscapeTime; // 0x38
	private ObjectPtr`1 m_effectHolder; // 0x40
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x0
	private static DelegateBridge __Hotfix0_OnEvent; // 0x8
	private static DelegateBridge __Hotfix0__UpdateDynamicVar; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1ebc9e4 VA: 0x75944d49e4
	public override Void OnCastStart() { }
	// RVA: 0x1ebcce4 VA: 0x75944d4ce4
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ebca4c VA: 0x75944d4a4c
	private Void _UpdateDynamicVar() { }
	// RVA: 0x1ebcd84 VA: 0x75944d4d84
	public Void .ctor() { }
	// RVA: 0x1ebce50 VA: 0x75944d4e50
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ebce58 VA: 0x75944d4e58
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```
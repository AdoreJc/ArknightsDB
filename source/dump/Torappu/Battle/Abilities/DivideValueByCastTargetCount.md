# DivideValueByCastTargetCount

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Event _event`

- `String _blackboardKey`

- `Single m_blackboardValue`


## Methods

- `Int32 GetTargetCount()`

- `Void _UpdateBlackboard()`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class DivideValueByCastTargetCount : Behaviour
{
	private Event _event; // 0x20
	private String _blackboardKey; // 0x28
	private Single m_blackboardValue; // 0x30
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_OnEvent; // 0x8
	private static DelegateBridge __Hotfix0_GetTargetCount; // 0x10
	private static DelegateBridge __Hotfix0__UpdateBlackboard; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ecf018 VA: 0x75944e7018
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ecf0f0 VA: 0x75944e70f0
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ecf378 VA: 0x75944e7378
	private Int32 GetTargetCount() { }
	// RVA: 0x1ecf198 VA: 0x75944e7198
	private Void _UpdateBlackboard() { }
	// RVA: 0x1ecf59c VA: 0x75944e759c
	public Void .ctor() { }
	// RVA: 0x1ecf614 VA: 0x75944e7614
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ecf61c VA: 0x75944e761c
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```
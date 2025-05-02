# GameObjectSetActiveWrapper

**Namespace:** `Torappu.Battle`


## Fields

- `GameObject m_gameObjectNullable`

- `Boolean m_lastValue`


## Methods

- `Void SetActiveVal(Boolean)`

- `Void ApplyActiveVal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GameObjectSetActiveWrapper : IHotfixable
{
	private GameObject m_gameObjectNullable; // 0x10
	private Boolean m_lastValue; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetActiveVal; // 0x8
	private static DelegateBridge __Hotfix0_ApplyActiveVal; // 0x10


	// RVA: 0x1c4c8b8 VA: 0x75942648b8
	public Void .ctor(GameObject gameObjectNullable) { }
	// RVA: 0x1c4c9a8 VA: 0x75942649a8
	public Void SetActiveVal(Boolean value) { }
	// RVA: 0x1c4ca28 VA: 0x7594264a28
	public Void ApplyActiveVal() { }
}
```
# RandomDirection

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Vector3 _randomRotationFrom`

- `Vector3 _randomRotationTo`


## Methods

- `Void UpdateDirection()`

- `Void _RandomDirection(Entity)`

- `Void <>xLuaBaseProxy_OnPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class RandomDirection : Behaviour
{
	private Vector3 _randomRotationFrom; // 0x20
	private Vector3 _randomRotationTo; // 0x2c
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_UpdateDirection; // 0x8
	private static DelegateBridge __Hotfix0__RandomDirection; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2006dac VA: 0x759461edac
	public override Void OnPlay() { }
	// RVA: 0x2006e1c VA: 0x759461ee1c
	private Void UpdateDirection() { }
	// RVA: 0x2006ef8 VA: 0x759461eef8
	private Void _RandomDirection(Entity entity) { }
	// RVA: 0x2006fd0 VA: 0x759461efd0
	public Void .ctor() { }
	// RVA: 0x200703c VA: 0x759461f03c
	private Void <>xLuaBaseProxy_OnPlay() { }
}
```
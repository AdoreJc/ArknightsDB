# ExtraActions

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ActionArray _actions`


## Methods

- `Void GatherActionNodes(List`1)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ExtraActions : Behaviour, IActionNodeSource
{
	private ActionArray _actions; // 0x20
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x0
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1eb85fc VA: 0x75944d05fc
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1eb889c VA: 0x75944d089c
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1eb8930 VA: 0x75944d0930
	public Void .ctor() { }
	// RVA: 0x1eb89e0 VA: 0x75944d09e0
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0) { }
}
```
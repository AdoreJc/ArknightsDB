# AlwaysTrigger

**Namespace:** `Torappu.Battle`


## Methods

- `Boolean <>xLuaBaseProxy_get_isReadyToTrig()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AlwaysTrigger : TargetTrigger
{
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_get_isReadyToTrig; // 0x8
	private static DelegateBridge __Hotfix0_Search; // 0x10
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Entity target { get; }
	public override Boolean isReadyToTrig { get; }

	// RVA: 0x1bd3d90 VA: 0x75941ebd90
	public override Entity get_target() { }
	// RVA: 0x1bd3df4 VA: 0x75941ebdf4
	public override Boolean get_isReadyToTrig() { }
	// RVA: 0x1bd3e5c VA: 0x75941ebe5c
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd3ed8 VA: 0x75941ebed8
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd3f54 VA: 0x75941ebf54
	public Void .ctor() { }
	// RVA: 0x1bd4030 VA: 0x75941ec030
	private Boolean <>xLuaBaseProxy_get_isReadyToTrig() { }
}
```
# BUncleanedRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `GameObject _infoPanel`


## Methods

- `String <>xLuaBaseProxy_get_roomName()`

- `Boolean <>xLuaBaseProxy_OnRoomClicked()`

- `Void <>xLuaBaseProxy_OnActiveArchitecture(Boolean, Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BUncleanedRoom : BRoom
{
	private GameObject _infoPanel; // 0x50
	private static DelegateBridge __Hotfix0_get_roomName; // 0x0
	private static DelegateBridge __Hotfix0_OnRoomClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnActiveArchitecture; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override String roomName { get; }

	// RVA: 0x3d21110 VA: 0x7596339110
	protected override String get_roomName() { }
	// RVA: 0x3d2119c VA: 0x759633919c
	protected override Boolean OnRoomClicked() { }
	// RVA: 0x3d21204 VA: 0x7596339204
	protected override Void OnActiveArchitecture(Boolean active, Func`2 validPred) { }
	// RVA: 0x3d21338 VA: 0x7596339338
	public Void .ctor() { }
	// RVA: 0x3d213a8 VA: 0x75963393a8
	private String <>xLuaBaseProxy_get_roomName() { }
	// RVA: 0x3d213b0 VA: 0x75963393b0
	private Boolean <>xLuaBaseProxy_OnRoomClicked() { }
	// RVA: 0x3d213b8 VA: 0x75963393b8
	private Void <>xLuaBaseProxy_OnActiveArchitecture(Boolean P0, Func`2 P1) { }
}
```
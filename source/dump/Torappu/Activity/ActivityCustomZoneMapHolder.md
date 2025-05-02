# ActivityCustomZoneMapHolder

**Namespace:** `Torappu.Activity`


## Fields

- `String _zoneId`


## Properties

- `String zoneId`


## Methods

- `String get_zoneId()`

- `Boolean <>xLuaBaseProxy_LockAspect(String, Action`1)`

- `Boolean <>xLuaBaseProxy_PrefabUpdated()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCustomZoneMapHolder : ActivityAssetHolder
{
	private String _zoneId; // 0x28
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0_GetAssetIdList; // 0x8
	private static DelegateBridge __Hotfix0_LockAspect; // 0x10
	private static DelegateBridge __Hotfix0_PrefabUpdated; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String zoneId { get; }

	// RVA: 0x30bf878 VA: 0x75956d7878
	public String get_zoneId() { }
	// RVA: 0x30bfa74 VA: 0x75956d7a74
	public override String[] GetAssetIdList() { }
	// RVA: 0x30bfb60 VA: 0x75956d7b60
	protected override Boolean LockAspect(String curAspect, Action`1 setAspect) { }
	// RVA: 0x30bfc30 VA: 0x75956d7c30
	protected override Boolean PrefabUpdated() { }
	// RVA: 0x30bfdb0 VA: 0x75956d7db0
	public Void .ctor() { }
	// RVA: 0x30bfe1c VA: 0x75956d7e1c
	private Boolean <>xLuaBaseProxy_LockAspect(String P0, Action`1 P1) { }
	// RVA: 0x30bfe20 VA: 0x75956d7e20
	private Boolean <>xLuaBaseProxy_PrefabUpdated() { }
}
```
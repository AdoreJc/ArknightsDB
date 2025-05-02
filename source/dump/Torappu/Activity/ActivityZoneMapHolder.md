# ActivityZoneMapHolder

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
public class ActivityZoneMapHolder : ActivityAssetHolder
{
	private String _zoneId; // 0x28
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0_GetAssetIdList; // 0x8
	private static DelegateBridge __Hotfix0_LockAspect; // 0x10
	private static DelegateBridge __Hotfix0_PrefabUpdated; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String zoneId { get; }

	// RVA: 0x30c2dfc VA: 0x75956dadfc
	public String get_zoneId() { }
	// RVA: 0x30c2e64 VA: 0x75956dae64
	public override String[] GetAssetIdList() { }
	// RVA: 0x30c2f50 VA: 0x75956daf50
	protected override Boolean LockAspect(String curAspect, Action`1 setAspect) { }
	// RVA: 0x30c3020 VA: 0x75956db020
	protected override Boolean PrefabUpdated() { }
	// RVA: 0x30c31a4 VA: 0x75956db1a4
	public Void .ctor() { }
	// RVA: 0x30c3214 VA: 0x75956db214
	private Boolean <>xLuaBaseProxy_LockAspect(String P0, Action`1 P1) { }
	// RVA: 0x30c321c VA: 0x75956db21c
	private Boolean <>xLuaBaseProxy_PrefabUpdated() { }
}
```
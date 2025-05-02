# ActivityZoneMapPluginHolder

**Namespace:** `Torappu.Activity`


## Fields

- `StageZoneMapStatePlugin _plugin`


## Properties

- `StageZoneMapStatePlugin plugin`


## Methods

- `StageZoneMapStatePlugin get_plugin()`

- `Boolean <>xLuaBaseProxy_LockAspect(String, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityZoneMapPluginHolder : ActivityAssetHolder
{
	private StageZoneMapStatePlugin _plugin; // 0x28
	private static DelegateBridge __Hotfix0_LockAspect; // 0x0
	private static DelegateBridge __Hotfix0_GetAssetIdList; // 0x8
	private static DelegateBridge __Hotfix0_get_plugin; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public StageZoneMapStatePlugin plugin { get; }

	// RVA: 0x30c37c0 VA: 0x75956db7c0
	protected override Boolean LockAspect(String curAspect, Action`1 setAspect) { }
	// RVA: 0x30c3890 VA: 0x75956db890
	public override String[] GetAssetIdList() { }
	// RVA: 0x30c3974 VA: 0x75956db974
	public StageZoneMapStatePlugin get_plugin() { }
	// RVA: 0x30c39dc VA: 0x75956db9dc
	public Void .ctor() { }
	// RVA: 0x30c3a4c VA: 0x75956dba4c
	private Boolean <>xLuaBaseProxy_LockAspect(String P0, Action`1 P1) { }
}
```
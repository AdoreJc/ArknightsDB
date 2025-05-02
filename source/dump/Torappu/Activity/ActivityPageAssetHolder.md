# ActivityPageAssetHolder

**Namespace:** `Torappu.Activity`


## Fields

- `String _pageName`


## Methods

- `Boolean <>xLuaBaseProxy_LockAspect(String, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityPageAssetHolder : ActivityAssetHolder
{
	private String _pageName; // 0x28
	private static DelegateBridge __Hotfix0_GetAssetIdList; // 0x0
	private static DelegateBridge __Hotfix0_LockAspect; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30c151c VA: 0x75956d951c
	public override String[] GetAssetIdList() { }
	// RVA: 0x30c1620 VA: 0x75956d9620
	protected override Boolean LockAspect(String curAspect, Action`1 setAspect) { }
	// RVA: 0x30c16f0 VA: 0x75956d96f0
	public Void .ctor() { }
	// RVA: 0x30c1760 VA: 0x75956d9760
	private Boolean <>xLuaBaseProxy_LockAspect(String P0, Action`1 P1) { }
}
```
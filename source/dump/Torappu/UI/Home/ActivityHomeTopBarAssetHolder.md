# ActivityHomeTopBarAssetHolder

**Namespace:** `Torappu.UI.Home`


## Fields

- `ActivityTopBarView _singleEntry`

- `ActivityTopBarView _multiEntry`


## Methods

- `ActivityTopBarView GetProperPrefab(Int32)`

- `Boolean <>xLuaBaseProxy_LockAspect(String, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class ActivityHomeTopBarAssetHolder : ActivityAssetHolder
{
	private ActivityTopBarView _singleEntry; // 0x28
	private ActivityTopBarView _multiEntry; // 0x30
	private static DelegateBridge __Hotfix0_GetAssetIdList; // 0x0
	private static DelegateBridge __Hotfix0_LockAspect; // 0x8
	private static DelegateBridge __Hotfix0_GetProperPrefab; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x282142c VA: 0x7594e3942c
	public override String[] GetAssetIdList() { }
	// RVA: 0x2821510 VA: 0x7594e39510
	protected override Boolean LockAspect(String curAspect, Action`1 setAspect) { }
	// RVA: 0x28215e0 VA: 0x7594e395e0
	public ActivityTopBarView GetProperPrefab(Int32 entryCount) { }
	// RVA: 0x28216a8 VA: 0x7594e396a8
	public Void .ctor() { }
	// RVA: 0x2821718 VA: 0x7594e39718
	private Boolean <>xLuaBaseProxy_LockAspect(String P0, Action`1 P1) { }
}
```
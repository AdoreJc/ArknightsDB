# ActivityHiddenStageToastHolder

**Namespace:** `Torappu.Activity`


## Fields

- `HiddenStageMissionNotifyView _hiddenStageToast`


## Methods

- `Boolean TryGetHiddenStageToastPrefab(out)`

- `Boolean <>xLuaBaseProxy_LockAspect(String, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityHiddenStageToastHolder : ActivityAssetHolder
{
	private HiddenStageMissionNotifyView _hiddenStageToast; // 0x28
	private static DelegateBridge __Hotfix0_GetAssetIdList; // 0x0
	private static DelegateBridge __Hotfix0_LockAspect; // 0x8
	private static DelegateBridge __Hotfix0_TryGetHiddenStageToastPrefab; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30c0204 VA: 0x75956d8204
	public override String[] GetAssetIdList() { }
	// RVA: 0x30c02fc VA: 0x75956d82fc
	protected override Boolean LockAspect(String curAspect, Action`1 setAspect) { }
	// RVA: 0x30c03cc VA: 0x75956d83cc
	public Boolean TryGetHiddenStageToastPrefab(out HiddenStageMissionNotifyView notifyView) { }
	// RVA: 0x30c04ac VA: 0x75956d84ac
	public Void .ctor() { }
	// RVA: 0x30c0518 VA: 0x75956d8518
	private Boolean <>xLuaBaseProxy_LockAspect(String P0, Action`1 P1) { }
}
```
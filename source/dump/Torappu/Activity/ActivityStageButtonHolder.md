# ActivityStageButtonHolder

**Namespace:** `Torappu.Activity`


## Methods

- `Boolean TryGetStageButtonPatch(String, out)`

- `Boolean SavePatch(StageButtonPatch)`

- `Boolean <>xLuaBaseProxy_LockAspect(String, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityStageButtonHolder : ActivityAssetHolder, IStageButtonPatchCollection
{
	private List`1 _btnPatches; // 0x28
	private static DelegateBridge __Hotfix0_GetAssetIdList; // 0x0
	private static DelegateBridge __Hotfix0_LockAspect; // 0x8
	private static DelegateBridge __Hotfix0_TryGetStageButtonPatch; // 0x10
	private static DelegateBridge __Hotfix0_SavePatch; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30c1b4c VA: 0x75956d9b4c
	public override String[] GetAssetIdList() { }
	// RVA: 0x30c1d1c VA: 0x75956d9d1c
	protected override Boolean LockAspect(String curAspect, Action`1 setAspect) { }
	// RVA: 0x30c1dec VA: 0x75956d9dec
	public Boolean TryGetStageButtonPatch(String stageId, out StageButtonPatch patch) { }
	// RVA: 0x30c1f5c VA: 0x75956d9f5c
	public Boolean SavePatch(StageButtonPatch patch) { }
	// RVA: 0x30c2168 VA: 0x75956da168
	public Void .ctor() { }
	// RVA: 0x30c222c VA: 0x75956da22c
	private Boolean <>xLuaBaseProxy_LockAspect(String P0, Action`1 P1) { }
}
```
# ActivityTimelyDropAssetHolder

**Namespace:** `Torappu.Activity`


## Fields

- `GameObject _zoneSelectExDrop`

- `GameObject _dropPicExDrop`

- `GameObject _dropPicAndApProtectExDrop`

- `GameObject _stagePicExDrop`

- `StageTimelyDropStyle _stageTimelyDropStyle`


## Methods

- `Boolean TryToGetTimelyDropAsset(TimelyDropAssetType, out)`

- `Boolean _TryToGetZoneSelectExDrop(out)`

- `Boolean _TryToGetDropPicExDrop(out)`

- `Boolean _TryToGetDropPicAndApProtectExDrop(out)`

- `Boolean _TryToGetStagePicExDrop(out)`

- `Boolean _TryToGetStageTimelyDropStyle(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityTimelyDropAssetHolder : ActivityAssetHolder
{
	private GameObject _zoneSelectExDrop; // 0x28
	private GameObject _dropPicExDrop; // 0x30
	private GameObject _dropPicAndApProtectExDrop; // 0x38
	private GameObject _stagePicExDrop; // 0x40
	private StageTimelyDropStyle _stageTimelyDropStyle; // 0x48
	private static DelegateBridge __Hotfix0_GetAssetIdList; // 0x0
	private static DelegateBridge __Hotfix0_TryToGetTimelyDropAsset; // 0x8
	private static DelegateBridge __Hotfix0__TryToGetZoneSelectExDrop; // 0x10
	private static DelegateBridge __Hotfix0__TryToGetDropPicExDrop; // 0x18
	private static DelegateBridge __Hotfix0__TryToGetDropPicAndApProtectExDrop; // 0x20
	private static DelegateBridge __Hotfix0__TryToGetStagePicExDrop; // 0x28
	private static DelegateBridge __Hotfix0__TryToGetStageTimelyDropStyle; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x30c2644 VA: 0x75956da644
	public override String[] GetAssetIdList() { }
	// RVA: 0x30c2784 VA: 0x75956da784
	public Boolean TryToGetTimelyDropAsset(TimelyDropAssetType assetType, out Object result) { }
	// RVA: 0x30c28b4 VA: 0x75956da8b4
	private Boolean _TryToGetZoneSelectExDrop(out Object result) { }
	// RVA: 0x30c2994 VA: 0x75956da994
	private Boolean _TryToGetDropPicExDrop(out Object result) { }
	// RVA: 0x30c2a74 VA: 0x75956daa74
	private Boolean _TryToGetDropPicAndApProtectExDrop(out Object result) { }
	// RVA: 0x30c2bcc VA: 0x75956dabcc
	private Boolean _TryToGetStagePicExDrop(out Object result) { }
	// RVA: 0x30c2cac VA: 0x75956dacac
	private Boolean _TryToGetStageTimelyDropStyle(out Object result) { }
	// RVA: 0x30c2d8c VA: 0x75956dad8c
	public Void .ctor() { }
}
```
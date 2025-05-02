# UITimelyDropAssetHolder

**Namespace:** `Torappu.UI`


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
// Namespace : Torappu.UI
public class UITimelyDropAssetHolder : MonoBehaviour, IHotfixable
{
	private GameObject _zoneSelectExDrop; // 0x18
	private GameObject _dropPicExDrop; // 0x20
	private GameObject _dropPicAndApProtectExDrop; // 0x28
	private GameObject _stagePicExDrop; // 0x30
	private StageTimelyDropStyle _stageTimelyDropStyle; // 0x38
	private static DelegateBridge __Hotfix0_TryToGetTimelyDropAsset; // 0x0
	private static DelegateBridge __Hotfix0__TryToGetZoneSelectExDrop; // 0x8
	private static DelegateBridge __Hotfix0__TryToGetDropPicExDrop; // 0x10
	private static DelegateBridge __Hotfix0__TryToGetDropPicAndApProtectExDrop; // 0x18
	private static DelegateBridge __Hotfix0__TryToGetStagePicExDrop; // 0x20
	private static DelegateBridge __Hotfix0__TryToGetStageTimelyDropStyle; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x21f3608 VA: 0x759480b608
	public Boolean TryToGetTimelyDropAsset(TimelyDropAssetType assetType, out Object result) { }
	// RVA: 0x21f3738 VA: 0x759480b738
	private Boolean _TryToGetZoneSelectExDrop(out Object result) { }
	// RVA: 0x21f3818 VA: 0x759480b818
	public Boolean _TryToGetDropPicExDrop(out Object result) { }
	// RVA: 0x21f38f8 VA: 0x759480b8f8
	private Boolean _TryToGetDropPicAndApProtectExDrop(out Object result) { }
	// RVA: 0x21f3a50 VA: 0x759480ba50
	private Boolean _TryToGetStagePicExDrop(out Object result) { }
	// RVA: 0x21f3b30 VA: 0x759480bb30
	private Boolean _TryToGetStageTimelyDropStyle(out Object result) { }
	// RVA: 0x21f3c10 VA: 0x759480bc10
	public Void .ctor() { }
}
```
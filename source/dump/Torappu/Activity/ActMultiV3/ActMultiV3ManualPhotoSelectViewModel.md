# ActMultiV3ManualPhotoSelectViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String actId`

- `String weekRewardId`

- `String templateId`

- `Int32 selectedIdx`

- `Boolean showDetail`

- `Int32 collectionLimit`

- `Int32 photoTypeIdx`

- `String photoTypeName`

- `String photoBg`

- `String photoDesc`

- `String initSelectedInstId`

- `Boolean isWeekComitted`

- `Int32 initSeqNum`


## Properties

- `ActMultiV3PhotoDetailViewModel selectedPhoto`


## Methods

- `ActMultiV3PhotoDetailViewModel get_selectedPhoto()`

- `Void InitData(Input)`

- `Void UpdateFriendStatus(Dictionary`2)`

- `Void SelectPhoto(Int32, Boolean)`

- `Void _LoadData(ActMultiV3PhotoTypeData)`

- `Void _FindSelectedIdx()`

- `Int32 <_LoadData>b__19_0(ActMultiV3PhotoDetailViewModel, ActMultiV3PhotoDetailViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualPhotoSelectViewModel : IHotfixable
{
	public String actId; // 0x10
	public String weekRewardId; // 0x18
	public String templateId; // 0x20
	public Int32 selectedIdx; // 0x28
	public Boolean showDetail; // 0x2c
	public Int32 collectionLimit; // 0x30
	public Int32 photoTypeIdx; // 0x34
	public String photoTypeName; // 0x38
	public String photoBg; // 0x40
	public String photoDesc; // 0x48
	public String initSelectedInstId; // 0x50
	public Boolean isWeekComitted; // 0x58
	public Int32 initSeqNum; // 0x5c
	public List`1 photoModels; // 0x60
	private static DelegateBridge __Hotfix0_get_selectedPhoto; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateFriendStatus; // 0x10
	private static DelegateBridge __Hotfix0_SelectPhoto; // 0x18
	private static DelegateBridge __Hotfix0__LoadData; // 0x20
	private static DelegateBridge __Hotfix0__FindSelectedIdx; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public ActMultiV3PhotoDetailViewModel selectedPhoto { get; }

	// RVA: 0x311cb68 VA: 0x7595734b68
	public ActMultiV3PhotoDetailViewModel get_selectedPhoto() { }
	// RVA: 0x311efdc VA: 0x7595736fdc
	public Void InitData(Input input) { }
	// RVA: 0x311f610 VA: 0x7595737610
	public Void UpdateFriendStatus(Dictionary`2 cachedFriendStatus) { }
	// RVA: 0x311f770 VA: 0x7595737770
	public Void SelectPhoto(Int32 photoIdx, Boolean firstSelect) { }
	// RVA: 0x311f1e0 VA: 0x75957371e0
	private Void _LoadData(ActMultiV3PhotoTypeData photoTypeData) { }
	// RVA: 0x311fdc4 VA: 0x7595737dc4
	private Void _FindSelectedIdx() { }
	// RVA: 0x311fefc VA: 0x7595737efc
	public Void .ctor() { }
	// RVA: 0x311ffc0 VA: 0x7595737fc0
	private Int32 <_LoadData>b__19_0(ActMultiV3PhotoDetailViewModel lhs, ActMultiV3PhotoDetailViewModel rhs) { }
}
```
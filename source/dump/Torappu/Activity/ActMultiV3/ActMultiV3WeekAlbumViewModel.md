# ActMultiV3WeekAlbumViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Int32 tabIndex`

- `String weekRewardId`

- `Int32 order`

- `String titleDesc`

- `Int64 unlockTime`

- `Boolean isPrevCommitted`

- `Boolean isUnlocked`

- `Boolean isCommitted`

- `Int32 collectCnt`

- `Int32 totalCnt`

- `Boolean hasTrackPoint`


## Methods

- `Void LoadData(String, Photo, Dictionary`2, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3WeekAlbumViewModel : IHotfixable
{
	public Int32 tabIndex; // 0x10
	public String weekRewardId; // 0x18
	public Int32 order; // 0x20
	public String titleDesc; // 0x28
	public Int64 unlockTime; // 0x30
	public Boolean isPrevCommitted; // 0x38
	public Boolean isUnlocked; // 0x39
	public Boolean isCommitted; // 0x3a
	public Int32 collectCnt; // 0x3c
	public Int32 totalCnt; // 0x40
	public List`1 rewards; // 0x48
	public Boolean hasTrackPoint; // 0x50
	public List`1 photos; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8


	// RVA: 0x3122a60 VA: 0x759573aa60
	public Void .ctor(Int32 tabIdx, String rewardId, ActMultiV3WeeklyPhotoRewardData rewardData) { }
	// RVA: 0x3122c84 VA: 0x759573ac84
	public Void LoadData(String actId, Photo photo, Dictionary`2 photoTypeDataDict, ref Boolean prevCommited) { }
}
```
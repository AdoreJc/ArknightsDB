# ActMultiV3ManualViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ManualTabType selectedTabType`

- `Int32 initSeqNum`

- `String actId`

- `ActMultiV3ManualProfileModel profileModel`

- `ActMultiV3ManualMissionModel missionModel`

- `ActMultiV3ManualAlbumModel albumModel`


## Methods

- `Void InitData(String)`

- `Void LoadData()`

- `Boolean HasTabTrackPoint(ManualTabType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualViewModel : IHotfixable
{
	public ManualTabType selectedTabType; // 0x10
	public Int32 initSeqNum; // 0x14
	public String actId; // 0x18
	public ActMultiV3ManualProfileModel profileModel; // 0x20
	public ActMultiV3ManualMissionModel missionModel; // 0x28
	public ActMultiV3ManualAlbumModel albumModel; // 0x30
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_HasTabTrackPoint; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31213b0 VA: 0x75957393b0
	public Void InitData(String actId) { }
	// RVA: 0x3121ea8 VA: 0x7595739ea8
	public Void LoadData() { }
	// RVA: 0x3122484 VA: 0x759573a484
	public Boolean HasTabTrackPoint(ManualTabType selectedTabType) { }
	// RVA: 0x3122534 VA: 0x759573a534
	public Void .ctor() { }
}
```
# ActMultiV3ManualAlbumModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Boolean hasTrackPoint`

- `Int32 selectedWeekTabIdx`

- `Int32 renderSeqNum`


## Properties

- `ActMultiV3WeekAlbumViewModel activeAlbum`


## Methods

- `ActMultiV3WeekAlbumViewModel get_activeAlbum()`

- `Void InitData(String)`

- `Void LoadData(String)`

- `Void UpdateFocusWeek()`

- `Void SelectWeek(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualAlbumModel : IHotfixable
{
	public List`1 weekModels; // 0x10
	public Boolean hasTrackPoint; // 0x18
	public Int32 selectedWeekTabIdx; // 0x1c
	public Int32 renderSeqNum; // 0x20
	private static DelegateBridge __Hotfix0_get_activeAlbum; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_UpdateFocusWeek; // 0x18
	private static DelegateBridge __Hotfix0_SelectWeek; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public ActMultiV3WeekAlbumViewModel activeAlbum { get; }

	// RVA: 0x311911c VA: 0x759573111c
	public ActMultiV3WeekAlbumViewModel get_activeAlbum() { }
	// RVA: 0x3121b84 VA: 0x7595739b84
	public Void InitData(String actId) { }
	// RVA: 0x31222cc VA: 0x759573a2cc
	public Void LoadData(String actId) { }
	// RVA: 0x3122b9c VA: 0x759573ab9c
	public Void UpdateFocusWeek() { }
	// RVA: 0x31231a4 VA: 0x759573b1a4
	public Void SelectWeek(Int32 weekIdx) { }
	// RVA: 0x3122784 VA: 0x759573a784
	public Void .ctor() { }
}
```
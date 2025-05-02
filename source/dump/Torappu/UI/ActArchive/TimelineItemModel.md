# TimelineItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Int32 timelineSortId`

- `String timelineTitle`

- `String timelineDesc`


## Properties

- `Boolean isUnlockedAndUnchecked`


## Methods

- `Boolean get_isUnlockedAndUnchecked()`

- `Void LoadData(ActArchiveTimelineItemData, ActArchiveInfo)`

- `Boolean IsValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class TimelineItemModel : IHotfixable
{
	public TimelineResModel`1 musicItem; // 0x10
	public TimelineResModel`1 picItem; // 0x18
	public TimelineResModel`1 avgItem; // 0x20
	public TimelineResModel`1 storyItem; // 0x28
	public TimelineResModel`1 newsItem; // 0x30
	public Int32 timelineSortId; // 0x38
	public String timelineTitle; // 0x40
	public String timelineDesc; // 0x48
	private static DelegateBridge __Hotfix0_get_isUnlockedAndUnchecked; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_IsValid; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isUnlockedAndUnchecked { get; }

	// RVA: 0x30886f0 VA: 0x75956a06f0
	public Boolean get_isUnlockedAndUnchecked() { }
	// RVA: 0x3088828 VA: 0x75956a0828
	public Void LoadData(ActArchiveTimelineItemData timelineItemData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x30894e0 VA: 0x75956a14e0
	public Boolean IsValid() { }
	// RVA: 0x3089578 VA: 0x75956a1578
	public Void .ctor() { }
}
```
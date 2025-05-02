# TimelineProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _onTimelineCategoryClicked(ActArchiveType)`

- `Void _onTimelineItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class TimelineProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_InitComp; // 0x8
	private static DelegateBridge __Hotfix0__onTimelineCategoryClicked; // 0x10
	private static DelegateBridge __Hotfix0__onTimelineItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x300c31c VA: 0x759562431c
	protected override String get_compType() { }
	// RVA: 0x300c398 VA: 0x7595624398
	protected override Void InitComp() { }
	// RVA: 0x300c6b0 VA: 0x75956246b0
	private Void _onTimelineCategoryClicked(ActArchiveType archiveItemType) { }
	// RVA: 0x300c8d4 VA: 0x75956248d4
	private Void _onTimelineItemClicked(ActArchiveType archiveItemType, String archiveItemId) { }
	// RVA: 0x300cae4 VA: 0x7595624ae4
	public Void .ctor() { }
}
```
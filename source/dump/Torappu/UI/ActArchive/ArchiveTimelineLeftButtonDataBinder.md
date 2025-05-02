# ArchiveTimelineLeftButtonDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveTimelineCategoryBtn _btnMusic`

- `ArchiveTimelineCategoryBtn _btnPic`

- `ArchiveTimelineCategoryBtn _btnAvg`

- `ArchiveTimelineCategoryBtn _btnStory`

- `ArchiveTimelineCategoryBtn _btnNews`


## Properties

- `ArchiveTimelineController controller`


## Methods

- `Void set_controller(ArchiveTimelineController)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTimelineLeftButtonDataBinder : DataBinder`1
{
	private ArchiveTimelineCategoryBtn _btnMusic; // 0x20
	private ArchiveTimelineCategoryBtn _btnPic; // 0x28
	private ArchiveTimelineCategoryBtn _btnAvg; // 0x30
	private ArchiveTimelineCategoryBtn _btnStory; // 0x38
	private ArchiveTimelineCategoryBtn _btnNews; // 0x40
	private static DelegateBridge __Hotfix0_set_controller; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public ArchiveTimelineController controller { set; }

	// RVA: 0x308459c VA: 0x759569c59c
	public Void set_controller(ArchiveTimelineController value) { }
	// RVA: 0x3088548 VA: 0x75956a0548
	public override Void OnValueChanged(TimelineProperty property) { }
	// RVA: 0x3088660 VA: 0x75956a0660
	public Void .ctor() { }
}
```
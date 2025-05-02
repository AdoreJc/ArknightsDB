# ArchiveTimelineController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveTimelineDataBinder _timelineListBinder`

- `ArchiveTimelineLeftButtonDataBinder _timelineLeftButtonBinder`

- `UIAnimationLocation _animEnter`

- `ArchiveTimelineResHolder <subResHolder>k__BackingField`


## Properties

- `ArchiveTimelineResHolder subResHolder`


## Methods

- `ArchiveTimelineResHolder get_subResHolder()`

- `Void set_subResHolder(ArchiveTimelineResHolder)`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_Show(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTimelineController : ActArchiveController
{
	private ArchiveTimelineDataBinder _timelineListBinder; // 0x38
	private ArchiveTimelineLeftButtonDataBinder _timelineLeftButtonBinder; // 0x40
	private UIAnimationLocation _animEnter; // 0x48
	public Action`1 onTimelineCategoryClicked; // 0x58
	public Action`2 onTimelineItemClicked; // 0x60
	private ArchiveTimelineResHolder <subResHolder>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_subResHolder; // 0x0
	private static DelegateBridge __Hotfix0_set_subResHolder; // 0x8
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_Show; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public ArchiveTimelineResHolder subResHolder { get; set; }

	// RVA: 0x3083cf8 VA: 0x759569bcf8
	public ArchiveTimelineResHolder get_subResHolder() { }
	// RVA: 0x30842c8 VA: 0x759569c2c8
	private Void set_subResHolder(ArchiveTimelineResHolder value) { }
	// RVA: 0x308434c VA: 0x759569c34c
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x3084664 VA: 0x759569c664
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x30847c0 VA: 0x759569c7c0
	public override Void OnEnter() { }
	// RVA: 0x3084874 VA: 0x759569c874
	public override IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x3084964 VA: 0x759569c964
	public Void .ctor() { }
	// RVA: 0x30849d4 VA: 0x759569c9d4
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x30849dc VA: 0x759569c9dc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x30849e4 VA: 0x759569c9e4
	private IEnumerator <>xLuaBaseProxy_Show(Boolean P0) { }
}
```
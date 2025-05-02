# RL03ScrollReportPlugin

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RoguelikeScrollReportTitleView _titlePrefab`

- `RL03ReportCastView _castPrefab`

- `RoguelikeScrollReportItemView _initPrefab`

- `RoguelikeScrollReportItemView _summaryPrefab`

- `RoguelikeScrollReportItemView _endFailPrefab`

- `RoguelikeScrollReportItemView _zonePrefab`

- `RoguelikeScrollReportItemView _nodePrefab`

- `RoguelikeScrollReportItemView _endPrefab`

- `RL03ReportZoneOverviewView _zoneOverviewPrefab`

- `RoguelikeScrollReportItemView _endPaddingPrefab`


## Methods

- `RoguelikeScrollReportTitleView <>xLuaBaseProxy_get_titlePrefab()`

- `RoguelikeScrollReportItemView <>xLuaBaseProxy_get_initPrefab()`

- `RoguelikeScrollReportItemView <>xLuaBaseProxy_get_summaryPrefab()`

- `RoguelikeScrollReportItemView <>xLuaBaseProxy_get_endFailPrefab()`

- `RoguelikeScrollReportItemView <>xLuaBaseProxy_get_zonePrefab()`

- `RoguelikeScrollReportItemView <>xLuaBaseProxy_get_nodePrefab()`

- `RoguelikeScrollReportItemView <>xLuaBaseProxy_get_endPrefab()`

- `RoguelikeScrollReportItemView <>xLuaBaseProxy_get_endPaddingPrefab()`

- `RoguelikeScrollReportEndingFrameViewModelPlugin <>xLuaBaseProxy_get_endingFrameViewModelPlugin()`

- `IVirtualView <>xLuaBaseProxy_GetCastVirtualView(List`1)`

- `IVirtualView <>xLuaBaseProxy_GetZoneOverViewVirtualView(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03ScrollReportPlugin : RoguelikeScrollReportPlugin
{
	private RoguelikeScrollReportTitleView _titlePrefab; // 0x58
	private RL03ReportCastView _castPrefab; // 0x60
	private RoguelikeScrollReportItemView _initPrefab; // 0x68
	private RoguelikeScrollReportItemView _summaryPrefab; // 0x70
	private RoguelikeScrollReportItemView _endFailPrefab; // 0x78
	private RoguelikeScrollReportItemView _zonePrefab; // 0x80
	private RoguelikeScrollReportItemView _nodePrefab; // 0x88
	private RoguelikeScrollReportItemView _endPrefab; // 0x90
	private RL03ReportZoneOverviewView _zoneOverviewPrefab; // 0x98
	private RoguelikeScrollReportItemView _endPaddingPrefab; // 0xa0
	private static DelegateBridge __Hotfix0_get_titlePrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_initPrefab; // 0x8
	private static DelegateBridge __Hotfix0_get_summaryPrefab; // 0x10
	private static DelegateBridge __Hotfix0_get_endFailPrefab; // 0x18
	private static DelegateBridge __Hotfix0_get_zonePrefab; // 0x20
	private static DelegateBridge __Hotfix0_get_nodePrefab; // 0x28
	private static DelegateBridge __Hotfix0_get_endPrefab; // 0x30
	private static DelegateBridge __Hotfix0_get_endPaddingPrefab; // 0x38
	private static DelegateBridge __Hotfix0_get_endingFrameViewModelPlugin; // 0x40
	private static DelegateBridge __Hotfix0_GetCastVirtualView; // 0x48
	private static DelegateBridge __Hotfix0_GetZoneOverViewVirtualView; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override RoguelikeScrollReportTitleView titlePrefab { get; }
	public override RoguelikeScrollReportItemView initPrefab { get; }
	public override RoguelikeScrollReportItemView summaryPrefab { get; }
	public override RoguelikeScrollReportItemView endFailPrefab { get; }
	public override RoguelikeScrollReportItemView zonePrefab { get; }
	public override RoguelikeScrollReportItemView nodePrefab { get; }
	public override RoguelikeScrollReportItemView endPrefab { get; }
	public override RoguelikeScrollReportItemView endPaddingPrefab { get; }
	public override RoguelikeScrollReportEndingFrameViewModelPlugin endingFrameViewModelPlugin { get; }

	// RVA: 0x2b9b2ac VA: 0x75951b32ac
	public override RoguelikeScrollReportTitleView get_titlePrefab() { }
	// RVA: 0x2b9b314 VA: 0x75951b3314
	public override RoguelikeScrollReportItemView get_initPrefab() { }
	// RVA: 0x2b9b37c VA: 0x75951b337c
	public override RoguelikeScrollReportItemView get_summaryPrefab() { }
	// RVA: 0x2b9b3e4 VA: 0x75951b33e4
	public override RoguelikeScrollReportItemView get_endFailPrefab() { }
	// RVA: 0x2b9b44c VA: 0x75951b344c
	public override RoguelikeScrollReportItemView get_zonePrefab() { }
	// RVA: 0x2b9b4b4 VA: 0x75951b34b4
	public override RoguelikeScrollReportItemView get_nodePrefab() { }
	// RVA: 0x2b9b51c VA: 0x75951b351c
	public override RoguelikeScrollReportItemView get_endPrefab() { }
	// RVA: 0x2b9b584 VA: 0x75951b3584
	public override RoguelikeScrollReportItemView get_endPaddingPrefab() { }
	// RVA: 0x2b9b5ec VA: 0x75951b35ec
	public override RoguelikeScrollReportEndingFrameViewModelPlugin get_endingFrameViewModelPlugin() { }
	// RVA: 0x2b9b680 VA: 0x75951b3680
	public override IVirtualView GetCastVirtualView(List`1 nameList) { }
	// RVA: 0x2b9b914 VA: 0x75951b3914
	public override IVirtualView GetZoneOverViewVirtualView(List`1 zoneIdList) { }
	// RVA: 0x2b9b9f8 VA: 0x75951b39f8
	public Void .ctor() { }
	// RVA: 0x2b9ba68 VA: 0x75951b3a68
	private RoguelikeScrollReportTitleView <>xLuaBaseProxy_get_titlePrefab() { }
	// RVA: 0x2b9ba70 VA: 0x75951b3a70
	private RoguelikeScrollReportItemView <>xLuaBaseProxy_get_initPrefab() { }
	// RVA: 0x2b9ba78 VA: 0x75951b3a78
	private RoguelikeScrollReportItemView <>xLuaBaseProxy_get_summaryPrefab() { }
	// RVA: 0x2b9ba80 VA: 0x75951b3a80
	private RoguelikeScrollReportItemView <>xLuaBaseProxy_get_endFailPrefab() { }
	// RVA: 0x2b9ba88 VA: 0x75951b3a88
	private RoguelikeScrollReportItemView <>xLuaBaseProxy_get_zonePrefab() { }
	// RVA: 0x2b9ba90 VA: 0x75951b3a90
	private RoguelikeScrollReportItemView <>xLuaBaseProxy_get_nodePrefab() { }
	// RVA: 0x2b9ba98 VA: 0x75951b3a98
	private RoguelikeScrollReportItemView <>xLuaBaseProxy_get_endPrefab() { }
	// RVA: 0x2b9baa0 VA: 0x75951b3aa0
	private RoguelikeScrollReportItemView <>xLuaBaseProxy_get_endPaddingPrefab() { }
	// RVA: 0x2b9baa8 VA: 0x75951b3aa8
	private RoguelikeScrollReportEndingFrameViewModelPlugin <>xLuaBaseProxy_get_endingFrameViewModelPlugin() { }
	// RVA: 0x2b9bab0 VA: 0x75951b3ab0
	private IVirtualView <>xLuaBaseProxy_GetCastVirtualView(List`1 P0) { }
	// RVA: 0x2b9bab8 VA: 0x75951b3ab8
	private IVirtualView <>xLuaBaseProxy_GetZoneOverViewVirtualView(List`1 P0) { }
}
```
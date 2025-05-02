# StageMainlineRetroMapDecroView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String _actMissionGroupId`

- `String _retroMissionGroupId`

- `String _permanentId`

- `UICommonTrackPoint _trackPoint`

- `TemplateMissionViewModel m_viewModel`

- `TemplateMissionInputParam m_inputParam`

- `TrackPointViewProperty m_trackPoint`

- `Boolean m_hasInited`


## Methods

- `Void EventOnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageMainlineRetroMapDecroView : StageSideStoryMapDecroViewBase, IHotfixable
{
	private String _actMissionGroupId; // 0x20
	private String _retroMissionGroupId; // 0x28
	private String _permanentId; // 0x30
	private UICommonTrackPoint _trackPoint; // 0x38
	private TemplateMissionViewModel m_viewModel; // 0x40
	private TemplateMissionInputParam m_inputParam; // 0x48
	private TrackPointViewProperty m_trackPoint; // 0x50
	private Boolean m_hasInited; // 0x58
	private static DelegateBridge __Hotfix0_OnRefresh; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f18ed0 VA: 0x7595530ed0
	public override Void OnRefresh(List`1 viewModelList, ZoneViewModel selectViewModel) { }
	// RVA: 0x2f19344 VA: 0x7595531344
	public Void EventOnClicked() { }
	// RVA: 0x2f1900c VA: 0x759553100c
	private Void _InitIfNot() { }
	// RVA: 0x2f19470 VA: 0x7595531470
	public Void .ctor() { }
}
```
# Act13sideDailyMissionListView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Act13sideDailyMissionItemView _missionItemTemplate`

- `Text _textAgenda`

- `Text _textAgendaMax`

- `Color _hintColor`

- `UICommonTrackPoint _dailyMissionTrackPoint`

- `String m_actId`

- `Boolean m_hasInited`

- `Act13SideData m_actData`

- `Action m_onNavToPool`

- `Act13sideDailyMissionViewModel m_viewModel`

- `TrackPointViewProperty m_trackPointProp`


## Properties

- `Int32 boardMax`


## Methods

- `Int32 get_boardMax()`

- `Void Init(String, Action`1, Action`1, Action, Action`1)`

- `Void _InitIfNot()`

- `Void RegisterTutorialGo()`

- `Void PlayCompleteAnim(Int32, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionListView : DataBinder`1
{
	private RectTransform[] _missionItemParentList; // 0x20
	private Act13sideDailyMissionItemView _missionItemTemplate; // 0x28
	private Text _textAgenda; // 0x30
	private Text _textAgendaMax; // 0x38
	private Color _hintColor; // 0x40
	private UICommonTrackPoint _dailyMissionTrackPoint; // 0x50
	private String m_actId; // 0x58
	private Boolean m_hasInited; // 0x60
	private Act13SideData m_actData; // 0x68
	private Action`1 m_onMissionCancel; // 0x70
	private Action`1 m_onMissionCommit; // 0x78
	private Action m_onNavToPool; // 0x80
	private Action`1 m_onNavToStage; // 0x88
	private Act13sideDailyMissionViewModel m_viewModel; // 0x90
	private List`1 m_missionItemList; // 0x98
	private TrackPointViewProperty m_trackPointProp; // 0xa0
	private static DelegateBridge __Hotfix0_get_boardMax; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x20
	private static DelegateBridge __Hotfix0_PlayCompleteAnim; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Int32 boardMax { get; }

	// RVA: 0x343b720 VA: 0x7595a53720
	private Int32 get_boardMax() { }
	// RVA: 0x343b79c VA: 0x7595a5379c
	public Void Init(String actId, Action`1 onMissionCancel, Action`1 onMissionCommit, Action onNavToPool, Action`1 onNavToStage) { }
	// RVA: 0x343b8b4 VA: 0x7595a538b4
	public override Void OnValueChanged(Act13sideDailyMissionProperty property) { }
	// RVA: 0x343bc78 VA: 0x7595a53c78
	private Void _InitIfNot() { }
	// RVA: 0x343bf10 VA: 0x7595a53f10
	public Void RegisterTutorialGo() { }
	// RVA: 0x343c064 VA: 0x7595a54064
	public Void PlayCompleteAnim(Int32 boardIdx, Action onComplete) { }
	// RVA: 0x343c16c VA: 0x7595a5416c
	public Void .ctor() { }
}
```
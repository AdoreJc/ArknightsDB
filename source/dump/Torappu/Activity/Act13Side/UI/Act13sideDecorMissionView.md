# Act13sideDecorMissionView

**Namespace:** `Torappu.Activity.Act13Side.UI`


## Fields

- `GameObject _panelBtnFullScreen`

- `RectTransform _panelMissionBtn`

- `SimpleLayoutContent _viewContainer`

- `RectTransform _panelRectMask`

- `CanvasGroup _missionListCanvasGroup`

- `RectTransform _panelMissionList`

- `Vector2 _defaultPos`

- `Vector2 _showPos`

- `MissionSwitchTween m_missionSwitchTween`

- `Boolean m_hasInit`

- `Adapter m_missionListAdapter`

- `String m_actId`


## Methods

- `Void Init()`

- `Boolean _TryRenderMission()`

- `DailyMissionData _TryGetDailyMissionData(String)`

- `Void _TryLoadMissionDBData(String)`

- `Void EventOnShowMissionBtnClicked()`

- `Void EventOnHideMissionBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side.UI
public class Act13sideDecorMissionView : DataBinder`1
{
	private const Int32 MAX_MISSION_ITEM_NUM; // 0x0
	private GameObject _panelBtnFullScreen; // 0x20
	private RectTransform _panelMissionBtn; // 0x28
	private SimpleLayoutContent _viewContainer; // 0x30
	private RectTransform _panelRectMask; // 0x38
	private CanvasGroup _missionListCanvasGroup; // 0x40
	private RectTransform _panelMissionList; // 0x48
	private Vector2 _defaultPos; // 0x50
	private Vector2 _showPos; // 0x58
	private List`1 m_dailyMissionDataList; // 0x60
	private MissionSwitchTween m_missionSwitchTween; // 0x68
	private Boolean m_hasInit; // 0x70
	private Adapter m_missionListAdapter; // 0x78
	private String m_actId; // 0x80
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__TryRenderMission; // 0x10
	private static DelegateBridge __Hotfix0__TryGetDailyMissionData; // 0x18
	private static DelegateBridge __Hotfix0__TryLoadMissionDBData; // 0x20
	private static DelegateBridge __Hotfix0_EventOnShowMissionBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnHideMissionBtnClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3446b7c VA: 0x7595a5eb7c
	public Void Init() { }
	// RVA: 0x3447004 VA: 0x7595a5f004
	public override Void OnValueChanged(Act13sideZoneDescGroupViewProperty property) { }
	// RVA: 0x3446e94 VA: 0x7595a5ee94
	private Boolean _TryRenderMission() { }
	// RVA: 0x3447168 VA: 0x7595a5f168
	private DailyMissionData _TryGetDailyMissionData(String missionId) { }
	// RVA: 0x3446df0 VA: 0x7595a5edf0
	private Void _TryLoadMissionDBData(String actId) { }
	// RVA: 0x3447284 VA: 0x7595a5f284
	public Void EventOnShowMissionBtnClicked() { }
	// RVA: 0x3447314 VA: 0x7595a5f314
	public Void EventOnHideMissionBtnClicked() { }
	// RVA: 0x344738c VA: 0x7595a5f38c
	public Void .ctor() { }
}
```
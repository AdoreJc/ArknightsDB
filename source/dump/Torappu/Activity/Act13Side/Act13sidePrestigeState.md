# Act13sidePrestigeState

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `RectTransform _topMenuContainer`

- `Text _textUserName`

- `UIAnimationLocation _enterAnim`

- `Single _enterAnimDelay`

- `UICommonTrackPoint _missionTrackPoint`

- `UICommonTrackPoint _missionNewTrackPoint`

- `UICommonTrackPoint _archiveTrackPoint`

- `Boolean m_hasInited`

- `TemplateActivityController m_stageController`

- `StateCache m_stateCache`

- `TrackPointViewProperty m_missionTrackProp`

- `TrackPointViewProperty m_missionNewTrackProp`

- `TrackPointViewProperty m_archiveTrackProp`


## Properties

- `TemplateActivityController actController`

- `String activityId`


## Methods

- `TemplateActivityController get_actController()`

- `String get_activityId()`

- `Void _RenderOrgPanel(Boolean)`

- `Void _UpdateTrackPoint()`

- `Void OnBtnOpenArchive()`

- `Void OnBtnOpenMission()`

- `Void _OnOrgRewardClick(OrgData, PrestigeRank)`

- `Void _InitIfNot()`

- `Void _RegisterToRewardState(IStateBean)`

- `Void _RegisterFromMissionState(IStateBean)`

- `T _FetchStageController()`

- `Void <_InitIfNot>b__31_0()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sidePrestigeState : PopupFadeState
{
	private RectTransform _topMenuContainer; // 0x70
	private Text _textUserName; // 0x78
	private Act13sideOrgPanelView[] _orgPanelList; // 0x80
	private UIAnimationLocation _enterAnim; // 0x88
	private UIAnimationLocation[] _orgAnimList; // 0x98
	private Single _enterAnimDelay; // 0xa0
	private UICommonTrackPoint _missionTrackPoint; // 0xa8
	private UICommonTrackPoint _missionNewTrackPoint; // 0xb0
	private UICommonTrackPoint _archiveTrackPoint; // 0xb8
	private Boolean m_hasInited; // 0xc0
	private TemplateActivityController m_stageController; // 0xc8
	private StateCache m_stateCache; // 0xd0
	private TrackPointViewProperty m_missionTrackProp; // 0xe0
	private TrackPointViewProperty m_missionNewTrackProp; // 0xe8
	private TrackPointViewProperty m_archiveTrackProp; // 0xf0
	private static DelegateBridge __Hotfix0_get_actController; // 0x0
	private static DelegateBridge __Hotfix0_get_activityId; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnResume; // 0x38
	private static DelegateBridge __Hotfix0__RenderOrgPanel; // 0x40
	private static DelegateBridge __Hotfix0__UpdateTrackPoint; // 0x48
	private static DelegateBridge __Hotfix0_OnBtnOpenArchive; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnOpenMission; // 0x58
	private static DelegateBridge __Hotfix0__OnOrgRewardClick; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x68
	private static DelegateBridge __Hotfix0__RegisterToRewardState; // 0x70
	private static DelegateBridge __Hotfix0__RegisterFromMissionState; // 0x78
	private static DelegateBridge __Hotfix0__FetchStageController; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	protected TemplateActivityController actController { get; }
	protected String activityId { get; }

	// RVA: 0x3435248 VA: 0x7595a4d248
	protected TemplateActivityController get_actController() { }
	// RVA: 0x3435320 VA: 0x7595a4d320
	protected String get_activityId() { }
	// RVA: 0x34353f0 VA: 0x7595a4d3f0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3435454 VA: 0x7595a4d454
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x34355cc VA: 0x7595a4d5cc
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x3435644 VA: 0x7595a4d644
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x34357bc VA: 0x7595a4d7bc
	protected override Void OnEnter() { }
	// RVA: 0x3436098 VA: 0x7595a4e098
	protected override Void OnResume() { }
	// RVA: 0x3435c70 VA: 0x7595a4dc70
	private Void _RenderOrgPanel(Boolean needAnim) { }
	// RVA: 0x3435e10 VA: 0x7595a4de10
	private Void _UpdateTrackPoint() { }
	// RVA: 0x3436948 VA: 0x7595a4e948
	public Void OnBtnOpenArchive() { }
	// RVA: 0x3436a7c VA: 0x7595a4ea7c
	public Void OnBtnOpenMission() { }
	// RVA: 0x3436b88 VA: 0x7595a4eb88
	private Void _OnOrgRewardClick(OrgData orgData, PrestigeRank currentRank) { }
	// RVA: 0x3435a9c VA: 0x7595a4da9c
	private Void _InitIfNot() { }
	// RVA: 0x3436cf8 VA: 0x7595a4ecf8
	private Void _RegisterToRewardState(IStateBean stateBean) { }
	// RVA: 0x3436e00 VA: 0x7595a4ee00
	private Void _RegisterFromMissionState(IStateBean stateBean) { }
	// RVA: 0x VA: 0x0
	private T _FetchStageController() { }
	// RVA: 0x3436e80 VA: 0x7595a4ee80
	public Void .ctor() { }
	// RVA: 0x3436efc VA: 0x7595a4eefc
	private Void <_InitIfNot>b__31_0() { }
	// RVA: 0x3436f0c VA: 0x7595a4ef0c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3436f14 VA: 0x7595a4ef14
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x3436f1c VA: 0x7595a4ef1c
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x3436f24 VA: 0x7595a4ef24
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3436f2c VA: 0x7595a4ef2c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```
# StageZoneHomeMainGroupPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageZoneHomeEntryBinder _entryBinder`

- `StageZoneHomeToDoBinder _todoBinder`

- `RectTransform _recentViewHolder`

- `StageZoneHomeRecentView _recentViewPrefab`

- `StageZoneHomeThemeView _themeView`

- `CanvasGroup _alphaBkg`

- `CanvasGroup _alphaContent`

- `ZoneHomeEntryGroupProp m_entryProp`

- `ZoneHomeToDoGroupProp m_todoProp`

- `ZoneHomeRecentViewProp m_recentProp`

- `ZoneHomeThemeViewProp m_themeProp`

- `Boolean m_isInited`

- `StageZoneHomeRecentView m_recentBinder`

- `CrisisV2DataFromServer m_crisisData`

- `Boolean m_requestingCrisisData`

- `Tween m_exitTween`


## Methods

- `Void _InitIfNot()`

- `Void Update()`

- `Void _OnScalerChanged(CanvasScaler)`

- `Void _OnEntryClicked(ZoneHomeEntryItemModel)`

- `Void _OnToDoClicked(ZoneHomeToDoItemModel)`

- `Void _OnRecentViewClicked()`

- `Void _JumpToRecentDefault(String)`

- `Void _OnCrisisDataFetched()`

- `Void _UpdateData()`

- `Void _CancelExitTween()`

- `Void _CancelEnterTweens()`

- `Void _StartRequestForCrisisData()`

- `CrisisV2ServerDataWrapper _GetValidCrisisData()`

- `IEnumerator _UpdateLayoutCoroutine()`

- `Void _JumpToMainlineZone(ZoneHomeEntryItemModel)`

- `Void _JumpToRoguelike(ZoneHomeEntryItemModel)`

- `Void _JumpToRoguelike(ZoneHomeToDoItemModel)`

- `Void _JumpToRoguelikeByTopicId(String)`

- `Void _JumpToSandboxPerm(ZoneHomeEntryItemModel)`

- `Void _JumpToSandboxPerm(ZoneHomeToDoItemModel)`

- `Void _JumpToSandboxPermByTopicId(String)`

- `Void _JumpToCampaignWeekly(ZoneHomeToDoItemModel)`

- `Void _JumpToCampaignStage(String)`

- `Void _JumpToClimbTowerStage(ZoneHomeToDoItemModel)`

- `Void _JumpToCrisisV2Stage(ZoneHomeToDoItemModel)`

- `Void _JumpToCrisisV2Stage(ZoneHomeEntryItemModel)`

- `Void _JumpToActivity(ZoneHomeEntryItemModel)`

- `Void _JumpToStageActivity(String)`

- `Void _JumpToPageEntryActivity(String)`

- `IEnumerator _ExitYieldToActivity()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnDataUpdated(ZoneGroupViewProperty)`

- `IEnumerator <>xLuaBaseProxy_EnterYieldInstruction()`

- `Void <>xLuaBaseProxy_CancelEnter()`

- `IEnumerator <>xLuaBaseProxy_ExitYieldInstruction()`

- `Void <>xLuaBaseProxy_CancelExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeMainGroupPanel : StageZoneGroupPanel, IHotfixable
{
	private const Single FADE_DUR_TO_ACT; // 0x0
	private StageZoneHomeEntryBinder _entryBinder; // 0x60
	private StageZoneHomeToDoBinder _todoBinder; // 0x68
	private RectTransform _recentViewHolder; // 0x70
	private StageZoneHomeRecentView _recentViewPrefab; // 0x78
	private StageZoneHomeThemeView _themeView; // 0x80
	private CanvasGroup _alphaBkg; // 0x88
	private CanvasGroup _alphaContent; // 0x90
	private ZoneHomeEntryGroupProp m_entryProp; // 0x98
	private ZoneHomeToDoGroupProp m_todoProp; // 0xa0
	private ZoneHomeRecentViewProp m_recentProp; // 0xa8
	private ZoneHomeThemeViewProp m_themeProp; // 0xb0
	private Boolean m_isInited; // 0xb8
	private StageZoneHomeRecentView m_recentBinder; // 0xc0
	private CrisisV2DataFromServer m_crisisData; // 0xc8
	private Boolean m_requestingCrisisData; // 0xd0
	private List`1 m_enterTweens; // 0xd8
	private Tween m_exitTween; // 0xe0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x10
	private static DelegateBridge __Hotfix0_EnterYieldInstruction; // 0x18
	private static DelegateBridge __Hotfix0_CancelEnter; // 0x20
	private static DelegateBridge __Hotfix0_ExitYieldInstruction; // 0x28
	private static DelegateBridge __Hotfix0_CancelExit; // 0x30
	private static DelegateBridge __Hotfix0_Update; // 0x38
	private static DelegateBridge __Hotfix0__OnScalerChanged; // 0x40
	private static DelegateBridge __Hotfix0__OnEntryClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnToDoClicked; // 0x50
	private static DelegateBridge __Hotfix0__OnRecentViewClicked; // 0x58
	private static DelegateBridge __Hotfix0__JumpToRecentDefault; // 0x60
	private static DelegateBridge __Hotfix0__OnCrisisDataFetched; // 0x68
	private static DelegateBridge __Hotfix0__UpdateData; // 0x70
	private static DelegateBridge __Hotfix0__CancelExitTween; // 0x78
	private static DelegateBridge __Hotfix0__CancelEnterTweens; // 0x80
	private static DelegateBridge __Hotfix0__StartRequestForCrisisData; // 0x88
	private static DelegateBridge __Hotfix0__GetValidCrisisData; // 0x90
	private static DelegateBridge __Hotfix0__UpdateLayoutCoroutine; // 0x98
	private static DelegateBridge __Hotfix0__CheckIfEntryLocked; // 0xa0
	private static DelegateBridge __Hotfix0__JumpToMainlineZone; // 0xa8
	private static DelegateBridge __Hotfix0__JumpToRoguelike; // 0xb0
	private static DelegateBridge __Hotfix1__JumpToRoguelike; // 0xb8
	private static DelegateBridge __Hotfix0__JumpToRoguelikeByTopicId; // 0xc0
	private static DelegateBridge __Hotfix0__JumpToSandboxPerm; // 0xc8
	private static DelegateBridge __Hotfix1__JumpToSandboxPerm; // 0xd0
	private static DelegateBridge __Hotfix0__JumpToSandboxPermByTopicId; // 0xd8
	private static DelegateBridge __Hotfix0__JumpToCampaignWeekly; // 0xe0
	private static DelegateBridge __Hotfix0__JumpToCampaignStage; // 0xe8
	private static DelegateBridge __Hotfix0__JumpToClimbTowerStage; // 0xf0
	private static DelegateBridge __Hotfix0__JumpToCrisisV2Stage; // 0xf8
	private static DelegateBridge __Hotfix1__JumpToCrisisV2Stage; // 0x100
	private static DelegateBridge __Hotfix0__JumpToActivity; // 0x108
	private static DelegateBridge __Hotfix0__JumpToStageActivity; // 0x110
	private static DelegateBridge __Hotfix0__JumpToPageEntryActivity; // 0x118
	private static DelegateBridge __Hotfix0__ExitYieldToActivity; // 0x120
	private static DelegateBridge _c__Hotfix0_ctor; // 0x128


	// RVA: 0x2fb4c4c VA: 0x75955ccc4c
	private Void _InitIfNot() { }
	// RVA: 0x2fb5018 VA: 0x75955cd018
	protected override Void OnEnter() { }
	// RVA: 0x2fb53a0 VA: 0x75955cd3a0
	protected override Void OnDataUpdated(ZoneGroupViewProperty prop) { }
	// RVA: 0x2fb5428 VA: 0x75955cd428
	protected override IEnumerator EnterYieldInstruction() { }
	// RVA: 0x2fb54fc VA: 0x75955cd4fc
	protected override Void CancelEnter() { }
	// RVA: 0x2fb5564 VA: 0x75955cd564
	protected override IEnumerator ExitYieldInstruction() { }
	// RVA: 0x2fb5700 VA: 0x75955cd700
	protected override Void CancelExit() { }
	// RVA: 0x2fb5804 VA: 0x75955cd804
	private Void Update() { }
	// RVA: 0x2fb597c VA: 0x75955cd97c
	private Void _OnScalerChanged(CanvasScaler scaler) { }
	// RVA: 0x2fb5aec VA: 0x75955cdaec
	private Void _OnEntryClicked(ZoneHomeEntryItemModel entryModel) { }
	// RVA: 0x2fb6298 VA: 0x75955ce298
	private Void _OnToDoClicked(ZoneHomeToDoItemModel todoModel) { }
	// RVA: 0x2fb69f8 VA: 0x75955ce9f8
	private Void _OnRecentViewClicked() { }
	// RVA: 0x2fb6c24 VA: 0x75955cec24
	private Void _JumpToRecentDefault(String stageId) { }
	// RVA: 0x2fb58b0 VA: 0x75955cd8b0
	private Void _OnCrisisDataFetched() { }
	// RVA: 0x2fb5090 VA: 0x75955cd090
	private Void _UpdateData() { }
	// RVA: 0x2fb5770 VA: 0x75955cd770
	private Void _CancelExitTween() { }
	// RVA: 0x2fb6f80 VA: 0x75955cef80
	private Void _CancelEnterTweens() { }
	// RVA: 0x2fb6ed0 VA: 0x75955ceed0
	private Void _StartRequestForCrisisData() { }
	// RVA: 0x2fb6e10 VA: 0x75955cee10
	private CrisisV2ServerDataWrapper _GetValidCrisisData() { }
	// RVA: 0x2fb5a40 VA: 0x75955cda40
	private IEnumerator _UpdateLayoutCoroutine() { }
	// RVA: 0x2fb5c68 VA: 0x75955cdc68
	private static Boolean _CheckIfEntryLocked(ZoneHomeEntryItemModel model) { }
	// RVA: 0x2fb5d38 VA: 0x75955cdd38
	private Void _JumpToMainlineZone(ZoneHomeEntryItemModel entryModel) { }
	// RVA: 0x2fb60c8 VA: 0x75955ce0c8
	private Void _JumpToRoguelike(ZoneHomeEntryItemModel entryModel) { }
	// RVA: 0x2fb66c0 VA: 0x75955ce6c0
	private Void _JumpToRoguelike(ZoneHomeToDoItemModel todoModel) { }
	// RVA: 0x2fb70cc VA: 0x75955cf0cc
	private Void _JumpToRoguelikeByTopicId(String topicId) { }
	// RVA: 0x2fb61b0 VA: 0x75955ce1b0
	private Void _JumpToSandboxPerm(ZoneHomeEntryItemModel itemModel) { }
	// RVA: 0x2fb690c VA: 0x75955ce90c
	private Void _JumpToSandboxPerm(ZoneHomeToDoItemModel todoModel) { }
	// RVA: 0x2fb7190 VA: 0x75955cf190
	private Void _JumpToSandboxPermByTopicId(String topicId) { }
	// RVA: 0x2fb63fc VA: 0x75955ce3fc
	private Void _JumpToCampaignWeekly(ZoneHomeToDoItemModel itemModel) { }
	// RVA: 0x2fb6b00 VA: 0x75955ceb00
	private Void _JumpToCampaignStage(String stageId) { }
	// RVA: 0x2fb67c0 VA: 0x75955ce7c0
	private Void _JumpToClimbTowerStage(ZoneHomeToDoItemModel todoModel) { }
	// RVA: 0x2fb6578 VA: 0x75955ce578
	private Void _JumpToCrisisV2Stage(ZoneHomeToDoItemModel todoModel) { }
	// RVA: 0x2fb5e4c VA: 0x75955cde4c
	private Void _JumpToCrisisV2Stage(ZoneHomeEntryItemModel entryModel) { }
	// RVA: 0x2fb5f9c VA: 0x75955cdf9c
	private Void _JumpToActivity(ZoneHomeEntryItemModel entryModel) { }
	// RVA: 0x2fb7404 VA: 0x75955cf404
	private Void _JumpToStageActivity(String actId) { }
	// RVA: 0x2fb7274 VA: 0x75955cf274
	private Void _JumpToPageEntryActivity(String actId) { }
	// RVA: 0x2fb5654 VA: 0x75955cd654
	private IEnumerator _ExitYieldToActivity() { }
	// RVA: 0x2fb74c8 VA: 0x75955cf4c8
	public Void .ctor() { }
	// RVA: 0x2fb76b4 VA: 0x75955cf6b4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2fb76b8 VA: 0x75955cf6b8
	private Void <>xLuaBaseProxy_OnDataUpdated(ZoneGroupViewProperty P0) { }
	// RVA: 0x2fb76bc VA: 0x75955cf6bc
	private IEnumerator <>xLuaBaseProxy_EnterYieldInstruction() { }
	// RVA: 0x2fb76c0 VA: 0x75955cf6c0
	private Void <>xLuaBaseProxy_CancelEnter() { }
	// RVA: 0x2fb76c4 VA: 0x75955cf6c4
	private IEnumerator <>xLuaBaseProxy_ExitYieldInstruction() { }
	// RVA: 0x2fb76c8 VA: 0x75955cf6c8
	private Void <>xLuaBaseProxy_CancelExit() { }
}
```
# TemplateMissionCommonViewController

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `Transform _bigRewardViewContainer`

- `Transform _missionTitleViewContainer`

- `Transform _coinInfoViewContainer`

- `Transform _missionListViewContainer`

- `Transform _bgViewContainer`

- `SkinPreviewPanel _previewPanelPrefab`

- `Transform _previewPanelContainer`

- `TemplateMissionBigRewardView m_bigRewardView`

- `TemplateMissionTitleView m_titleView`

- `TemplateMissionCoinInfoView m_coinInfoView`

- `TemplateMissionListView m_listView`

- `TemplateMissionBgView m_bgView`

- `TemplateMissionCustomResHolder m_customResHolder`

- `TemplateMissionCustomViewHolder m_customViewHolder`

- `SkinPreviewPanel m_previewPanel`

- `Boolean m_isInited`

- `TemplateMissionState m_bindState`

- `UIPageFinder m_pageFinder`

- `Sequence m_viewTweenSequence`

- `TemplateMissionInputParam m_inputParam`


## Methods

- `Void _InitIfNot(TemplateMissionInputParam)`

- `Void _InitTopMenuPart()`

- `Void _InstViews(TemplateMissionInputParam)`

- `Void _InitCustomResHolder(TemplateMissionInputParam)`

- `Void _InitCustomViewHolder(TemplateMissionInputParam)`

- `T _InstView(T, Transform)`

- `Void _InitData(TemplateMissionInputParam)`

- `Void _BindPropToViews()`

- `Boolean _CheckIfCanReact()`

- `Void _EventOnBackClick()`

- `Void _EventOnCharDetailClick(String)`

- `Void _EventOnClaimAllClick()`

- `Void _EventOnMissionItemClick(TemplateMissionListNormalItemViewModel)`

- `Void _EventOnSkinDetailBtnClicked(CharUISkinStruct)`

- `Void _OnConfirmCallBack(List`1)`

- `Void _OnActConfirmAllMissionServiceSuccess(TemplateMissionCommonConfirmResponse)`

- `Void _OnActConfirmMissionServiceSuccess(TemplateMissionCommonConfirmResponse)`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void <_InitTopMenuPart>b__33_0(GameObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionCommonViewController : AbstractTemplateMissionViewController
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x18
	private Transform _bigRewardViewContainer; // 0x20
	private Transform _missionTitleViewContainer; // 0x28
	private Transform _coinInfoViewContainer; // 0x30
	private Transform _missionListViewContainer; // 0x38
	private Transform _bgViewContainer; // 0x40
	private SkinPreviewPanel _previewPanelPrefab; // 0x48
	private Transform _previewPanelContainer; // 0x50
	private TemplateMissionBigRewardView m_bigRewardView; // 0x58
	private TemplateMissionTitleView m_titleView; // 0x60
	private TemplateMissionCoinInfoView m_coinInfoView; // 0x68
	private TemplateMissionListView m_listView; // 0x70
	private TemplateMissionBgView m_bgView; // 0x78
	private TemplateMissionCustomResHolder m_customResHolder; // 0x80
	private TemplateMissionCustomViewHolder m_customViewHolder; // 0x88
	private SkinPreviewPanel m_previewPanel; // 0x90
	private Boolean m_isInited; // 0x98
	private List`1 m_views; // 0xa0
	private TemplateMissionState m_bindState; // 0xa8
	private UIPageFinder m_pageFinder; // 0xb0
	private Sequence m_viewTweenSequence; // 0xc0
	private TemplateMissionInputParam m_inputParam; // 0xc8
	public const Int32 MSG_CHAR_DETAIL_CLICKED; // 0x0
	public const Int32 MSG_CLAIM_ALL_BTN_CLICKED; // 0x0
	public const Int32 MSG_MISSION_ITEM_CLICKED; // 0x0
	public const Int32 MSG_SKIN_DETAIL_BTN_CLICKED; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnStateResume; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0_BindState; // 0x18
	private static DelegateBridge __Hotfix0_ResetEntryTween; // 0x20
	private static DelegateBridge __Hotfix0_PlayEntryTween; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__InitTopMenuPart; // 0x38
	private static DelegateBridge __Hotfix0__InstViews; // 0x40
	private static DelegateBridge __Hotfix0__InitCustomResHolder; // 0x48
	private static DelegateBridge __Hotfix0__InitCustomViewHolder; // 0x50
	private static DelegateBridge __Hotfix0__InstView; // 0x58
	private static DelegateBridge __Hotfix0__InitData; // 0x60
	private static DelegateBridge __Hotfix0__BindPropToViews; // 0x68
	private static DelegateBridge __Hotfix0__CheckIfCanReact; // 0x70
	private static DelegateBridge __Hotfix0__EventOnBackClick; // 0x78
	private static DelegateBridge __Hotfix0__EventOnCharDetailClick; // 0x80
	private static DelegateBridge __Hotfix0__EventOnClaimAllClick; // 0x88
	private static DelegateBridge __Hotfix0__EventOnMissionItemClick; // 0x90
	private static DelegateBridge __Hotfix0__EventOnSkinDetailBtnClicked; // 0x98
	private static DelegateBridge __Hotfix0__OnConfirmCallBack; // 0xa0
	private static DelegateBridge __Hotfix0__OnActConfirmAllMissionServiceSuccess; // 0xa8
	private static DelegateBridge __Hotfix0__OnActConfirmMissionServiceSuccess; // 0xb0
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0


	// RVA: 0x23629e4 VA: 0x759497a9e4
	public override Void OnInit(TemplateMissionInputParam inputParam) { }
	// RVA: 0x2362cac VA: 0x759497acac
	public override Void OnStateResume() { }
	// RVA: 0x2362d10 VA: 0x759497ad10
	public override Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2363674 VA: 0x759497b674
	public override Void BindState(TemplateMissionState state) { }
	// RVA: 0x23636f8 VA: 0x759497b6f8
	public override Void ResetEntryTween() { }
	// RVA: 0x2363860 VA: 0x759497b860
	public override IEnumerator PlayEntryTween() { }
	// RVA: 0x2362a94 VA: 0x759497aa94
	private Void _InitIfNot(TemplateMissionInputParam inputParam) { }
	// RVA: 0x2363934 VA: 0x759497b934
	private Void _InitTopMenuPart() { }
	// RVA: 0x2363c78 VA: 0x759497bc78
	private Void _InstViews(TemplateMissionInputParam inputParam) { }
	// RVA: 0x23639f8 VA: 0x759497b9f8
	private Void _InitCustomResHolder(TemplateMissionInputParam inputParam) { }
	// RVA: 0x2363b98 VA: 0x759497bb98
	private Void _InitCustomViewHolder(TemplateMissionInputParam inputParam) { }
	// RVA: 0x VA: 0x0
	private T _InstView(T prefab, Transform container) { }
	// RVA: 0x2362b5c VA: 0x759497ab5c
	private Void _InitData(TemplateMissionInputParam inputParam) { }
	// RVA: 0x2363ff8 VA: 0x759497bff8
	private Void _BindPropToViews() { }
	// RVA: 0x2364188 VA: 0x759497c188
	private Boolean _CheckIfCanReact() { }
	// RVA: 0x236436c VA: 0x759497c36c
	private Void _EventOnBackClick() { }
	// RVA: 0x2362eb4 VA: 0x759497aeb4
	private Void _EventOnCharDetailClick(String charId) { }
	// RVA: 0x2362fd4 VA: 0x759497afd4
	private Void _EventOnClaimAllClick() { }
	// RVA: 0x2363210 VA: 0x759497b210
	private Void _EventOnMissionItemClick(TemplateMissionListNormalItemViewModel missionModel) { }
	// RVA: 0x2363468 VA: 0x759497b468
	private Void _EventOnSkinDetailBtnClicked(CharUISkinStruct skinStruct) { }
	// RVA: 0x23643f8 VA: 0x759497c3f8
	private Void _OnConfirmCallBack(List`1 rewardList) { }
	// RVA: 0x2364634 VA: 0x759497c634
	private Void _OnActConfirmAllMissionServiceSuccess(TemplateMissionCommonConfirmResponse response) { }
	// RVA: 0x23646bc VA: 0x759497c6bc
	private Void _OnActConfirmMissionServiceSuccess(TemplateMissionCommonConfirmResponse response) { }
	// RVA: 0x2364574 VA: 0x759497c574
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x236476c VA: 0x759497c76c
	public Void .ctor() { }
	// RVA: 0x236482c VA: 0x759497c82c
	private Void <_InitTopMenuPart>b__33_0(GameObject gameObj) { }
}
```
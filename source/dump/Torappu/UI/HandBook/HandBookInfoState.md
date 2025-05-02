# HandBookInfoState

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookInfoStateBean _stateBean`

- `HandBookInfoView _infoView`

- `UICommonTrackPoint _avgTrackPoint`

- `UICommonTrackPoint _stageTrackPoint`

- `UICommonTrackPoint _newVoiceTrackPoint`

- `GameObject _infoButton`

- `UIPointClickListener _pointSpreadIllustClicked`

- `CharacterInfoIllustSpreadPanel _spreadPanel`

- `UIAnimationLocation _enterFromCharInfo`

- `UIAnimationLocation _enterOtherwise`

- `HandBookVoiceLangView _voiceLangView`

- `HandBookDesignerView _designerView`

- `HandBookInfoStageView _lockedStageView`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `Boolean m_flag`

- `String m_cacheStoryId`

- `Boolean m_inited`

- `HandBookVoiceLangView m_voiceLangView`

- `HandBookInfoStageView m_lockedStageView`

- `HandBookDesignerView m_designerView`

- `UnityEvent _onIllustrationSpread`

- `UIAnimationLocation _illustSpreadAnim`

- `UnityEvent _unspreadIllustEvent`

- `Boolean m_isIllustAnimating`


## Methods

- `Void _InitIfNot()`

- `Void OnSwitchIllustrationClicked()`

- `Boolean _LockIllustAnimation(Single)`

- `IEnumerator _UnlockIllustAnimCoroutine(Single)`

- `Void _RefreshState()`

- `Void EventOnBackToSlider()`

- `Void EventOnStageLocked()`

- `Void EventOnStageDetailLocked()`

- `Void EventOnButtonCharacterInfo()`

- `Void OnUnspreadIllustrationClicked()`

- `Void OnSpreadIllustrationClicked()`

- `Void OnVoiceLangBtnClick()`

- `Void OnDesignerBtnClick()`

- `UIAnimationLocation _PickAnimation(TransactionContext)`

- `Void _ShowCharacterInfo(Int32)`

- `Void OnCollectionRequest(String)`

- `Void _ReloadHandBookInfo(HandBookCardViewModel)`

- `Void _RefreshVoiceLangInfo()`

- `Void _OnIllustSpread()`

- `Void _OnIllustUnspread()`

- `Void _OnAvgItemClicked(String)`

- `Void _OnVoiceLangItemClicked(VoiceLangType)`

- `Void _SendChangeRogueNpcVoiceLangReq(VoiceLangType)`

- `Void _SetCharVoiceLangReq(VoiceLangType)`

- `Void _OnSetVoiceLangSuc()`

- `Void _UpdateNewVoiceVisited()`

- `Void _SetTopMenuActive(Boolean)`

- `Boolean _IsDuringTransiting()`

- `Void _StopAudios()`

- `Void _OpenUnlockStoryPage()`

- `Void <_InitIfNot>b__21_0(GameObject)`

- `Void <RegisterFromDataListener>b__48_0(IStateBean)`

- `Void <_SendChangeRogueNpcVoiceLangReq>b__55_0(ChangeRogueNpcVoiceLanResponse)`

- `Void <_SetCharVoiceLangReq>b__56_0(SetCharVoiceLanResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoState : PopupFadeState
{
	private HandBookInfoStateBean _stateBean; // 0x70
	private HandBookInfoView _infoView; // 0x78
	private UICommonTrackPoint _avgTrackPoint; // 0x80
	private UICommonTrackPoint _stageTrackPoint; // 0x88
	private UICommonTrackPoint _newVoiceTrackPoint; // 0x90
	private GameObject _infoButton; // 0x98
	private UIPointClickListener _pointSpreadIllustClicked; // 0xa0
	private CharacterInfoIllustSpreadPanel _spreadPanel; // 0xa8
	private UIAnimationLocation _enterFromCharInfo; // 0xb0
	private UIAnimationLocation _enterOtherwise; // 0xc0
	private HandBookVoiceLangView _voiceLangView; // 0xd0
	private HandBookDesignerView _designerView; // 0xd8
	private HandBookInfoStageView _lockedStageView; // 0xe0
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0xe8
	private Boolean m_flag; // 0xf0
	private String m_cacheStoryId; // 0xf8
	private Boolean m_inited; // 0x100
	private HandBookVoiceLangView m_voiceLangView; // 0x108
	private HandBookInfoStageView m_lockedStageView; // 0x110
	private HandBookDesignerView m_designerView; // 0x118
	private UnityEvent _onIllustrationSpread; // 0x120
	private UIAnimationLocation _illustSpreadAnim; // 0x128
	private UnityEvent _unspreadIllustEvent; // 0x138
	private Boolean m_isIllustAnimating; // 0x140
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0_OnSwitchIllustrationClicked; // 0x20
	private static DelegateBridge __Hotfix0__LockIllustAnimation; // 0x28
	private static DelegateBridge __Hotfix0__UnlockIllustAnimCoroutine; // 0x30
	private static DelegateBridge __Hotfix0__RefreshState; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBackToSlider; // 0x40
	private static DelegateBridge __Hotfix0_EventOnStageLocked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnStageDetailLocked; // 0x50
	private static DelegateBridge __Hotfix0_EventOnButtonCharacterInfo; // 0x58
	private static DelegateBridge __Hotfix0_OnUnspreadIllustrationClicked; // 0x60
	private static DelegateBridge __Hotfix0_OnSpreadIllustrationClicked; // 0x68
	private static DelegateBridge __Hotfix0_OnVoiceLangBtnClick; // 0x70
	private static DelegateBridge __Hotfix0_OnDesignerBtnClick; // 0x78
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x80
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x88
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x90
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x98
	private static DelegateBridge __Hotfix0__PickAnimation; // 0xa0
	private static DelegateBridge __Hotfix0__ShowCharacterInfo; // 0xa8
	private static DelegateBridge __Hotfix0_OnCollectionRequest; // 0xb0
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0xb8
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0xc0
	private static DelegateBridge __Hotfix0__ReloadHandBookInfo; // 0xc8
	private static DelegateBridge __Hotfix0__RefreshVoiceLangInfo; // 0xd0
	private static DelegateBridge __Hotfix0__OnIllustSpread; // 0xd8
	private static DelegateBridge __Hotfix0__OnIllustUnspread; // 0xe0
	private static DelegateBridge __Hotfix0__OnAvgItemClicked; // 0xe8
	private static DelegateBridge __Hotfix0__OnVoiceLangItemClicked; // 0xf0
	private static DelegateBridge __Hotfix0__SendChangeRogueNpcVoiceLangReq; // 0xf8
	private static DelegateBridge __Hotfix0__SetCharVoiceLangReq; // 0x100
	private static DelegateBridge __Hotfix0__OnSetVoiceLangSuc; // 0x108
	private static DelegateBridge __Hotfix0__UpdateNewVoiceVisited; // 0x110
	private static DelegateBridge __Hotfix0__SetTopMenuActive; // 0x118
	private static DelegateBridge __Hotfix0__IsDuringTransiting; // 0x120
	private static DelegateBridge __Hotfix0__StopAudios; // 0x128
	private static DelegateBridge __Hotfix0__OpenUnlockStoryPage; // 0x130
	private static DelegateBridge _c__Hotfix0_ctor; // 0x138


	// RVA: 0x2ea1984 VA: 0x75954b9984
	protected override Void OnEnter() { }
	// RVA: 0x2ea1c64 VA: 0x75954b9c64
	private Void _InitIfNot() { }
	// RVA: 0x2ea1fe0 VA: 0x75954b9fe0
	protected override Void OnResume() { }
	// RVA: 0x2ea3958 VA: 0x75954bb958
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ea39c0 VA: 0x75954bb9c0
	public Void OnSwitchIllustrationClicked() { }
	// RVA: 0x2ea3a24 VA: 0x75954bba24
	private Boolean _LockIllustAnimation(Single duration) { }
	// RVA: 0x2ea3ad4 VA: 0x75954bbad4
	private IEnumerator _UnlockIllustAnimCoroutine(Single duration) { }
	// RVA: 0x2ea1ed4 VA: 0x75954b9ed4
	private Void _RefreshState() { }
	// RVA: 0x2ea3cdc VA: 0x75954bbcdc
	public Void EventOnBackToSlider() { }
	// RVA: 0x2ea3d50 VA: 0x75954bbd50
	public Void EventOnStageLocked() { }
	// RVA: 0x2ea3f78 VA: 0x75954bbf78
	public Void EventOnStageDetailLocked() { }
	// RVA: 0x2ea4230 VA: 0x75954bc230
	public Void EventOnButtonCharacterInfo() { }
	// RVA: 0x2ea4410 VA: 0x75954bc410
	public Void OnUnspreadIllustrationClicked() { }
	// RVA: 0x2ea46bc VA: 0x75954bc6bc
	public Void OnSpreadIllustrationClicked() { }
	// RVA: 0x2ea4900 VA: 0x75954bc900
	public Void OnVoiceLangBtnClick() { }
	// RVA: 0x2ea4b28 VA: 0x75954bcb28
	public Void OnDesignerBtnClick() { }
	// RVA: 0x2ea4c80 VA: 0x75954bcc80
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2ea4e14 VA: 0x75954bce14
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2ea4fa8 VA: 0x75954bcfa8
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2ea523c VA: 0x75954bd23c
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2ea50e4 VA: 0x75954bd0e4
	private UIAnimationLocation _PickAnimation(TransactionContext context) { }
	// RVA: 0x2ea42b0 VA: 0x75954bc2b0
	private Void _ShowCharacterInfo(Int32 chrInstId) { }
	// RVA: 0x2ea5380 VA: 0x75954bd380
	public Void OnCollectionRequest(String id) { }
	// RVA: 0x2ea55f0 VA: 0x75954bd5f0
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2ea5668 VA: 0x75954bd668
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2ea3bc0 VA: 0x75954bbbc0
	private Void _ReloadHandBookInfo(HandBookCardViewModel newCardModel) { }
	// RVA: 0x2ea5d80 VA: 0x75954bdd80
	private Void _RefreshVoiceLangInfo() { }
	// RVA: 0x2ea4880 VA: 0x75954bc880
	private Void _OnIllustSpread() { }
	// RVA: 0x2ea4638 VA: 0x75954bc638
	private Void _OnIllustUnspread() { }
	// RVA: 0x2ea5e00 VA: 0x75954bde00
	private Void _OnAvgItemClicked(String storyId) { }
	// RVA: 0x2ea6144 VA: 0x75954be144
	private Void _OnVoiceLangItemClicked(VoiceLangType voiceLangType) { }
	// RVA: 0x2ea6228 VA: 0x75954be228
	private Void _SendChangeRogueNpcVoiceLangReq(VoiceLangType voiceLangType) { }
	// RVA: 0x2ea6428 VA: 0x75954be428
	private Void _SetCharVoiceLangReq(VoiceLangType voiceLangType) { }
	// RVA: 0x2ea6658 VA: 0x75954be658
	private Void _OnSetVoiceLangSuc() { }
	// RVA: 0x2ea4a34 VA: 0x75954bca34
	private Void _UpdateNewVoiceVisited() { }
	// RVA: 0x2ea21ac VA: 0x75954ba1ac
	private Void _SetTopMenuActive(Boolean isActive) { }
	// RVA: 0x2ea4534 VA: 0x75954bc534
	private Boolean _IsDuringTransiting() { }
	// RVA: 0x2ea47d4 VA: 0x75954bc7d4
	private Void _StopAudios() { }
	// RVA: 0x2ea68f0 VA: 0x75954be8f0
	private Void _OpenUnlockStoryPage() { }
	// RVA: 0x2ea6adc VA: 0x75954beadc
	public Void .ctor() { }
	// RVA: 0x2ea6b4c VA: 0x75954beb4c
	private Void <_InitIfNot>b__21_0(GameObject inst) { }
	// RVA: 0x2ea6c3c VA: 0x75954bec3c
	private Void <RegisterFromDataListener>b__48_0(IStateBean stateBean) { }
	// RVA: 0x2ea6d54 VA: 0x75954bed54
	private Void <_SendChangeRogueNpcVoiceLangReq>b__55_0(ChangeRogueNpcVoiceLanResponse response) { }
	// RVA: 0x2ea6d58 VA: 0x75954bed58
	private Void <_SetCharVoiceLangReq>b__56_0(SetCharVoiceLanResponse response) { }
	// RVA: 0x2ea6d5c VA: 0x75954bed5c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ea6d64 VA: 0x75954bed64
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2ea6d6c VA: 0x75954bed6c
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x2ea6d94 VA: 0x75954bed94
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x2ea6dbc VA: 0x75954bedbc
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
	// RVA: 0x2ea6de4 VA: 0x75954bede4
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
	// RVA: 0x2ea6e0c VA: 0x75954bee0c
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2ea6e14 VA: 0x75954bee14
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```
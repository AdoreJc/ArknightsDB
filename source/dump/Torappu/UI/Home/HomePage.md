# HomePage

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeMainStateBean _homeStateBean`

- `AutoPopupController m_autoPopupController`

- `Boolean m_isHomeShowAnimPlaying`

- `UIBlocker m_homeShowAnimblocker`

- `Boolean m_playDynEntranceWhenRouted`


## Properties

- `AutoPopupController autoPopupController`


## Methods

- `AutoPopupController get_autoPopupController()`

- `Boolean IsInitialState()`

- `Boolean IsStateTransiting()`

- `Void TryEnterHomeCommonActivity(String, DataBundle)`

- `Void RouteToCrisisV2Stage()`

- `Void RouteToRoguelike(String)`

- `Void PlayHomeMusic(String)`

- `Void ResetHomeMusicToConfig()`

- `Void BackToLastStateOrIllustPage()`

- `Void _BackToLastStateOrCertainPage(String)`

- `IEnumerator _BackToInitStateAndOpenPageCoroutine(String)`

- `Boolean _IsNotResetToDefaultHomeState()`

- `Void _MarkPlayDynEntranceWhenRouted(Boolean, Boolean)`

- `IEnumerator _PlayHomeShowAnim()`

- `IEnumerator _PlayDynEntrance(Param)`

- `IEnumerator _CoroutineOnPageRouted()`

- `Void _AfterHomePageRouted()`

- `IEnumerator _CoroutinePlayDynEntrance(CharUISkinStruct, Boolean)`

- `Void PlayDynEntrance(CharUISkinStruct, Boolean)`

- `Void _OnRouteFromNonPluginPage(Boolean)`

- `Boolean _CheckIfFromPluginPage()`

- `Boolean _CanShowExitGameDialog()`

- `Boolean _InitHomeStateFromParam(Params)`

- `IEnumerator _TryOpenIllustEditStateCoroutine()`

- `IEnumerator _TryOpenInitHomeActivityCoroutine(String, DataBundle)`

- `IEnumerator _TryOpenReplaceableStateCoroutine(Boolean)`

- `IEnumerator _JumpToCharRotationRelateState()`

- `CharWordData TryLoadRandomIllustText()`

- `Void _InitHomeMusic()`

- `Void _ModifyHomeMusicChunk(String)`

- `Void _JumpToRoguelikeEntryView(String)`

- `Void _JumpToRoguelikeTabView(String)`

- `Void OnDisable()`

- `IEnumerator <>n__0(Boolean)`

- `Void <_PlayDynEntrance>b__30_0(CharUISkinStruct)`

- `Void <_PlayDynEntrance>b__30_1(CharUISkinStruct)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `AVGPageKey <>xLuaBaseProxy_get_avgPage()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_OnPageReservedDuringReset(UIPageStackParam)`

- `Void <>xLuaBaseProxy_OnPageRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomePage : StateEnginePage
{
	private static readonly ListSet`1 PLUGIN_PAGES; // 0x0
	private HomeMainStateBean _homeStateBean; // 0xe8
	private AutoPopupController m_autoPopupController; // 0xf0
	private Boolean m_isHomeShowAnimPlaying; // 0xf8
	private UIBlocker m_homeShowAnimblocker; // 0x100
	private Boolean m_playDynEntranceWhenRouted; // 0x108
	private static DelegateBridge __Hotfix0_get_autoPopupController; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_OnStart; // 0x18
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x20
	private static DelegateBridge __Hotfix0_IsInitialState; // 0x28
	private static DelegateBridge __Hotfix0_IsStateTransiting; // 0x30
	private static DelegateBridge __Hotfix0_TryEnterHomeCommonActivity; // 0x38
	private static DelegateBridge __Hotfix0_RouteToCrisisV2Stage; // 0x40
	private static DelegateBridge __Hotfix0_RouteToRoguelike; // 0x48
	private static DelegateBridge __Hotfix0_PlayHomeMusic; // 0x50
	private static DelegateBridge __Hotfix0_ResetHomeMusicToConfig; // 0x58
	private static DelegateBridge __Hotfix0_BackToLastStateOrIllustPage; // 0x60
	private static DelegateBridge __Hotfix0__BackToLastStateOrCertainPage; // 0x68
	private static DelegateBridge __Hotfix0__BackToInitStateAndOpenPageCoroutine; // 0x70
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x78
	private static DelegateBridge __Hotfix0_OnPageReservedDuringReset; // 0x80
	private static DelegateBridge __Hotfix0__IsNotResetToDefaultHomeState; // 0x88
	private static DelegateBridge __Hotfix0__MarkPlayDynEntranceWhenRouted; // 0x90
	private static DelegateBridge __Hotfix0__PlayHomeShowAnim; // 0x98
	private static DelegateBridge __Hotfix0__PlayDynEntrance; // 0xa0
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0xa8
	private static DelegateBridge __Hotfix0__CoroutineOnPageRouted; // 0xb0
	private static DelegateBridge __Hotfix0__AfterHomePageRouted; // 0xb8
	private static DelegateBridge __Hotfix0__CoroutinePlayDynEntrance; // 0xc0
	private static DelegateBridge __Hotfix0_PlayDynEntrance; // 0xc8
	private static DelegateBridge __Hotfix0__OnRouteFromNonPluginPage; // 0xd0
	private static DelegateBridge __Hotfix0__CheckIfFromPluginPage; // 0xd8
	private static DelegateBridge __Hotfix0__CanShowExitGameDialog; // 0xe0
	private static DelegateBridge __Hotfix0__ShowExitGameDialog; // 0xe8
	private static DelegateBridge __Hotfix0__InitHomeStateFromParam; // 0xf0
	private static DelegateBridge __Hotfix0__TryOpenIllustEditStateCoroutine; // 0xf8
	private static DelegateBridge __Hotfix0__TryOpenInitHomeActivityCoroutine; // 0x100
	private static DelegateBridge __Hotfix0__TryOpenReplaceableStateCoroutine; // 0x108
	private static DelegateBridge __Hotfix0__JumpToCharRotationRelateState; // 0x110
	private static DelegateBridge __Hotfix0_TryLoadRandomIllustText; // 0x118
	private static DelegateBridge __Hotfix0__InitHomeMusic; // 0x120
	private static DelegateBridge __Hotfix0__ModifyHomeMusicChunk; // 0x128
	private static DelegateBridge __Hotfix0__GetMusicIdFromSelectedBkg; // 0x130
	private static DelegateBridge __Hotfix0__JumpToRoguelikeEntryView; // 0x138
	private static DelegateBridge __Hotfix0__JumpToRoguelikeTabView; // 0x140
	private static DelegateBridge __Hotfix0_OnDisable; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150

	public AutoPopupController autoPopupController { get; }
	public override AVGPageKey avgPage { get; }

	// RVA: 0x27d86a0 VA: 0x7594df06a0
	public AutoPopupController get_autoPopupController() { }
	// RVA: 0x27d8718 VA: 0x7594df0718
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x27d8898 VA: 0x7594df0898
	protected override Void OnStart() { }
	// RVA: 0x27d8a38 VA: 0x7594df0a38
	public override AVGPageKey get_avgPage() { }
	// RVA: 0x27d8ab0 VA: 0x7594df0ab0
	public Boolean IsInitialState() { }
	// RVA: 0x27d8bdc VA: 0x7594df0bdc
	public Boolean IsStateTransiting() { }
	// RVA: 0x27d8cc4 VA: 0x7594df0cc4
	public Void TryEnterHomeCommonActivity(String funcActId, DataBundle actMeta) { }
	// RVA: 0x27d8e10 VA: 0x7594df0e10
	public Void RouteToCrisisV2Stage() { }
	// RVA: 0x27d91c0 VA: 0x7594df11c0
	public Void RouteToRoguelike(String topicId) { }
	// RVA: 0x27d9730 VA: 0x7594df1730
	public Void PlayHomeMusic(String musicId) { }
	// RVA: 0x27d98b8 VA: 0x7594df18b8
	public Void ResetHomeMusicToConfig() { }
	// RVA: 0x27d995c VA: 0x7594df195c
	public Void BackToLastStateOrIllustPage() { }
	// RVA: 0x27d99ec VA: 0x7594df19ec
	private Void _BackToLastStateOrCertainPage(String pageName) { }
	// RVA: 0x27d9b0c VA: 0x7594df1b0c
	private IEnumerator _BackToInitStateAndOpenPageCoroutine(String pageName) { }
	// RVA: 0x27d9c14 VA: 0x7594df1c14
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x27d9d14 VA: 0x7594df1d14
	protected override IEnumerator OnPageReservedDuringReset(UIPageStackParam param) { }
	// RVA: 0x27d9e40 VA: 0x7594df1e40
	private Boolean _IsNotResetToDefaultHomeState() { }
	// RVA: 0x27d9ef4 VA: 0x7594df1ef4
	private Void _MarkPlayDynEntranceWhenRouted(Boolean useHomeMainState, Boolean isFromStack) { }
	// RVA: 0x27da0b8 VA: 0x7594df20b8
	private IEnumerator _PlayHomeShowAnim() { }
	// RVA: 0x27da19c VA: 0x7594df219c
	private IEnumerator _PlayDynEntrance(Param param) { }
	// RVA: 0x27da2a4 VA: 0x7594df22a4
	protected override Void OnPageRouted() { }
	// RVA: 0x27da358 VA: 0x7594df2358
	private IEnumerator _CoroutineOnPageRouted() { }
	// RVA: 0x27da414 VA: 0x7594df2414
	private Void _AfterHomePageRouted() { }
	// RVA: 0x27da754 VA: 0x7594df2754
	private IEnumerator _CoroutinePlayDynEntrance(CharUISkinStruct skin, Boolean backToMainState) { }
	// RVA: 0x27da884 VA: 0x7594df2884
	public Void PlayDynEntrance(CharUISkinStruct skin, Boolean backToMainState) { }
	// RVA: 0x27da5ec VA: 0x7594df25ec
	private Void _OnRouteFromNonPluginPage(Boolean playedDynEntranceWhenRouted) { }
	// RVA: 0x27da4dc VA: 0x7594df24dc
	private Boolean _CheckIfFromPluginPage() { }
	// RVA: 0x27da948 VA: 0x7594df2948
	private Boolean _CanShowExitGameDialog() { }
	// RVA: 0x27dab7c VA: 0x7594df2b7c
	private static Void _ShowExitGameDialog() { }
	// RVA: 0x27dada8 VA: 0x7594df2da8
	private Boolean _InitHomeStateFromParam(Params param) { }
	// RVA: 0x27db018 VA: 0x7594df3018
	private IEnumerator _TryOpenIllustEditStateCoroutine() { }
	// RVA: 0x27daf20 VA: 0x7594df2f20
	private IEnumerator _TryOpenInitHomeActivityCoroutine(String actId, DataBundle actMeta) { }
	// RVA: 0x VA: 0x0
	private IEnumerator _TryOpenReplaceableStateCoroutine(Boolean fastMode) { }
	// RVA: 0x VA: 0x0
	private IEnumerator _JumpToCharRotationRelateState() { }
	// RVA: 0x27db124 VA: 0x7594df3124
	public CharWordData TryLoadRandomIllustText() { }
	// RVA: 0x27d89a8 VA: 0x7594df09a8
	private Void _InitHomeMusic() { }
	// RVA: 0x27d97ec VA: 0x7594df17ec
	private Void _ModifyHomeMusicChunk(String musicId) { }
	// RVA: 0x27db204 VA: 0x7594df3204
	private static String _GetMusicIdFromSelectedBkg() { }
	// RVA: 0x27d9298 VA: 0x7594df1298
	private Void _JumpToRoguelikeEntryView(String topicId) { }
	// RVA: 0x27d934c VA: 0x7594df134c
	private Void _JumpToRoguelikeTabView(String topicId) { }
	// RVA: 0x27db304 VA: 0x7594df3304
	private Void OnDisable() { }
	// RVA: 0x27db3a8 VA: 0x7594df33a8
	public Void .ctor() { }
	// RVA: 0x27db4a8 VA: 0x7594df34a8
	private static Void .cctor() { }
	// RVA: 0x27db5d0 VA: 0x7594df35d0
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x27db5dc VA: 0x7594df35dc
	private Void <_PlayDynEntrance>b__30_0(CharUISkinStruct skin) { }
	// RVA: 0x27db718 VA: 0x7594df3718
	private Void <_PlayDynEntrance>b__30_1(CharUISkinStruct skin) { }
	// RVA: 0x27db854 VA: 0x7594df3854
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x27db85c VA: 0x7594df385c
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x27db864 VA: 0x7594df3864
	private AVGPageKey <>xLuaBaseProxy_get_avgPage() { }
	// RVA: 0x27db86c VA: 0x7594df386c
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x27db878 VA: 0x7594df3878
	private IEnumerator <>xLuaBaseProxy_OnPageReservedDuringReset(UIPageStackParam P0) { }
	// RVA: 0x27db8a8 VA: 0x7594df38a8
	private Void <>xLuaBaseProxy_OnPageRouted() { }
}
```
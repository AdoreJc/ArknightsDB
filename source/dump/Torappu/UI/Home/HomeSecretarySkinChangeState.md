# HomeSecretarySkinChangeState

**Namespace:** `Torappu.UI.Home`


## Fields

- `CanvasGroup _alphaFadePart`

- `CanvasGroup _alphaNormPart1`

- `CanvasGroup _alphaNormPart2`

- `RectTransform _rectBack`

- `HomeSecretarySkinChangeView _view`

- `Boolean m_isInited`

- `Int32 m_instId`

- `HomeSecretaryChangeSkinStateBean m_stateBean`

- `InputParams m_toCharChangeParams`

- `SwitchTween m_tweenFadePart`

- `SwitchTween m_tweenNormPart1`

- `SwitchTween m_tweenNormPart2`

- `HomeIllustView m_illustView`

- `DisplayHandler m_IllustDisplayHandler`


## Methods

- `Void _InitIfNot()`

- `Void _StartPreviewMode()`

- `Void _ExitPreviewMode()`

- `Boolean _IsStateStable()`

- `Void _ModifyIllustViewConfig(Boolean)`

- `Void _SyncIllustView()`

- `Void _UpdateIllustView(Boolean)`

- `Void _DisposeIllustConfig()`

- `Void OnDestroy()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnSkinItemClicked(String)`

- `Void _OnCancel()`

- `Void _SavePresetSlots()`

- `Void _CleanAllSelect()`

- `Void _OpenSelectCharState()`

- `Void _OpenIllustEditState()`

- `Void _OnFilterClicked(Object)`

- `Void _GenerateNewRotationListIfNeed(String, String)`

- `Boolean _CheckIfMatchWithPlayerData(String, List`1)`

- `Boolean <ShowEffect>b__34_0()`

- `Boolean <HideEffect>b__35_0()`

- `Void <RegisterToDataListener>b__38_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretarySkinChangeState : HomeReplaceableState, IValueMsgReceiver
{
	public const Int32 ON_SKIN_ITEM_CLICKED; // 0x0
	public const Int32 ON_CONFIRM_CLICKED; // 0x0
	public const Int32 ON_CANCEL_CLICKED; // 0x0
	public const Int32 ON_CLEAN_ALL_CLICKED; // 0x0
	public const Int32 OPEN_SELECT_CHAR_STATE; // 0x0
	public const Int32 ON_ILLUST_EDIT_CLICKED; // 0x0
	public const Int32 ON_FILTER_CLICKED; // 0x0
	private CanvasGroup _alphaFadePart; // 0x60
	private CanvasGroup _alphaNormPart1; // 0x68
	private CanvasGroup _alphaNormPart2; // 0x70
	private RectTransform _rectBack; // 0x78
	private HomeSecretarySkinChangeView _view; // 0x80
	private Boolean m_isInited; // 0x88
	private Int32 m_instId; // 0x8c
	private HomeSecretaryChangeSkinStateBean m_stateBean; // 0x90
	private InputParams m_toCharChangeParams; // 0x98
	private SwitchTween m_tweenFadePart; // 0xa8
	private SwitchTween m_tweenNormPart1; // 0xb0
	private SwitchTween m_tweenNormPart2; // 0xb8
	private HomeIllustView m_illustView; // 0xc0
	private DisplayHandler m_IllustDisplayHandler; // 0xc8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__StartPreviewMode; // 0x8
	private static DelegateBridge __Hotfix0__ExitPreviewMode; // 0x10
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x18
	private static DelegateBridge __Hotfix0__ModifyIllustViewConfig; // 0x20
	private static DelegateBridge __Hotfix0__SyncIllustView; // 0x28
	private static DelegateBridge __Hotfix0__UpdateIllustView; // 0x30
	private static DelegateBridge __Hotfix0__DisposeIllustConfig; // 0x38
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x40
	private static DelegateBridge __Hotfix0_OnEnter; // 0x48
	private static DelegateBridge __Hotfix0_OnResume; // 0x50
	private static DelegateBridge __Hotfix0_OnExit; // 0x58
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x60
	private static DelegateBridge __Hotfix0_ShowEffect; // 0x68
	private static DelegateBridge __Hotfix0_HideEffect; // 0x70
	private static DelegateBridge __Hotfix0_ShowFastMode; // 0x78
	private static DelegateBridge __Hotfix0_HideFastMode; // 0x80
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x88
	private static DelegateBridge __Hotfix0_OnMessage; // 0x90
	private static DelegateBridge __Hotfix0__OnSkinItemClicked; // 0x98
	private static DelegateBridge __Hotfix0__OnCancel; // 0xa0
	private static DelegateBridge __Hotfix0__SavePresetSlots; // 0xa8
	private static DelegateBridge __Hotfix0__CleanAllSelect; // 0xb0
	private static DelegateBridge __Hotfix0__OpenSelectCharState; // 0xb8
	private static DelegateBridge __Hotfix0__OpenIllustEditState; // 0xc0
	private static DelegateBridge __Hotfix0__OnFilterClicked; // 0xc8
	private static DelegateBridge __Hotfix0__GenerateNewRotationListIfNeed; // 0xd0
	private static DelegateBridge __Hotfix0__GetSkinListFromPlayerPreset; // 0xd8
	private static DelegateBridge __Hotfix0__CheckIfMatchWithPlayerData; // 0xe0
	private static DelegateBridge __Hotfix0__GetNewSecretarySkinId; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0


	// RVA: 0x2802344 VA: 0x7594e1a344
	private Void _InitIfNot() { }
	// RVA: 0x280257c VA: 0x7594e1a57c
	private Void _StartPreviewMode() { }
	// RVA: 0x2802670 VA: 0x7594e1a670
	private Void _ExitPreviewMode() { }
	// RVA: 0x2802794 VA: 0x7594e1a794
	private Boolean _IsStateStable() { }
	// RVA: 0x2802870 VA: 0x7594e1a870
	private Void _ModifyIllustViewConfig(Boolean show) { }
	// RVA: 0x2802998 VA: 0x7594e1a998
	private Void _SyncIllustView() { }
	// RVA: 0x2802a14 VA: 0x7594e1aa14
	private Void _UpdateIllustView(Boolean show) { }
	// RVA: 0x2802a9c VA: 0x7594e1aa9c
	private Void _DisposeIllustConfig() { }
	// RVA: 0x2802b1c VA: 0x7594e1ab1c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2802b84 VA: 0x7594e1ab84
	protected override Void OnEnter() { }
	// RVA: 0x2802cd0 VA: 0x7594e1acd0
	protected override Void OnResume() { }
	// RVA: 0x2802d48 VA: 0x7594e1ad48
	protected override Void OnExit() { }
	// RVA: 0x2802dc4 VA: 0x7594e1adc4
	protected Void OnDestroy() { }
	// RVA: 0x2802e34 VA: 0x7594e1ae34
	protected override IEnumerator ShowEffect(HomeReplaceableState extractState) { }
	// RVA: 0x2802f2c VA: 0x7594e1af2c
	protected override IEnumerator HideEffect() { }
	// RVA: 0x2803000 VA: 0x7594e1b000
	protected override Void ShowFastMode() { }
	// RVA: 0x28030b8 VA: 0x7594e1b0b8
	protected override Void HideFastMode() { }
	// RVA: 0x2803130 VA: 0x7594e1b130
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x28032a8 VA: 0x7594e1b2a8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2803400 VA: 0x7594e1b400
	private Void _OnSkinItemClicked(String skinId) { }
	// RVA: 0x2803a08 VA: 0x7594e1ba08
	private Void _OnCancel() { }
	// RVA: 0x2803534 VA: 0x7594e1b534
	private Void _SavePresetSlots() { }
	// RVA: 0x2803a94 VA: 0x7594e1ba94
	private Void _CleanAllSelect() { }
	// RVA: 0x2803b68 VA: 0x7594e1bb68
	private Void _OpenSelectCharState() { }
	// RVA: 0x2803e00 VA: 0x7594e1be00
	private Void _OpenIllustEditState() { }
	// RVA: 0x2803f18 VA: 0x7594e1bf18
	private Void _OnFilterClicked(Object objVal) { }
	// RVA: 0x2804548 VA: 0x7594e1c548
	private Void _GenerateNewRotationListIfNeed(String instId, String secretarySkinId) { }
	// RVA: 0x280465c VA: 0x7594e1c65c
	private static List`1 _GetSkinListFromPlayerPreset(String instId) { }
	// RVA: 0x2804064 VA: 0x7594e1c064
	private Boolean _CheckIfMatchWithPlayerData(String playerPresetInstId, List`1 savedPresetSlots) { }
	// RVA: 0x28042ec VA: 0x7594e1c2ec
	private static Boolean _GetNewSecretarySkinId(List`1 newSlots, String prevSecretary, out String newSecretarySkinId) { }
	// RVA: 0x2804940 VA: 0x7594e1c940
	public Void .ctor() { }
	// RVA: 0x28049ec VA: 0x7594e1c9ec
	private Boolean <ShowEffect>b__34_0() { }
	// RVA: 0x2804a40 VA: 0x7594e1ca40
	private Boolean <HideEffect>b__35_0() { }
	// RVA: 0x2804a94 VA: 0x7594e1ca94
	private Void <RegisterToDataListener>b__38_0(IStateBean stateBean) { }
	// RVA: 0x2804b9c VA: 0x7594e1cb9c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2804ba4 VA: 0x7594e1cba4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2804bac VA: 0x7594e1cbac
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2804bb4 VA: 0x7594e1cbb4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```
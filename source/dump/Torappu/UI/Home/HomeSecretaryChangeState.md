# HomeSecretaryChangeState

**Namespace:** `Torappu.UI.Home`


## Fields

- `CanvasGroup _alphaFadePart1`

- `CanvasGroup _alphaFadePart2`

- `CanvasGroup _alphaNormPart1`

- `CanvasGroup _alphaNormPart2`

- `RectTransform _rectBack`

- `HomeSecretaryChangeView _view`

- `UICharacterSortTypeGroupBinder _sortTypeBinder`

- `UICharacterStarMarkTopItemBinder _starMarkBinder`

- `UICharacterSecretarySortFilterPanelBinder _filterBinder`

- `Boolean m_isInited`

- `Int32 m_instId`

- `HomeSecretaryChangeStateBean m_stateBean`

- `SwitchTween m_tweenFadePart1`

- `SwitchTween m_tweenFadePart2`

- `SwitchTween m_tweenNormPart1`

- `SwitchTween m_tweenNormPart2`

- `InputParams m_paramToSkinChangeState`

- `HomeIllustView m_illustView`

- `DisplayHandler m_IllustDisplayHandler`


## Methods

- `Void EventOnCancelClicked()`

- `Void EventOnConfirmChangeClicked()`

- `Void EventOnFilterClick(CharacterFilterViewModel)`

- `Void EventOnSortClick(CharacterSortType)`

- `Void EventOnStarMarkToggleClick()`

- `Void EventOnCharItemClick(Int32)`

- `Void _InitIfNot()`

- `Void _StartPreviewMode()`

- `Void _ExitPreviewMode()`

- `Void _OnCancel()`

- `Void _GotoSecretarySkinChangeState()`

- `Void _ModifyIllustViewConfig(Boolean)`

- `Void _SyncIllustView()`

- `Void _UpdateIllustView(Boolean)`

- `Void _DisposeIllustConfig()`

- `Void OnDestroy()`

- `Boolean <ShowEffect>b__39_0()`

- `Boolean <HideEffect>b__40_0()`

- `Void <RegisterToDataListener>b__43_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretaryChangeState : HomeReplaceableState
{
	private CanvasGroup _alphaFadePart1; // 0x60
	private CanvasGroup _alphaFadePart2; // 0x68
	private CanvasGroup _alphaNormPart1; // 0x70
	private CanvasGroup _alphaNormPart2; // 0x78
	private RectTransform _rectBack; // 0x80
	private HomeSecretaryChangeView _view; // 0x88
	private UICharacterSortTypeGroupBinder _sortTypeBinder; // 0x90
	private UICharacterStarMarkTopItemBinder _starMarkBinder; // 0x98
	private UICharacterSecretarySortFilterPanelBinder _filterBinder; // 0xa0
	private Boolean m_isInited; // 0xa8
	private Int32 m_instId; // 0xac
	private HomeSecretaryChangeStateBean m_stateBean; // 0xb0
	private SwitchTween m_tweenFadePart1; // 0xb8
	private SwitchTween m_tweenFadePart2; // 0xc0
	private SwitchTween m_tweenNormPart1; // 0xc8
	private SwitchTween m_tweenNormPart2; // 0xd0
	private InputParams m_paramToSkinChangeState; // 0xd8
	private HomeIllustView m_illustView; // 0xf8
	private DisplayHandler m_IllustDisplayHandler; // 0x100
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0x0
	private static DelegateBridge __Hotfix0_EventOnConfirmChangeClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnFilterClick; // 0x10
	private static DelegateBridge __Hotfix0_EventOnSortClick; // 0x18
	private static DelegateBridge __Hotfix0_EventOnStarMarkToggleClick; // 0x20
	private static DelegateBridge __Hotfix0_EventOnCharItemClick; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__StartPreviewMode; // 0x38
	private static DelegateBridge __Hotfix0__ExitPreviewMode; // 0x40
	private static DelegateBridge __Hotfix0__OnCancel; // 0x48
	private static DelegateBridge __Hotfix0__GotoSecretarySkinChangeState; // 0x50
	private static DelegateBridge __Hotfix0__ModifyIllustViewConfig; // 0x58
	private static DelegateBridge __Hotfix0__SyncIllustView; // 0x60
	private static DelegateBridge __Hotfix0__UpdateIllustView; // 0x68
	private static DelegateBridge __Hotfix0__DisposeIllustConfig; // 0x70
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x78
	private static DelegateBridge __Hotfix0_OnEnter; // 0x80
	private static DelegateBridge __Hotfix0_OnResume; // 0x88
	private static DelegateBridge __Hotfix0_OnExit; // 0x90
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x98
	private static DelegateBridge __Hotfix0_ShowEffect; // 0xa0
	private static DelegateBridge __Hotfix0_HideEffect; // 0xa8
	private static DelegateBridge __Hotfix0_ShowFastMode; // 0xb0
	private static DelegateBridge __Hotfix0_HideFastMode; // 0xb8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0xc0
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0


	// RVA: 0x27ffddc VA: 0x7594e17ddc
	public Void EventOnCancelClicked() { }
	// RVA: 0x27fff64 VA: 0x7594e17f64
	public Void EventOnConfirmChangeClicked() { }
	// RVA: 0x2800334 VA: 0x7594e18334
	public Void EventOnFilterClick(CharacterFilterViewModel filterModel) { }
	// RVA: 0x28003c0 VA: 0x7594e183c0
	public Void EventOnSortClick(CharacterSortType sortType) { }
	// RVA: 0x2800450 VA: 0x7594e18450
	public Void EventOnStarMarkToggleClick() { }
	// RVA: 0x28004c4 VA: 0x7594e184c4
	public Void EventOnCharItemClick(Int32 chrInstId) { }
	// RVA: 0x2800604 VA: 0x7594e18604
	private Void _InitIfNot() { }
	// RVA: 0x2800914 VA: 0x7594e18914
	private Void _StartPreviewMode() { }
	// RVA: 0x2800b14 VA: 0x7594e18b14
	private Void _ExitPreviewMode() { }
	// RVA: 0x27ffe60 VA: 0x7594e17e60
	private Void _OnCancel() { }
	// RVA: 0x27fffe8 VA: 0x7594e17fe8
	private Void _GotoSecretarySkinChangeState() { }
	// RVA: 0x28011c0 VA: 0x7594e191c0
	private Void _ModifyIllustViewConfig(Boolean show) { }
	// RVA: 0x28012d4 VA: 0x7594e192d4
	private Void _SyncIllustView() { }
	// RVA: 0x280057c VA: 0x7594e1857c
	private Void _UpdateIllustView(Boolean show) { }
	// RVA: 0x2801350 VA: 0x7594e19350
	private Void _DisposeIllustConfig() { }
	// RVA: 0x28013d0 VA: 0x7594e193d0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2801438 VA: 0x7594e19438
	protected override Void OnEnter() { }
	// RVA: 0x2801594 VA: 0x7594e19594
	protected override Void OnResume() { }
	// RVA: 0x2801624 VA: 0x7594e19624
	protected override Void OnExit() { }
	// RVA: 0x28016a0 VA: 0x7594e196a0
	protected Void OnDestroy() { }
	// RVA: 0x2801710 VA: 0x7594e19710
	protected override IEnumerator ShowEffect(HomeReplaceableState extractState) { }
	// RVA: 0x2801808 VA: 0x7594e19808
	protected override IEnumerator HideEffect() { }
	// RVA: 0x28018dc VA: 0x7594e198dc
	protected override Void ShowFastMode() { }
	// RVA: 0x28019a8 VA: 0x7594e199a8
	protected override Void HideFastMode() { }
	// RVA: 0x2801a20 VA: 0x7594e19a20
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2801b98 VA: 0x7594e19b98
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2801c10 VA: 0x7594e19c10
	public Void .ctor() { }
	// RVA: 0x2801cbc VA: 0x7594e19cbc
	private Boolean <ShowEffect>b__39_0() { }
	// RVA: 0x2801d24 VA: 0x7594e19d24
	private Boolean <HideEffect>b__40_0() { }
	// RVA: 0x2801d8c VA: 0x7594e19d8c
	private Void <RegisterToDataListener>b__43_0(IStateBean stateBean) { }
	// RVA: 0x2801e98 VA: 0x7594e19e98
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2801ea0 VA: 0x7594e19ea0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2801ea8 VA: 0x7594e19ea8
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2801eb0 VA: 0x7594e19eb0
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2801eb8 VA: 0x7594e19eb8
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
}
```
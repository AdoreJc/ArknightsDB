# CharacterRepoHomeState

**Namespace:** `Torappu.UI.CharacterRepo`


## Fields

- `Scrollbar _charListScrollbar`

- `UIAnimationLocation _repoFilterPanelSwitchAnim`

- `UICharacterRepoSortFilterPanelBinder _sortFilterPanelBinder`

- `CharacterRepoGridGroup _charGroupView`

- `AnimationSwitchTween m_filterPanelSwitch`

- `String m_cachedPageName`

- `AsyncGameObjectLoader m_cardLoader`


## Methods

- `Void UpdateTime(Single)`

- `Void _InitAnimation(Boolean)`

- `Void EventOnEnableStarMarkEditMode()`

- `Void OnStarMarkEditConfirm()`

- `Void SelectStarMark(Int32)`

- `Void eventOnFilterClick(CharacterFilterViewModel)`

- `Void EventOnShowFilterBar()`

- `Void eventOnSortClick(CharacterSortType)`

- `Void _OnSendStarMarkEditRequest(ListDict`2)`

- `Void _OnFilterPanelSwitch(Boolean)`

- `Void _InitSortPanelSwitch(Boolean)`

- `Void _TryUpdateFilterPanelShow(Boolean)`

- `Trigger _CreateRoutedAVGSignal()`

- `Void <_OnSendStarMarkEditRequest>b__20_0(ChangeStarMarkCharResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterRepo
public class CharacterRepoHomeState : CharacterRepoCommonState, ITimeWatcher, IHotfixable
{
	private const Int32 LOAD_CARD_PER_FRAME; // 0x0
	private const Boolean USE_ASYNC_CARD_LOADER; // 0x0
	private Scrollbar _charListScrollbar; // 0x58
	private UIAnimationLocation _repoFilterPanelSwitchAnim; // 0x60
	private UICharacterRepoSortFilterPanelBinder _sortFilterPanelBinder; // 0x70
	private CharacterRepoGridGroup _charGroupView; // 0x78
	private AnimationSwitchTween m_filterPanelSwitch; // 0x80
	private String m_cachedPageName; // 0x88
	private AsyncGameObjectLoader m_cardLoader; // 0x90
	private StateCacheHandler`1 m_runtimeHandler; // 0x98
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x8
	private static DelegateBridge __Hotfix0__InitAnimation; // 0x10
	private static DelegateBridge __Hotfix0_EventOnEnableStarMarkEditMode; // 0x18
	private static DelegateBridge __Hotfix0_OnStarMarkEditConfirm; // 0x20
	private static DelegateBridge __Hotfix0_SelectStarMark; // 0x28
	private static DelegateBridge __Hotfix0_eventOnFilterClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnShowFilterBar; // 0x38
	private static DelegateBridge __Hotfix0_eventOnSortClick; // 0x40
	private static DelegateBridge __Hotfix0__OnSendStarMarkEditRequest; // 0x48
	private static DelegateBridge __Hotfix0__OnFilterPanelSwitch; // 0x50
	private static DelegateBridge __Hotfix0__InitSortPanelSwitch; // 0x58
	private static DelegateBridge __Hotfix0__TryUpdateFilterPanelShow; // 0x60
	private static DelegateBridge __Hotfix0__CreateRoutedAVGSignal; // 0x68
	private static DelegateBridge __Hotfix0__CreateCardLoader; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2cf9ed4 VA: 0x7595311ed4
	protected override Void OnEnter() { }
	// RVA: 0x2cfa5e8 VA: 0x75953125e8
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x2cfa43c VA: 0x759531243c
	private Void _InitAnimation(Boolean isPanelShow) { }
	// RVA: 0x2cfa76c VA: 0x759531276c
	public Void EventOnEnableStarMarkEditMode() { }
	// RVA: 0x2cfa8e4 VA: 0x75953128e4
	public Void OnStarMarkEditConfirm() { }
	// RVA: 0x2cfae8c VA: 0x7595312e8c
	public Void SelectStarMark(Int32 chrInstId) { }
	// RVA: 0x2cfaf80 VA: 0x7595312f80
	public Void eventOnFilterClick(CharacterFilterViewModel filterModel) { }
	// RVA: 0x2cfb1e0 VA: 0x75953131e0
	public Void EventOnShowFilterBar() { }
	// RVA: 0x2cfb24c VA: 0x759531324c
	public Void eventOnSortClick(CharacterSortType sortType) { }
	// RVA: 0x2cfab8c VA: 0x7595312b8c
	private Void _OnSendStarMarkEditRequest(ListDict`2 starMarkDict) { }
	// RVA: 0x2cfb08c VA: 0x759531308c
	private Void _OnFilterPanelSwitch(Boolean isShow) { }
	// RVA: 0x2cfa67c VA: 0x759531267c
	private Void _InitSortPanelSwitch(Boolean isShow) { }
	// RVA: 0x2cfb3c4 VA: 0x75953133c4
	private Void _TryUpdateFilterPanelShow(Boolean isFilterPanelShow) { }
	// RVA: 0x2cfa0f8 VA: 0x75953120f8
	private Trigger _CreateRoutedAVGSignal() { }
	// RVA: 0x2cfa4bc VA: 0x75953124bc
	private static AsyncGameObjectLoader _CreateCardLoader() { }
	// RVA: 0x2cfb468 VA: 0x7595313468
	public Void .ctor() { }
	// RVA: 0x2cfb4d4 VA: 0x75953134d4
	private Void <_OnSendStarMarkEditRequest>b__20_0(ChangeStarMarkCharResponse response) { }
	// RVA: 0x2cfb54c VA: 0x759531354c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```
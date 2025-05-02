# CrisisV2AchievementState

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2AchievementView _achievementView`

- `CrisisV2AchievementPageGroupView _pageView`

- `RectTransform _topMenuContainer`

- `AnimationWrapper _animationWrapper`

- `CrisisV2AchievementStateBean m_stateBean`

- `Tween m_enterTween`

- `Tween m_switchTween`

- `Boolean m_hasInited`

- `Boolean m_requestingCrisisData`

- `Boolean m_requestingSnapshotData`

- `CrisisV2DataFromServer m_crisisData`

- `CrisisV2SnapshotDataFromServer m_snapshotData`


## Methods

- `Void _OnJumpToMedalDisplayState(IStateBean)`

- `Void _OnJumpToHistoryState(IStateBean)`

- `Void Update()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnNextBtnClicked()`

- `Void _OnPrevBtnClicked()`

- `Void _OnMedalGroupClicked()`

- `Void _OnHistoryClicked()`

- `Void _InitIfNot()`

- `Void _OnBackClick()`

- `Void _SwitchToSeason(Int32)`

- `Void _OnCrisisDataFetched()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2AchievementState : State, IValueMsgReceiver, IHotfixable
{
	private const String ENTER_ANIM_NAME; // 0x0
	private const String FADE_OUT_ANIM_NAME; // 0x0
	private const String FADE_IN_ANIM_NAME; // 0x0
	public const Int32 ON_NEXT_BUTTON_CLICKED; // 0x0
	public const Int32 ON_PREV_BUTTON_CLICKED; // 0x0
	public const Int32 ON_MEDAL_GROUP_CLICKED; // 0x0
	public const Int32 ON_HISTORY_CLICKED; // 0x0
	private CrisisV2AchievementView _achievementView; // 0x50
	private CrisisV2AchievementPageGroupView _pageView; // 0x58
	private RectTransform _topMenuContainer; // 0x60
	private AnimationWrapper _animationWrapper; // 0x68
	private CrisisV2AchievementStateBean m_stateBean; // 0x70
	private Tween m_enterTween; // 0x78
	private Tween m_switchTween; // 0x80
	private Boolean m_hasInited; // 0x88
	private Boolean m_requestingCrisisData; // 0x89
	private Boolean m_requestingSnapshotData; // 0x8a
	private CrisisV2DataFromServer m_crisisData; // 0x90
	private CrisisV2SnapshotDataFromServer m_snapshotData; // 0x98
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToMedalDisplayState; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToHistoryState; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge __Hotfix0_OnMessage; // 0x38
	private static DelegateBridge __Hotfix0__OnNextBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnPrevBtnClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnMedalGroupClicked; // 0x50
	private static DelegateBridge __Hotfix0__OnHistoryClicked; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x60
	private static DelegateBridge __Hotfix0__OnBackClick; // 0x68
	private static DelegateBridge __Hotfix0__SwitchToSeason; // 0x70
	private static DelegateBridge __Hotfix0__OnCrisisDataFetched; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x2bd7e84 VA: 0x75951efe84
	protected override Void OnEnter() { }
	// RVA: 0x2bd82b4 VA: 0x75951f02b4
	protected override Void OnResume() { }
	// RVA: 0x2bd83b4 VA: 0x75951f03b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2bd841c VA: 0x75951f041c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2bd8610 VA: 0x75951f0610
	private Void _OnJumpToMedalDisplayState(IStateBean stateBean) { }
	// RVA: 0x2bd8734 VA: 0x75951f0734
	private Void _OnJumpToHistoryState(IStateBean obj) { }
	// RVA: 0x2bd8868 VA: 0x75951f0868
	private Void Update() { }
	// RVA: 0x2bd8944 VA: 0x75951f0944
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2bd8a4c VA: 0x75951f0a4c
	private Void _OnNextBtnClicked() { }
	// RVA: 0x2bd8ab8 VA: 0x75951f0ab8
	private Void _OnPrevBtnClicked() { }
	// RVA: 0x2bd8b24 VA: 0x75951f0b24
	private Void _OnMedalGroupClicked() { }
	// RVA: 0x2bd8ce8 VA: 0x75951f0ce8
	private Void _OnHistoryClicked() { }
	// RVA: 0x2bd7fc8 VA: 0x75951effc8
	private Void _InitIfNot() { }
	// RVA: 0x2bd9190 VA: 0x75951f1190
	private Void _OnBackClick() { }
	// RVA: 0x2bd8eb4 VA: 0x75951f0eb4
	private Void _SwitchToSeason(Int32 indexDelta) { }
	// RVA: 0x2bd8128 VA: 0x75951f0128
	private Void _OnCrisisDataFetched() { }
	// RVA: 0x2bd9390 VA: 0x75951f1390
	public Void .ctor() { }
	// RVA: 0x2bd9564 VA: 0x75951f1564
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2bd956c VA: 0x75951f156c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2bd9574 VA: 0x75951f1574
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```
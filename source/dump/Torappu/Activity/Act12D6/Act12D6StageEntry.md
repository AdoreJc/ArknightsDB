# Act12D6StageEntry

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `RectTransform _topMenuContainer`

- `Act12D6StageEntryView _view`

- `Act12D6RetireConfirmView _unlockPanel`

- `CommonTopMenu m_topMenu`


## Methods

- `Void NotifyStageTimeout()`

- `Void NotifyRewardTimeout()`

- `Void EventOnRetireClicked()`

- `Void EventOnStartGameClicked()`

- `Void EventOnRetireConfirmClicked()`

- `Void EventOnOuterBuffClicked()`

- `Void EventOnMileStoneClicked()`

- `Void EventOnDifficultyToggleClicked(Toggle)`

- `Void EventOnDifficultyLockedClicked(String)`

- `Void EventOnRelicBookHandClicked()`

- `Void _InitTopMenu()`

- `Void _EventOnRogueLikeEnd()`

- `Void <EventOnStartGameClicked>b__8_0(Act12D6CreateGameResponse)`

- `Void <EventOnRetireConfirmClicked>b__9_0(Act12D6GiveUpGameResponse)`

- `Void <>xLuaBaseProxy_OnLoaded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6StageEntry : ActivityStageSingleComponent, IHotfixable
{
	private RectTransform _topMenuContainer; // 0x20
	private Act12D6StageEntryView _view; // 0x28
	private Act12D6RetireConfirmView _unlockPanel; // 0x30
	private CommonTopMenu m_topMenu; // 0x38
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x0
	private static DelegateBridge __Hotfix0_NotifyStageTimeout; // 0x8
	private static DelegateBridge __Hotfix0_NotifyRewardTimeout; // 0x10
	private static DelegateBridge __Hotfix0_EventOnRetireClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnStartGameClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnRetireConfirmClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnOuterBuffClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnMileStoneClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnDifficultyToggleClicked; // 0x40
	private static DelegateBridge __Hotfix0_EventOnDifficultyLockedClicked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnRelicBookHandClicked; // 0x50
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x58
	private static DelegateBridge __Hotfix0__EventOnRogueLikeEnd; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x346bf80 VA: 0x7595a83f80
	protected override Void OnLoaded() { }
	// RVA: 0x346b2b4 VA: 0x7595a832b4
	public Void NotifyStageTimeout() { }
	// RVA: 0x346b448 VA: 0x7595a83448
	public Void NotifyRewardTimeout() { }
	// RVA: 0x346c394 VA: 0x7595a84394
	public Void EventOnRetireClicked() { }
	// RVA: 0x346c458 VA: 0x7595a84458
	public Void EventOnStartGameClicked() { }
	// RVA: 0x346c728 VA: 0x7595a84728
	public Void EventOnRetireConfirmClicked() { }
	// RVA: 0x346c940 VA: 0x7595a84940
	public Void EventOnOuterBuffClicked() { }
	// RVA: 0x346ca48 VA: 0x7595a84a48
	public Void EventOnMileStoneClicked() { }
	// RVA: 0x346cb50 VA: 0x7595a84b50
	public Void EventOnDifficultyToggleClicked(Toggle difficultyTg) { }
	// RVA: 0x346cc88 VA: 0x7595a84c88
	public Void EventOnDifficultyLockedClicked(String modeName) { }
	// RVA: 0x346cd44 VA: 0x7595a84d44
	public Void EventOnRelicBookHandClicked() { }
	// RVA: 0x346c1e8 VA: 0x7595a841e8
	private Void _InitTopMenu() { }
	// RVA: 0x346ce4c VA: 0x7595a84e4c
	private Void _EventOnRogueLikeEnd() { }
	// RVA: 0x346cefc VA: 0x7595a84efc
	public Void .ctor() { }
	// RVA: 0x346cf6c VA: 0x7595a84f6c
	private Void <EventOnStartGameClicked>b__8_0(Act12D6CreateGameResponse response) { }
	// RVA: 0x346d278 VA: 0x7595a85278
	private Void <EventOnRetireConfirmClicked>b__9_0(Act12D6GiveUpGameResponse response) { }
	// RVA: 0x346d2f0 VA: 0x7595a852f0
	private Void <>xLuaBaseProxy_OnLoaded() { }
}
```
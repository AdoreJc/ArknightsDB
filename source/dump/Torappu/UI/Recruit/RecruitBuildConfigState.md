# RecruitBuildConfigState

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RecruitBuildConfigStateBean _stateBean`

- `Animator _spreadAnim`

- `Text _detailText`

- `RefCountReference m_buildingContextRef`


## Methods

- `Void EventOnUpHourClick()`

- `Void EventOnDownHourClick()`

- `Void EventOnUpMinuteClick()`

- `Void EventOnDownMinuteClick()`

- `Void EventOnConfirmClick()`

- `Void EventOnRefreshClick()`

- `Void EventOnSpreadDetail()`

- `Void EventOnUnSpreadDetail()`

- `Void EventOnCancelClick()`

- `Void EventOnTagClick(Int32)`

- `Void _OnStartBuildSucceed(NormalGachaResponse)`

- `Void _SendStartBuild()`

- `Void _RefreshTags()`

- `Void <EventOnConfirmClick>b__15_0()`

- `Void <EventOnRefreshClick>b__16_0()`

- `Void <_RefreshTags>b__23_0(RefreshTagsGachaResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildConfigState : PopupFloatState
{
	public const Int64 MINUTE_MILLSEC_UNIT; // 0x0
	private const Int64 HOUR_MILLSEC_UNIT; // 0x0
	private const String ANIMATOR_PARAM; // 0x0
	private RecruitBuildConfigStateBean _stateBean; // 0x70
	private Animator _spreadAnim; // 0x78
	private Text _detailText; // 0x80
	private RefCountReference m_buildingContextRef; // 0x88
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnExit; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_EventOnUpHourClick; // 0x20
	private static DelegateBridge __Hotfix0_EventOnDownHourClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnUpMinuteClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnDownMinuteClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnConfirmClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnRefreshClick; // 0x48
	private static DelegateBridge __Hotfix0_EventOnSpreadDetail; // 0x50
	private static DelegateBridge __Hotfix0_EventOnUnSpreadDetail; // 0x58
	private static DelegateBridge __Hotfix0_EventOnCancelClick; // 0x60
	private static DelegateBridge __Hotfix0_EventOnTagClick; // 0x68
	private static DelegateBridge __Hotfix0__OnStartBuildSucceed; // 0x70
	private static DelegateBridge __Hotfix0__SendStartBuild; // 0x78
	private static DelegateBridge __Hotfix0__RefreshTags; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x26f38d4 VA: 0x7594d0b8d4
	protected override Void OnEnter() { }
	// RVA: 0x26f39f0 VA: 0x7594d0b9f0
	protected override Void OnExit() { }
	// RVA: 0x26f3a90 VA: 0x7594d0ba90
	public override IStateBean GetCacheBean() { }
	// RVA: 0x26f3af8 VA: 0x7594d0baf8
	protected override Void OnResume() { }
	// RVA: 0x26f3b6c VA: 0x7594d0bb6c
	public Void EventOnUpHourClick() { }
	// RVA: 0x26f3dcc VA: 0x7594d0bdcc
	public Void EventOnDownHourClick() { }
	// RVA: 0x26f3e44 VA: 0x7594d0be44
	public Void EventOnUpMinuteClick() { }
	// RVA: 0x26f3ebc VA: 0x7594d0bebc
	public Void EventOnDownMinuteClick() { }
	// RVA: 0x26f3f34 VA: 0x7594d0bf34
	public Void EventOnConfirmClick() { }
	// RVA: 0x26f4820 VA: 0x7594d0c820
	public Void EventOnRefreshClick() { }
	// RVA: 0x26f4c1c VA: 0x7594d0cc1c
	public Void EventOnSpreadDetail() { }
	// RVA: 0x26f4cac VA: 0x7594d0ccac
	public Void EventOnUnSpreadDetail() { }
	// RVA: 0x26f4d3c VA: 0x7594d0cd3c
	public Void EventOnCancelClick() { }
	// RVA: 0x26f4dc0 VA: 0x7594d0cdc0
	public Void EventOnTagClick(Int32 tagIndex) { }
	// RVA: 0x26f50dc VA: 0x7594d0d0dc
	private Void _OnStartBuildSucceed(NormalGachaResponse response) { }
	// RVA: 0x26f4674 VA: 0x7594d0c674
	private Void _SendStartBuild() { }
	// RVA: 0x26f53f4 VA: 0x7594d0d3f4
	private Void _RefreshTags() { }
	// RVA: 0x26f56f4 VA: 0x7594d0d6f4
	public Void .ctor() { }
	// RVA: 0x26f5764 VA: 0x7594d0d764
	private Void <EventOnConfirmClick>b__15_0() { }
	// RVA: 0x26f5768 VA: 0x7594d0d768
	private Void <EventOnRefreshClick>b__16_0() { }
	// RVA: 0x26f576c VA: 0x7594d0d76c
	private Void <_RefreshTags>b__23_0(RefreshTagsGachaResponse response) { }
	// RVA: 0x26f5d80 VA: 0x7594d0dd80
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x26f5d88 VA: 0x7594d0dd88
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x26f5d90 VA: 0x7594d0dd90
	private Void <>xLuaBaseProxy_OnResume() { }
}
```
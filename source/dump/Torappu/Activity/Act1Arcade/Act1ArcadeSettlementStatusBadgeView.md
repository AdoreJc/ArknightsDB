# Act1ArcadeSettlementStatusBadgeView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `UIAnimationLocation _entryAnim`

- `UIAnimationLocation _leaveAnim`

- `Arc1ArcadeSettlementBadgeHolder _badgeHolder`

- `Boolean m_blockClick`

- `Act1ArcadeSettlementModel m_model`

- `UIPageFinder m_pageFinder`


## Methods

- `IEnumerator _PlayAnim(UIAnimationLocation, TweenCallback)`

- `Void _OnLeaveAnimEnd()`

- `Void EventOnClickBg()`

- `Void <>xLuaBaseProxy_SetToDefaultShow()`

- `Void <>xLuaBaseProxy_ChangeInStatusAndRender(Act1ArcadeSettlementModel)`

- `Void <>xLuaBaseProxy_LeaveStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementStatusBadgeView : Act1ArcadeSettlementStatusBaseView
{
	private UIAnimationLocation _entryAnim; // 0x28
	private UIAnimationLocation _leaveAnim; // 0x38
	private Arc1ArcadeSettlementBadgeHolder _badgeHolder; // 0x48
	private Boolean m_blockClick; // 0x50
	private Act1ArcadeSettlementModel m_model; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private static DelegateBridge __Hotfix0_get_viewStatus; // 0x0
	private static DelegateBridge __Hotfix0_get_nextViewStatus; // 0x8
	private static DelegateBridge __Hotfix0_SetToDefaultShow; // 0x10
	private static DelegateBridge __Hotfix0_ChangeInStatusAndRender; // 0x18
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x20
	private static DelegateBridge __Hotfix0_LeaveStatus; // 0x28
	private static DelegateBridge __Hotfix0__OnLeaveAnimEnd; // 0x30
	private static DelegateBridge __Hotfix0_EventOnClickBg; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override SettlementViewStatus viewStatus { get; }
	public override SettlementViewStatus nextViewStatus { get; }

	// RVA: 0x3408e00 VA: 0x7595a20e00
	public override SettlementViewStatus get_viewStatus() { }
	// RVA: 0x3408e68 VA: 0x7595a20e68
	public override SettlementViewStatus get_nextViewStatus() { }
	// RVA: 0x3408ed0 VA: 0x7595a20ed0
	public override Void SetToDefaultShow() { }
	// RVA: 0x3408fb8 VA: 0x7595a20fb8
	public override Void ChangeInStatusAndRender(Act1ArcadeSettlementModel model) { }
	// RVA: 0x3409118 VA: 0x7595a21118
	private IEnumerator _PlayAnim(UIAnimationLocation anim, TweenCallback onComplete) { }
	// RVA: 0x3409240 VA: 0x7595a21240
	public override Void LeaveStatus() { }
	// RVA: 0x34093a8 VA: 0x7595a213a8
	private Void _OnLeaveAnimEnd() { }
	// RVA: 0x3409420 VA: 0x7595a21420
	public Void EventOnClickBg() { }
	// RVA: 0x3409534 VA: 0x7595a21534
	public Void .ctor() { }
	// RVA: 0x3409610 VA: 0x7595a21610
	private Void <>xLuaBaseProxy_SetToDefaultShow() { }
	// RVA: 0x3409614 VA: 0x7595a21614
	private Void <>xLuaBaseProxy_ChangeInStatusAndRender(Act1ArcadeSettlementModel P0) { }
	// RVA: 0x3409618 VA: 0x7595a21618
	private Void <>xLuaBaseProxy_LeaveStatus() { }
}
```
# Act1ArcadeBadgeBookDetailContentAnimator

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Single REFRESH_POSITION`

- `Single REFRESH_WAIT_INTERVAL`

- `Int32 m_focusIndex`

- `Int32 m_presentingIndex`

- `Single m_playingPosition`

- `Direction m_playingDirection`

- `Int32 m_directionMove`

- `Tween m_playingTween`


## Methods

- `Void UpdateFocusIndex(Int32, Boolean, Direction)`

- `Single _GetPosition()`

- `Void _SetPosition(Single)`

- `Void _UpdateView()`

- `Direction _FetchDirection(Direction)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookDetailContentAnimator : IHotfixable
{
	private Single REFRESH_POSITION; // 0x10
	private Single REFRESH_WAIT_INTERVAL; // 0x14
	private readonly UIAnimationLocation m_animationLocation; // 0x18
	private readonly Single m_animationLength; // 0x28
	private readonly Action m_updateAction; // 0x30
	private Int32 m_focusIndex; // 0x38
	private Int32 m_presentingIndex; // 0x3c
	private Single m_playingPosition; // 0x40
	private Direction m_playingDirection; // 0x44
	private Int32 m_directionMove; // 0x48
	private Tween m_playingTween; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateFocusIndex; // 0x8
	private static DelegateBridge __Hotfix0__GetPosition; // 0x10
	private static DelegateBridge __Hotfix0__SetPosition; // 0x18
	private static DelegateBridge __Hotfix0__UpdateView; // 0x20
	private static DelegateBridge __Hotfix0__FetchDirection; // 0x28
	private static DelegateBridge __Hotfix0__CellModuleOne; // 0x30


	// RVA: 0x33f11cc VA: 0x7595a091cc
	public Void .ctor(UIAnimationLocation animationLocation, Action updateAction) { }
	// RVA: 0x33f12c8 VA: 0x7595a092c8
	public Void UpdateFocusIndex(Int32 index, Boolean fastMode, Direction preferredDirection) { }
	// RVA: 0x33f1a38 VA: 0x7595a09a38
	private Single _GetPosition() { }
	// RVA: 0x33f1824 VA: 0x7595a09824
	private Void _SetPosition(Single position) { }
	// RVA: 0x33f1798 VA: 0x7595a09798
	private Void _UpdateView() { }
	// RVA: 0x33f1974 VA: 0x7595a09974
	private Direction _FetchDirection(Direction preferredDirection) { }
	// RVA: 0x33f18c4 VA: 0x7595a098c4
	private static Single _CellModuleOne(Single val) { }
}
```
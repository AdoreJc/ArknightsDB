# ArchiveQuestContentAnimator

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Single REFRESH_POSITION`

- `Single REFRESH_WAIT_INTERVAL`

- `Int32 m_focusIndex`

- `Int32 m_presentingIndex`

- `Single m_playingPosition`

- `Direction m_playingDirection`

- `Tween m_playingTween`


## Methods

- `Void InitAsBlank()`

- `Void UpdateFocusIndex(Int32, Boolean)`

- `Single _GetPosition()`

- `Void _SetPosition(Single)`

- `Void _UpdateView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestContentAnimator : IHotfixable
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
	private Tween m_playingTween; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_InitAsBlank; // 0x8
	private static DelegateBridge __Hotfix0_UpdateFocusIndex; // 0x10
	private static DelegateBridge __Hotfix0__GetPosition; // 0x18
	private static DelegateBridge __Hotfix0__SetPosition; // 0x20
	private static DelegateBridge __Hotfix0__UpdateView; // 0x28
	private static DelegateBridge __Hotfix0__CellModuleOne; // 0x30


	// RVA: 0x306f91c VA: 0x759568791c
	public Void .ctor(UIAnimationLocation animationLocation, Action updateAction) { }
	// RVA: 0x306fa10 VA: 0x7595687a10
	public Void InitAsBlank() { }
	// RVA: 0x306facc VA: 0x7595687acc
	public Void UpdateFocusIndex(Int32 index, Boolean fastMode) { }
	// RVA: 0x3070178 VA: 0x7595688178
	private Single _GetPosition() { }
	// RVA: 0x3070028 VA: 0x7595688028
	private Void _SetPosition(Single position) { }
	// RVA: 0x306ffa0 VA: 0x7595687fa0
	private Void _UpdateView() { }
	// RVA: 0x30700c8 VA: 0x75956880c8
	private static Single _CellModuleOne(Single val) { }
}
```
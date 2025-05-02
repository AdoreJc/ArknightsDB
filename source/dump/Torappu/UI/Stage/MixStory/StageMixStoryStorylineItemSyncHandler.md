# StageMixStoryStorylineItemSyncHandler

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `StageStorylineViewModel m_focusedStoryline`

- `Single m_focusProgress`

- `Tween m_tween`


## Properties

- `StageStorylineViewModel focusedStoryline`


## Methods

- `StageStorylineViewModel get_focusedStoryline()`

- `Void Reset()`

- `Void UpdateState(MixStoryZoneGroupViewModel)`

- `Single GetProgressOfStoryline(String)`

- `Single _GetProgress()`

- `Void _SetProgress(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryStorylineItemSyncHandler : IHotfixable
{
	private readonly Single m_focusDuration; // 0x10
	private readonly ListDict`2 m_progressOfStorylines; // 0x18
	private StageStorylineViewModel m_focusedStoryline; // 0x20
	private Single m_focusProgress; // 0x28
	private Tween m_tween; // 0x30
	private static DelegateBridge __Hotfix0_get_focusedStoryline; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0_UpdateState; // 0x18
	private static DelegateBridge __Hotfix0_GetProgressOfStoryline; // 0x20
	private static DelegateBridge __Hotfix0__GetProgress; // 0x28
	private static DelegateBridge __Hotfix0__SetProgress; // 0x30

	public StageStorylineViewModel focusedStoryline { get; }

	// RVA: 0x2fe82ec VA: 0x75956002ec
	public StageStorylineViewModel get_focusedStoryline() { }
	// RVA: 0x2fe8354 VA: 0x7595600354
	public Void .ctor(UIAnimationLocation focusAnimation) { }
	// RVA: 0x2fe8458 VA: 0x7595600458
	public Void Reset() { }
	// RVA: 0x2fe8538 VA: 0x7595600538
	public Void UpdateState(MixStoryZoneGroupViewModel model) { }
	// RVA: 0x2fe8814 VA: 0x7595600814
	public Single GetProgressOfStoryline(String storylineId) { }
	// RVA: 0x2fe88c8 VA: 0x75956008c8
	private Single _GetProgress() { }
	// RVA: 0x2fe8930 VA: 0x7595600930
	private Void _SetProgress(Single value) { }
}
```
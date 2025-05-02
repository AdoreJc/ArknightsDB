# LevelAnimator

**Namespace:** ` `


## Fields

- `LevelAnimatorArgs m_args`

- `Int32 m_maxPosition`

- `Int32 m_cachedPosition`

- `Single m_playingPosition`

- `Tween m_itemTween`

- `Tween m_switchTween`

- `Single m_switchAlpha`


## Methods

- `Void InitLevelStep(List`1, Int32)`

- `Void SetLevel(Int32)`

- `Tweener _GenerateItemTweener()`

- `Single _GetItemPosition()`

- `Void _SetItemPosition(Single)`

- `Sequence _GenerateSequenceOfSwitch()`

- `Tweener _GenerateSwitchTweener(Single, Single)`

- `Single _GetSwitchAlpha()`

- `Void _SetSwitchAlpha(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LevelAnimator : IHotfixable
{
	private const Single NEAR_HIDE_POSITION; // 0x0
	private const Single HIGH_NEAR_DYNAMIC_TIME; // 0x0
	private const Single HIGH_FAR_HIDE_INVERSED_POSITION; // 0x0
	private LevelAnimatorArgs m_args; // 0x10
	private readonly GameObject m_levelPanel; // 0x58
	private readonly List`1 m_levelGroups; // 0x60
	private readonly List`1 m_levelGroupSwitchTweens; // 0x68
	private readonly UIAnimationLocation m_itemAnimationLocation; // 0x70
	private readonly CanvasGroup m_downGroup; // 0x80
	private readonly CanvasGroup m_highNearGroup; // 0x88
	private readonly CanvasGroup m_highFarGroup; // 0x90
	private readonly Single m_fullTime; // 0x98
	private readonly Single m_halfTime; // 0x9c
	private readonly List`1 m_switchGroups; // 0xa0
	private readonly Action m_updateAction; // 0xa8
	private Int32 m_maxPosition; // 0xb0
	private Int32 m_cachedPosition; // 0xb4
	private Single m_playingPosition; // 0xb8
	private Tween m_itemTween; // 0xc0
	private Tween m_switchTween; // 0xc8
	private Single m_switchAlpha; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_InitLevelStep; // 0x8
	private static DelegateBridge __Hotfix0_SetLevel; // 0x10
	private static DelegateBridge __Hotfix0__GenerateItemTweener; // 0x18
	private static DelegateBridge __Hotfix0__GetItemPosition; // 0x20
	private static DelegateBridge __Hotfix0__SetItemPosition; // 0x28
	private static DelegateBridge __Hotfix0__GenerateSequenceOfSwitch; // 0x30
	private static DelegateBridge __Hotfix0__GenerateSwitchTweener; // 0x38
	private static DelegateBridge __Hotfix0__GetSwitchAlpha; // 0x40
	private static DelegateBridge __Hotfix0__SetSwitchAlpha; // 0x48


	// RVA: 0x24f1634 VA: 0x7594b09634
	public Void .ctor(LevelAnimatorArgs args) { }
	// RVA: 0x24f273c VA: 0x7594b0a73c
	public Void InitLevelStep(List`1 makeItems, Int32 resetLevel) { }
	// RVA: 0x24f49dc VA: 0x7594b0c9dc
	public Void SetLevel(Int32 position) { }
	// RVA: 0x24f5e10 VA: 0x7594b0de10
	private Tweener _GenerateItemTweener() { }
	// RVA: 0x24f60dc VA: 0x7594b0e0dc
	private Single _GetItemPosition() { }
	// RVA: 0x24f6144 VA: 0x7594b0e144
	private Void _SetItemPosition(Single value) { }
	// RVA: 0x24f5f8c VA: 0x7594b0df8c
	private Sequence _GenerateSequenceOfSwitch() { }
	// RVA: 0x24f632c VA: 0x7594b0e32c
	private Tweener _GenerateSwitchTweener(Single target, Single duration) { }
	// RVA: 0x24f6484 VA: 0x7594b0e484
	private Single _GetSwitchAlpha() { }
	// RVA: 0x24f5c78 VA: 0x7594b0dc78
	private Void _SetSwitchAlpha(Single value) { }
}
```
# SandboxV2DungeonLodAnim

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAnimationLocation _animTrans`

- `Single _tweenMiddleValue`

- `Single _tweenDuration`

- `AnimationHandler m_animHandler`

- `SandboxV2DungeonLodRank m_lodRank`

- `Tween m_tween`

- `Single m_tweenValue`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Single _GetAnimProgress()`

- `Void _SetAnimProgress(Single)`

- `Single _GetTweenValue(SandboxV2DungeonLodRank)`

- `Void _ClearTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonLodAnim : SandboxV2DungeonLodElement
{
	private UIAnimationLocation _animTrans; // 0x20
	private Single _tweenMiddleValue; // 0x30
	private Single _tweenDuration; // 0x34
	private AnimationHandler m_animHandler; // 0x38
	private SandboxV2DungeonLodRank m_lodRank; // 0x40
	private Tween m_tween; // 0x48
	private Single m_tweenValue; // 0x50
	private Boolean m_inited; // 0x54
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__GetAnimProgress; // 0x8
	private static DelegateBridge __Hotfix0__SetAnimProgress; // 0x10
	private static DelegateBridge __Hotfix0__GetTweenValue; // 0x18
	private static DelegateBridge __Hotfix0__ClearTween; // 0x20
	private static DelegateBridge __Hotfix0_UpdateLod; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x25128d0 VA: 0x7594b2a8d0
	private Void _InitIfNot() { }
	// RVA: 0x2512984 VA: 0x7594b2a984
	private Single _GetAnimProgress() { }
	// RVA: 0x25129ec VA: 0x7594b2a9ec
	private Void _SetAnimProgress(Single value) { }
	// RVA: 0x2512a9c VA: 0x7594b2aa9c
	private Single _GetTweenValue(SandboxV2DungeonLodRank lodRank) { }
	// RVA: 0x2512b34 VA: 0x7594b2ab34
	private Void _ClearTween() { }
	// RVA: 0x2512bc4 VA: 0x7594b2abc4
	public override Void UpdateLod(Single lod, SandboxV2DungeonLodRank lodRank, Boolean fastMode) { }
	// RVA: 0x2512e34 VA: 0x7594b2ae34
	public Void .ctor() { }
}
```
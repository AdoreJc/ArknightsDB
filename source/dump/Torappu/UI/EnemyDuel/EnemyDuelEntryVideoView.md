# EnemyDuelEntryVideoView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Tween m_animTween`


## Methods

- `Void OnCreate()`

- `Void OnDispose()`

- `Void _CancelTweenIfNeeded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEntryVideoView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation[] _loopAnims; // 0x18
	private Tween m_animTween; // 0x20
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnDispose; // 0x8
	private static DelegateBridge __Hotfix0__CancelTweenIfNeeded; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x294d09c VA: 0x7594f6509c
	public Void OnCreate() { }
	// RVA: 0x294d490 VA: 0x7594f65490
	public Void OnDispose() { }
	// RVA: 0x294d568 VA: 0x7594f65568
	private Void _CancelTweenIfNeeded() { }
	// RVA: 0x294d608 VA: 0x7594f65608
	public Void .ctor() { }
}
```
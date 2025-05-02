# RL04DungeonDisasterEffect

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `TwoStateFadeSwitcher _fadeSwitcher`

- `GameObject _startEffect`

- `UIAnimationLocation _anim`

- `Tween m_cachedAnim`


## Methods

- `Void OnCreate()`

- `Void SetEffectShow(Boolean)`

- `Void PlayStartEffect()`

- `Void <PlayStartEffect>b__6_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04DungeonDisasterEffect : MonoBehaviour, IHotfixable
{
	private TwoStateFadeSwitcher _fadeSwitcher; // 0x18
	private GameObject _startEffect; // 0x20
	private UIAnimationLocation _anim; // 0x28
	private Tween m_cachedAnim; // 0x38
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_SetEffectShow; // 0x8
	private static DelegateBridge __Hotfix0_PlayStartEffect; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b1629c VA: 0x759512e29c
	public Void OnCreate() { }
	// RVA: 0x2b1630c VA: 0x759512e30c
	public Void SetEffectShow(Boolean hasDisaster) { }
	// RVA: 0x2b16398 VA: 0x759512e398
	public Void PlayStartEffect() { }
	// RVA: 0x2b164fc VA: 0x759512e4fc
	public Void .ctor() { }
	// RVA: 0x2b1656c VA: 0x759512e56c
	private Void <PlayStartEffect>b__6_0() { }
}
```
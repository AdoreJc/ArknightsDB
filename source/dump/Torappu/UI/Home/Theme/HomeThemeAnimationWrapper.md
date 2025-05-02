# HomeThemeAnimationWrapper

**Namespace:** `Torappu.UI.Home.Theme`


## Fields

- `AnimationWrapper _animWrapper`

- `String _clipName`

- `Tween m_tween`


## Methods

- `Void PlayAnim()`

- `Void StopLoop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Theme
public class HomeThemeAnimationWrapper : MonoBehaviour, IHotfixable
{
	private AnimationWrapper _animWrapper; // 0x18
	private String _clipName; // 0x20
	private Tween m_tween; // 0x28
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x0
	private static DelegateBridge __Hotfix0_StopLoop; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28499d4 VA: 0x7594e619d4
	public Void PlayAnim() { }
	// RVA: 0x2849a90 VA: 0x7594e61a90
	public Void StopLoop() { }
	// RVA: 0x2849b10 VA: 0x7594e61b10
	public Void .ctor() { }
}
```
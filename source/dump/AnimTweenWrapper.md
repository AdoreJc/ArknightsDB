# AnimTweenWrapper

**Namespace:** ` `


## Fields

- `UIAnimationTween m_animTween`


## Methods

- `Single GetCurrPos()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AnimTweenWrapper : TweenWrapper, ITweenProgress, IHotfixable
{
	private UIAnimationTween m_animTween; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetCurrPos; // 0x8


	// RVA: 0x2179fa0 VA: 0x7594791fa0
	public Void .ctor(UIAnimationTween tween) { }
	// RVA: 0x217a51c VA: 0x759479251c
	public Single GetCurrPos() { }
}
```
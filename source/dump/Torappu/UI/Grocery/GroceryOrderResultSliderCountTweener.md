# GroceryOrderResultSliderCountTweener

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Slider m_slider`

- `Tween m_tweener`

- `Single m_dur`


## Methods

- `Void Play(Single, Boolean, Single)`

- `Void _Reset(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderResultSliderCountTweener : IHotfixable
{
	private Slider m_slider; // 0x10
	private Tween m_tweener; // 0x18
	private Single m_dur; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Play; // 0x8
	private static DelegateBridge __Hotfix0__Reset; // 0x10


	// RVA: 0x289550c VA: 0x7594ead50c
	public Void .ctor(Slider slider, Single dur) { }
	// RVA: 0x289522c VA: 0x7594ead22c
	public Void Play(Single endVal, Boolean isFastMode, Single startVal) { }
	// RVA: 0x28956a8 VA: 0x7594ead6a8
	private Void _Reset(Single endCnt) { }
}
```
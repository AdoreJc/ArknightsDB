# HeightTweenLayoutElement

**Namespace:** `Torappu.UI`


## Fields

- `Single _speed`

- `LayoutElement _layoutElement`

- `Single _minTime`

- `Single m_heightTarget`

- `Tween m_tween`

- `Single m_currentHeight`


## Methods

- `Void SetInitHeight(Single)`

- `Boolean IsTweenActive()`

- `Void TweenHeight(Single)`

- `Single <TweenHeight>b__8_0()`

- `Void <TweenHeight>b__8_1(Single)`

- `Void <TweenHeight>b__8_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class HeightTweenLayoutElement : MonoBehaviour, IHotfixable
{
	private Single _speed; // 0x18
	private LayoutElement _layoutElement; // 0x20
	private Single _minTime; // 0x28
	private Single m_heightTarget; // 0x2c
	private Tween m_tween; // 0x30
	private Single m_currentHeight; // 0x38
	private static DelegateBridge __Hotfix0_SetInitHeight; // 0x0
	private static DelegateBridge __Hotfix0_IsTweenActive; // 0x8
	private static DelegateBridge __Hotfix0_TweenHeight; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x223e694 VA: 0x7594856694
	public Void SetInitHeight(Single target) { }
	// RVA: 0x223e744 VA: 0x7594856744
	public Boolean IsTweenActive() { }
	// RVA: 0x223e7b4 VA: 0x75948567b4
	public Void TweenHeight(Single target) { }
	// RVA: 0x223e9f8 VA: 0x75948569f8
	public Void .ctor() { }
	// RVA: 0x223ea74 VA: 0x7594856a74
	private Single <TweenHeight>b__8_0() { }
	// RVA: 0x223ea7c VA: 0x7594856a7c
	private Void <TweenHeight>b__8_1(Single val) { }
	// RVA: 0x223eaa8 VA: 0x7594856aa8
	private Void <TweenHeight>b__8_2() { }
}
```
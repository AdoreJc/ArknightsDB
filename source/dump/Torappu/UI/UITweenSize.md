# UITweenSize

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform m_transform`

- `Single m_tweenProcess`

- `RectSize m_tweenValue`

- `RectSize m_from`

- `RectSize m_to`


## Methods

- `Void _OnTweenChanged(Single)`

- `Single _GetTweenProcess()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UITweenSize : BasicTween`1
{
	private RectTransform m_transform; // 0x50
	private Single m_tweenProcess; // 0x58
	private RectSize m_tweenValue; // 0x60
	private RectSize m_from; // 0x68
	private RectSize m_to; // 0x70
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetTweenValue; // 0x8
	private static DelegateBridge __Hotfix0_SetTweenValue; // 0x10
	private static DelegateBridge __Hotfix0_ConstructTweener; // 0x18
	private static DelegateBridge __Hotfix0__OnTweenChanged; // 0x20
	private static DelegateBridge __Hotfix0__GetTweenProcess; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x21783c8 VA: 0x75947903c8
	protected override Void OnInit() { }
	// RVA: 0x2178458 VA: 0x7594790458
	protected override RectSize GetTweenValue() { }
	// RVA: 0x21784fc VA: 0x75947904fc
	protected override Void SetTweenValue(RectSize val) { }
	// RVA: 0x21785a8 VA: 0x75947905a8
	protected override Tweener ConstructTweener(RectSize fromValue, RectSize toValue, Single duration) { }
	// RVA: 0x2178744 VA: 0x7594790744
	private Void _OnTweenChanged(Single value) { }
	// RVA: 0x2178850 VA: 0x7594790850
	private Single _GetTweenProcess() { }
	// RVA: 0x21788b8 VA: 0x75947908b8
	public Void .ctor() { }
}
```
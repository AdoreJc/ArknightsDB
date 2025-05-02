# UITweenPosition

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform m_transform`

- `Single m_tweenProcess`

- `RectPosition m_tweenValue`

- `RectPosition m_from`

- `RectPosition m_to`


## Methods

- `Void _OnTweenChanged(Single)`

- `Single _GetTweenProcess()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UITweenPosition : BasicTween`1
{
	private RectTransform m_transform; // 0x50
	private Single m_tweenProcess; // 0x58
	private RectPosition m_tweenValue; // 0x60
	private RectPosition m_from; // 0x68
	private RectPosition m_to; // 0x70
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetTweenValue; // 0x8
	private static DelegateBridge __Hotfix0_SetTweenValue; // 0x10
	private static DelegateBridge __Hotfix0_ConstructTweener; // 0x18
	private static DelegateBridge __Hotfix0__OnTweenChanged; // 0x20
	private static DelegateBridge __Hotfix0__GetTweenProcess; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2177db8 VA: 0x759478fdb8
	protected override Void OnInit() { }
	// RVA: 0x2177e48 VA: 0x759478fe48
	protected override RectPosition GetTweenValue() { }
	// RVA: 0x2177ee4 VA: 0x759478fee4
	protected override Void SetTweenValue(RectPosition val) { }
	// RVA: 0x2177f90 VA: 0x759478ff90
	protected override Tweener ConstructTweener(RectPosition fromValue, RectPosition toValue, Single duration) { }
	// RVA: 0x217812c VA: 0x759479012c
	private Void _OnTweenChanged(Single value) { }
	// RVA: 0x2178218 VA: 0x7594790218
	private Single _GetTweenProcess() { }
	// RVA: 0x2178280 VA: 0x7594790280
	public Void .ctor() { }
}
```
# AutoHideComponent

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup _target`

- `Tweener m_showTweener`

- `Tweener m_hideTweener`

- `Tweener m_waitTweener`

- `Boolean m_isHide`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void NotifyInteract()`

- `Void _StartToHide()`

- `Void _StartToShow()`

- `Single _GetTargetAlpha()`

- `Void _SetTargetAlpha(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class AutoHideComponent : MonoBehaviour
{
	private const Single WAIT_DURATION; // 0x0
	private const Single TWEEN_DURATION; // 0x0
	private CanvasGroup _target; // 0x18
	private Tweener m_showTweener; // 0x20
	private Tweener m_hideTweener; // 0x28
	private Tweener m_waitTweener; // 0x30
	private Boolean m_isHide; // 0x38
	private Tweener[] m_activeTweens; // 0x40


	// RVA: 0x220aed4 VA: 0x7594822ed4
	private Void Start() { }
	// RVA: 0x220b400 VA: 0x7594823400
	private Void OnDestroy() { }
	// RVA: 0x220b4a4 VA: 0x75948234a4
	public Void NotifyInteract() { }
	// RVA: 0x220b53c VA: 0x759482353c
	private Void _StartToHide() { }
	// RVA: 0x220b4d4 VA: 0x75948234d4
	private Void _StartToShow() { }
	// RVA: 0x220b5a8 VA: 0x75948235a8
	private Single _GetTargetAlpha() { }
	// RVA: 0x220b5c4 VA: 0x75948235c4
	private Void _SetTargetAlpha(Single alpha) { }
	// RVA: 0x220b5e0 VA: 0x75948235e0
	public Void .ctor() { }
}
```
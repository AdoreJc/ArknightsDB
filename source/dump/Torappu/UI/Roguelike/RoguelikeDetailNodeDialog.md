# RoguelikeDetailNodeDialog

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _panel`

- `Vector3 _padding`

- `ViewBase _view`

- `RectTransform _backRt`

- `Boolean m_isInited`

- `Camera m_targetCamera`

- `GameObject m_target`

- `RectTransform m_transTarget`


## Methods

- `Void _InitIfNot()`

- `Boolean _PrepareSelf(GameObject)`

- `IEnumerator _OnChangeBound(OptionBase)`

- `Void ClosePanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDetailNodeDialog : UICustomDialog`1
{
	private RectTransform _panel; // 0x40
	private Vector3 _padding; // 0x48
	private ViewBase _view; // 0x58
	private RectTransform _backRt; // 0x60
	private Boolean m_isInited; // 0x68
	private Camera m_targetCamera; // 0x70
	private GameObject m_target; // 0x78
	private RectTransform m_transTarget; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__PrepareSelf; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0__OnChangeBound; // 0x18
	private static DelegateBridge __Hotfix0_ClosePanel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2a09e7c VA: 0x7595021e7c
	private Void _InitIfNot() { }
	// RVA: 0x2a09f9c VA: 0x7595021f9c
	private Boolean _PrepareSelf(GameObject target) { }
	// RVA: 0x2a0a204 VA: 0x7595022204
	protected override Void OnRender(OptionBase option) { }
	// RVA: 0x2a0a314 VA: 0x7595022314
	private IEnumerator _OnChangeBound(OptionBase option) { }
	// RVA: 0x2a0a40c VA: 0x759502240c
	public Void ClosePanel() { }
	// RVA: 0x2a0a490 VA: 0x7595022490
	public Void .ctor() { }
}
```
# RoguelikeFragmentOverloadDialog

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `GameObject _panelHeavy`

- `GameObject _panelOverload`

- `CanvasGroup _checkBox`

- `RectTransform _backRt`

- `UIRenderTextureImage _bkgBlur`

- `Plugin _plugin`

- `Options m_options`

- `Boolean m_judgeResult`

- `FadeSwitchTween m_viewFade`

- `FadeSwitchTween m_checkBoxFade`


## Methods

- `Void OnCheckboxClick()`

- `Void OnCancel()`

- `Void OnConfirm()`

- `Void _ConfirmCheckBox()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFragmentOverloadDialog : UICustomDialog`1
{
	private GameObject _panelHeavy; // 0x58
	private GameObject _panelOverload; // 0x60
	private CanvasGroup _checkBox; // 0x68
	private RectTransform _backRt; // 0x70
	private UIRenderTextureImage _bkgBlur; // 0x78
	private Plugin _plugin; // 0x80
	private Options m_options; // 0x88
	private Boolean m_judgeResult; // 0xa8
	private FadeSwitchTween m_viewFade; // 0xb0
	private FadeSwitchTween m_checkBoxFade; // 0xb8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_OnCheckboxClick; // 0x18
	private static DelegateBridge __Hotfix0_OnCancel; // 0x20
	private static DelegateBridge __Hotfix0_OnConfirm; // 0x28
	private static DelegateBridge __Hotfix0__ConfirmCheckBox; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2a094e0 VA: 0x75950214e0
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2a09548 VA: 0x7595021548
	protected override Void OnInit() { }
	// RVA: 0x2a096cc VA: 0x75950216cc
	protected override Void OnRender(Options options) { }
	// RVA: 0x2a09800 VA: 0x7595021800
	public Void OnCheckboxClick() { }
	// RVA: 0x2a09888 VA: 0x7595021888
	public Void OnCancel() { }
	// RVA: 0x2a0990c VA: 0x759502190c
	public Void OnConfirm() { }
	// RVA: 0x2a09998 VA: 0x7595021998
	private Void _ConfirmCheckBox() { }
	// RVA: 0x2a09a3c VA: 0x7595021a3c
	public Void .ctor() { }
}
```
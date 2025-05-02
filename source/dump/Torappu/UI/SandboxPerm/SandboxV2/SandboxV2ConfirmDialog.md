# SandboxV2ConfirmDialog

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _viewContainer`

- `UIRenderTextureImage _blurBg`

- `SandboxV2ConfirmDialogView m_dialogView`

- `Action m_callback`

- `Action m_cancelCallback`

- `Action m_backPressCallback`


## Methods

- `String _GetCancelStr(Options)`

- `Void _OnViewCancelClicked()`

- `Void _OnViewConfirmClicked()`

- `Void _OnViewBackPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ConfirmDialog : UICustomDialog`1
{
	private RectTransform _viewContainer; // 0xa0
	private UIRenderTextureImage _blurBg; // 0xa8
	private SandboxV2ConfirmDialogView m_dialogView; // 0xb0
	private Action m_callback; // 0xb8
	private Action m_cancelCallback; // 0xc0
	private Action m_backPressCallback; // 0xc8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_BeforeDestroy; // 0x10
	private static DelegateBridge __Hotfix0__GetCancelStr; // 0x18
	private static DelegateBridge __Hotfix0__OnViewCancelClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnViewConfirmClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnViewBackPressed; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x250330c VA: 0x7594b1b30c
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2503374 VA: 0x7594b1b374
	protected override Void OnRender(Options options) { }
	// RVA: 0x2503cf0 VA: 0x7594b1bcf0
	protected override Void BeforeDestroy() { }
	// RVA: 0x25039a8 VA: 0x7594b1b9a8
	private String _GetCancelStr(Options options) { }
	// RVA: 0x2503da0 VA: 0x7594b1bda0
	private Void _OnViewCancelClicked() { }
	// RVA: 0x2503e24 VA: 0x7594b1be24
	private Void _OnViewConfirmClicked() { }
	// RVA: 0x2503ea8 VA: 0x7594b1bea8
	private Void _OnViewBackPressed() { }
	// RVA: 0x2503f34 VA: 0x7594b1bf34
	public Void .ctor() { }
}
```
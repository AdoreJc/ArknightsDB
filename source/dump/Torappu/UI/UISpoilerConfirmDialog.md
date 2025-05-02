# UISpoilerConfirmDialog

**Namespace:** `Torappu.UI`


## Fields

- `UIRenderTextureImage _bkgBlur`

- `Text _textDesc`


## Methods

- `Void OnConfirmClicked()`

- `Void OnFinishClicked()`

- `Void OnCancelClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISpoilerConfirmDialog : UICustomDialog`1
{
	private UIRenderTextureImage _bkgBlur; // 0x50
	private Text _textDesc; // 0x58
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x8
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnFinishClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnCancelClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2269480 VA: 0x7594881480
	protected override Void OnRender(Options options) { }
	// RVA: 0x226967c VA: 0x759488167c
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x22696e4 VA: 0x75948816e4
	public Void OnConfirmClicked() { }
	// RVA: 0x226979c VA: 0x759488179c
	public Void OnFinishClicked() { }
	// RVA: 0x2269854 VA: 0x7594881854
	public Void OnCancelClicked() { }
	// RVA: 0x22698d8 VA: 0x75948818d8
	public Void .ctor() { }
}
```
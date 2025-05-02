# UICommonAntiSpoilerDialog

**Namespace:** `Torappu.UI`


## Fields

- `UIRenderTextureImage _bkgBlur`

- `Text _textDesc`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnConfirmClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICommonAntiSpoilerDialog : UICustomDialog`1
{
	private UIRenderTextureImage _bkgBlur; // 0x48
	private Text _textDesc; // 0x50
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2267224 VA: 0x759487f224
	private Void _InitIfNot() { }
	// RVA: 0x2267340 VA: 0x759487f340
	protected override Void OnRender(Options options) { }
	// RVA: 0x22673e4 VA: 0x759487f3e4
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x226744c VA: 0x759487f44c
	public Void OnConfirmClicked() { }
	// RVA: 0x22674f0 VA: 0x759487f4f0
	public Void .ctor() { }
}
```
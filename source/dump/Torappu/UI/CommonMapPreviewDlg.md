# CommonMapPreviewDlg

**Namespace:** `Torappu.UI`


## Fields

- `UIRenderTextureImage _blurBg`

- `Image _imgMapPreview`

- `RectTransform _backTrans`


## Methods

- `Void _EventOnCloseDlg()`

- `Void EventOnClose()`

- `Void <>xLuaBaseProxy_OnInit()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CommonMapPreviewDlg : UICompDialog`1
{
	private UIRenderTextureImage _blurBg; // 0x48
	private Image _imgMapPreview; // 0x50
	private RectTransform _backTrans; // 0x58
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x10
	private static DelegateBridge __Hotfix0__EventOnCloseDlg; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClose; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x213a178 VA: 0x7594752178
	protected override Void OnInit() { }
	// RVA: 0x213a280 VA: 0x7594752280
	protected override Void OnRender(Input input) { }
	// RVA: 0x213a3f4 VA: 0x75947523f4
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x213a45c VA: 0x759475245c
	private Void _EventOnCloseDlg() { }
	// RVA: 0x213a530 VA: 0x7594752530
	public Void EventOnClose() { }
	// RVA: 0x213a598 VA: 0x7594752598
	public Void .ctor() { }
	// RVA: 0x213a628 VA: 0x7594752628
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x213a630 VA: 0x7594752630
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```
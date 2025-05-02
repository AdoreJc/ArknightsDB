# RoguelikeDungeonRollNodeDialog

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeDungeonRollNodeDialogPlugin _plugin`

- `UIRenderTextureImage _bkgBlur`

- `RectTransform _backRt`

- `Options m_options`


## Methods

- `Void OnConfirm()`

- `Void OnCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonRollNodeDialog : UICustomDialog`1
{
	private RoguelikeDungeonRollNodeDialogPlugin _plugin; // 0x58
	private UIRenderTextureImage _bkgBlur; // 0x60
	private RectTransform _backRt; // 0x68
	private Options m_options; // 0x70
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_OnConfirm; // 0x18
	private static DelegateBridge __Hotfix0_OnCancel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2a18ae8 VA: 0x7595030ae8
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2a18b50 VA: 0x7595030b50
	protected override Void OnInit() { }
	// RVA: 0x2a18cb8 VA: 0x7595030cb8
	protected override Void OnRender(Options options) { }
	// RVA: 0x2a18db8 VA: 0x7595030db8
	public Void OnConfirm() { }
	// RVA: 0x2a18e64 VA: 0x7595030e64
	public Void OnCancel() { }
	// RVA: 0x2a18f10 VA: 0x7595030f10
	public Void .ctor() { }
}
```
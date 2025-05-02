# SiracusaMapCharCardUnlockDialog

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Text _textCharName`

- `Text _textCharDesc`

- `TwoStateToggle _viewStateToggle`

- `UIAnimationLocation _animEnter`

- `UIRenderTextureImage _blurBg`

- `Text _textCloseTip`

- `Text _textCaption1`

- `Text _textCaption2`

- `UIAVGCharacter _avgChar`

- `Image _imgItalyName`

- `RectTransform _backRt`


## Methods

- `Sprite _GetItalyNameSprite(String)`

- `Void EventOnConfirm()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapCharCardUnlockDialog : UICustomDialog`1
{
	private Text _textCharName; // 0x48
	private Text _textCharDesc; // 0x50
	private TwoStateToggle _viewStateToggle; // 0x58
	private Graphic[] _themeGraphics; // 0x60
	private UIAnimationLocation _animEnter; // 0x68
	private UIRenderTextureImage _blurBg; // 0x78
	private Text _textCloseTip; // 0x80
	private Text _textCaption1; // 0x88
	private Text _textCaption2; // 0x90
	private UIAVGCharacter _avgChar; // 0x98
	private Image _imgItalyName; // 0xa0
	private RectTransform _backRt; // 0xa8
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__GetItalyNameSprite; // 0x10
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x23f5210 VA: 0x7594a0d210
	protected override Void OnInit() { }
	// RVA: 0x23f532c VA: 0x7594a0d32c
	protected override Void OnRender(Options options) { }
	// RVA: 0x23f57c8 VA: 0x7594a0d7c8
	private Sprite _GetItalyNameSprite(String spriteId) { }
	// RVA: 0x23f5968 VA: 0x7594a0d968
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x23f59d0 VA: 0x7594a0d9d0
	public Void EventOnConfirm() { }
	// RVA: 0x23f5a54 VA: 0x7594a0da54
	public Void .ctor() { }
}
```
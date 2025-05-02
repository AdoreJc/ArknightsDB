# SiracusaMapAreaUnlockDialog

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Image _imgAreaIcon`

- `Text _txtAreaName`

- `Text _txtAreaItalyName`

- `AnimationWrapper _animationWrapper`

- `UIRenderTextureImage _blurBg`

- `RectTransform _backRt`


## Methods

- `Sprite _GetAreaIconSprite(String)`

- `Void EventOnConfirm()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapAreaUnlockDialog : UICustomDialog`1
{
	private const String ANIM_ENTER; // 0x0
	private Image _imgAreaIcon; // 0x40
	private Text _txtAreaName; // 0x48
	private Text _txtAreaItalyName; // 0x50
	private AnimationWrapper _animationWrapper; // 0x58
	private UIRenderTextureImage _blurBg; // 0x60
	private RectTransform _backRt; // 0x68
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__GetAreaIconSprite; // 0x10
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x23f4c10 VA: 0x7594a0cc10
	protected override Void OnInit() { }
	// RVA: 0x23f4d2c VA: 0x7594a0cd2c
	protected override Void OnRender(Options options) { }
	// RVA: 0x23f4ef4 VA: 0x7594a0cef4
	private Sprite _GetAreaIconSprite(String spriteId) { }
	// RVA: 0x23f5094 VA: 0x7594a0d094
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x23f50fc VA: 0x7594a0d0fc
	public Void EventOnConfirm() { }
	// RVA: 0x23f5180 VA: 0x7594a0d180
	public Void .ctor() { }
}
```
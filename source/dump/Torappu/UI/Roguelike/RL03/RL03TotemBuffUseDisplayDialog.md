# RL03TotemBuffUseDisplayDialog

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `UIRenderTextureImage _blurBg`

- `Image _imgTotemLocation`

- `Image _imgTotemEffect`

- `Image _imgTotemBg`

- `Text _txtLocation`

- `Text _txtEffect`

- `Text _txtResonance`

- `UIAnimationLocation _normalAnim`

- `UIAnimationLocation _resonanceAnim`

- `RectTransform _effectContainer`

- `GameObject _blueEffect`

- `GameObject _greenEffect`

- `GameObject _redEffect`

- `GameObject _bossEffect`

- `Tween m_animTween`


## Methods

- `Void _RenderEffect(String, RoguelikeTotemColorType)`

- `Void _PlayAnim(Boolean, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffUseDisplayDialog : UICustomDialog`1
{
	private UIRenderTextureImage _blurBg; // 0x58
	private Image _imgTotemLocation; // 0x60
	private Image _imgTotemEffect; // 0x68
	private Image _imgTotemBg; // 0x70
	private Text _txtLocation; // 0x78
	private Text _txtEffect; // 0x80
	private Text _txtResonance; // 0x88
	private UIAnimationLocation _normalAnim; // 0x90
	private UIAnimationLocation _resonanceAnim; // 0xa0
	private RectTransform _effectContainer; // 0xb0
	private GameObject _blueEffect; // 0xb8
	private GameObject _greenEffect; // 0xc0
	private GameObject _redEffect; // 0xc8
	private GameObject _bossEffect; // 0xd0
	private Tween m_animTween; // 0xd8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__RenderEffect; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2ba5370 VA: 0x75951bd370
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2ba53d8 VA: 0x75951bd3d8
	protected override Void OnRender(Options options) { }
	// RVA: 0x2ba5690 VA: 0x75951bd690
	private Void _RenderEffect(String combineGroupName, RoguelikeTotemColorType colorType) { }
	// RVA: 0x2ba57e4 VA: 0x75951bd7e4
	private Void _PlayAnim(Boolean canResonance, Action callback) { }
	// RVA: 0x2ba5a84 VA: 0x75951bda84
	public Void .ctor() { }
}
```
# TuningChatResultDialog

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `GameObject _panelFail`

- `GameObject _panelFailHidden`

- `GameObject _panelSuccNormel`

- `GameObject _panelSuccMajor`

- `GameObject _panelSuccHidden`

- `GameObject _panelNormal`

- `GameObject _panelChar`

- `Text _resultUp`

- `Text _resultDown`

- `Text _resultCharUp`

- `Text _resultCharDown`

- `Text _titleNormalSuccess`

- `Text _titleNormalFail`

- `Text _titleNormalSpecial`

- `Text _titleCharSuccess`

- `Text _titleCharSpecial`

- `Image _avatar`

- `Image _avatarHidden`

- `UIRenderTextureImage _bkgBlur`

- `RectTransform _backRt`

- `UIAnimationLocation _normalAnim`

- `UIAnimationLocation _charAnim`

- `Tween m_enterTween`

- `Options m_options`


## Methods

- `Sprite _LoadAvatar(String)`

- `Void EventOnConfirm()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatResultDialog : UICustomDialog`1
{
	private GameObject _panelFail; // 0x68
	private GameObject _panelFailHidden; // 0x70
	private GameObject _panelSuccNormel; // 0x78
	private GameObject _panelSuccMajor; // 0x80
	private GameObject _panelSuccHidden; // 0x88
	private GameObject _panelNormal; // 0x90
	private GameObject _panelChar; // 0x98
	private Text _resultUp; // 0xa0
	private Text _resultDown; // 0xa8
	private Text _resultCharUp; // 0xb0
	private Text _resultCharDown; // 0xb8
	private Text _titleNormalSuccess; // 0xc0
	private Text _titleNormalFail; // 0xc8
	private Text _titleNormalSpecial; // 0xd0
	private Text _titleCharSuccess; // 0xd8
	private Text _titleCharSpecial; // 0xe0
	private Image _avatar; // 0xe8
	private Image _avatarHidden; // 0xf0
	private UIRenderTextureImage _bkgBlur; // 0xf8
	private RectTransform _backRt; // 0x100
	private UIAnimationLocation _normalAnim; // 0x108
	private UIAnimationLocation _charAnim; // 0x118
	private Tween m_enterTween; // 0x128
	private Options m_options; // 0x130
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0__LoadAvatar; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x231ab78 VA: 0x7594932b78
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x231abe0 VA: 0x7594932be0
	protected override Void OnInit() { }
	// RVA: 0x231acfc VA: 0x7594932cfc
	protected override Void OnRender(Options options) { }
	// RVA: 0x231b1c8 VA: 0x75949331c8
	private Sprite _LoadAvatar(String avatarId) { }
	// RVA: 0x231b270 VA: 0x7594933270
	public Void EventOnConfirm() { }
	// RVA: 0x231b314 VA: 0x7594933314
	public Void .ctor() { }
}
```
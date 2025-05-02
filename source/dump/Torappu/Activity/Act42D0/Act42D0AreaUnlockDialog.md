# Act42D0AreaUnlockDialog

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Image _areaCodeIcon`

- `Text _areaUnlockText`

- `UIAnimationLocation _enterAnim`

- `UIRenderTextureImage _bkgBlur`

- `RectTransform _backRt`

- `Tween m_enterTween`

- `Options m_options`


## Methods

- `Void EventOnConfirm()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0AreaUnlockDialog : UICustomDialog`1
{
	private Image _areaCodeIcon; // 0x50
	private Text _areaUnlockText; // 0x58
	private UIAnimationLocation _enterAnim; // 0x60
	private UIRenderTextureImage _bkgBlur; // 0x70
	private RectTransform _backRt; // 0x78
	private Tween m_enterTween; // 0x80
	private Options m_options; // 0x88
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31e3c34 VA: 0x75957fbc34
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x31e3c9c VA: 0x75957fbc9c
	protected override Void OnInit() { }
	// RVA: 0x31e3db8 VA: 0x75957fbdb8
	protected override Void OnRender(Options options) { }
	// RVA: 0x31e4044 VA: 0x75957fc044
	public Void EventOnConfirm() { }
	// RVA: 0x31e40e8 VA: 0x75957fc0e8
	public Void .ctor() { }
}
```
# EntryWindow

**Namespace:** ` `


## Fields

- `UIAnimationLocation _wndShow`

- `UIAnimationLocation _wndClose`

- `CanvasGroup _wndCg`

- `CanvasGroup _btnEnableCg`

- `CanvasGroup _btnDisableCg`

- `Boolean m_isInited`

- `FadeSwitchTween m_btnEnableFade`

- `FadeSwitchTween m_btnDisableFade`

- `UIBiAnimClipSwitchTween m_wndTween`


## Properties

- `Boolean isTweening`


## Methods

- `Void _InitIfNot()`

- `Boolean get_isTweening()`

- `Void Set(Boolean, Boolean, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EntryWindow : IHotfixable
{
	private UIAnimationLocation _wndShow; // 0x10
	private UIAnimationLocation _wndClose; // 0x20
	private CanvasGroup _wndCg; // 0x30
	private CanvasGroup _btnEnableCg; // 0x38
	private CanvasGroup _btnDisableCg; // 0x40
	private Boolean m_isInited; // 0x48
	private FadeSwitchTween m_btnEnableFade; // 0x50
	private FadeSwitchTween m_btnDisableFade; // 0x58
	private UIBiAnimClipSwitchTween m_wndTween; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_isTweening; // 0x8
	private static DelegateBridge __Hotfix0_Set; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isTweening { get; }

	// RVA: 0x294e554 VA: 0x7594f66554
	private Void _InitIfNot() { }
	// RVA: 0x294de00 VA: 0x7594f65e00
	public Boolean get_isTweening() { }
	// RVA: 0x294da10 VA: 0x7594f65a10
	public Void Set(Boolean isShow, Boolean isFastMode, String audioEvent) { }
	// RVA: 0x294e754 VA: 0x7594f66754
	public Void .ctor() { }
}
```
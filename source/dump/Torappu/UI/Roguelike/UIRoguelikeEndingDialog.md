# UIRoguelikeEndingDialog

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _bossIcon`

- `Text _endingDesc`

- `AnimationWrapper _animation`

- `Action m_onConfirm`


## Methods

- `Void OnCancelClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class UIRoguelikeEndingDialog : UICustomDialog`1
{
	private const String ANIM_NAME; // 0x0
	private Image _bossIcon; // 0x50
	private Text _endingDesc; // 0x58
	private AnimationWrapper _animation; // 0x60
	private Action m_onConfirm; // 0x68
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_OnCancelClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29e6e74 VA: 0x7594ffee74
	protected override Void OnRender(Options options) { }
	// RVA: 0x29e71a4 VA: 0x7594fff1a4
	public Void OnCancelClicked() { }
	// RVA: 0x29e7228 VA: 0x7594fff228
	public Void .ctor() { }
}
```
# Act36sideZoneFocusAnimView

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _exitAnim`

- `Boolean m_isInited`

- `UIBiAnimClipSwitchTween m_focusAnimTween`


## Properties

- `Boolean isShow`


## Methods

- `Void _InitIfNot()`

- `Boolean get_isShow()`

- `Void set_isShow(Boolean)`

- `Void Reset(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideZoneFocusAnimView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _enterAnim; // 0x18
	private UIAnimationLocation _exitAnim; // 0x28
	private List`1 _loopAnims; // 0x38
	private Boolean m_isInited; // 0x40
	private UIBiAnimClipSwitchTween m_focusAnimTween; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_isShow; // 0x8
	private static DelegateBridge __Hotfix0_set_isShow; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isShow { get; set; }

	// RVA: 0x3248f78 VA: 0x7595860f78
	private Void _InitIfNot() { }
	// RVA: 0x32491b4 VA: 0x75958611b4
	public Boolean get_isShow() { }
	// RVA: 0x3249230 VA: 0x7595861230
	public Void set_isShow(Boolean value) { }
	// RVA: 0x32492c4 VA: 0x75958612c4
	public Void Reset(Boolean isShow) { }
	// RVA: 0x3249358 VA: 0x7595861358
	public Void .ctor() { }
}
```
# TuningProductSlotGroupItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `CanvasGroup _slotGroup`

- `Single _groupTweenDuration`

- `Boolean _defaultShow`

- `FadeSwitchTween m_fadeSwitchTween`

- `Boolean m_isInited`


## Methods

- `Void Render(Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductSlotGroupItemView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _slotGroup; // 0x18
	private Single _groupTweenDuration; // 0x20
	private Boolean _defaultShow; // 0x24
	private FadeSwitchTween m_fadeSwitchTween; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x232f288 VA: 0x7594947288
	public Void Render(Boolean isShow) { }
	// RVA: 0x23376e0 VA: 0x759494f6e0
	private Void _InitIfNot() { }
	// RVA: 0x23377d8 VA: 0x759494f7d8
	public Void .ctor() { }
}
```
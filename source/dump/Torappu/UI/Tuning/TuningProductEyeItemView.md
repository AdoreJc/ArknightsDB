# TuningProductEyeItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `CanvasGroup _eyeCanvasGroup`

- `UIAnimationLocation _showAnimLocation`

- `Single _eyeShowAlpha`

- `Single _eyeHideAlpha`

- `Single _eyeTweenDuration`

- `EyeSwitchTween m_eyeSwitchTween`

- `Boolean m_isInited`


## Methods

- `Void Render(Boolean)`

- `Void ResetStatus(Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductEyeItemView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _eyeCanvasGroup; // 0x18
	private UIAnimationLocation _showAnimLocation; // 0x20
	private Single _eyeShowAlpha; // 0x30
	private Single _eyeHideAlpha; // 0x34
	private Single _eyeTweenDuration; // 0x38
	private EyeSwitchTween m_eyeSwitchTween; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ResetStatus; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23342b8 VA: 0x759494c2b8
	public Void Render(Boolean isShow) { }
	// RVA: 0x233441c VA: 0x759494c41c
	public Void ResetStatus(Boolean isShow) { }
	// RVA: 0x233434c VA: 0x759494c34c
	private Void _InitIfNot() { }
	// RVA: 0x233453c VA: 0x759494c53c
	public Void .ctor() { }
}
```
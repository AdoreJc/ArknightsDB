# BuildingCharCtrlTouchBtn

**Namespace:** `Torappu.Building.UI`


## Fields

- `CanvasGroup _canvasGroupEnable`

- `CanvasGroup _canvasGroupActive`

- `Button _btnTouch`

- `FadeSwitchTween m_enableFadeTween`

- `FadeSwitchTween m_activeFadeTween`


## Methods

- `Void Render(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingCharCtrlTouchBtn : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasGroupEnable; // 0x18
	private CanvasGroup _canvasGroupActive; // 0x20
	private Button _btnTouch; // 0x28
	private FadeSwitchTween m_enableFadeTween; // 0x30
	private FadeSwitchTween m_activeFadeTween; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3d32db4 VA: 0x759634adb4
	public Void Render(Boolean isEnable, Boolean isActive) { }
	// RVA: 0x3d34170 VA: 0x759634c170
	public Void .ctor() { }
}
```
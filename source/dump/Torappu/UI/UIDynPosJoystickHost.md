# UIDynPosJoystickHost

**Namespace:** `Torappu.UI`


## Fields

- `String _joystickName`

- `RectTransform _panelJoystick`

- `CanvasGroup _canvasGroupJoystick`

- `Graphic _graphicTarget`

- `Boolean m_isInited`

- `UISwitchTween m_switchTween`

- `CanvasScaler m_rootCanvasScaler`

- `UIJoystickController m_joystickController`


## Properties

- `RectTransform panelJoystick`

- `UIJoystickController joystickController`

- `UISwitchTween switchTween`


## Methods

- `RectTransform get_panelJoystick()`

- `UIJoystickController get_joystickController()`

- `UISwitchTween get_switchTween()`

- `Void Start()`

- `Void Update()`

- `Void _OnJoystickDragStop()`

- `Void OnPointerDown(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIDynPosJoystickHost : MonoBehaviour, IHotfixable, IPointerDownHandler, IEventSystemHandler
{
	private String _joystickName; // 0x18
	private RectTransform _panelJoystick; // 0x20
	private CanvasGroup _canvasGroupJoystick; // 0x28
	private Graphic _graphicTarget; // 0x30
	private Boolean m_isInited; // 0x38
	private UISwitchTween m_switchTween; // 0x40
	private CanvasScaler m_rootCanvasScaler; // 0x48
	private UIJoystickController m_joystickController; // 0x50
	private static DelegateBridge __Hotfix0_get_panelJoystick; // 0x0
	private static DelegateBridge __Hotfix0_get_joystickController; // 0x8
	private static DelegateBridge __Hotfix0_get_switchTween; // 0x10
	private static DelegateBridge __Hotfix0_Start; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__OnJoystickDragStop; // 0x30
	private static DelegateBridge __Hotfix0_InitSwitchTween; // 0x38
	private static DelegateBridge __Hotfix0_CalculateJoystickPos; // 0x40
	private static DelegateBridge __Hotfix0_ResetJoystick; // 0x48
	private static DelegateBridge __Hotfix0_OnPointerDown; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	protected RectTransform panelJoystick { get; }
	protected UIJoystickController joystickController { get; }
	protected UISwitchTween switchTween { get; }

	// RVA: 0x21948dc VA: 0x75947ac8dc
	protected RectTransform get_panelJoystick() { }
	// RVA: 0x2194944 VA: 0x75947ac944
	protected UIJoystickController get_joystickController() { }
	// RVA: 0x21949ac VA: 0x75947ac9ac
	protected UISwitchTween get_switchTween() { }
	// RVA: 0x2194a14 VA: 0x75947aca14
	private Void Start() { }
	// RVA: 0x2194a84 VA: 0x75947aca84
	private Void Update() { }
	// RVA: 0x2194b64 VA: 0x75947acb64
	protected virtual Void _InitIfNot() { }
	// RVA: 0x2194f64 VA: 0x75947acf64
	private Void _OnJoystickDragStop() { }
	// RVA: 0x2194fd4 VA: 0x75947acfd4
	protected virtual UISwitchTween InitSwitchTween(CanvasGroup canvasGroupJoystick) { }
	// RVA: 0x2195090 VA: 0x75947ad090
	protected virtual Vector2 CalculateJoystickPos(PointerEventData eventData) { }
	// RVA: 0x219515c VA: 0x75947ad15c
	protected virtual Void ResetJoystick() { }
	// RVA: 0x21951d4 VA: 0x75947ad1d4
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x2195358 VA: 0x75947ad358
	public Void .ctor() { }
}
```
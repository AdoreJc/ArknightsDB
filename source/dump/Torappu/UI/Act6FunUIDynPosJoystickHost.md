# Act6FunUIDynPosJoystickHost

**Namespace:** `Torappu.UI`


## Fields

- `Single _inactiveAlpha`

- `Single _activeAlpha`

- `RectTransform _joystickRestrictArea`

- `Vector2 m_defaultJoystickPos`

- `EnableStateWithKey m_isJoystickDisabled`


## Properties

- `Boolean isJoystickDisabled`


## Methods

- `Boolean get_isJoystickDisabled()`

- `Void SetJoystickDisable(Boolean, String)`

- `Void <>xLuaBaseProxy__InitIfNot()`

- `UISwitchTween <>xLuaBaseProxy_InitSwitchTween(CanvasGroup)`

- `Vector2 <>xLuaBaseProxy_CalculateJoystickPos(PointerEventData)`

- `Void <>xLuaBaseProxy_ResetJoystick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class Act6FunUIDynPosJoystickHost : UIDynPosJoystickHost
{
	public const Single DEFAULT_TWEEN_DURATION; // 0x0
	private Single _inactiveAlpha; // 0x58
	private Single _activeAlpha; // 0x5c
	private RectTransform _joystickRestrictArea; // 0x60
	private Vector2 m_defaultJoystickPos; // 0x68
	private EnableStateWithKey m_isJoystickDisabled; // 0x70
	private static DelegateBridge __Hotfix0_get_isJoystickDisabled; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_InitSwitchTween; // 0x10
	private static DelegateBridge __Hotfix0_CalculateJoystickPos; // 0x18
	private static DelegateBridge __Hotfix0_ResetJoystick; // 0x20
	private static DelegateBridge __Hotfix0_SetJoystickDisable; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean isJoystickDisabled { get; }

	// RVA: 0x20f5ea4 VA: 0x759470dea4
	public Boolean get_isJoystickDisabled() { }
	// RVA: 0x20fbf58 VA: 0x7594713f58
	protected override Void _InitIfNot() { }
	// RVA: 0x20fbfe8 VA: 0x7594713fe8
	protected override UISwitchTween InitSwitchTween(CanvasGroup canvasGroupJoystick) { }
	// RVA: 0x20fc1e4 VA: 0x75947141e4
	protected override Vector2 CalculateJoystickPos(PointerEventData eventData) { }
	// RVA: 0x20fc33c VA: 0x759471433c
	protected override Void ResetJoystick() { }
	// RVA: 0x20f6aac VA: 0x759470eaac
	public Void SetJoystickDisable(Boolean isDisable, String disableKey) { }
	// RVA: 0x20fc3c8 VA: 0x75947143c8
	public Void .ctor() { }
	// RVA: 0x20fc484 VA: 0x7594714484
	private Void <>xLuaBaseProxy__InitIfNot() { }
	// RVA: 0x20fc48c VA: 0x759471448c
	private UISwitchTween <>xLuaBaseProxy_InitSwitchTween(CanvasGroup P0) { }
	// RVA: 0x20fc494 VA: 0x7594714494
	private Vector2 <>xLuaBaseProxy_CalculateJoystickPos(PointerEventData P0) { }
	// RVA: 0x20fc49c VA: 0x759471449c
	private Void <>xLuaBaseProxy_ResetJoystick() { }
}
```
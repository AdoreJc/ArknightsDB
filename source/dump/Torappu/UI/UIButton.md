# UIButton

**Namespace:** `Torappu.UI`


## Fields

- `ClickGuardModule _clickGuard`

- `AudioModule _audio`

- `LongPressModule _longPress`

- `BindKeyCodeModule _bindKey`

- `TickFunction m_tickLongPress`


## Properties

- `ClickGuardEnum clickableCheckRule`


## Methods

- `ClickGuardEnum get_clickableCheckRule()`

- `Void SetSelfDefineCheck(Func`1)`

- `Boolean CheckSelfDefineFuncClick()`

- `Void SetBindStateDirty()`

- `Void _OnTickForLongPress(Single)`

- `Void _StartTickLongPress()`

- `Void _StopTickLongPress()`

- `Void InterruptClickState()`

- `Boolean TryTickPressByKeyCode()`

- `Void _InterruptAllPress()`

- `Void _TryTriggerClick(Boolean)`

- `Boolean _CheckButtonClickEnabled()`

- `KeyBoardVirtualButtonEnum GetBindKeyCodeEnum()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.UI
public class UIButton : Button
{
	private ClickGuardModule _clickGuard; // 0x100
	private AudioModule _audio; // 0x108
	private LongPressModule _longPress; // 0x110
	private BindKeyCodeModule _bindKey; // 0x118
	private TickFunction m_tickLongPress; // 0x120
	public const Single DEFAULT_COOLDOWN; // 0x0
	private const String EDITOR_LONG_PRESS_PREFIX; // 0x0
	private const String EDITOR_LONG_PRESS_GROUP; // 0x0

	public ClickGuardEnum clickableCheckRule { get; }

	// RVA: 0x677ba34 VA: 0x7598d93a34
	public ClickGuardEnum get_clickableCheckRule() { }
	// RVA: 0x677ba50 VA: 0x7598d93a50
	public Void SetSelfDefineCheck(Func`1 checkFunc) { }
	// RVA: 0x677ba6c VA: 0x7598d93a6c
	public Boolean CheckSelfDefineFuncClick() { }
	// RVA: 0x677bac4 VA: 0x7598d93ac4
	public override Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x677bac8 VA: 0x7598d93ac8
	public override Void OnSubmit(BaseEventData eventData) { }
	// RVA: 0x677bacc VA: 0x7598d93acc
	public override Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x677bff8 VA: 0x7598d93ff8
	public override Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x677c234 VA: 0x7598d94234
	protected override Void OnEnable() { }
	// RVA: 0x677c2e0 VA: 0x7598d942e0
	protected override Void OnDisable() { }
	// RVA: 0x677c250 VA: 0x7598d94250
	public Void SetBindStateDirty() { }
	// RVA: 0x677c518 VA: 0x7598d94518
	protected override Void OnDestroy() { }
	// RVA: 0x677c6d4 VA: 0x7598d946d4
	private Void _OnTickForLongPress(Single timeDelta) { }
	// RVA: 0x677bda8 VA: 0x7598d93da8
	private Void _StartTickLongPress() { }
	// RVA: 0x677c7f4 VA: 0x7598d947f4
	private Void _StopTickLongPress() { }
	// RVA: 0x677c808 VA: 0x7598d94808
	public Void InterruptClickState() { }
	// RVA: 0x677c80c VA: 0x7598d9480c
	public Boolean TryTickPressByKeyCode() { }
	// RVA: 0x677c304 VA: 0x7598d94304
	private Void _InterruptAllPress() { }
	// RVA: 0x677c174 VA: 0x7598d94174
	private Void _TryTriggerClick(Boolean isPressed) { }
	// RVA: 0x677bbb0 VA: 0x7598d93bb0
	private Boolean _CheckButtonClickEnabled() { }
	// RVA: 0x677cddc VA: 0x7598d94ddc
	public KeyBoardVirtualButtonEnum GetBindKeyCodeEnum() { }
	// RVA: 0x677cdf8 VA: 0x7598d94df8
	public Void .ctor() { }
}
```
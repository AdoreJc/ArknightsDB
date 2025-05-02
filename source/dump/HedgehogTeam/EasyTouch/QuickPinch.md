# QuickPinch

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `OnPinchAction onPinchAction`

- `Boolean isGestureOnMe`

- `ActionTiggering actionTriggering`

- `ActionPinchDirection pinchDirection`

- `Single axisActionValue`

- `Boolean enableSimpleAction`


## Methods

- `Void OnDestroy()`

- `Void UnsubscribeEvent()`

- `Void On_Pinch(Gesture)`

- `Void On_PinchIn(Gesture)`

- `Void On_PinchOut(Gesture)`

- `Void On_PichEnd(Gesture)`

- `Void DoAction(Gesture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class QuickPinch : QuickBase
{
	public OnPinchAction onPinchAction; // 0x70
	public Boolean isGestureOnMe; // 0x78
	public ActionTiggering actionTriggering; // 0x7c
	public ActionPinchDirection pinchDirection; // 0x80
	private Single axisActionValue; // 0x84
	public Boolean enableSimpleAction; // 0x88


	// RVA: 0x375d4b8 VA: 0x7595d754b8
	public Void .ctor() { }
	// RVA: 0x375d570 VA: 0x7595d75570
	public override Void OnEnable() { }
	// RVA: 0x375d6dc VA: 0x7595d756dc
	public override Void OnDisable() { }
	// RVA: 0x375d84c VA: 0x7595d7584c
	private Void OnDestroy() { }
	// RVA: 0x375d6e0 VA: 0x7595d756e0
	private Void UnsubscribeEvent() { }
	// RVA: 0x375d850 VA: 0x7595d75850
	private Void On_Pinch(Gesture gesture) { }
	// RVA: 0x375da80 VA: 0x7595d75a80
	private Void On_PinchIn(Gesture gesture) { }
	// RVA: 0x375da9c VA: 0x7595d75a9c
	private Void On_PinchOut(Gesture gesture) { }
	// RVA: 0x375dab8 VA: 0x7595d75ab8
	private Void On_PichEnd(Gesture gesture) { }
	// RVA: 0x375d868 VA: 0x7595d75868
	private Void DoAction(Gesture gesture) { }
}
```
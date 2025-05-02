# QuickTwist

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `OnTwistAction onTwistAction`

- `Boolean isGestureOnMe`

- `ActionTiggering actionTriggering`

- `ActionRotationDirection rotationDirection`

- `Single axisActionValue`

- `Boolean enableSimpleAction`


## Methods

- `Void OnDestroy()`

- `Void UnsubscribeEvent()`

- `Void On_Twist(Gesture)`

- `Void On_TwistEnd(Gesture)`

- `Boolean IsRightRotation(Gesture)`

- `Void DoAction(Gesture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class QuickTwist : QuickBase
{
	public OnTwistAction onTwistAction; // 0x70
	public Boolean isGestureOnMe; // 0x78
	public ActionTiggering actionTriggering; // 0x7c
	public ActionRotationDirection rotationDirection; // 0x80
	private Single axisActionValue; // 0x84
	public Boolean enableSimpleAction; // 0x88


	// RVA: 0x375ecf8 VA: 0x7595d76cf8
	public Void .ctor() { }
	// RVA: 0x375edb0 VA: 0x7595d76db0
	public override Void OnEnable() { }
	// RVA: 0x375ee7c VA: 0x7595d76e7c
	public override Void OnDisable() { }
	// RVA: 0x375ef4c VA: 0x7595d76f4c
	private Void OnDestroy() { }
	// RVA: 0x375ee80 VA: 0x7595d76e80
	private Void UnsubscribeEvent() { }
	// RVA: 0x375ef50 VA: 0x7595d76f50
	private Void On_Twist(Gesture gesture) { }
	// RVA: 0x375f220 VA: 0x7595d77220
	private Void On_TwistEnd(Gesture gesture) { }
	// RVA: 0x375ef90 VA: 0x7595d76f90
	private Boolean IsRightRotation(Gesture gesture) { }
	// RVA: 0x375f020 VA: 0x7595d77020
	private Void DoAction(Gesture gesture) { }
}
```
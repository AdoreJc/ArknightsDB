# QuickSwipe

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `OnSwipeAction onSwipeAction`

- `Boolean allowSwipeStartOverMe`

- `ActionTriggering actionTriggering`

- `SwipeDirection swipeDirection`

- `Single axisActionValue`

- `Boolean enableSimpleAction`


## Methods

- `Void OnDestroy()`

- `Void UnsubscribeEvent()`

- `Void On_Swipe(Gesture)`

- `Void On_SwipeEnd(Gesture)`

- `Void On_DragEnd(Gesture)`

- `Void On_Drag(Gesture)`

- `Boolean isRightDirection(Gesture)`

- `Void DoAction(Gesture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class QuickSwipe : QuickBase
{
	public OnSwipeAction onSwipeAction; // 0x70
	public Boolean allowSwipeStartOverMe; // 0x78
	public ActionTriggering actionTriggering; // 0x7c
	public SwipeDirection swipeDirection; // 0x80
	private Single axisActionValue; // 0x84
	public Boolean enableSimpleAction; // 0x88


	// RVA: 0x375db14 VA: 0x7595d75b14
	public Void .ctor() { }
	// RVA: 0x375dbdc VA: 0x7595d75bdc
	public override Void OnEnable() { }
	// RVA: 0x375dd48 VA: 0x7595d75d48
	public override Void OnDisable() { }
	// RVA: 0x375deb8 VA: 0x7595d75eb8
	private Void OnDestroy() { }
	// RVA: 0x375dd4c VA: 0x7595d75d4c
	private Void UnsubscribeEvent() { }
	// RVA: 0x375debc VA: 0x7595d75ebc
	private Void On_Swipe(Gesture gesture) { }
	// RVA: 0x375e1f8 VA: 0x7595d761f8
	private Void On_SwipeEnd(Gesture gesture) { }
	// RVA: 0x375e29c VA: 0x7595d7629c
	private Void On_DragEnd(Gesture gesture) { }
	// RVA: 0x375e34c VA: 0x7595d7634c
	private Void On_Drag(Gesture gesture) { }
	// RVA: 0x375dfc4 VA: 0x7595d75fc4
	private Boolean isRightDirection(Gesture gesture) { }
	// RVA: 0x375e194 VA: 0x7595d76194
	private Void DoAction(Gesture gesture) { }
}
```
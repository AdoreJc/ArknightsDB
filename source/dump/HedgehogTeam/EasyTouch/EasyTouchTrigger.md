# EasyTouchTrigger

**Namespace:** `HedgehogTeam.EasyTouch`


## Methods

- `Void Start()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnDestroy()`

- `Void SubscribeEasyTouchEvent()`

- `Void UnsubscribeEasyTouchEvent()`

- `Void On_TouchStart(Gesture)`

- `Void On_TouchDown(Gesture)`

- `Void On_TouchUp(Gesture)`

- `Void On_SimpleTap(Gesture)`

- `Void On_DoubleTap(Gesture)`

- `Void On_LongTapStart(Gesture)`

- `Void On_LongTap(Gesture)`

- `Void On_LongTapEnd(Gesture)`

- `Void On_SwipeStart(Gesture)`

- `Void On_Swipe(Gesture)`

- `Void On_SwipeEnd(Gesture)`

- `Void On_DragStart(Gesture)`

- `Void On_Drag(Gesture)`

- `Void On_DragEnd(Gesture)`

- `Void On_Cancel(Gesture)`

- `Void On_TouchStart2Fingers(Gesture)`

- `Void On_TouchDown2Fingers(Gesture)`

- `Void On_TouchUp2Fingers(Gesture)`

- `Void On_LongTapStart2Fingers(Gesture)`

- `Void On_LongTap2Fingers(Gesture)`

- `Void On_LongTapEnd2Fingers(Gesture)`

- `Void On_DragStart2Fingers(Gesture)`

- `Void On_Drag2Fingers(Gesture)`

- `Void On_DragEnd2Fingers(Gesture)`

- `Void On_SwipeStart2Fingers(Gesture)`

- `Void On_Swipe2Fingers(Gesture)`

- `Void On_SwipeEnd2Fingers(Gesture)`

- `Void On_Twist(Gesture)`

- `Void On_TwistEnd(Gesture)`

- `Void On_Pinch(Gesture)`

- `Void On_PinchOut(Gesture)`

- `Void On_PinchIn(Gesture)`

- `Void On_PinchEnd(Gesture)`

- `Void On_SimpleTap2Fingers(Gesture)`

- `Void On_DoubleTap2Fingers(Gesture)`

- `Void On_UIElementTouchUp(Gesture)`

- `Void On_OverUIElement(Gesture)`

- `Void AddTrigger(EvtType)`

- `Boolean SetTriggerEnable(String, Boolean)`

- `Boolean GetTriggerEnable(String)`

- `Void TriggerScheduler(EvtType, Gesture)`

- `Boolean IsRecevier4(EvtType)`

- `EasyTouchReceiver GetTrigger(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class EasyTouchTrigger : MonoBehaviour
{
	public List`1 receivers; // 0x18


	// RVA: 0x37549a4 VA: 0x7595d6c9a4
	private Void Start() { }
	// RVA: 0x3754a2c VA: 0x7595d6ca2c
	private Void OnEnable() { }
	// RVA: 0x3755848 VA: 0x7595d6d848
	private Void OnDisable() { }
	// RVA: 0x3756408 VA: 0x7595d6e408
	private Void OnDestroy() { }
	// RVA: 0x3754a30 VA: 0x7595d6ca30
	private Void SubscribeEasyTouchEvent() { }
	// RVA: 0x375584c VA: 0x7595d6d84c
	private Void UnsubscribeEasyTouchEvent() { }
	// RVA: 0x37599cc VA: 0x7595d719cc
	private Void On_TouchStart(Gesture gesture) { }
	// RVA: 0x375a294 VA: 0x7595d72294
	private Void On_TouchDown(Gesture gesture) { }
	// RVA: 0x375a2a0 VA: 0x7595d722a0
	private Void On_TouchUp(Gesture gesture) { }
	// RVA: 0x375a2ac VA: 0x7595d722ac
	private Void On_SimpleTap(Gesture gesture) { }
	// RVA: 0x375a2b8 VA: 0x7595d722b8
	private Void On_DoubleTap(Gesture gesture) { }
	// RVA: 0x375a2c4 VA: 0x7595d722c4
	private Void On_LongTapStart(Gesture gesture) { }
	// RVA: 0x375a2d0 VA: 0x7595d722d0
	private Void On_LongTap(Gesture gesture) { }
	// RVA: 0x375a2dc VA: 0x7595d722dc
	private Void On_LongTapEnd(Gesture gesture) { }
	// RVA: 0x375a2e8 VA: 0x7595d722e8
	private Void On_SwipeStart(Gesture gesture) { }
	// RVA: 0x375a2f4 VA: 0x7595d722f4
	private Void On_Swipe(Gesture gesture) { }
	// RVA: 0x375a300 VA: 0x7595d72300
	private Void On_SwipeEnd(Gesture gesture) { }
	// RVA: 0x375a30c VA: 0x7595d7230c
	private Void On_DragStart(Gesture gesture) { }
	// RVA: 0x375a318 VA: 0x7595d72318
	private Void On_Drag(Gesture gesture) { }
	// RVA: 0x375a324 VA: 0x7595d72324
	private Void On_DragEnd(Gesture gesture) { }
	// RVA: 0x375a330 VA: 0x7595d72330
	private Void On_Cancel(Gesture gesture) { }
	// RVA: 0x375a33c VA: 0x7595d7233c
	private Void On_TouchStart2Fingers(Gesture gesture) { }
	// RVA: 0x375a348 VA: 0x7595d72348
	private Void On_TouchDown2Fingers(Gesture gesture) { }
	// RVA: 0x375a354 VA: 0x7595d72354
	private Void On_TouchUp2Fingers(Gesture gesture) { }
	// RVA: 0x375a360 VA: 0x7595d72360
	private Void On_LongTapStart2Fingers(Gesture gesture) { }
	// RVA: 0x375a36c VA: 0x7595d7236c
	private Void On_LongTap2Fingers(Gesture gesture) { }
	// RVA: 0x375a378 VA: 0x7595d72378
	private Void On_LongTapEnd2Fingers(Gesture gesture) { }
	// RVA: 0x375a384 VA: 0x7595d72384
	private Void On_DragStart2Fingers(Gesture gesture) { }
	// RVA: 0x375a390 VA: 0x7595d72390
	private Void On_Drag2Fingers(Gesture gesture) { }
	// RVA: 0x375a39c VA: 0x7595d7239c
	private Void On_DragEnd2Fingers(Gesture gesture) { }
	// RVA: 0x375a3a8 VA: 0x7595d723a8
	private Void On_SwipeStart2Fingers(Gesture gesture) { }
	// RVA: 0x375a3b4 VA: 0x7595d723b4
	private Void On_Swipe2Fingers(Gesture gesture) { }
	// RVA: 0x375a3c0 VA: 0x7595d723c0
	private Void On_SwipeEnd2Fingers(Gesture gesture) { }
	// RVA: 0x375a3cc VA: 0x7595d723cc
	private Void On_Twist(Gesture gesture) { }
	// RVA: 0x375a3d8 VA: 0x7595d723d8
	private Void On_TwistEnd(Gesture gesture) { }
	// RVA: 0x375a3e4 VA: 0x7595d723e4
	private Void On_Pinch(Gesture gesture) { }
	// RVA: 0x375a3f0 VA: 0x7595d723f0
	private Void On_PinchOut(Gesture gesture) { }
	// RVA: 0x375a3fc VA: 0x7595d723fc
	private Void On_PinchIn(Gesture gesture) { }
	// RVA: 0x375a408 VA: 0x7595d72408
	private Void On_PinchEnd(Gesture gesture) { }
	// RVA: 0x375a414 VA: 0x7595d72414
	private Void On_SimpleTap2Fingers(Gesture gesture) { }
	// RVA: 0x375a420 VA: 0x7595d72420
	private Void On_DoubleTap2Fingers(Gesture gesture) { }
	// RVA: 0x375a42c VA: 0x7595d7242c
	private Void On_UIElementTouchUp(Gesture gesture) { }
	// RVA: 0x375a438 VA: 0x7595d72438
	private Void On_OverUIElement(Gesture gesture) { }
	// RVA: 0x375a444 VA: 0x7595d72444
	public Void AddTrigger(EvtType ev) { }
	// RVA: 0x375a5a0 VA: 0x7595d725a0
	public Boolean SetTriggerEnable(String triggerName, Boolean value) { }
	// RVA: 0x375a6ac VA: 0x7595d726ac
	public Boolean GetTriggerEnable(String triggerName) { }
	// RVA: 0x37599d8 VA: 0x7595d719d8
	private Void TriggerScheduler(EvtType evnt, Gesture gesture) { }
	// RVA: 0x375640c VA: 0x7595d6e40c
	private Boolean IsRecevier4(EvtType evnt) { }
	// RVA: 0x375a5c4 VA: 0x7595d725c4
	private EasyTouchReceiver GetTrigger(String triggerName) { }
	// RVA: 0x375a6dc VA: 0x7595d726dc
	public Void .ctor() { }
}
```
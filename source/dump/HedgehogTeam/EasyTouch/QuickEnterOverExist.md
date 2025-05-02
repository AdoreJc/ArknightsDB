# QuickEnterOverExist

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `OnTouchEnter onTouchEnter`

- `OnTouchOver onTouchOver`

- `OnTouchExit onTouchExit`


## Methods

- `Void Awake()`

- `Void OnDestroy()`

- `Void UnsubscribeEvent()`

- `Void On_TouchDown(Gesture)`

- `Void On_TouchUp(Gesture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class QuickEnterOverExist : QuickBase
{
	public OnTouchEnter onTouchEnter; // 0x70
	public OnTouchOver onTouchOver; // 0x78
	public OnTouchExit onTouchExit; // 0x80
	private Boolean[] fingerOver; // 0x88


	// RVA: 0x375c718 VA: 0x7595d74718
	public Void .ctor() { }
	// RVA: 0x375c800 VA: 0x7595d74800
	private Void Awake() { }
	// RVA: 0x375c840 VA: 0x7595d74840
	public override Void OnEnable() { }
	// RVA: 0x375c90c VA: 0x7595d7490c
	public override Void OnDisable() { }
	// RVA: 0x375c9dc VA: 0x7595d749dc
	private Void OnDestroy() { }
	// RVA: 0x375c910 VA: 0x7595d74910
	private Void UnsubscribeEvent() { }
	// RVA: 0x375c9e0 VA: 0x7595d749e0
	private Void On_TouchDown(Gesture gesture) { }
	// RVA: 0x375cc6c VA: 0x7595d74c6c
	private Void On_TouchUp(Gesture gesture) { }
}
```
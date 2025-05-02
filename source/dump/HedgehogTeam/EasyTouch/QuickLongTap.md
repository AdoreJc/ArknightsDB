# QuickLongTap

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `OnLongTap onLongTap`

- `ActionTriggering actionTriggering`

- `Gesture currentGesture`


## Methods

- `Void Update()`

- `Void DoAction(Gesture)`

- `Boolean IsOverMe(Gesture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class QuickLongTap : QuickBase
{
	public OnLongTap onLongTap; // 0x70
	public ActionTriggering actionTriggering; // 0x78
	private Gesture currentGesture; // 0x80


	// RVA: 0x375cddc VA: 0x7595d74ddc
	public Void .ctor() { }
	// RVA: 0x375ce94 VA: 0x7595d74e94
	private Void Update() { }
	// RVA: 0x375d1dc VA: 0x7595d751dc
	private Void DoAction(Gesture gesture) { }
	// RVA: 0x375d060 VA: 0x7595d75060
	private Boolean IsOverMe(Gesture gesture) { }
}
```
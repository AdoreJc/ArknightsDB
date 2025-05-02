# QuickTap

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `OnTap onTap`

- `ActionTriggering actionTriggering`

- `Gesture currentGesture`


## Methods

- `Void Update()`

- `Void DoAction(Gesture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class QuickTap : QuickBase
{
	public OnTap onTap; // 0x70
	public ActionTriggering actionTriggering; // 0x78
	private Gesture currentGesture; // 0x80


	// RVA: 0x375e444 VA: 0x7595d76444
	public Void .ctor() { }
	// RVA: 0x375e4fc VA: 0x7595d764fc
	private Void Update() { }
	// RVA: 0x375e5c4 VA: 0x7595d765c4
	private Void DoAction(Gesture gesture) { }
}
```
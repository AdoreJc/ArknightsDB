# QuickTouch

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `OnTouch onTouch`

- `OnTouchNotOverMe onTouchNotOverMe`

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
public class QuickTouch : QuickBase
{
	public OnTouch onTouch; // 0x70
	public OnTouchNotOverMe onTouchNotOverMe; // 0x78
	public ActionTriggering actionTriggering; // 0x80
	private Gesture currentGesture; // 0x88


	// RVA: 0x375e7ac VA: 0x7595d767ac
	public Void .ctor() { }
	// RVA: 0x375e864 VA: 0x7595d76864
	private Void Update() { }
	// RVA: 0x375ebf4 VA: 0x7595d76bf4
	private Void DoAction(Gesture gesture) { }
	// RVA: 0x375ea78 VA: 0x7595d76a78
	private Boolean IsOverMe(Gesture gesture) { }
}
```
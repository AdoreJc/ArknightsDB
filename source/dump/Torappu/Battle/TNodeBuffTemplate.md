# TNodeBuffTemplate

**Namespace:** `Torappu.Battle`


## Fields

- `String templateKey`

- `String effectKey`

- `OnEventPriority onEventPriority`

- `IDToTNodeDataActionMap nodeDataActionDict`


## Methods

- `BuffTemplate ConvertToBuffTemplate()`

- `EventToActionMap GetEventToActionMap()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TNodeBuffTemplate
{
	public String templateKey; // 0x10
	public String effectKey; // 0x18
	public OnEventPriority onEventPriority; // 0x20
	public IDToTNodeDataActionMap nodeDataActionDict; // 0x28


	// RVA: 0x1c45458 VA: 0x759425d458
	public BuffTemplate ConvertToBuffTemplate() { }
	// RVA: 0x1c454f4 VA: 0x759425d4f4
	public EventToActionMap GetEventToActionMap() { }
	// RVA: 0x1c45ad0 VA: 0x759425dad0
	public override String ToString() { }
	// RVA: 0x1c45ad8 VA: 0x759425dad8
	public Void .ctor() { }
}
```
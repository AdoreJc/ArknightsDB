# BuffTemplate

**Namespace:** `Torappu.Battle`


## Fields

- `String templateKey`

- `String effectKey`

- `OnEventPriority onEventPriority`

- `EventToActionMap eventToActions`


## Methods

- `BuffTemplateDBData ConvertToDBData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BuffTemplate
{
	public String templateKey; // 0x10
	public String effectKey; // 0x18
	public OnEventPriority onEventPriority; // 0x20
	public EventToActionMap eventToActions; // 0x28


	// RVA: 0x1c42b2c VA: 0x759425ab2c
	public override String ToString() { }
	// RVA: 0x1c42b34 VA: 0x759425ab34
	public static BuffTemplate op_Implicit(BuffTemplateDBData dbData) { }
	// RVA: 0x1c42eec VA: 0x759425aeec
	public static BuffTemplateDBData op_Implicit(BuffTemplate template) { }
	// RVA: 0x1c42efc VA: 0x759425aefc
	public BuffTemplateDBData ConvertToDBData() { }
	// RVA: 0x1c42e00 VA: 0x759425ae00
	public Void .ctor() { }
}
```
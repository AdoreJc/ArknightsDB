# RetroActData

**Namespace:** `Torappu`


## Fields

- `String retroId`

- `RetroType type`

- `Int64 startTime`

- `Int64 trailStartTime`

- `Int32 index`

- `String name`

- `Boolean haveTrail`

- `String customActId`

- `ActivityType customActType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RetroActData
{
	public String retroId; // 0x10
	public RetroType type; // 0x18
	public String[] linkedActId; // 0x20
	public Int64 startTime; // 0x28
	public Int64 trailStartTime; // 0x30
	public Int32 index; // 0x38
	public String name; // 0x40
	public Boolean haveTrail; // 0x48
	public String customActId; // 0x50
	public ActivityType customActType; // 0x58


	// RVA: 0x34a7044 VA: 0x7595abf044
	public Void .ctor() { }
}
```
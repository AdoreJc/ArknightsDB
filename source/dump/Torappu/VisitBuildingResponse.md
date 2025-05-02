# VisitBuildingResponse

**Namespace:** `Torappu`


## Fields

- `Snapshot snapshot`

- `Int32 notice`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class VisitBuildingResponse : PlayerDeltaResponse
{
	public Snapshot snapshot; // 0x28
	public List`1 visitorList; // 0x30
	public ItemBundle[] rewards; // 0x38
	public Int32 notice; // 0x40


	// RVA: 0x32cdd78 VA: 0x75958e5d78
	public Void .ctor() { }
}
```
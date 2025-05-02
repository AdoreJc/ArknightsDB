# NewbeeGachaPoolClientData

**Namespace:** `Torappu`


## Fields

- `String gachaPoolId`

- `Int32 gachaIndex`

- `String gachaPoolName`

- `String gachaPoolDetail`

- `Int32 gachaPrice`

- `Int32 gachaTimes`

- `String gachaOffset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class NewbeeGachaPoolClientData : IComparable`1
{
	public String gachaPoolId; // 0x10
	public Int32 gachaIndex; // 0x18
	public String gachaPoolName; // 0x20
	public String gachaPoolDetail; // 0x28
	public Int32 gachaPrice; // 0x30
	public Int32 gachaTimes; // 0x34
	public String gachaOffset; // 0x38


	// RVA: 0x34a2218 VA: 0x7595aba218
	public virtual Int32 CompareTo(NewbeeGachaPoolClientData otherModel) { }
	// RVA: 0x34a2238 VA: 0x7595aba238
	public Void .ctor() { }
}
```
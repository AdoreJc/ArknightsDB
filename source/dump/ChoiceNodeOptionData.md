# ChoiceNodeOptionData

**Namespace:** ` `


## Fields

- `Boolean canRepeat`

- `String eventId`

- `String des`

- `String unlockDes`

- `String unlockCondType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ChoiceNodeOptionData
{
	public Boolean canRepeat; // 0x10
	public String eventId; // 0x18
	public String des; // 0x20
	public String unlockDes; // 0x28
	public String unlockCondType; // 0x30
	public List`1 unlockParams; // 0x38


	// RVA: 0x33b5568 VA: 0x75959cd568
	public virtual Boolean ShouldSerializeunlockCondType() { }
	// RVA: 0x33b5578 VA: 0x75959cd578
	public virtual Boolean ShouldSerializeunlockParams() { }
	// RVA: 0x33b55cc VA: 0x75959cd5cc
	public Void .ctor() { }
}
```
# SpCharMissionData

**Namespace:** `Torappu`


## Fields

- `String charId`

- `String missionId`

- `Int32 sortId`

- `SpCharMissionCondType condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SpCharMissionData
{
	public String charId; // 0x10
	public String missionId; // 0x18
	public Int32 sortId; // 0x20
	public SpCharMissionCondType condType; // 0x24
	public List`1 param; // 0x28
	public List`1 rewards; // 0x30


	// RVA: 0x33ca39c VA: 0x75959e239c
	public Void .ctor() { }
}
```
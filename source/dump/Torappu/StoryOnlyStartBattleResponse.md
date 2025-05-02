# StoryOnlyStartBattleResponse

**Namespace:** `Torappu`


## Fields

- `Int32 result`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StoryOnlyStartBattleResponse : PlayerDeltaResponse, IAlertResponse
{
	public Int32 result; // 0x28
	public List`1 rewards; // 0x30
	public String[] unlockStages; // 0x38
	public List`1 alert; // 0x40


	// RVA: 0x32cdccc VA: 0x75958e5ccc
	public List`1 GetAlert() { }
	// RVA: 0x32cdcd4 VA: 0x75958e5cd4
	public Void .ctor() { }
}
```
# ActivityEnemyDuelAnnounceData

**Namespace:** `Torappu`


## Fields

- `Int64 startTs`

- `Int64 endTs`

- `String announceText`

- `Boolean showNew`


## Methods

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActivityEnemyDuelAnnounceData : ITimeValidInfo
{
	public Int64 startTs; // 0x10
	public Int64 endTs; // 0x18
	public String announceText; // 0x20
	public Boolean showNew; // 0x28


	// RVA: 0x33baf98 VA: 0x75959d2f98
	public Int64 GetStartTs() { }
	// RVA: 0x33bafa0 VA: 0x75959d2fa0
	public Int64 GetEndTs() { }
	// RVA: 0x33bafa8 VA: 0x75959d2fa8
	public Void .ctor() { }
}
```
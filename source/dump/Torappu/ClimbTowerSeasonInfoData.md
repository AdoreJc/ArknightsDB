# ClimbTowerSeasonInfoData

**Namespace:** `Torappu`


## Fields

- `String id`

- `String name`

- `Int32 seasonNum`

- `Int64 startTs`

- `Int64 endTs`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ClimbTowerSeasonInfoData
{
	public String id; // 0x10
	public String name; // 0x18
	public Int32 seasonNum; // 0x20
	public Int64 startTs; // 0x28
	public Int64 endTs; // 0x30
	public List`1 towers; // 0x38
	public List`1 seasonCards; // 0x40
	public List`1 replicatedTowers; // 0x48


	// RVA: 0x349bfb8 VA: 0x7595ab3fb8
	public Void .ctor() { }
}
```
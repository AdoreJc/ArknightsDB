# CrisisV2ZoneGroupViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Boolean isInited`

- `String seasonId`

- `Int32 shopCoin`

- `String seasonName`

- `String seasonCode`

- `String themeColor`

- `Perm perm`

- `DateTime endTime`

- `String medalId`

- `Boolean medalAvail`

- `CrisisV2SeasonInfo seasonInfo`


## Methods

- `Void InitBase()`

- `Void ApplyServerData(CrisisV2CacheServerData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class CrisisV2ZoneGroupViewModel : ZoneGroupViewModel
{
	public Boolean isInited; // 0x28
	public String seasonId; // 0x30
	public Int32 shopCoin; // 0x38
	public String seasonName; // 0x40
	public String seasonCode; // 0x48
	public String themeColor; // 0x50
	public Perm perm; // 0x58
	public DateTime endTime; // 0x60
	public String medalId; // 0x68
	public Boolean medalAvail; // 0x70
	public List`1 tempList; // 0x78
	public List`1 tempStageList; // 0x80
	public CrisisV2SeasonInfo seasonInfo; // 0x88


	// RVA: 0x2f76b70 VA: 0x759558eb70
	public Void InitBase() { }
	// RVA: 0x2f76cb8 VA: 0x759558ecb8
	public Void ApplyServerData(CrisisV2CacheServerData sharedData) { }
	// RVA: 0x2f77240 VA: 0x759558f240
	public Void .ctor() { }
}
```
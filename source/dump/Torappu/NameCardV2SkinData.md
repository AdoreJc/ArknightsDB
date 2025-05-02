# NameCardV2SkinData

**Namespace:** `Torappu`


## Fields

- `String id`

- `String name`

- `NameCardV2SkinType type`

- `Int32 sortId`

- `Boolean isSpTheme`

- `Boolean defaultShowDetail`

- `String themeName`

- `String themeEnName`

- `Int64 skinStartTime`

- `String skinDesc`

- `String usageDesc`

- `String skinApproach`

- `Int32 unlockConditionCnt`

- `ItemRarity rarity`

- `Int32 skinTmplCnt`

- `Boolean canChangeTmpl`

- `Boolean isTimeLimit`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class NameCardV2SkinData
{
	public String id; // 0x10
	public String name; // 0x18
	public NameCardV2SkinType type; // 0x20
	public Int32 sortId; // 0x24
	public Boolean isSpTheme; // 0x28
	public Boolean defaultShowDetail; // 0x29
	public String themeName; // 0x30
	public String themeEnName; // 0x38
	public Int64 skinStartTime; // 0x40
	public String skinDesc; // 0x48
	public String usageDesc; // 0x50
	public String skinApproach; // 0x58
	public Int32 unlockConditionCnt; // 0x60
	public List`1 unlockDescList; // 0x68
	public List`1 fixedModuleList; // 0x70
	public ItemRarity rarity; // 0x78
	public Int32 skinTmplCnt; // 0x7c
	public Boolean canChangeTmpl; // 0x80
	public Boolean isTimeLimit; // 0x81
	public List`1 timeLimitInfoList; // 0x88


	// RVA: 0x349db1c VA: 0x7595ab5b1c
	public Void .ctor() { }
}
```
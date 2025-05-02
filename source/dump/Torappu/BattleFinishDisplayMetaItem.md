# BattleFinishDisplayMetaItem

**Namespace:** `Torappu`


## Fields

- `String battleFinishDisplayKey`

- `Boolean isAllStageActive`

- `CommonAvailCheck availCheck`

- `String relateActId`

- `String overrideStageName`

- `String signal`

- `String overrideCharWord`


## Methods

- `MetaUIDisplayType GetDisplayType()`

- `CommonAvailCheck GetAvailCheckNullable()`

- `String GetRelatedActId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BattleFinishDisplayMetaItem : IMetaDisplayItem
{
	public String battleFinishDisplayKey; // 0x10
	public Boolean isAllStageActive; // 0x18
	public List`1 stageIdList; // 0x20
	public CommonAvailCheck availCheck; // 0x28
	public String relateActId; // 0x30
	public String overrideStageName; // 0x38
	public String signal; // 0x40
	public String overrideCharWord; // 0x48


	// RVA: 0x34a56e4 VA: 0x7595abd6e4
	public MetaUIDisplayType GetDisplayType() { }
	// RVA: 0x34a56ec VA: 0x7595abd6ec
	public CommonAvailCheck GetAvailCheckNullable() { }
	// RVA: 0x34a56f4 VA: 0x7595abd6f4
	public String GetRelatedActId() { }
	// RVA: 0x34a56fc VA: 0x7595abd6fc
	public Void .ctor() { }
}
```
# BattleLoadingDisplayMetaItem

**Namespace:** `Torappu`


## Fields

- `Boolean isAllStageActive`

- `String battleLoadingPicId`

- `String relateActId`

- `CommonAvailCheck availCheck`


## Methods

- `MetaUIDisplayType GetDisplayType()`

- `CommonAvailCheck GetAvailCheckNullable()`

- `String GetRelatedActId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BattleLoadingDisplayMetaItem : IMetaDisplayItem
{
	public Boolean isAllStageActive; // 0x10
	public List`1 stageIdList; // 0x18
	public String battleLoadingPicId; // 0x20
	public String relateActId; // 0x28
	public CommonAvailCheck availCheck; // 0x30


	// RVA: 0x34a55a4 VA: 0x7595abd5a4
	public MetaUIDisplayType GetDisplayType() { }
	// RVA: 0x34a55ac VA: 0x7595abd5ac
	public CommonAvailCheck GetAvailCheckNullable() { }
	// RVA: 0x34a55b4 VA: 0x7595abd5b4
	public String GetRelatedActId() { }
	// RVA: 0x34a55bc VA: 0x7595abd5bc
	public Void .ctor() { }
}
```
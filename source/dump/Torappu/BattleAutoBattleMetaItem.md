# BattleAutoBattleMetaItem

**Namespace:** `Torappu`


## Fields

- `String battleAutoBattleDisplayKey`

- `Boolean isAllStageActive`

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
public class BattleAutoBattleMetaItem : IMetaDisplayItem
{
	public String battleAutoBattleDisplayKey; // 0x10
	public Boolean isAllStageActive; // 0x18
	public String relateActId; // 0x20
	public List`1 stageIdList; // 0x28
	public CommonAvailCheck availCheck; // 0x30


	// RVA: 0x34a5644 VA: 0x7595abd644
	public MetaUIDisplayType GetDisplayType() { }
	// RVA: 0x34a564c VA: 0x7595abd64c
	public CommonAvailCheck GetAvailCheckNullable() { }
	// RVA: 0x34a5654 VA: 0x7595abd654
	public String GetRelatedActId() { }
	// RVA: 0x34a565c VA: 0x7595abd65c
	public Void .ctor() { }
}
```
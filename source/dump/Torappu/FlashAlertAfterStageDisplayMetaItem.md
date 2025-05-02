# FlashAlertAfterStageDisplayMetaItem

**Namespace:** `Torappu`


## Fields

- `String flashAlertId`

- `CommonAvailCheck availCheck`

- `Boolean isAllStageActive`

- `String relateActId`

- `String detailText`

- `Boolean isBasicInfo`

- `Int32 times`


## Methods

- `MetaUIDisplayType GetDisplayType()`

- `CommonAvailCheck GetAvailCheckNullable()`

- `String GetRelatedActId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class FlashAlertAfterStageDisplayMetaItem : IMetaDisplayItem
{
	public String flashAlertId; // 0x10
	public CommonAvailCheck availCheck; // 0x18
	public Boolean isAllStageActive; // 0x20
	public List`1 stageIdList; // 0x28
	public String relateActId; // 0x30
	public String detailText; // 0x38
	public Boolean isBasicInfo; // 0x40
	public Int32 times; // 0x44


	// RVA: 0x34a5504 VA: 0x7595abd504
	public MetaUIDisplayType GetDisplayType() { }
	// RVA: 0x34a550c VA: 0x7595abd50c
	public CommonAvailCheck GetAvailCheckNullable() { }
	// RVA: 0x34a5514 VA: 0x7595abd514
	public String GetRelatedActId() { }
	// RVA: 0x34a551c VA: 0x7595abd51c
	public Void .ctor() { }
}
```
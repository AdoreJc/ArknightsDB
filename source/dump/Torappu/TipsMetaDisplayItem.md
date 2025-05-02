# TipsMetaDisplayItem

**Namespace:** `Torappu`


## Fields

- `String tipsId`

- `String loadingPic`

- `CommonAvailCheck availCheck`

- `String relateActId`

- `Boolean isAllStageActive`


## Methods

- `MetaUIDisplayType GetDisplayType()`

- `CommonAvailCheck GetAvailCheckNullable()`

- `String GetRelatedActId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TipsMetaDisplayItem : IMetaDisplayItem
{
	public String tipsId; // 0x10
	public String loadingPic; // 0x18
	public CommonAvailCheck availCheck; // 0x20
	public String relateActId; // 0x28
	public Boolean isAllStageActive; // 0x30
	public List`1 stageIdList; // 0x38
	public List`1 zoneIdList; // 0x40
	public TipData[] tips; // 0x48


	// RVA: 0x34a5394 VA: 0x7595abd394
	public MetaUIDisplayType GetDisplayType() { }
	// RVA: 0x34a539c VA: 0x7595abd39c
	public CommonAvailCheck GetAvailCheckNullable() { }
	// RVA: 0x34a53a4 VA: 0x7595abd3a4
	public String GetRelatedActId() { }
	// RVA: 0x34a53ac VA: 0x7595abd3ac
	public Void .ctor() { }
}
```
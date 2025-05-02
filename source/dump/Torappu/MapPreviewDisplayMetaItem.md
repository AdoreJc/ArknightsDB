# MapPreviewDisplayMetaItem

**Namespace:** `Torappu`


## Fields

- `String mapPreviewPicId`

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
public class MapPreviewDisplayMetaItem : IMetaDisplayItem
{
	public String mapPreviewPicId; // 0x10
	public CommonAvailCheck availCheck; // 0x18
	public String relateActId; // 0x20
	public Boolean isAllStageActive; // 0x28
	public List`1 stageIdList; // 0x30


	// RVA: 0x34a5464 VA: 0x7595abd464
	public MetaUIDisplayType GetDisplayType() { }
	// RVA: 0x34a546c VA: 0x7595abd46c
	public CommonAvailCheck GetAvailCheckNullable() { }
	// RVA: 0x34a5474 VA: 0x7595abd474
	public String GetRelatedActId() { }
	// RVA: 0x34a547c VA: 0x7595abd47c
	public Void .ctor() { }
}
```
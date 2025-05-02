# ShopRecommendItem

**Namespace:** `Torappu`


## Fields

- `String tagId`

- `String displayType`

- `String tagName`

- `RecommendItemTagTips itemTag`

- `Int32 orderNum`

- `Int64 startDatetime`

- `Int64 endDatetime`

- `ShopKeeperWord tagWord`

- `ShopRecommendTemplateType templateType`

- `ShopRecommendTemplateParam templateParam`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ShopRecommendItem
{
	public String tagId; // 0x10
	public String displayType; // 0x18
	public String tagName; // 0x20
	public RecommendItemTagTips itemTag; // 0x28
	public Int32 orderNum; // 0x2c
	public Int64 startDatetime; // 0x30
	public Int64 endDatetime; // 0x38
	public List`1 groupList; // 0x40
	public ShopKeeperWord tagWord; // 0x48
	public ShopRecommendTemplateType templateType; // 0x50
	public ShopRecommendTemplateParam templateParam; // 0x58


	// RVA: 0x34f46f8 VA: 0x7595b0c6f8
	public Void .ctor() { }
}
```
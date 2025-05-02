# HandBookV2MissionListItemModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `String missionId`

- `Int32 missionSort`

- `String forceId`

- `String forceName`

- `HandBookV2ForceFavorViewModel favorModel`

- `ItemBundle item`

- `Int32 needFavorPoint`

- `Boolean isRewardAvail`


## Methods

- `Int32 CompareTo(HandBookV2MissionListItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MissionListItemModel : IComparable`1
{
	public String missionId; // 0x10
	public Int32 missionSort; // 0x18
	public String forceId; // 0x20
	public String forceName; // 0x28
	public List`1 charDataList; // 0x30
	public HandBookV2ForceFavorViewModel favorModel; // 0x38
	public ItemBundle item; // 0x40
	public Int32 needFavorPoint; // 0x48
	public Boolean isRewardAvail; // 0x4c


	// RVA: 0x2edc1c0 VA: 0x75954f41c0
	public Int32 CompareTo(HandBookV2MissionListItemModel other) { }
	// RVA: 0x2edc1e0 VA: 0x75954f41e0
	public Void .ctor() { }
}
```
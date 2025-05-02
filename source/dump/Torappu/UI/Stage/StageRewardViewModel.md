# StageRewardViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIItemViewModel itemModel`

- `Boolean isOnce`

- `Boolean isComplete`

- `Boolean isOverrideDrop`

- `String timelyDropId`

- `Boolean isTimelyDropReplace`

- `String overrideBuffId`

- `OccPer occPerInfo`


## Methods

- `Void LoadData(DisplayRewards, String, String, Boolean)`

- `Int32 CompareTo(StageRewardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageRewardViewModel : IComparable`1
{
	public UIItemViewModel itemModel; // 0x10
	public Boolean isOnce; // 0x18
	public Boolean isComplete; // 0x19
	public Boolean isOverrideDrop; // 0x1a
	public String timelyDropId; // 0x20
	public Boolean isTimelyDropReplace; // 0x28
	public String overrideBuffId; // 0x30
	public OccPer occPerInfo; // 0x38


	// RVA: 0x2f76568 VA: 0x759558e568
	public Void LoadData(DisplayRewards rewardData, String timelyDropId, String overrideBuffId, Boolean istimelyDropReplace) { }
	// RVA: 0x2f7ffd0 VA: 0x7595597fd0
	public Int32 CompareTo(StageRewardViewModel other) { }
	// RVA: 0x2f76560 VA: 0x759558e560
	public Void .ctor() { }
}
```
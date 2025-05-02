# CraftStageInfoModel

**Namespace:** ` `


## Fields

- `String stageId`

- `String stageCode`

- `String stageName`

- `String zoneId`

- `Boolean isSpecialStage`

- `Int32 stageRank`

- `Int32 sortId`

- `PlayerStageState stageState`

- `Int32 trapPosX`

- `Int32 trapPosY`


## Methods

- `Int32 CompareTo(CraftStageInfoModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CraftStageInfoModel : IHotfixable, IComparable`1
{
	public String stageId; // 0x10
	public String stageCode; // 0x18
	public String stageName; // 0x20
	public String zoneId; // 0x28
	public Boolean isSpecialStage; // 0x30
	public Int32 stageRank; // 0x34
	public Int32 sortId; // 0x38
	public PlayerStageState stageState; // 0x3c
	public Int32 trapPosX; // 0x40
	public Int32 trapPosY; // 0x44
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2905840 VA: 0x7594f1d840
	public Int32 CompareTo(CraftStageInfoModel other) { }
	// RVA: 0x2905108 VA: 0x7594f1d108
	public Void .ctor() { }
}
```
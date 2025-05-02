# CraftZoneInfoModel

**Namespace:** ` `


## Fields

- `String zoneId`

- `String zoneName`

- `Boolean isUnlock`

- `Int32 sortIdByStage`

- `String firstLockedNonSpStageId`


## Methods

- `Int32 CompareTo(CraftZoneInfoModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CraftZoneInfoModel : IHotfixable, IComparable`1
{
	public String zoneId; // 0x10
	public String zoneName; // 0x18
	public Boolean isUnlock; // 0x20
	public List`1 stages; // 0x28
	public Int32 sortIdByStage; // 0x30
	public String firstLockedNonSpStageId; // 0x38
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x29058f4 VA: 0x7594f1d8f4
	public Int32 CompareTo(CraftZoneInfoModel other) { }
	// RVA: 0x2905044 VA: 0x7594f1d044
	public Void .ctor() { }
}
```
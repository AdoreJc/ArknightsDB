# ActMultiV3RewardDetailViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String actId`

- `Int32 totalCount`

- `Int32 currCount`

- `String dailyMissionName`

- `String dailyMissionRule`


## Methods

- `Void LoadData(String, Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3RewardDetailViewModel : IHotfixable
{
	public String actId; // 0x10
	public Int32 totalCount; // 0x18
	public Int32 currCount; // 0x1c
	public String dailyMissionName; // 0x20
	public String dailyMissionRule; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30ebacc VA: 0x7595703acc
	public Void LoadData(String actId, Int32 totalCount, Int32 currCount) { }
	// RVA: 0x30f3004 VA: 0x759570b004
	public Void .ctor() { }
}
```
# Act24sideEntryViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String actId`

- `Act24sideEntryEatViewModel eatViewModel`

- `Act24sideEntryBattleTrapViewModel trapViewModel`

- `Act24sideEntryMissionViewModel missionViewModel`


## Methods

- `Void RefreshMissionData()`

- `Void RefreshBattleTrapData()`

- `Void RefreshEatData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideEntryViewModel : TemplateActivityViewModel
{
	public String actId; // 0x20
	public Act24sideEntryEatViewModel eatViewModel; // 0x28
	public Act24sideEntryBattleTrapViewModel trapViewModel; // 0x30
	public Act24sideEntryMissionViewModel missionViewModel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RefreshMissionData; // 0x8
	private static DelegateBridge __Hotfix0_RefreshBattleTrapData; // 0x10
	private static DelegateBridge __Hotfix0_RefreshEatData; // 0x18


	// RVA: 0x329e5a8 VA: 0x75958b65a8
	public Void .ctor(Object param) { }
	// RVA: 0x329ee40 VA: 0x75958b6e40
	public Void RefreshMissionData() { }
	// RVA: 0x329eeb4 VA: 0x75958b6eb4
	public Void RefreshBattleTrapData() { }
	// RVA: 0x329ef28 VA: 0x75958b6f28
	public Void RefreshEatData() { }
}
```
# Act42D0ChallengeStageGroupViewModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String actId`

- `String challengeDesc`

- `String challengeName`

- `String stageSelected`


## Methods

- `Void LoadData(String, String)`

- `Void RefreshPlayerData()`

- `Act42D0ChallengeStageViewModel GetStageById(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0ChallengeStageGroupViewModel : IHotfixable
{
	public String actId; // 0x10
	public String challengeDesc; // 0x18
	public String challengeName; // 0x20
	public String stageSelected; // 0x28
	public List`1 stageViewModelList; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge __Hotfix0_GetStageById; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x320a150 VA: 0x7595822150
	public Void LoadData(String actId, String selectStageId) { }
	// RVA: 0x320aa34 VA: 0x7595822a34
	public Void RefreshPlayerData() { }
	// RVA: 0x3209a98 VA: 0x7595821a98
	public Act42D0ChallengeStageViewModel GetStageById(String stageId) { }
	// RVA: 0x320acf4 VA: 0x7595822cf4
	public Void .ctor() { }
}
```
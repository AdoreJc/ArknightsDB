# Act42D0ChallengeStageViewModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String stageId`

- `String stageCode`

- `String stageName`

- `String stageDesc`

- `String levelId`

- `String loadingPicId`

- `String openHint`

- `Boolean isNew`

- `Boolean unlocked`

- `Boolean allComplete`


## Methods

- `Void LoadData(String, Act42D0ChallengeInfoData)`

- `Void RefreshPlayerData(String, ChallengeStageInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0ChallengeStageViewModel : IHotfixable
{
	public String stageId; // 0x10
	public String stageCode; // 0x18
	public String stageName; // 0x20
	public String stageDesc; // 0x28
	public String levelId; // 0x30
	public String loadingPicId; // 0x38
	public String openHint; // 0x40
	public Boolean isNew; // 0x48
	public Boolean unlocked; // 0x49
	public Boolean allComplete; // 0x4a
	public List`1 missionItemViewModelList; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x320a598 VA: 0x7595822598
	public Void LoadData(String actId, Act42D0ChallengeInfoData challengeInfoData) { }
	// RVA: 0x320ab6c VA: 0x7595822b6c
	public Void RefreshPlayerData(String actId, ChallengeStageInfo stageInfo) { }
	// RVA: 0x320a4d4 VA: 0x75958224d4
	public Void .ctor() { }
}
```
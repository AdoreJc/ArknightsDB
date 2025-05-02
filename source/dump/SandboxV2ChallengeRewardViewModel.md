# SandboxV2ChallengeRewardViewModel

**Namespace:** ` `


## Fields

- `String rewardId`

- `Int32 sortId`

- `Int32 rewardDay`

- `State state`


## Methods

- `Void LoadData(String, SandboxV2ChallengeModeRewardData, Dictionary`2, Int32)`

- `Int32 CompareTo(SandboxV2ChallengeRewardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxV2ChallengeRewardViewModel : IHotfixable
{
	public String rewardId; // 0x10
	public Int32 sortId; // 0x18
	public Int32 rewardDay; // 0x1c
	public List`1 rewards; // 0x20
	public State state; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x25cb7a0 VA: 0x7594be37a0
	public Void LoadData(String rewardId, SandboxV2ChallengeModeRewardData rewardData, Dictionary`2 playerChallengeReward, Int32 playerBestChallengeDay) { }
	// RVA: 0x25cb8e0 VA: 0x7594be38e0
	public Int32 CompareTo(SandboxV2ChallengeRewardViewModel other) { }
	// RVA: 0x25cb9e4 VA: 0x7594be39e4
	public Void .ctor() { }
}
```
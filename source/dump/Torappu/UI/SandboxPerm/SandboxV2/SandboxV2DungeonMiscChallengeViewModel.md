# SandboxV2DungeonMiscChallengeViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 challengeDay`

- `Int32 bestDay`

- `Int32 nextDebuffDay`

- `String titleDesc`

- `String debuffCountdownDesc`

- `String debuffGainAllDesc`

- `String debuffTitleDesc`

- `Int32 debuffNum`

- `ChallengeStatus challengeStatus`


## Methods

- `Void LoadData(SandboxV2Data, PlayerSandboxV2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonMiscChallengeViewModel : IHotfixable
{
	public Int32 challengeDay; // 0x10
	public Int32 bestDay; // 0x14
	public Int32 nextDebuffDay; // 0x18
	public String titleDesc; // 0x20
	public String debuffCountdownDesc; // 0x28
	public String debuffGainAllDesc; // 0x30
	public String debuffTitleDesc; // 0x38
	public Int32 debuffNum; // 0x40
	public List`1 debuffDesc; // 0x48
	public ChallengeStatus challengeStatus; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25b45dc VA: 0x7594bcc5dc
	public Void LoadData(SandboxV2Data topicDetailData, PlayerSandboxV2 playerTopicData) { }
	// RVA: 0x25b48d4 VA: 0x7594bcc8d4
	public Void .ctor() { }
}
```
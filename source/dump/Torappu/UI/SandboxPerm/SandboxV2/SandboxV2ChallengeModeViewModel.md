# SandboxV2ChallengeModeViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean challengeSysEnabled`

- `Boolean challengeModeActivated`

- `Boolean challengeModeUnlocked`

- `Boolean isInChallengeMode`

- `Boolean isChallengeViewSelected`

- `String challengeModeDesc`

- `Int32 rewardCanReceiveCount`

- `Boolean isInRift`

- `Boolean currTopicActivated`

- `Boolean otherTopicInChallenge`

- `Boolean hasEnteredOnce`

- `ChallengeStatus challengeStatus`

- `SandboxV2ChallengeModeCurrentViewModel currentStatus`

- `SandboxV2ChallengeModeHistoryViewModel bestStatus`

- `SandboxV2ChallengeModeHistoryViewModel lastStatus`

- `ChallengeStatus m_cachedChallengeStatus`


## Methods

- `Void LoadData(String, SandboxV2Data, PlayerSandboxV2)`

- `Void _RefreshChallengeViewSelection()`

- `Boolean SetChallengeViewSelected(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ChallengeModeViewModel : IHotfixable
{
	public Boolean challengeSysEnabled; // 0x10
	public Boolean challengeModeActivated; // 0x11
	public Boolean challengeModeUnlocked; // 0x12
	public Boolean isInChallengeMode; // 0x13
	public List`1 challengeModeUnlockCondList; // 0x18
	public Boolean isChallengeViewSelected; // 0x20
	public String challengeModeDesc; // 0x28
	public Int32 rewardCanReceiveCount; // 0x30
	public Boolean isInRift; // 0x34
	public Boolean currTopicActivated; // 0x35
	public Boolean otherTopicInChallenge; // 0x36
	public Boolean hasEnteredOnce; // 0x37
	public ChallengeStatus challengeStatus; // 0x38
	public SandboxV2ChallengeModeCurrentViewModel currentStatus; // 0x40
	public SandboxV2ChallengeModeHistoryViewModel bestStatus; // 0x48
	public SandboxV2ChallengeModeHistoryViewModel lastStatus; // 0x50
	private ChallengeStatus m_cachedChallengeStatus; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__RefreshChallengeViewSelection; // 0x8
	private static DelegateBridge __Hotfix0_SetChallengeViewSelected; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25d1d3c VA: 0x7594be9d3c
	public Void LoadData(String topicId, SandboxV2Data dataBase, PlayerSandboxV2 playerData) { }
	// RVA: 0x25d2860 VA: 0x7594bea860
	private Void _RefreshChallengeViewSelection() { }
	// RVA: 0x25d28d4 VA: 0x7594bea8d4
	public Boolean SetChallengeViewSelected(Boolean selected) { }
	// RVA: 0x25d298c VA: 0x7594bea98c
	public Void .ctor() { }
}
```
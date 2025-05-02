# SandboxV2ChallengeSettleViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String userName`

- `Int32 challengeDay`

- `Int32 enemyRushKilledCount`

- `Int32 startDay`

- `Int32 startLoadTimes`

- `Boolean hasNewRecord`

- `String topicId`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ChallengeSettleViewModel : IHotfixable
{
	public String userName; // 0x10
	public Int32 challengeDay; // 0x18
	public Int32 enemyRushKilledCount; // 0x1c
	public Int32 startDay; // 0x20
	public Int32 startLoadTimes; // 0x24
	public Boolean hasNewRecord; // 0x28
	public String topicId; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2519560 VA: 0x7594b31560
	public Void LoadData(String topicId) { }
	// RVA: 0x251a640 VA: 0x7594b32640
	public Void .ctor() { }
}
```
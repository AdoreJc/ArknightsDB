# SandboxV2ChallengeModeCurrentViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean isInChallengeMode`

- `Int32 latestArchiveDay`

- `Int32 startDay`

- `Int32 startLoadTimes`

- `Int32 challengeDay`


## Methods

- `Void LoadData(Boolean, PlayerSandboxV2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ChallengeModeCurrentViewModel : IHotfixable
{
	public Boolean isInChallengeMode; // 0x10
	public Int32 latestArchiveDay; // 0x14
	public Int32 startDay; // 0x18
	public Int32 startLoadTimes; // 0x1c
	public Int32 challengeDay; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25d1b9c VA: 0x7594be9b9c
	public Void LoadData(Boolean isInChallengeMode, PlayerSandboxV2 playerData) { }
	// RVA: 0x25d1ccc VA: 0x7594be9ccc
	public Void .ctor() { }
}
```
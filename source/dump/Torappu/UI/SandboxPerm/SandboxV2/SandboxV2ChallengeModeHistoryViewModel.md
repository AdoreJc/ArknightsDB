# SandboxV2ChallengeModeHistoryViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 startDay`

- `Int32 startLoadTimes`

- `Int64 ts`

- `Int32 challengeDay`


## Methods

- `Void LoadData(History)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ChallengeModeHistoryViewModel : IHotfixable
{
	public Int32 startDay; // 0x10
	public Int32 startLoadTimes; // 0x14
	public Int64 ts; // 0x18
	public Int32 challengeDay; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25d1a98 VA: 0x7594be9a98
	public Void LoadData(History playerHistory) { }
	// RVA: 0x25d1b2c VA: 0x7594be9b2c
	public Void .ctor() { }
}
```
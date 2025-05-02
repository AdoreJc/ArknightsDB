# SandboxV2ChallengeModeUnlockCondViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String condId`

- `Int32 condSortId`

- `String condDesc`

- `Int32 currProgress`

- `Int32 totProgress`


## Properties

- `Boolean completed`


## Methods

- `Boolean get_completed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ChallengeModeUnlockCondViewModel : IHotfixable
{
	public String condId; // 0x10
	public Int32 condSortId; // 0x18
	public String condDesc; // 0x20
	public Int32 currProgress; // 0x28
	public Int32 totProgress; // 0x2c
	private static DelegateBridge __Hotfix0_get_completed; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Boolean completed { get; }

	// RVA: 0x25d19a4 VA: 0x7594be99a4
	public Boolean get_completed() { }
	// RVA: 0x25d1a28 VA: 0x7594be9a28
	public Void .ctor() { }
}
```
# SandboxPlacedItemStatus

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `SandboxPlacedItemStatusKey key`

- `SandboxPlacedItemStatusValue value`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxPlacedItemStatus : IHotfixable
{
	public SandboxPlacedItemStatusKey key; // 0x10
	public SandboxPlacedItemStatusValue value; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_op_Implicit; // 0x8


	// RVA: 0x1df8948 VA: 0x7594410948
	public Void .ctor(SandboxPlacedItemStatusKey key, SandboxPlacedItemStatusValue value) { }
	// RVA: 0x1df8a0c VA: 0x7594410a0c
	public static SandboxPlacedItemStatus op_Implicit(Building v) { }
}
```
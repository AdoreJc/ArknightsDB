# SandboxEntityStatus

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `SandboxEntityStatusKey key`

- `SandboxEntityStatusValue value`


## Methods

- `String <>xLuaBaseProxy_ToString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxEntityStatus : IHotfixable
{
	public SandboxEntityStatusKey key; // 0x10
	public SandboxEntityStatusValue value; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_op_Implicit; // 0x8
	private static DelegateBridge __Hotfix0_ToString; // 0x10


	// RVA: 0x1df8dd4 VA: 0x7594410dd4
	public Void .ctor(SandboxEntityStatusKey key, SandboxEntityStatusValue value) { }
	// RVA: 0x1df8e98 VA: 0x7594410e98
	public static SandboxEntityStatus op_Implicit(EntityStatus v) { }
	// RVA: 0x1df9170 VA: 0x7594411170
	public override String ToString() { }
	// RVA: 0x1df92c4 VA: 0x75944112c4
	private String <>xLuaBaseProxy_ToString() { }
}
```
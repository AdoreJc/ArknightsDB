# EnvEventExecutor

**Namespace:** ` `


## Properties

- `Context context`


## Methods

- `Context get_context()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnvEventExecutor : Behaviour
{
	private static DelegateBridge __Hotfix0_get_context; // 0x0
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x8
	private static DelegateBridge __Hotfix1_OnEnvChanged; // 0x10
	private static DelegateBridge __Hotfix0_OnEnvChangedOnDummy; // 0x18
	private static DelegateBridge __Hotfix2_OnEnvChanged; // 0x20
	private static DelegateBridge __Hotfix3_OnEnvChanged; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Context context { get; }

	// RVA: 0x4029ddc VA: 0x7596641ddc
	public Context get_context() { }
	// RVA: 0x402353c VA: 0x759663b53c
	public virtual Void OnEnvChanged(Tile tileNotNull, String status) { }
	// RVA: 0x4025bc4 VA: 0x759663dbc4
	public virtual Void OnEnvChanged(String status, Entity target, Entity sourceNullable) { }
	// RVA: 0x4026758 VA: 0x759663e758
	public virtual Void OnEnvChangedOnDummy(Unit unit, String status) { }
	// RVA: 0x40257fc VA: 0x759663d7fc
	public virtual Void OnEnvChanged(Tile tile, Int32 param) { }
	// RVA: 0x4027fd0 VA: 0x759663ffd0
	public virtual Void OnEnvChanged(String status) { }
	// RVA: 0x40255f4 VA: 0x759663d5f4
	public Void .ctor() { }
}
```
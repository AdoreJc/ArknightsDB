# SandboxV2UniEnemyStatus

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `Int32 hpRatio`


## Properties

- `Single statusHpRatio`


## Methods

- `Void set_statusHpRatio(Single)`

- `Single get_statusHpRatio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxV2UniEnemyStatus : IHotfixable
{
	public Int32 hpRatio; // 0x10
	private static DelegateBridge __Hotfix0_set_statusHpRatio; // 0x0
	private static DelegateBridge __Hotfix0_get_statusHpRatio; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Single statusHpRatio { get; set; }

	// RVA: 0x1df9d94 VA: 0x7594411d94
	public Void set_statusHpRatio(Single value) { }
	// RVA: 0x1df9e80 VA: 0x7594411e80
	public Single get_statusHpRatio() { }
	// RVA: 0x1df9ef8 VA: 0x7594411ef8
	public Void .ctor() { }
}
```
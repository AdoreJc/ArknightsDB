# SandboxRushBossStatus

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `Int32 modeIndex`

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
public class SandboxRushBossStatus : IHotfixable
{
	public Int32 modeIndex; // 0x10
	public Int32 hpRatio; // 0x14
	private static DelegateBridge __Hotfix0_set_statusHpRatio; // 0x0
	private static DelegateBridge __Hotfix0_get_statusHpRatio; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Single statusHpRatio { get; set; }

	// RVA: 0x1df9f68 VA: 0x7594411f68
	public Void set_statusHpRatio(Single value) { }
	// RVA: 0x1dfa054 VA: 0x7594412054
	public Single get_statusHpRatio() { }
	// RVA: 0x1dfa0cc VA: 0x75944120cc
	public Void .ctor() { }
}
```
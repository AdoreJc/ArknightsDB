# ClientUpgradeNode

**Namespace:** ` `


## Fields

- `Content m_reason`

- `Boolean m_isUpgradeFinished`


## Methods

- `IEnumerator _UpgradeClientVersionRoutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ClientUpgradeNode : Node
{
	private const Single ALERT_COOLDOWN; // 0x0
	private Content m_reason; // 0x20
	private Boolean m_isUpgradeFinished; // 0x28
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_Work; // 0x8
	private static DelegateBridge __Hotfix0__UpgradeClientVersionRoutine; // 0x10
	private static DelegateBridge __Hotfix0__GameUpgradeProcess; // 0x18
	private static DelegateBridge __Hotfix0__TryUpgradeGameVersion; // 0x20
	private static DelegateBridge __Hotfix0__OverrideGameUpgrading; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override ENode type { get; }

	// RVA: 0x27c6074 VA: 0x7594dde074
	public override ENode get_type() { }
	// RVA: 0x27c60dc VA: 0x7594dde0dc
	public override CustomYieldInstruction Work() { }
	// RVA: 0x27c6278 VA: 0x7594dde278
	private IEnumerator _UpgradeClientVersionRoutine() { }
	// RVA: 0x27c634c VA: 0x7594dde34c
	private static IEnumerator _GameUpgradeProcess(Content reason) { }
	// RVA: 0x27c6420 VA: 0x7594dde420
	private static Void _TryUpgradeGameVersion(Configuration networkConfig) { }
	// RVA: 0x27c64c8 VA: 0x7594dde4c8
	private static Boolean _OverrideGameUpgrading() { }
	// RVA: 0x27bf904 VA: 0x7594dd7904
	public Void .ctor() { }
}
```
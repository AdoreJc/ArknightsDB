# EnableComponentWithBuff

**Namespace:** `Torappu.Battle.Effects`


## Methods

- `Void Update()`

- `Void _CheckBuffs()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnPostImport()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class EnableComponentWithBuff : Behaviour
{
	private buffWithComp[] _buffWithComps; // 0x20
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_OnPostImport; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0__CheckBuffs; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ffa85c VA: 0x759461285c
	public override Void OnPlay() { }
	// RVA: 0x1ffaa14 VA: 0x7594612a14
	public override Void OnPostImport() { }
	// RVA: 0x1ffab14 VA: 0x7594612b14
	private Void Update() { }
	// RVA: 0x1ffa8cc VA: 0x75946128cc
	private Void _CheckBuffs() { }
	// RVA: 0x1ffab7c VA: 0x7594612b7c
	public Void .ctor() { }
	// RVA: 0x1ffac24 VA: 0x7594612c24
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ffac28 VA: 0x7594612c28
	private Void <>xLuaBaseProxy_OnPostImport() { }
}
```
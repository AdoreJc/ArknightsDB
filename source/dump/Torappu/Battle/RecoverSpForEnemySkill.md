# RecoverSpForEnemySkill

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _recoverSpIfNoTarget`


## Methods

- `Void _RecoverSp(Int32)`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RecoverSpForEnemySkill : Behaviour
{
	private Boolean _recoverSpIfNoTarget; // 0x20
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x0
	private static DelegateBridge __Hotfix0__RecoverSp; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3fbb0c4 VA: 0x75965d30c4
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x3fbb288 VA: 0x75965d3288
	private Void _RecoverSp(Int32 delta) { }
	// RVA: 0x3fbb694 VA: 0x75965d3694
	public Void .ctor() { }
	// RVA: 0x3fbb700 VA: 0x75965d3700
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
}
```
# PassiveSkill

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _attachInDummy`


## Methods

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class PassiveSkill : BasicSkill
{
	private Boolean _attachInDummy; // 0xf8
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_DoCast; // 0x8
	private static DelegateBridge __Hotfix0_UseSkill; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1b70f20 VA: 0x7594188f20
	public override Void OnInit() { }
	// RVA: 0x1b7106c VA: 0x759418906c
	protected override Boolean DoCast(FinishCallbackDelegate finishCb, PlayerSide operationSide) { }
	// RVA: 0x1b710ec VA: 0x75941890ec
	public override Boolean UseSkill(PlayerSide operationSide) { }
	// RVA: 0x1b71164 VA: 0x7594189164
	public Void .ctor() { }
	// RVA: 0x1b711dc VA: 0x75941891dc
	private Void <>xLuaBaseProxy_OnInit() { }
}
```
# CastFinishReasonActionBehaviour

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `FinishReason _reason`

- `Boolean _isReasonMatch`

- `ActionArray _actions`


## Methods

- `Void GatherActionNodes(List`1)`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class CastFinishReasonActionBehaviour : Behaviour, IActionNodeSource
{
	private FinishReason _reason; // 0x20
	private Boolean _isReasonMatch; // 0x24
	private ActionArray _actions; // 0x28
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x0
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1ecec40 VA: 0x75944e6c40
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1eceee8 VA: 0x75944e6ee8
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1ecefa0 VA: 0x75944e6fa0
	public Void .ctor() { }
	// RVA: 0x1ecf010 VA: 0x75944e7010
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
}
```
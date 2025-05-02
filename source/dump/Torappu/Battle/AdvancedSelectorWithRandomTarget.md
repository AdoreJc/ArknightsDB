# AdvancedSelectorWithRandomTarget

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _additionalNum`

- `Boolean _randomSelectTarget`

- `FP m_prob`


## Methods

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithRandomTarget : AdvancedSelector
{
	private Int32 _additionalNum; // 0xe8
	private Boolean _randomSelectTarget; // 0xec
	private FP m_prob; // 0xf0
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b9e114 VA: 0x75941b6114
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1b9f010 VA: 0x75941b7010
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1b9f104 VA: 0x75941b7104
	public Void .ctor() { }
	// RVA: 0x1b9f1b0 VA: 0x75941b71b0
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
	// RVA: 0x1b9f1b8 VA: 0x75941b71b8
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
}
```
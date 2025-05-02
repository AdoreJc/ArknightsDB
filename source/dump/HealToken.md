# HealToken

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceTarget`

- `Boolean _ignoreHealFree`

- `Boolean _healByRatio`

- `Boolean _createEffect`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HealToken : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _sourceTarget; // 0x10
	private Boolean _ignoreHealFree; // 0x14
	private Boolean _healByRatio; // 0x15
	private Boolean _createEffect; // 0x16
	private List`1 m_targets; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f5e178 VA: 0x7594576178
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5e1e0 VA: 0x75945761e0
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5e248 VA: 0x7594576248
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5e774 VA: 0x7594576774
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f5e7ec VA: 0x75945767ec
	public Void .ctor() { }
}
```
# SetDisableClickCharacterInfo

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `DisableClickCharacterInfoReasonMask _reasonMask`

- `Boolean _enabled`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetDisableClickCharacterInfo : ActionNode
{
	private ActionTargetType _target; // 0x10
	private DisableClickCharacterInfoReasonMask _reasonMask; // 0x14
	private Boolean _enabled; // 0x15
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc4794 VA: 0x75945dc794
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc47fc VA: 0x75945dc7fc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc497c VA: 0x75945dc97c
	public Void .ctor() { }
}
```
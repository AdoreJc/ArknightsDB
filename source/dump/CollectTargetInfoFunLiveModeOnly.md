# CollectTargetInfoFunLiveModeOnly

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _collectRareTargetInfo`

- `String m_targetInfo`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CollectTargetInfoFunLiveModeOnly : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _collectRareTargetInfo; // 0x14
	private String m_targetInfo; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f51f44 VA: 0x7594569f44
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f51fac VA: 0x7594569fac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f52200 VA: 0x759456a200
	public Void .ctor() { }
}
```
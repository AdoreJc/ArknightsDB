# ShowRoutePreviewCursor

**Namespace:** ` `


## Fields

- `ShowType _showType`

- `String _branchId`

- `Int32 _actionIndex`

- `ActionTargetType _targetType`

- `Boolean _fromCurrentPos`

- `String _overridePreviewEffect`


## Properties

- `Boolean isFromBranch`

- `Boolean isFromTarget`


## Methods

- `Boolean get_isFromBranch()`

- `Boolean get_isFromTarget()`

- `Void GatherEffects(List`1)`

- `Boolean _ShowTargetPreviewCursor(Blackboard, SourceType, String, ref)`

- `Boolean _ShowBranchPreviewCursor(Blackboard, SourceType, String, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ShowRoutePreviewCursor : ActionNode, IEffectSource
{
	private ShowType _showType; // 0x10
	private String _branchId; // 0x18
	private Int32 _actionIndex; // 0x20
	private ActionTargetType _targetType; // 0x24
	private Boolean _fromCurrentPos; // 0x28
	private String _overridePreviewEffect; // 0x30
	private static DelegateBridge __Hotfix0_get_isFromBranch; // 0x0
	private static DelegateBridge __Hotfix0_get_isFromTarget; // 0x8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x10
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x18
	private static DelegateBridge __Hotfix0_Execute; // 0x20
	private static DelegateBridge __Hotfix0__ShowTargetPreviewCursor; // 0x28
	private static DelegateBridge __Hotfix0__ShowBranchPreviewCursor; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Boolean isFromBranch { get; }
	private Boolean isFromTarget { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fda624 VA: 0x75945f2624
	private Boolean get_isFromBranch() { }
	// RVA: 0x1fda694 VA: 0x75945f2694
	private Boolean get_isFromTarget() { }
	// RVA: 0x1fda704 VA: 0x75945f2704
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fda76c VA: 0x75945f276c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1fda880 VA: 0x75945f2880
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdab5c VA: 0x75945f2b5c
	private Boolean _ShowTargetPreviewCursor(Blackboard blackboard, SourceType sourceType, String overrideEffect, ref Snapshot snapshot) { }
	// RVA: 0x1fda9a8 VA: 0x75945f29a8
	private Boolean _ShowBranchPreviewCursor(Blackboard blackboard, SourceType sourceType, String overrideEffect, ref Snapshot snapshot) { }
	// RVA: 0x1fdae60 VA: 0x75945f2e60
	public Void .ctor() { }
}
```
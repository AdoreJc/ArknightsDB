# EpDamageScale

**Namespace:** ` `


## Fields

- `Boolean _filterElementType`

- `ElementType _elementType`

- `Boolean _filterApplyWay`

- `SourceApplyWay _applyWayFilter`

- `Boolean _isOneMinus`

- `Boolean _isStackable`

- `Boolean _isValidStackCnt`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EpDamageScale : ActionNode
{
	private Boolean _filterElementType; // 0x10
	private ElementType _elementType; // 0x14
	private Boolean _filterApplyWay; // 0x18
	private SourceApplyWay _applyWayFilter; // 0x1c
	private Boolean _isOneMinus; // 0x20
	private Boolean _isStackable; // 0x21
	private Boolean _isValidStackCnt; // 0x22
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f448c0 VA: 0x759455c8c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f44928 VA: 0x759455c928
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f44d7c VA: 0x759455cd7c
	public Void .ctor() { }
}
```
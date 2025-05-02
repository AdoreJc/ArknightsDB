# ModifyEnemyGraphicScale

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `Boolean _isAdd`

- `Single _scaleValue`

- `Boolean _needMax`

- `Single _maxValue`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyEnemyGraphicScale : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private Boolean _isAdd; // 0x14
	private Single _scaleValue; // 0x18
	private Boolean _needMax; // 0x1c
	private Single _maxValue; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc8ef4 VA: 0x75945e0ef4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc8f5c VA: 0x75945e0f5c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc920c VA: 0x75945e120c
	public Void .ctor() { }
}
```
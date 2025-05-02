# CheckTargetRootTileInfoMask

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `TileInfoMask _infoMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTargetRootTileInfoMask : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private TileInfoMask _infoMask; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2ca7c VA: 0x7594544a7c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2cae4 VA: 0x7594544ae4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2cc70 VA: 0x7594544c70
	public Void .ctor() { }
}
```
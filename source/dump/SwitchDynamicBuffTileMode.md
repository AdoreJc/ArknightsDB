# SwitchDynamicBuffTileMode

**Namespace:** ` `


## Fields

- `Operation _operation`

- `Int32 _modeIndex`

- `String _decBbKey`

- `Boolean _useSwitchResult`

- `Boolean _specifyTileType`

- `TileType _tileType`

- `Boolean _useOwnerRootTile`


## Properties

- `Boolean specifyTileType`


## Methods

- `Boolean get_specifyTileType()`

- `Int32 <Execute>b__13_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchDynamicBuffTileMode : ActionNode
{
	private Operation _operation; // 0x10
	private Int32 _modeIndex; // 0x14
	private String _decBbKey; // 0x18
	private Boolean _useSwitchResult; // 0x20
	private Boolean _specifyTileType; // 0x21
	private TileType _tileType; // 0x24
	private Boolean _useOwnerRootTile; // 0x28
	private static DelegateBridge __Hotfix0_get_specifyTileType; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Boolean specifyTileType { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fe1600 VA: 0x75945f9600
	private Boolean get_specifyTileType() { }
	// RVA: 0x1fe1668 VA: 0x75945f9668
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe16d0 VA: 0x75945f96d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe1a80 VA: 0x75945f9a80
	public Void .ctor() { }
	// RVA: 0x1fe1b28 VA: 0x75945f9b28
	private Int32 <Execute>b__13_1(Int32 modeIndex) { }
}
```
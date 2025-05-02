# CheckDynamicBuffTileModeOneLine

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Direction _direction`

- `Boolean _useCurrentTileDirection`

- `Int32 _modeIndex`

- `Boolean _exceptCurrentTile`

- `Boolean _dontCheckButRecordDirectionToBb`

- `String _blackBoardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckDynamicBuffTileModeOneLine : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Direction _direction; // 0x14
	private Boolean _useCurrentTileDirection; // 0x18
	private Int32 _modeIndex; // 0x1c
	private Boolean _exceptCurrentTile; // 0x20
	private Boolean _dontCheckButRecordDirectionToBb; // 0x21
	private String _blackBoardKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe1e4c VA: 0x75945f9e4c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe1eb4 VA: 0x75945f9eb4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe2264 VA: 0x75945fa264
	public Void .ctor() { }
}
```
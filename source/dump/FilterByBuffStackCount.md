# FilterByBuffStackCount

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _buffKey`

- `Int32 _stackCount`

- `String _stackCountKey`

- `Int32 _stackCountPeeling`

- `CompareType _condType`

- `Boolean _checkFromUnoverridableBuffCount`

- `Boolean _checkSnapshotBuff`

- `Boolean _checkBuffSource`

- `ActionTargetType _sourceType`


## Properties

- `Boolean checkBuffSource`


## Methods

- `Boolean get_checkBuffSource()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByBuffStackCount : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _buffKey; // 0x18
	private Int32 _stackCount; // 0x20
	private String _stackCountKey; // 0x28
	private Int32 _stackCountPeeling; // 0x30
	private CompareType _condType; // 0x34
	private Boolean _checkFromUnoverridableBuffCount; // 0x38
	private Boolean _checkSnapshotBuff; // 0x39
	private Boolean _checkBuffSource; // 0x3a
	private ActionTargetType _sourceType; // 0x3c
	private static DelegateBridge __Hotfix0_get_checkBuffSource; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean checkBuffSource { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f17aec VA: 0x759452faec
	public Boolean get_checkBuffSource() { }
	// RVA: 0x1f17b54 VA: 0x759452fb54
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f17bbc VA: 0x759452fbbc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f17ed0 VA: 0x759452fed0
	public Void .ctor() { }
}
```
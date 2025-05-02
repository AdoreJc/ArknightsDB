# LogExtraBattleInfo

**Namespace:** ` `


## Fields

- `LogType _logType`

- `String _key`

- `Boolean _loadKeyFromBlackBoard`

- `Boolean _countInHostIfToken`

- `Int32 _additionValue`

- `LogAttributeType _attributeType`

- `ActionTargetType _target`


## Properties

- `Boolean InspectKey`

- `Boolean InspectAttributeType`


## Methods

- `Boolean get_InspectKey()`

- `Boolean get_InspectAttributeType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LogExtraBattleInfo : ActionNode
{
	private LogType _logType; // 0x10
	private String _key; // 0x18
	private Boolean _loadKeyFromBlackBoard; // 0x20
	private Boolean _countInHostIfToken; // 0x21
	private Int32 _additionValue; // 0x24
	private LogAttributeType _attributeType; // 0x28
	private ActionTargetType _target; // 0x2c
	private static DelegateBridge __Hotfix0_get_InspectKey; // 0x0
	private static DelegateBridge __Hotfix0_get_InspectAttributeType; // 0x8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Boolean InspectKey { get; }
	private Boolean InspectAttributeType { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1ee9468 VA: 0x7594501468
	private Boolean get_InspectKey() { }
	// RVA: 0x1ee94f4 VA: 0x75945014f4
	private Boolean get_InspectAttributeType() { }
	// RVA: 0x1ee9564 VA: 0x7594501564
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee95cc VA: 0x75945015cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eea430 VA: 0x7594502430
	public Void .ctor() { }
}
```
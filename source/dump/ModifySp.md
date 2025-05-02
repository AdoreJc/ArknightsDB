# ModifySp

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _modifyByRatio`

- `Single _modifyRatio`

- `Boolean _modifyByRatioBasedOnCurSP`

- `Boolean _dontCheckSpType`

- `SpType _spMask`

- `Boolean _forceFlag`

- `Boolean _dontShowSpUI`

- `Int32 _modifyValue`

- `String _spString`

- `Boolean _isMinis`


## Properties

- `Boolean checkSpType`


## Methods

- `Boolean get_checkSpType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifySp : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _modifyByRatio; // 0x14
	private Single _modifyRatio; // 0x18
	private Boolean _modifyByRatioBasedOnCurSP; // 0x1c
	private Boolean _dontCheckSpType; // 0x1d
	private SpType _spMask; // 0x20
	private Boolean _forceFlag; // 0x24
	private Boolean _dontShowSpUI; // 0x25
	private Int32 _modifyValue; // 0x28
	private String _spString; // 0x30
	private Boolean _isMinis; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_checkSpType; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	public Boolean checkSpType { get; }

	// RVA: 0x1f0d1f4 VA: 0x75945251f4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0d25c VA: 0x759452525c
	public Boolean get_checkSpType() { }
	// RVA: 0x1f0d2cc VA: 0x75945252cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0d64c VA: 0x759452564c
	public Void .ctor() { }
}
```
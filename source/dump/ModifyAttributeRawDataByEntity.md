# ModifyAttributeRawDataByEntity

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `ActionTargetType _sourceType`

- `Boolean _useCardSnapshot`

- `Boolean _useRatio`


## Methods

- `Void _DoModifyRawData(ObscuredFP[], Character, FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyAttributeRawDataByEntity : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private Boolean _useCardSnapshot; // 0x18
	private Boolean _useRatio; // 0x19
	private AttributeType[] _typesNeedtoUseRatio; // 0x20
	private AttributeType[] _typesNeedtoModify; // 0x28
	private ObscuredFP[] m_data; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__DoModifyRawData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f36008 VA: 0x759454e008
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f36070 VA: 0x759454e070
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3643c VA: 0x759454e43c
	private Void _DoModifyRawData(ObscuredFP[] newData, Character target, FP ratio) { }
	// RVA: 0x1f3667c VA: 0x759454e67c
	public Void .ctor() { }
}
```
# ModifierConfig

**Namespace:** ` `


## Fields

- `FormulaType _formulaType`

- `Boolean _acceptEmptyBB`

- `Boolean _validateSkillIndices`

- `DataType _source`

- `String _sourceTalentKey`

- `String _sourceKey`

- `DataType _source2`

- `String _sourceTalentKey2`

- `String _sourceKey2`

- `DataType _target`

- `String _targetTalentKey`

- `String _targetKey`

- `Boolean _overrideRangeId`

- `ModifyType _type`


## Properties

- `HelpItem helpInfo`

- `Boolean ValidateSkillIndices`

- `Boolean IsFormulaType3`

- `Boolean IsTalentSource`

- `Boolean IsTalentSource2`

- `Boolean IsTalentTarget`


## Methods

- `HelpItem get_helpInfo()`

- `Boolean get_ValidateSkillIndices()`

- `Boolean get_IsFormulaType3()`

- `Boolean get_IsTalentSource()`

- `Boolean get_IsTalentSource2()`

- `Boolean get_IsTalentTarget()`

- `Void GetSource(DataType, BattleCharacterData, Dictionary`2, ref, ref, String)`

- `Modifier CreateModifier(BattleCharacterData, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifierConfig
{
	private FormulaType _formulaType; // 0x10
	private Boolean _acceptEmptyBB; // 0x14
	private Boolean _validateSkillIndices; // 0x15
	private Int32[] _skillIndices; // 0x18
	private DataType _source; // 0x20
	private String _sourceTalentKey; // 0x28
	private String _sourceKey; // 0x30
	private DataType _source2; // 0x38
	private String _sourceTalentKey2; // 0x40
	private String _sourceKey2; // 0x48
	private DataType _target; // 0x50
	private String _targetTalentKey; // 0x58
	private String _targetKey; // 0x60
	private Boolean _overrideRangeId; // 0x68
	private ModifyType _type; // 0x6c

	private HelpItem helpInfo { get; }
	private Boolean ValidateSkillIndices { get; }
	private Boolean IsFormulaType3 { get; }
	private Boolean IsTalentSource { get; }
	private Boolean IsTalentSource2 { get; }
	private Boolean IsTalentTarget { get; }

	// RVA: 0x1c3a528 VA: 0x7594252528
	private HelpItem get_helpInfo() { }
	// RVA: 0x1c3b358 VA: 0x7594253358
	private Boolean get_ValidateSkillIndices() { }
	// RVA: 0x1c3b360 VA: 0x7594253360
	private Boolean get_IsFormulaType3() { }
	// RVA: 0x1c3b370 VA: 0x7594253370
	private Boolean get_IsTalentSource() { }
	// RVA: 0x1c3b380 VA: 0x7594253380
	private Boolean get_IsTalentSource2() { }
	// RVA: 0x1c3b3a0 VA: 0x75942533a0
	private Boolean get_IsTalentTarget() { }
	// RVA: 0x1c3b3b0 VA: 0x75942533b0
	private Void GetSource(DataType dataType, BattleCharacterData dataSource, Dictionary`2 talentMap, ref Blackboard blackboard, ref String rangeIdToOverride, String sourceTalentKey) { }
	// RVA: 0x1c398cc VA: 0x75942518cc
	public Modifier CreateModifier(BattleCharacterData dataSource, Dictionary`2 talentMap) { }
	// RVA: 0x1c3b4d8 VA: 0x75942534d8
	public Void .ctor() { }
}
```
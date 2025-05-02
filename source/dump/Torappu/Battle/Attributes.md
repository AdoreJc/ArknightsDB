# Attributes

**Namespace:** `Torappu.Battle`


## Fields

- `AbnormalComboManager m_abnormalComboMgr`

- `Int64 m_dirtyMask`


## Methods

- `Void Reset(AttributesData)`

- `Void OverwriteRawData(AttributeType, FP, Boolean)`

- `Void AddModifier(IAttributesModifier)`

- `Void RemoveModifier(IAttributesModifier)`

- `Void AddModifierToSingleAttribute(IAttributesModifier, AttributeType)`

- `FP GetValue(AttributeType)`

- `FP GetRawValue(AttributeType)`

- `Int32 GetValueRoundToInt(AttributeType)`

- `Boolean GetAbnormalFlag(AbnormalFlag)`

- `Boolean GetAbnormalImmune(AbnormalFlag)`

- `Boolean GetAbnormalCombo(AbnormalCombo)`

- `Boolean GetAbnormalAnti(AbnormalFlag)`

- `Boolean GetAbnormalFlagWithImmune(AbnormalFlag, AbnormalFlag, AbnormalCombo)`

- `Boolean GetAbnormalFlagWithImmuneFlag(AbnormalFlag, AbnormalFlag)`

- `Boolean GetAbnormalFlagWithImmuneCombo(AbnormalFlag, AbnormalCombo)`

- `Void MarkAttributeDirty(AttributeType)`

- `Void MarkAttributesDirty(Int64)`

- `Boolean CheckAbnormalImmune(AbnormalFlag)`

- `Boolean CheckAbnormalComboImmune(AbnormalCombo)`

- `AttributesData Dump()`

- `FP _CalculateAttributeValue(AttributeType)`

- `Void _MarkAbnormalFlagDirty(AbnormalFlag)`

- `Void _MarkAbnormalComboDirty(AbnormalCombo)`

- `Void _CalculateAbnormalDirtyByModifier(IAttributesModifier)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Attributes
{
	private HashSet`1 m_abnormalFlagModifiers; // 0x10
	private HashSet`1[] m_attributeModifiers; // 0x18
	private Int16[] m_abnormalFlagsCounter; // 0x20
	private Int16[] m_abnormalImmuneCounter; // 0x28
	private Int16[] m_abnormalAntiCounter; // 0x30
	private AbnormalComboManager m_abnormalComboMgr; // 0x38
	private ObscuredFP[] m_rawData; // 0x40
	private TSVector2[] m_dataRange; // 0x48
	private ObscuredFP[] m_cachedData; // 0x50
	private Int64 m_dirtyMask; // 0x58
	public Action`2 onAttributeMarkedDirty; // 0x60
	public Action`1 onAbnormalFlagDirty; // 0x68
	public Action`1 onAbnormalComboDirty; // 0x70

	public ObscuredFP[] rawData { get; }

	// RVA: 0x3f675b0 VA: 0x759657f5b0
	public ObscuredFP[] get_rawData() { }
	// RVA: 0x3f675b8 VA: 0x759657f5b8
	public Void .ctor() { }
	// RVA: 0x3f67814 VA: 0x759657f814
	public Void .ctor(AttributesData rawData) { }
	// RVA: 0x3f67a08 VA: 0x759657fa08
	public Void Reset(AttributesData rawData) { }
	// RVA: 0x3f680cc VA: 0x75965800cc
	public Void OverwriteRawData(AttributeType attributeType, FP rawValue, Boolean refresh) { }
	// RVA: 0x3f68214 VA: 0x7596580214
	public Void AddModifier(IAttributesModifier modifier) { }
	// RVA: 0x3f68904 VA: 0x7596580904
	public Void RemoveModifier(IAttributesModifier modifier) { }
	// RVA: 0x3f68df0 VA: 0x7596580df0
	public Void AddModifierToSingleAttribute(IAttributesModifier modifier, AttributeType attributeType) { }
	// RVA: 0x3f60f98 VA: 0x7596578f98
	public FP GetValue(AttributeType attributeType) { }
	// RVA: 0x3f693c0 VA: 0x75965813c0
	public FP GetRawValue(AttributeType attributeType) { }
	// RVA: 0x3f69414 VA: 0x7596581414
	public Int32 GetValueRoundToInt(AttributeType attributeType) { }
	// RVA: 0x3f6948c VA: 0x759658148c
	public Boolean GetAbnormalFlag(AbnormalFlag abnormalFlag) { }
	// RVA: 0x3f69528 VA: 0x7596581528
	public Boolean GetAbnormalImmune(AbnormalFlag abnormalFlag) { }
	// RVA: 0x3f69560 VA: 0x7596581560
	public Boolean GetAbnormalCombo(AbnormalCombo abnormalCombo) { }
	// RVA: 0x3f695e0 VA: 0x75965815e0
	public Boolean GetAbnormalAnti(AbnormalFlag abnormalFlag) { }
	// RVA: 0x3f69618 VA: 0x7596581618
	public Boolean GetAbnormalFlagWithImmune(AbnormalFlag abnormalFlag, AbnormalFlag abnormalImmune, AbnormalCombo abnormalComboImmune) { }
	// RVA: 0x3f6965c VA: 0x759658165c
	public Boolean GetAbnormalFlagWithImmuneFlag(AbnormalFlag abnormalFlag, AbnormalFlag abnormalImmune) { }
	// RVA: 0x3f696f0 VA: 0x75965816f0
	public Boolean GetAbnormalFlagWithImmuneCombo(AbnormalFlag abnormalFlag, AbnormalCombo abnormalComboImmune) { }
	// RVA: 0x3f68180 VA: 0x7596580180
	public Void MarkAttributeDirty(AttributeType attributeType) { }
	// RVA: 0x3f697e0 VA: 0x75965817e0
	public Void MarkAttributesDirty(Int64 attributeMask) { }
	// RVA: 0x3f698ac VA: 0x75965818ac
	public Boolean CheckAbnormalImmune(AbnormalFlag abnormalFlag) { }
	// RVA: 0x3f698e4 VA: 0x75965818e4
	public Boolean CheckAbnormalComboImmune(AbnormalCombo abnormalCombo) { }
	// RVA: 0x3f69934 VA: 0x7596581934
	public AttributesData Dump() { }
	// RVA: 0x3f68f10 VA: 0x7596580f10
	private FP _CalculateAttributeValue(AttributeType attributeType) { }
	// RVA: 0x3f69bc8 VA: 0x7596581bc8
	private Void _MarkAbnormalFlagDirty(AbnormalFlag abnormalFlag) { }
	// RVA: 0x3f69be4 VA: 0x7596581be4
	private Void _MarkAbnormalComboDirty(AbnormalCombo abnormalCombo) { }
	// RVA: 0x3f68618 VA: 0x7596580618
	private Void _CalculateAbnormalDirtyByModifier(IAttributesModifier modifier) { }
}
```
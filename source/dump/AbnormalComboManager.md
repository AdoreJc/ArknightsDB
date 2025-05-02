# AbnormalComboManager

**Namespace:** ` `


## Fields

- `Int64 m_abnormalComboMask`

- `Int64 m_abnormalFlagMask`


## Methods

- `Void Reset()`

- `Void PushMask(Int64, Int64)`

- `Void PopMask(Int64, Int64)`

- `Boolean GetAbnormalFlag(AbnormalFlag)`

- `Boolean GetAbnormalFlagWithImmuneComboFlag(AbnormalFlag, AbnormalCombo)`

- `Boolean GetComboFlag(AbnormalCombo)`

- `Boolean CheckAbnormalComboImmune(AbnormalCombo)`

- `Boolean _UpdateAbnormalCombo(Int32, Int64)`

- `Int64 _GenerateAbnormalFlagMaskFromComboMask(Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AbnormalComboManager
{
	private static readonly Int64[] ABNORMAL_COMBO_TO_FLAG_MASK; // 0x0
	private Int16[] m_abnormalComboCounter; // 0x10
	private Int16[] m_abnormalComboImmuneCounter; // 0x18
	private Int64 m_abnormalComboMask; // 0x20
	private Int64 m_abnormalFlagMask; // 0x28


	// RVA: 0x3f67f84 VA: 0x759657ff84
	public Void Reset() { }
	// RVA: 0x3f67fe4 VA: 0x759657ffe4
	public Void PushMask(Int64 comboMask, Int64 immuneMask) { }
	// RVA: 0x3f68d08 VA: 0x7596580d08
	public Void PopMask(Int64 comboMask, Int64 immuneMask) { }
	// RVA: 0x3f69510 VA: 0x7596581510
	public Boolean GetAbnormalFlag(AbnormalFlag abnormalFlag) { }
	// RVA: 0x3f69764 VA: 0x7596581764
	public Boolean GetAbnormalFlagWithImmuneComboFlag(AbnormalFlag abnormalFlag, AbnormalCombo abnormalComboImmune) { }
	// RVA: 0x3f69578 VA: 0x7596581578
	public Boolean GetComboFlag(AbnormalCombo abnormalCombo) { }
	// RVA: 0x3f698fc VA: 0x75965818fc
	public Boolean CheckAbnormalComboImmune(AbnormalCombo abnormalCombo) { }
	// RVA: 0x3f69c00 VA: 0x7596581c00
	private Boolean _UpdateAbnormalCombo(Int32 index, Int64 pow2Mask) { }
	// RVA: 0x3f69ca8 VA: 0x7596581ca8
	private Int64 _GenerateAbnormalFlagMaskFromComboMask(Int64 abnormalComboMask) { }
	// RVA: 0x3f67794 VA: 0x759657f794
	public Void .ctor() { }
	// RVA: 0x3f69d5c VA: 0x7596581d5c
	private static Void .cctor() { }
}
```
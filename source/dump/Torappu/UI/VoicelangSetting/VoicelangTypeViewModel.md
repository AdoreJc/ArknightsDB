# VoicelangTypeViewModel

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `String m_typeName`

- `VoiceLangGroupType m_type`

- `Int32 m_count`

- `Boolean m_selected`

- `Boolean m_valid`

- `Boolean m_isAll`


## Properties

- `String TypeName`

- `VoiceLangGroupType type`

- `Boolean valid`

- `Boolean selected`

- `Boolean isAll`

- `Int32 count`


## Methods

- `String get_TypeName()`

- `VoiceLangGroupType get_type()`

- `Boolean get_valid()`

- `Boolean get_selected()`

- `Void set_selected(Boolean)`

- `Boolean get_isAll()`

- `Void set_isAll(Boolean)`

- `Int32 get_count()`

- `Void set_count(Int32)`

- `Void FillModel(VoiceLangGroupType, Boolean, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangTypeViewModel
{
	private String m_typeName; // 0x10
	private VoiceLangGroupType m_type; // 0x18
	private Int32 m_count; // 0x1c
	private Boolean m_selected; // 0x20
	private Boolean m_valid; // 0x21
	private Boolean m_isAll; // 0x22

	public String TypeName { get; }
	public VoiceLangGroupType type { get; }
	public Boolean valid { get; }
	public Boolean selected { get; set; }
	public Boolean isAll { get; set; }
	public Int32 count { get; set; }

	// RVA: 0x229ca90 VA: 0x75948b4a90
	public String get_TypeName() { }
	// RVA: 0x229ca98 VA: 0x75948b4a98
	public VoiceLangGroupType get_type() { }
	// RVA: 0x229caa0 VA: 0x75948b4aa0
	public Boolean get_valid() { }
	// RVA: 0x229caa8 VA: 0x75948b4aa8
	public Boolean get_selected() { }
	// RVA: 0x229cab0 VA: 0x75948b4ab0
	public Void set_selected(Boolean value) { }
	// RVA: 0x229cabc VA: 0x75948b4abc
	public Boolean get_isAll() { }
	// RVA: 0x229cac4 VA: 0x75948b4ac4
	public Void set_isAll(Boolean value) { }
	// RVA: 0x229cad0 VA: 0x75948b4ad0
	public Int32 get_count() { }
	// RVA: 0x229cad8 VA: 0x75948b4ad8
	public Void set_count(Int32 value) { }
	// RVA: 0x229c348 VA: 0x75948b4348
	public Void FillModel(VoiceLangGroupType type, Boolean valid, Boolean selected, Boolean isAll) { }
	// RVA: 0x229c340 VA: 0x75948b4340
	public Void .ctor() { }
}
```
# VoicelangPowerViewModel

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `String m_powerId`

- `String m_powerCode`

- `String m_powerName`

- `Int32 m_orderNum`

- `Boolean m_isAll`

- `Boolean m_isNew`


## Properties

- `String powerId`

- `String powerCode`

- `String powerName`

- `Int32 orderNum`

- `Boolean isAll`

- `Boolean isNew`


## Methods

- `String get_powerId()`

- `String get_powerCode()`

- `Void set_powerCode(String)`

- `String get_powerName()`

- `Void set_powerName(String)`

- `Int32 get_orderNum()`

- `Void set_orderNum(Int32)`

- `Boolean get_isAll()`

- `Void set_isAll(Boolean)`

- `Boolean get_isNew()`

- `Void set_isNew(Boolean)`

- `Void FillViewModel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangPowerViewModel
{
	public const String POWERID_ALL; // 0x0
	private String m_powerId; // 0x10
	private String m_powerCode; // 0x18
	private String m_powerName; // 0x20
	private Int32 m_orderNum; // 0x28
	private Boolean m_isAll; // 0x2c
	private Boolean m_isNew; // 0x2d

	public String powerId { get; }
	public String powerCode { get; set; }
	public String powerName { get; set; }
	public Int32 orderNum { get; set; }
	public Boolean isAll { get; set; }
	public Boolean isNew { get; set; }

	// RVA: 0x229b844 VA: 0x75948b3844
	public String get_powerId() { }
	// RVA: 0x229b84c VA: 0x75948b384c
	public String get_powerCode() { }
	// RVA: 0x229b854 VA: 0x75948b3854
	public Void set_powerCode(String value) { }
	// RVA: 0x229b85c VA: 0x75948b385c
	public String get_powerName() { }
	// RVA: 0x229b864 VA: 0x75948b3864
	public Void set_powerName(String value) { }
	// RVA: 0x229b86c VA: 0x75948b386c
	public Int32 get_orderNum() { }
	// RVA: 0x229b874 VA: 0x75948b3874
	public Void set_orderNum(Int32 value) { }
	// RVA: 0x229b87c VA: 0x75948b387c
	public Boolean get_isAll() { }
	// RVA: 0x229b884 VA: 0x75948b3884
	public Void set_isAll(Boolean value) { }
	// RVA: 0x229b890 VA: 0x75948b3890
	public Boolean get_isNew() { }
	// RVA: 0x229b898 VA: 0x75948b3898
	public Void set_isNew(Boolean value) { }
	// RVA: 0x229b8a4 VA: 0x75948b38a4
	public Void FillViewModel(String p_powerId) { }
	// RVA: 0x229ba80 VA: 0x75948b3a80
	public Void .ctor() { }
}
```
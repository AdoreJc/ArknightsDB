# VoicelangPowerGroupViewModel

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `String m_selectPowerId`


## Properties

- `String selectPowerId`


## Methods

- `Void set_dataSource(List`1)`

- `String get_selectPowerId()`

- `Void set_selectPowerId(String)`

- `Void RefreshRedPoint(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangPowerGroupViewModel
{
	private List`1 m_powerViewModels; // 0x10
	private String m_selectPowerId; // 0x18

	public List`1 dataSource { get; set; }
	public String selectPowerId { get; set; }

	// RVA: 0x229b50c VA: 0x75948b350c
	public List`1 get_dataSource() { }
	// RVA: 0x229b514 VA: 0x75948b3514
	public Void set_dataSource(List`1 value) { }
	// RVA: 0x229b51c VA: 0x75948b351c
	public String get_selectPowerId() { }
	// RVA: 0x229b524 VA: 0x75948b3524
	public Void set_selectPowerId(String value) { }
	// RVA: 0x229b52c VA: 0x75948b352c
	public Void RefreshRedPoint(List`1 cardListWithRedPoint) { }
	// RVA: 0x229b750 VA: 0x75948b3750
	public Void .ctor() { }
}
```
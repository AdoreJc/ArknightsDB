# CharGroupViewModel

**Namespace:** ` `


## Fields

- `Boolean isFromHandBook`

- `Int32 equipScrollSequenceNum`

- `Int32 m_focusPos`

- `Int32 m_instId`


## Properties

- `CharViewModel focusCharViewModel`

- `Int32 focusPos`

- `Int32 instId`


## Methods

- `Void RefreshInstId(Int32)`

- `Void CheckIfResumeBackChangeEquip()`

- `Void NotifyRefreshEquipScroll()`

- `CharViewModel get_focusCharViewModel()`

- `Int32 get_focusPos()`

- `Void set_focusPos(Int32)`

- `Int32 get_instId()`

- `Void set_instId(Int32)`

- `Void InitViewModel(List`1, Int32, Boolean)`

- `Void InitViewModel(ICharInfoHomeInitParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CharGroupViewModel
{
	public List`1 charViewModelGroup; // 0x10
	public Boolean isFromHandBook; // 0x18
	public Int32 equipScrollSequenceNum; // 0x1c
	private Int32 m_focusPos; // 0x20
	private Int32 m_instId; // 0x24

	public CharViewModel focusCharViewModel { get; }
	public Int32 focusPos { get; set; }
	public Int32 instId { get; set; }

	// RVA: 0x2d54bcc VA: 0x759536cbcc
	public Void RefreshInstId(Int32 instId) { }
	// RVA: 0x2d56cc4 VA: 0x759536ecc4
	public Void CheckIfResumeBackChangeEquip() { }
	// RVA: 0x2d56d00 VA: 0x759536ed00
	public Void NotifyRefreshEquipScroll() { }
	// RVA: 0x2d544b8 VA: 0x759536c4b8
	public CharViewModel get_focusCharViewModel() { }
	// RVA: 0x2d56d10 VA: 0x759536ed10
	public Int32 get_focusPos() { }
	// RVA: 0x2d54a8c VA: 0x759536ca8c
	public Void set_focusPos(Int32 value) { }
	// RVA: 0x2d56d18 VA: 0x759536ed18
	public Int32 get_instId() { }
	// RVA: 0x2d56d20 VA: 0x759536ed20
	public Void set_instId(Int32 value) { }
	// RVA: 0x2d56df0 VA: 0x759536edf0
	public Void InitViewModel(List`1 i_charViewModelGroup, Int32 i_instId, Boolean i_isFromHandBook) { }
	// RVA: 0x2d54840 VA: 0x759536c840
	public Void InitViewModel(ICharInfoHomeInitParam param) { }
	// RVA: 0x2d54838 VA: 0x759536c838
	public Void .ctor() { }
}
```
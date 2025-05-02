# TuningFragModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_fragId`

- `String m_fragName`

- `Int32 m_fragNum`

- `Int32 m_selectFragNum`

- `Int32 m_sortId`

- `String m_fragFormIconId`

- `String m_fragSmallIconId`


## Properties

- `String fragId`

- `String fragName`

- `Int32 fragNum`

- `Int32 displayFragNum`

- `Int32 selectFragNum`

- `Int32 sortId`

- `String fragFormIconId`

- `String fragSmallIconId`


## Methods

- `String get_fragId()`

- `String get_fragName()`

- `Int32 get_fragNum()`

- `Int32 get_displayFragNum()`

- `Int32 get_selectFragNum()`

- `Int32 get_sortId()`

- `String get_fragFormIconId()`

- `String get_fragSmallIconId()`

- `Void LoadData(Act29SideFragData)`

- `Void UpdateNum(Int32)`

- `Boolean CheckIfDisplayNumZero()`

- `Boolean TrySelectFrag()`

- `Void ClearSelectFrag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningFragModel : IHotfixable
{
	private String m_fragId; // 0x10
	private String m_fragName; // 0x18
	private Int32 m_fragNum; // 0x20
	private Int32 m_selectFragNum; // 0x24
	private Int32 m_sortId; // 0x28
	private String m_fragFormIconId; // 0x30
	private String m_fragSmallIconId; // 0x38
	private static DelegateBridge __Hotfix0_get_fragId; // 0x0
	private static DelegateBridge __Hotfix0_get_fragName; // 0x8
	private static DelegateBridge __Hotfix0_get_fragNum; // 0x10
	private static DelegateBridge __Hotfix0_get_displayFragNum; // 0x18
	private static DelegateBridge __Hotfix0_get_selectFragNum; // 0x20
	private static DelegateBridge __Hotfix0_get_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_fragFormIconId; // 0x30
	private static DelegateBridge __Hotfix0_get_fragSmallIconId; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_UpdateNum; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfDisplayNumZero; // 0x50
	private static DelegateBridge __Hotfix0_TrySelectFrag; // 0x58
	private static DelegateBridge __Hotfix0_ClearSelectFrag; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public String fragId { get; }
	public String fragName { get; }
	public Int32 fragNum { get; }
	public Int32 displayFragNum { get; }
	public Int32 selectFragNum { get; }
	public Int32 sortId { get; }
	public String fragFormIconId { get; }
	public String fragSmallIconId { get; }

	// RVA: 0x233d9ec VA: 0x75949559ec
	public String get_fragId() { }
	// RVA: 0x233da54 VA: 0x7594955a54
	public String get_fragName() { }
	// RVA: 0x233dabc VA: 0x7594955abc
	public Int32 get_fragNum() { }
	// RVA: 0x233db24 VA: 0x7594955b24
	public Int32 get_displayFragNum() { }
	// RVA: 0x233db90 VA: 0x7594955b90
	public Int32 get_selectFragNum() { }
	// RVA: 0x233d8a0 VA: 0x75949558a0
	public Int32 get_sortId() { }
	// RVA: 0x233dbf8 VA: 0x7594955bf8
	public String get_fragFormIconId() { }
	// RVA: 0x233dc60 VA: 0x7594955c60
	public String get_fragSmallIconId() { }
	// RVA: 0x233dcc8 VA: 0x7594955cc8
	public Void LoadData(Act29SideFragData fragData) { }
	// RVA: 0x233dd8c VA: 0x7594955d8c
	public Void UpdateNum(Int32 num) { }
	// RVA: 0x233de08 VA: 0x7594955e08
	public Boolean CheckIfDisplayNumZero() { }
	// RVA: 0x233de78 VA: 0x7594955e78
	public Boolean TrySelectFrag() { }
	// RVA: 0x233defc VA: 0x7594955efc
	public Void ClearSelectFrag() { }
	// RVA: 0x233df64 VA: 0x7594955f64
	public Void .ctor() { }
}
```
# MagneticDotSliderViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Int32 m_selectIndex`


## Methods

- `Int32 GetSelectIndex()`

- `Void LoadData(List`1)`

- `Boolean UpdateSelection(Single, Single)`

- `Int32 GetCurValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class MagneticDotSliderViewModel : IHotfixable
{
	private List`1 m_dotItemList; // 0x10
	private Int32 m_selectIndex; // 0x18
	private static DelegateBridge __Hotfix0_get_dotItemList; // 0x0
	private static DelegateBridge __Hotfix0_GetSelectIndex; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_UpdateSelection; // 0x18
	private static DelegateBridge __Hotfix0_GetCurValue; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public List`1 dotItemList { get; }

	// RVA: 0x28a76a0 VA: 0x7594ebf6a0
	public List`1 get_dotItemList() { }
	// RVA: 0x28a7b18 VA: 0x7594ebfb18
	public Int32 GetSelectIndex() { }
	// RVA: 0x28a7b80 VA: 0x7594ebfb80
	public Void LoadData(List`1 input) { }
	// RVA: 0x28a7dc8 VA: 0x7594ebfdc8
	public Boolean UpdateSelection(Single curIndex, Single dotBias) { }
	// RVA: 0x28a7608 VA: 0x7594ebf608
	public Int32 GetCurValue() { }
	// RVA: 0x28a7f34 VA: 0x7594ebff34
	public Void .ctor() { }
}
```
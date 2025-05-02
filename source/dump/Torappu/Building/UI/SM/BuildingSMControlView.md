# BuildingSMControlView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `Text _textMpCost`

- `Text _textMpReduce`

- `SimpleLayoutContent _mpCostLayout`

- `SimpleLayoutContent _mpReduceLayout`

- `ListAdapter m_mpCostAdapter`

- `ListAdapter m_mpReduceAdapter`


## Methods

- `Void _FormatControlBuffedValue(Int64, SimpleLayoutContent, ref, Color, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingSMControlView : BuildingSMSingleRoomTypeView
{
	private Text _textMpCost; // 0x38
	private Text _textMpReduce; // 0x40
	private SimpleLayoutContent _mpCostLayout; // 0x48
	private SimpleLayoutContent _mpReduceLayout; // 0x50
	private ListAdapter m_mpCostAdapter; // 0x58
	private ListAdapter m_mpReduceAdapter; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__FormatControlBuffedValue; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3db6528 VA: 0x75963ce528
	public override Void Render(SelectedRoomDetailViewModel roomModel) { }
	// RVA: 0x3db66e8 VA: 0x75963ce6e8
	private Void _FormatControlBuffedValue(Int64 buffVal, SimpleLayoutContent layout, ref ListAdapter refAdapter, Color bkgColor, Color textColor) { }
	// RVA: 0x3db694c VA: 0x75963ce94c
	public Void .ctor() { }
}
```
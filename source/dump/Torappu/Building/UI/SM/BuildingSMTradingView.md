# BuildingSMTradingView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `Text _textManpowerCost`

- `SimpleLayoutContent _mpBuffLayout`

- `ThreeStateToggle _toggleManpowerCost`

- `Text _textSpeedEmpty`

- `SimpleLayoutContent _speedBuffLayout`

- `ThreeStateToggle _toggleOrderSpeed`

- `Color _bkgBuffColor`

- `Color _textBuffColor`

- `ListAdapter m_mpBuffAdapter`

- `ListAdapter m_speedBuffAdapter`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingSMTradingView : BuildingSMSingleRoomTypeView
{
	private Text _textManpowerCost; // 0x38
	private SimpleLayoutContent _mpBuffLayout; // 0x40
	private ThreeStateToggle _toggleManpowerCost; // 0x48
	private Text _textSpeedEmpty; // 0x50
	private SimpleLayoutContent _speedBuffLayout; // 0x58
	private ThreeStateToggle _toggleOrderSpeed; // 0x60
	private Color _bkgBuffColor; // 0x68
	private Color _textBuffColor; // 0x78
	private ListAdapter m_mpBuffAdapter; // 0x88
	private ListAdapter m_speedBuffAdapter; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__UpdateToggleByBuff; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3db6ef8 VA: 0x75963ceef8
	public override Void Render(SelectedRoomDetailViewModel roomModel) { }
	// RVA: 0x3db7128 VA: 0x75963cf128
	private static Void _UpdateToggleByBuff(ThreeStateToggle toggle, Single buffVal, Int32 sign) { }
	// RVA: 0x3db723c VA: 0x75963cf23c
	public Void .ctor() { }
}
```
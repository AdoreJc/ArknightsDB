# BuildingSMManufactureView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `Text _textManpowerCost`

- `SimpleLayoutContent _mpBuffLayout`

- `Text _textSpeed`

- `SimpleLayoutContent _speedBuffLayout`

- `GameObject _iconSpeedUp`

- `GameObject _iconMpDown`

- `Color _bkgBuffColor`

- `Color _textBuffColor`

- `ListAdapter m_speedBuffAdapter`

- `ListAdapter m_mpBuffAdapter`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingSMManufactureView : BuildingSMSingleRoomTypeView
{
	private Text _textManpowerCost; // 0x38
	private SimpleLayoutContent _mpBuffLayout; // 0x40
	private Text _textSpeed; // 0x48
	private SimpleLayoutContent _speedBuffLayout; // 0x50
	private GameObject _iconSpeedUp; // 0x58
	private GameObject _iconMpDown; // 0x60
	private Color _bkgBuffColor; // 0x68
	private Color _textBuffColor; // 0x78
	private ListAdapter m_speedBuffAdapter; // 0x88
	private ListAdapter m_mpBuffAdapter; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3db69bc VA: 0x75963ce9bc
	public override Void Render(SelectedRoomDetailViewModel roomModel) { }
	// RVA: 0x3db6c4c VA: 0x75963cec4c
	public Void .ctor() { }
}
```
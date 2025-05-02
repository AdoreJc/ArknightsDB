# BuildingHireRefreshCountView

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Image _imgBkg`

- `Text _textCount`

- `Text _textLimit`

- `Color _colorBkgFull`

- `Color _colorBkgHalf`

- `Color _colorTextFull`

- `Color _colorTextHalf`


## Methods

- `Void Render(HiringSnapshot)`

- `Color _PickColor(HiringSnapshot, Color, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingHireRefreshCountView : MonoBehaviour
{
	private Image _imgBkg; // 0x18
	private Text _textCount; // 0x20
	private Text _textLimit; // 0x28
	private Color _colorBkgFull; // 0x30
	private Color _colorBkgHalf; // 0x40
	private Color _colorTextFull; // 0x50
	private Color _colorTextHalf; // 0x60


	// RVA: 0x3e2fcc8 VA: 0x7596447cc8
	public Void Render(HiringSnapshot snapshot) { }
	// RVA: 0x3e2fea4 VA: 0x7596447ea4
	private Color _PickColor(HiringSnapshot snapshot, Color halfColor, Color fullColor) { }
	// RVA: 0x3e2fec0 VA: 0x7596447ec0
	public Void .ctor() { }
}
```
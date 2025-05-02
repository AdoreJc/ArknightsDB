# BStationViewForProgressRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `Text _textNumber`

- `Text _textHilightNumber`

- `Text _textLimit`

- `GameObject _iconCharTired`

- `GameObject _iconCharNormal`


## Methods

- `Void Render(BStationInfoModel)`

- `Void _ChooseText(String, Text, Text)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BStationViewForProgressRoom : MonoBehaviour
{
	private Text _textNumber; // 0x18
	private Text _textHilightNumber; // 0x20
	private Text _textLimit; // 0x28
	private GameObject _iconCharTired; // 0x30
	private GameObject _iconCharNormal; // 0x38


	// RVA: 0x3d1cae4 VA: 0x7596334ae4
	public Void Render(BStationInfoModel infoModel) { }
	// RVA: 0x3d21eb4 VA: 0x7596339eb4
	private Void _ChooseText(String text, Text enabled, Text disabled) { }
	// RVA: 0x3d21fac VA: 0x7596339fac
	public Void .ctor() { }
}
```
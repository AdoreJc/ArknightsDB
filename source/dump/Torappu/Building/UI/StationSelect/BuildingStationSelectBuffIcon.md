# BuildingStationSelectBuffIcon

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `Image _icon`

- `Image _imgHalo`

- `Image _imgHilight`

- `Single _disableAlpha`

- `BuffStruct m_buffCache`

- `Boolean m_isInited`

- `BuildingBuffImgConfig m_imageConfig`


## Methods

- `Void Render(BuffStruct)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectBuffIcon : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private Image _imgHalo; // 0x20
	private Image _imgHilight; // 0x28
	private Single _disableAlpha; // 0x30
	private BuffStruct m_buffCache; // 0x38
	private Boolean m_isInited; // 0x90
	private BuildingBuffImgConfig m_imageConfig; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3d97dfc VA: 0x75963afdfc
	public Void Render(BuffStruct buffStruct) { }
	// RVA: 0x3d981bc VA: 0x75963b01bc
	public Void .ctor() { }
}
```
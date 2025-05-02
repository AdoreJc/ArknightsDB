# BuildingWorkshopFilterPanelItem

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `Text _txtNameNormal`

- `Text _txtNameSelect`

- `Image _imgStrip`

- `TwoStateToggle _stateToggle`

- `Int32 m_index`

- `String m_cachedColorStr`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(RenderParam)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopFilterPanelItem : MonoBehaviour, IHotfixable
{
	private Text _txtNameNormal; // 0x18
	private Text _txtNameSelect; // 0x20
	private Image _imgStrip; // 0x28
	private TwoStateToggle _stateToggle; // 0x30
	private Int32 m_index; // 0x38
	private String m_cachedColorStr; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3d6c5bc VA: 0x75963845bc
	public Void Render(RenderParam param) { }
	// RVA: 0x3d6c6f4 VA: 0x75963846f4
	public Void OnClick() { }
	// RVA: 0x3d6c7fc VA: 0x75963847fc
	public Void .ctor() { }
}
```
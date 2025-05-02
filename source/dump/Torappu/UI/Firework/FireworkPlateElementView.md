# FireworkPlateElementView

**Namespace:** `Torappu.UI.Firework`


## Fields

- `GameObject _pnlDisabled`

- `GameObject _pnlCenter`

- `GameObject _pnlConflict`

- `UIAtlasImage _imgBkg`

- `UIAtlasImage _imgDisabled`

- `UIAtlasImage _imgCenter`

- `UIAtlasImage _imgConflict`

- `Single _tweenDuration`

- `Tween m_tween`

- `Int32 m_cachedLoadSeqNum`

- `GridPosition <gridPos>k__BackingField`


## Properties

- `GridPosition gridPos`


## Methods

- `GridPosition get_gridPos()`

- `Void set_gridPos(GridPosition)`

- `Void Render(FireworkPlateModel, FireworkPlateViewStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateElementView : MonoBehaviour, IFireworkPlateElementView, IHotfixable
{
	private GameObject _pnlDisabled; // 0x18
	private GameObject _pnlCenter; // 0x20
	private GameObject _pnlConflict; // 0x28
	private UIAtlasImage _imgBkg; // 0x30
	private UIAtlasImage _imgDisabled; // 0x38
	private UIAtlasImage _imgCenter; // 0x40
	private UIAtlasImage _imgConflict; // 0x48
	private Single _tweenDuration; // 0x50
	private Tween m_tween; // 0x58
	private Int32 m_cachedLoadSeqNum; // 0x60
	private GridPosition <gridPos>k__BackingField; // 0x64
	private static DelegateBridge __Hotfix0_get_gridPos; // 0x0
	private static DelegateBridge __Hotfix0_set_gridPos; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public GridPosition gridPos { get; set; }

	// RVA: 0x28eb7b0 VA: 0x7594f037b0
	public GridPosition get_gridPos() { }
	// RVA: 0x28eb818 VA: 0x7594f03818
	public Void set_gridPos(GridPosition value) { }
	// RVA: 0x28eb894 VA: 0x7594f03894
	public Void Render(FireworkPlateModel plateModel, FireworkPlateViewStyle style) { }
	// RVA: 0x28ebe40 VA: 0x7594f03e40
	public Void .ctor() { }
}
```
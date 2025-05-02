# FireworkPlateSelectionElementView

**Namespace:** `Torappu.UI.Firework`


## Fields

- `Image _imgOutline`

- `CanvasGroup _alphaHandler`

- `Single _highlightDuration`

- `Boolean m_inited`

- `PlateSlotData m_cachedSelectedPlatePiece`

- `PlateSlotData m_cachedLastFilledPlatePiece`

- `UISwitchTween m_showTween`

- `Tween m_highlightTween`

- `GridPosition <gridPos>k__BackingField`


## Properties

- `GridPosition gridPos`


## Methods

- `Void _InitIfNot()`

- `GridPosition get_gridPos()`

- `Void set_gridPos(GridPosition)`

- `Void Render(FireworkPlateGroupModel, FireworkPlateViewStyle)`

- `Void <Render>b__13_0()`

- `Void <Render>b__13_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateSelectionElementView : MonoBehaviour, IFireworkPlateElementView, IHotfixable
{
	private Image _imgOutline; // 0x18
	private CanvasGroup _alphaHandler; // 0x20
	private Single _highlightDuration; // 0x28
	private Boolean m_inited; // 0x2c
	private PlateSlotData m_cachedSelectedPlatePiece; // 0x30
	private PlateSlotData m_cachedLastFilledPlatePiece; // 0x38
	private UISwitchTween m_showTween; // 0x40
	private Tween m_highlightTween; // 0x48
	private GridPosition <gridPos>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_gridPos; // 0x8
	private static DelegateBridge __Hotfix0_set_gridPos; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public GridPosition gridPos { get; set; }

	// RVA: 0x28f1718 VA: 0x7594f09718
	private Void _InitIfNot() { }
	// RVA: 0x28f17fc VA: 0x7594f097fc
	public GridPosition get_gridPos() { }
	// RVA: 0x28f1864 VA: 0x7594f09864
	public Void set_gridPos(GridPosition value) { }
	// RVA: 0x28f18e0 VA: 0x7594f098e0
	public Void Render(FireworkPlateGroupModel plateModel, FireworkPlateViewStyle style) { }
	// RVA: 0x28f1c44 VA: 0x7594f09c44
	public Void .ctor() { }
	// RVA: 0x28f1cb4 VA: 0x7594f09cb4
	private Void <Render>b__13_0() { }
	// RVA: 0x28f1cd4 VA: 0x7594f09cd4
	private Void <Render>b__13_1() { }
}
```
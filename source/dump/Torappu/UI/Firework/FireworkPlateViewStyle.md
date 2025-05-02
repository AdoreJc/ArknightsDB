# FireworkPlateViewStyle

**Namespace:** `Torappu.UI.Firework`


## Fields

- `Color _bkgOutlineColor`

- `Color _centerMarkColor`

- `Color _unavailableMarkColor`

- `Color _filledUnavailableColor`

- `Color _selectedOutlineColor`

- `Color _bkgFrontColor`

- `Single _bkgShadowAlpha`

- `Vector2 _bkgOffset`


## Properties

- `Color bkgOutlineColor`

- `Color centerMarkColor`

- `Color unavailableMarkColor`

- `Color filledUnavailableColor`

- `Color selectedOutlineColor`

- `Color bkgFrontColor`

- `Single bkgShadowAlpha`

- `Vector2 bkgOffset`


## Methods

- `Color get_bkgOutlineColor()`

- `Color get_centerMarkColor()`

- `Color get_unavailableMarkColor()`

- `Color get_filledUnavailableColor()`

- `Color get_selectedOutlineColor()`

- `Color get_bkgFrontColor()`

- `Single get_bkgShadowAlpha()`

- `Vector2 get_bkgOffset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateViewStyle : ScriptableObject, IHotfixable
{
	private Color _bkgOutlineColor; // 0x18
	private Color[] _gridBkgColors; // 0x28
	private Color _centerMarkColor; // 0x30
	private Color _unavailableMarkColor; // 0x40
	private Color _filledUnavailableColor; // 0x50
	private Color _selectedOutlineColor; // 0x60
	private Color _bkgFrontColor; // 0x70
	private Single _bkgShadowAlpha; // 0x80
	private Vector2 _bkgOffset; // 0x84
	private static DelegateBridge __Hotfix0_get_bkgOutlineColor; // 0x0
	private static DelegateBridge __Hotfix0_get_gridBkgColors; // 0x8
	private static DelegateBridge __Hotfix0_get_centerMarkColor; // 0x10
	private static DelegateBridge __Hotfix0_get_unavailableMarkColor; // 0x18
	private static DelegateBridge __Hotfix0_get_filledUnavailableColor; // 0x20
	private static DelegateBridge __Hotfix0_get_selectedOutlineColor; // 0x28
	private static DelegateBridge __Hotfix0_get_bkgFrontColor; // 0x30
	private static DelegateBridge __Hotfix0_get_bkgShadowAlpha; // 0x38
	private static DelegateBridge __Hotfix0_get_bkgOffset; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Color bkgOutlineColor { get; }
	public Color[] gridBkgColors { get; }
	public Color centerMarkColor { get; }
	public Color unavailableMarkColor { get; }
	public Color filledUnavailableColor { get; }
	public Color selectedOutlineColor { get; }
	public Color bkgFrontColor { get; }
	public Single bkgShadowAlpha { get; }
	public Vector2 bkgOffset { get; }

	// RVA: 0x28f30cc VA: 0x7594f0b0cc
	public Color get_bkgOutlineColor() { }
	// RVA: 0x28ebca0 VA: 0x7594f03ca0
	public Color[] get_gridBkgColors() { }
	// RVA: 0x28ebd08 VA: 0x7594f03d08
	public Color get_centerMarkColor() { }
	// RVA: 0x28ebd70 VA: 0x7594f03d70
	public Color get_unavailableMarkColor() { }
	// RVA: 0x28ebdd8 VA: 0x7594f03dd8
	public Color get_filledUnavailableColor() { }
	// RVA: 0x28f1bdc VA: 0x7594f09bdc
	public Color get_selectedOutlineColor() { }
	// RVA: 0x28f3198 VA: 0x7594f0b198
	public Color get_bkgFrontColor() { }
	// RVA: 0x28f3200 VA: 0x7594f0b200
	public Single get_bkgShadowAlpha() { }
	// RVA: 0x28f3134 VA: 0x7594f0b134
	public Vector2 get_bkgOffset() { }
	// RVA: 0x28f32e4 VA: 0x7594f0b2e4
	public Void .ctor() { }
}
```
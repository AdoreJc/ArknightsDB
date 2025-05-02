# CharmCard

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Button _btn`

- `Image _bg`

- `GameObject _selectedFlag`

- `Text _selectedIdx`

- `GameObject _duplication`

- `Text _dupIdx`

- `GameObject _newFlag`

- `GameObject _priceGO`

- `Text _priceLabel`

- `GameObject _recycleBuble`

- `Text _recycleNum`

- `Image _icon`

- `Text _name`

- `GameObject _notOwnFlag`

- `Color _iconNotOwnClr`

- `Color _bgNotOwnClr`

- `AnimationWrapper _animWrapper`

- `CharmModel <data>k__BackingField`


## Properties

- `CharmModel data`

- `Boolean visible`

- `Boolean selected`

- `Boolean clickable`


## Methods

- `CharmModel get_data()`

- `Void set_data(CharmModel)`

- `Void Flush(CharmModel, CharmCardMode)`

- `Void SetVisible(Boolean)`

- `Boolean get_visible()`

- `Boolean get_selected()`

- `Void set_selected(Boolean)`

- `Void SetSelected(Boolean, Boolean)`

- `Void _UpdateSelectStatus(Boolean, Int32)`

- `Tween FadeOut()`

- `Void EventOnClick()`

- `Boolean get_clickable()`

- `Void set_clickable(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmCard : MonoBehaviour, IHotfixable
{
	private Button _btn; // 0x18
	private Sprite[] _raritySprites; // 0x20
	private Image _bg; // 0x28
	private GameObject _selectedFlag; // 0x30
	private Text _selectedIdx; // 0x38
	private GameObject _duplication; // 0x40
	private Text _dupIdx; // 0x48
	private GameObject _newFlag; // 0x50
	private GameObject _priceGO; // 0x58
	private Text _priceLabel; // 0x60
	private GameObject _recycleBuble; // 0x68
	private Text _recycleNum; // 0x70
	private Image _icon; // 0x78
	private Text _name; // 0x80
	private GameObject _notOwnFlag; // 0x88
	private Color _iconNotOwnClr; // 0x90
	private Color _bgNotOwnClr; // 0xa0
	private AnimationWrapper _animWrapper; // 0xb0
	private const String ANIM_FADE_OUT; // 0x0
	private CharmModel <data>k__BackingField; // 0xb8
	public Action`1 onSelectChanged; // 0xc0
	private static DelegateBridge __Hotfix0_get_data; // 0x0
	private static DelegateBridge __Hotfix0_set_data; // 0x8
	private static DelegateBridge __Hotfix0_Flush; // 0x10
	private static DelegateBridge __Hotfix0_SetVisible; // 0x18
	private static DelegateBridge __Hotfix0_get_visible; // 0x20
	private static DelegateBridge __Hotfix0_get_selected; // 0x28
	private static DelegateBridge __Hotfix0_set_selected; // 0x30
	private static DelegateBridge __Hotfix0_SetSelected; // 0x38
	private static DelegateBridge __Hotfix0__UpdateSelectStatus; // 0x40
	private static DelegateBridge __Hotfix0_FadeOut; // 0x48
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x50
	private static DelegateBridge __Hotfix0_get_clickable; // 0x58
	private static DelegateBridge __Hotfix0_set_clickable; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public CharmModel data { get; set; }
	public Boolean visible { get; }
	public Boolean selected { get; set; }
	public Boolean clickable { get; set; }

	// RVA: 0x344fd74 VA: 0x7595a67d74
	public CharmModel get_data() { }
	// RVA: 0x344fddc VA: 0x7595a67ddc
	private Void set_data(CharmModel value) { }
	// RVA: 0x344fe60 VA: 0x7595a67e60
	public Void Flush(CharmModel cm, CharmCardMode mode) { }
	// RVA: 0x3450314 VA: 0x7595a68314
	public Void SetVisible(Boolean v) { }
	// RVA: 0x34503a0 VA: 0x7595a683a0
	public Boolean get_visible() { }
	// RVA: 0x345041c VA: 0x7595a6841c
	public Boolean get_selected() { }
	// RVA: 0x3450494 VA: 0x7595a68494
	public Void set_selected(Boolean value) { }
	// RVA: 0x3450518 VA: 0x7595a68518
	public Void SetSelected(Boolean sel, Boolean notify) { }
	// RVA: 0x3450200 VA: 0x7595a68200
	private Void _UpdateSelectStatus(Boolean sel, Int32 selIdx) { }
	// RVA: 0x3450614 VA: 0x7595a68614
	public Tween FadeOut() { }
	// RVA: 0x34506a8 VA: 0x7595a686a8
	public Void EventOnClick() { }
	// RVA: 0x3450744 VA: 0x7595a68744
	public Boolean get_clickable() { }
	// RVA: 0x34507c4 VA: 0x7595a687c4
	public Void set_clickable(Boolean value) { }
	// RVA: 0x3450858 VA: 0x7595a68858
	public Void .ctor() { }
}
```
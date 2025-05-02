# Act12sideMissionFilterItemView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `ActZoneClass _zoneClass`

- `Image _imgSelected`

- `Text _textClass`

- `Color _colorNormal`

- `Color _colorSelected`


## Methods

- `Void set_onFilterSelected(Action`1)`

- `Void Render(ActZoneClass)`

- `Void OnFilterClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideMissionFilterItemView : MonoBehaviour, IHotfixable
{
	private ActZoneClass _zoneClass; // 0x18
	private Image _imgSelected; // 0x20
	private Text _textClass; // 0x28
	private Color _colorNormal; // 0x30
	private Color _colorSelected; // 0x40
	private Action`1 <onFilterSelected>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onFilterSelected; // 0x0
	private static DelegateBridge __Hotfix0_set_onFilterSelected; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnFilterClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onFilterSelected { get; set; }

	// RVA: 0x3466650 VA: 0x7595a7e650
	private Action`1 get_onFilterSelected() { }
	// RVA: 0x34666b8 VA: 0x7595a7e6b8
	public Void set_onFilterSelected(Action`1 value) { }
	// RVA: 0x346673c VA: 0x7595a7e73c
	public Void Render(ActZoneClass filterClass) { }
	// RVA: 0x3466834 VA: 0x7595a7e834
	public Void OnFilterClick() { }
	// RVA: 0x34668d4 VA: 0x7595a7e8d4
	public Void .ctor() { }
}
```
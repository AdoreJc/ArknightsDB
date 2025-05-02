# SiracusaBigMapAreaFogView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `UIDynImage _imgAreaIcon`

- `Text _txtAreaName`

- `Text _txtAreaItalyName`

- `String m_areaId`

- `Action <fogClickAction>k__BackingField`


## Properties

- `Action fogClickAction`


## Methods

- `Action get_fogClickAction()`

- `Void set_fogClickAction(Action)`

- `Void EventOnFogClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaBigMapAreaFogView : SiracusaMapAreaFogViewBase
{
	private UIDynImage _imgAreaIcon; // 0x38
	private Text _txtAreaName; // 0x40
	private Text _txtAreaItalyName; // 0x48
	private String m_areaId; // 0x50
	private Action <fogClickAction>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_fogClickAction; // 0x0
	private static DelegateBridge __Hotfix0_set_fogClickAction; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnFogClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action fogClickAction { get; set; }

	// RVA: 0x24089fc VA: 0x7594a209fc
	private Action get_fogClickAction() { }
	// RVA: 0x2408a64 VA: 0x7594a20a64
	public Void set_fogClickAction(Action value) { }
	// RVA: 0x2408ae8 VA: 0x7594a20ae8
	public override Void Render(AreaData areaData, Boolean isShow) { }
	// RVA: 0x2408dd0 VA: 0x7594a20dd0
	public Void EventOnFogClicked() { }
	// RVA: 0x2408e6c VA: 0x7594a20e6c
	public Void .ctor() { }
}
```
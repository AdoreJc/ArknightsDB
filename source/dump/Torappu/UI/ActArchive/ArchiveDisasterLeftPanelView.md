# ArchiveDisasterLeftPanelView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _bigIcon`

- `Text _disasterName`

- `Text _disasterDesc`

- `ArchiveDisasterController <controller>k__BackingField`


## Properties

- `ArchiveDisasterController controller`


## Methods

- `ArchiveDisasterController get_controller()`

- `Void set_controller(ArchiveDisasterController)`

- `Void Render(DisasterTypeModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDisasterLeftPanelView : MonoBehaviour, IHotfixable
{
	private Image _bigIcon; // 0x18
	private Text _disasterName; // 0x20
	private Text _disasterDesc; // 0x28
	private ArchiveDisasterController <controller>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private ArchiveDisasterController controller { get; set; }

	// RVA: 0x30484c0 VA: 0x75956604c0
	private ArchiveDisasterController get_controller() { }
	// RVA: 0x3048528 VA: 0x7595660528
	public Void set_controller(ArchiveDisasterController value) { }
	// RVA: 0x30485ac VA: 0x75956605ac
	public Void Render(DisasterTypeModel typeModel) { }
	// RVA: 0x30487f4 VA: 0x75956607f4
	public Void .ctor() { }
}
```
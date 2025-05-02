# ArchiveActivityEntryButtonView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _panelNew`

- `ActArchiveType _archivePanelType`

- `GameObject _panelLocked`

- `GameObject _panelUnlocked`

- `Button _buttonSelf`

- `ArchiveEntryButtonBasePlugin _plugin`

- `ArchiveActivityEntryController <controller>k__BackingField`


## Properties

- `ArchiveActivityEntryController controller`


## Methods

- `ArchiveActivityEntryController get_controller()`

- `Void set_controller(ArchiveActivityEntryController)`

- `Void ApplyData(Dictionary`2)`

- `Void EventOnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveActivityEntryButtonView : MonoBehaviour, IHotfixable
{
	private GameObject _panelNew; // 0x18
	private ActArchiveType _archivePanelType; // 0x20
	private GameObject _panelLocked; // 0x28
	private GameObject _panelUnlocked; // 0x30
	private Button _buttonSelf; // 0x38
	private ArchiveEntryButtonBasePlugin _plugin; // 0x40
	private ArchiveActivityEntryController <controller>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBtnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public ArchiveActivityEntryController controller { get; set; }

	// RVA: 0x301a2e0 VA: 0x75956322e0
	public ArchiveActivityEntryController get_controller() { }
	// RVA: 0x3019f0c VA: 0x7595631f0c
	public Void set_controller(ArchiveActivityEntryController value) { }
	// RVA: 0x301a0d4 VA: 0x75956320d4
	public Void ApplyData(Dictionary`2 itemData) { }
	// RVA: 0x301a348 VA: 0x7595632348
	public Void EventOnBtnClicked() { }
	// RVA: 0x301a43c VA: 0x759563243c
	public Void .ctor() { }
}
```
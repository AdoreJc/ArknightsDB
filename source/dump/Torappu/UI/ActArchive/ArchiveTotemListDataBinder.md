# ArchiveTotemListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveTotemDetailView _detailView`

- `ArchiveTotemRecycleAdapter _adapter`

- `Boolean m_hasInited`

- `ArchiveTotemController <controller>k__BackingField`


## Properties

- `ArchiveTotemController controller`


## Methods

- `ArchiveTotemController get_controller()`

- `Void set_controller(ArchiveTotemController)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTotemListDataBinder : DataBinder`1
{
	private ArchiveTotemDetailView _detailView; // 0x20
	private ArchiveTotemRecycleAdapter _adapter; // 0x28
	private Boolean m_hasInited; // 0x30
	private ArchiveTotemController <controller>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ArchiveTotemController controller { get; set; }

	// RVA: 0x308a7d8 VA: 0x75956a27d8
	private ArchiveTotemController get_controller() { }
	// RVA: 0x308a840 VA: 0x75956a2840
	public Void set_controller(ArchiveTotemController value) { }
	// RVA: 0x308a8c4 VA: 0x75956a28c4
	public override Void OnValueChanged(TotemProperty property) { }
	// RVA: 0x308a9f0 VA: 0x75956a29f0
	private Void _InitIfNot() { }
	// RVA: 0x308ae54 VA: 0x75956a2e54
	public Void .ctor() { }
}
```
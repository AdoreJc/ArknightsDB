# ArchiveTrapListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveTrapRecycleAdapter _adapter`

- `Boolean m_hasInited`

- `ArchiveTrapController <controller>k__BackingField`


## Properties

- `ArchiveTrapController controller`

- `ArchiveTrapRecycleAdapter adapter`


## Methods

- `ArchiveTrapController get_controller()`

- `Void set_controller(ArchiveTrapController)`

- `ArchiveTrapRecycleAdapter get_adapter()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTrapListDataBinder : DataBinder`1
{
	private ArchiveTrapRecycleAdapter _adapter; // 0x20
	private Boolean m_hasInited; // 0x28
	private ArchiveTrapController <controller>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_get_adapter; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private ArchiveTrapController controller { get; set; }
	public ArchiveTrapRecycleAdapter adapter { get; }

	// RVA: 0x308eecc VA: 0x75956a6ecc
	private ArchiveTrapController get_controller() { }
	// RVA: 0x308e7dc VA: 0x75956a67dc
	public Void set_controller(ArchiveTrapController value) { }
	// RVA: 0x308ee14 VA: 0x75956a6e14
	public ArchiveTrapRecycleAdapter get_adapter() { }
	// RVA: 0x308ef34 VA: 0x75956a6f34
	private Void _InitIfNot() { }
	// RVA: 0x308f054 VA: 0x75956a7054
	public override Void OnValueChanged(TrapProperty property) { }
	// RVA: 0x308f384 VA: 0x75956a7384
	public Void .ctor() { }
}
```
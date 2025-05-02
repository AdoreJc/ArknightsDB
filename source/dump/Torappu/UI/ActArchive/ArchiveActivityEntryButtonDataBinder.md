# ArchiveActivityEntryButtonDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Properties

- `ArchiveActivityEntryController controller`


## Methods

- `Void set_controller(ArchiveActivityEntryController)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveActivityEntryButtonDataBinder : DataBinder`1, IHotfixable
{
	private ArchiveActivityEntryButtonView[] _entryButtons; // 0x20
	private static DelegateBridge __Hotfix0_set_controller; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public ArchiveActivityEntryController controller { set; }

	// RVA: 0x3019de0 VA: 0x7595631de0
	public Void set_controller(ArchiveActivityEntryController value) { }
	// RVA: 0x3019f90 VA: 0x7595631f90
	public override Void OnValueChanged(ArchiveActivityEntryProperty property) { }
	// RVA: 0x301a250 VA: 0x7595632250
	public Void .ctor() { }
}
```
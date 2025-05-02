# ArchiveQuestFullScreenDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Boolean m_cachedFullScreen`

- `ActArchiveController <controller>k__BackingField`


## Properties

- `ActArchiveController controller`


## Methods

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestFullScreenDataBinder : DataBinder`1
{
	private Boolean m_cachedFullScreen; // 0x20
	private ActArchiveController <controller>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private ActArchiveController controller { get; set; }

	// RVA: 0x3073900 VA: 0x759568b900
	private ActArchiveController get_controller() { }
	// RVA: 0x3070798 VA: 0x7595688798
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x3073968 VA: 0x759568b968
	public override Void OnValueChanged(ArchiveQuestProperty property) { }
	// RVA: 0x3073e84 VA: 0x759568be84
	public Void .ctor() { }
}
```
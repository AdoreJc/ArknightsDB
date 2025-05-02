# ArchiveDynamicPicFullscreenDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Boolean m_cachedFullscreen`

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
public class ArchiveDynamicPicFullscreenDataBinder : DataBinder`1
{
	private Boolean m_cachedFullscreen; // 0x20
	private ActArchiveController <controller>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private ActArchiveController controller { get; set; }

	// RVA: 0x3068684 VA: 0x7595680684
	private ActArchiveController get_controller() { }
	// RVA: 0x3067f64 VA: 0x759567ff64
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x30686ec VA: 0x75956806ec
	public override Void OnValueChanged(PicProperty property) { }
	// RVA: 0x3068c08 VA: 0x7595680c08
	public Void .ctor() { }
}
```
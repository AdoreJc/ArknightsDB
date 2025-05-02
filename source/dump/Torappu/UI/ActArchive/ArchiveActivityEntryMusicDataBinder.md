# ArchiveActivityEntryMusicDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String m_musicId`

- `ArchiveActivityEntryController <controller>k__BackingField`


## Properties

- `ArchiveActivityEntryController controller`


## Methods

- `ArchiveActivityEntryController get_controller()`

- `Void set_controller(ArchiveActivityEntryController)`

- `Int64 _GetBgmInstId()`

- `Void RefreshBGM()`

- `Void ClearBGM()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveActivityEntryMusicDataBinder : DataBinder`1
{
	private String m_musicId; // 0x20
	private ArchiveActivityEntryController <controller>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__GetBgmInstId; // 0x18
	private static DelegateBridge __Hotfix0_RefreshBGM; // 0x20
	private static DelegateBridge __Hotfix0_ClearBGM; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public ArchiveActivityEntryController controller { get; set; }

	// RVA: 0x3032fd4 VA: 0x759564afd4
	public ArchiveActivityEntryController get_controller() { }
	// RVA: 0x3032170 VA: 0x759564a170
	public Void set_controller(ArchiveActivityEntryController value) { }
	// RVA: 0x303303c VA: 0x759564b03c
	public override Void OnValueChanged(ArchiveActivityEntryProperty property) { }
	// RVA: 0x30330fc VA: 0x759564b0fc
	private Int64 _GetBgmInstId() { }
	// RVA: 0x30326b0 VA: 0x759564a6b0
	public Void RefreshBGM() { }
	// RVA: 0x3032844 VA: 0x759564a844
	public Void ClearBGM() { }
	// RVA: 0x3033170 VA: 0x759564b170
	public Void .ctor() { }
}
```
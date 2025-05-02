# ActArchiveStateBean

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ActArchiveInfo <archiveInfo>k__BackingField`

- `IntProperty selectedEntryCompProp`

- `IntProperty selectedDetailCompProp`


## Properties

- `ActArchiveInfo archiveInfo`


## Methods

- `ActArchiveInfo get_archiveInfo()`

- `Void set_archiveInfo(ActArchiveInfo)`

- `Void LoadData(Param)`

- `Void RefreshEntryComp()`

- `Void SetEntryCompType(ActArchiveType, DataBundle)`

- `Void SetDetailCompType(ActArchiveType, DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ActArchiveStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	private ActArchiveInfo <archiveInfo>k__BackingField; // 0x18
	public IntProperty selectedEntryCompProp; // 0x20
	public IntProperty selectedDetailCompProp; // 0x28
	private static DelegateBridge __Hotfix0_get_archiveInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_archiveInfo; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_RefreshEntryComp; // 0x18
	private static DelegateBridge __Hotfix0_SetEntryCompType; // 0x20
	private static DelegateBridge __Hotfix0_SetDetailCompType; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public ActArchiveInfo archiveInfo { get; set; }

	// RVA: 0x30052ac VA: 0x759561d2ac
	public ActArchiveInfo get_archiveInfo() { }
	// RVA: 0x3013978 VA: 0x759562b978
	private Void set_archiveInfo(ActArchiveInfo value) { }
	// RVA: 0x30069d4 VA: 0x759561e9d4
	public Void LoadData(Param param) { }
	// RVA: 0x3013cfc VA: 0x759562bcfc
	public Void RefreshEntryComp() { }
	// RVA: 0x3007708 VA: 0x759561f708
	public Void SetEntryCompType(ActArchiveType compType, DataBundle data) { }
	// RVA: 0x3007828 VA: 0x759561f828
	public Void SetDetailCompType(ActArchiveType compType, DataBundle data) { }
	// RVA: 0x3013dc0 VA: 0x759562bdc0
	public Void .ctor() { }
}
```
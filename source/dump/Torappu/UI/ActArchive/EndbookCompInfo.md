# EndbookCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `EndbookProperty endbook`


## Methods

- `Void SetSelectedEnd(String, Boolean, Boolean)`

- `Void SetSelectedEnd(String)`

- `Void SetSelectedEndItem(Int32)`

- `Void SetFocusedIndex(Int32)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`

- `Boolean <>xLuaBaseProxy_OnBackBtnPressed()`

- `Boolean <>xLuaBaseProxy_IsUnlocked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class EndbookCompInfo : ActArchiveCompInfo
{
	public const String KEY_ARCHIVE_ENDBOOK_OPEN_DETAIL; // 0x0
	public EndbookProperty endbook; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedEnd; // 0x10
	private static DelegateBridge __Hotfix1_SetSelectedEnd; // 0x18
	private static DelegateBridge __Hotfix0_SetSelectedEndItem; // 0x20
	private static DelegateBridge __Hotfix0_SetFocusedIndex; // 0x28
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x30
	private static DelegateBridge __Hotfix0_IsValid; // 0x38
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x40
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x48
	private static DelegateBridge __Hotfix0_OnBackBtnPressed; // 0x50
	private static DelegateBridge __Hotfix0_IsUnlocked; // 0x58


	// RVA: 0x3052874 VA: 0x759566a874
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3052938 VA: 0x759566a938
	public override Void LoadData(String archiveId) { }
	// RVA: 0x3052a6c VA: 0x759566aa6c
	public Void SetSelectedEnd(String endId, Boolean isInit, Boolean openDetail) { }
	// RVA: 0x3052c54 VA: 0x759566ac54
	public Void SetSelectedEnd(String endId) { }
	// RVA: 0x3052e44 VA: 0x759566ae44
	public Void SetSelectedEndItem(Int32 index) { }
	// RVA: 0x3052fa4 VA: 0x759566afa4
	public Void SetFocusedIndex(Int32 index) { }
	// RVA: 0x3053084 VA: 0x759566b084
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3053168 VA: 0x759566b168
	public override Boolean IsValid() { }
	// RVA: 0x30531f4 VA: 0x759566b1f4
	public override Void NotifyUpdate() { }
	// RVA: 0x305329c VA: 0x759566b29c
	public override Boolean HasNewItem() { }
	// RVA: 0x30533e0 VA: 0x759566b3e0
	public override Boolean OnBackBtnPressed() { }
	// RVA: 0x30534ac VA: 0x759566b4ac
	public override Boolean IsUnlocked() { }
	// RVA: 0x30535e8 VA: 0x759566b5e8
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
	// RVA: 0x30535f0 VA: 0x759566b5f0
	private Boolean <>xLuaBaseProxy_OnBackBtnPressed() { }
	// RVA: 0x30535f8 VA: 0x759566b5f8
	private Boolean <>xLuaBaseProxy_IsUnlocked() { }
}
```
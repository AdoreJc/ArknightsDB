# UniEquipArchiveCollectionInfoViewModel

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `Int32 m_equipTotalCount`

- `Int32 m_equipGetCount`

- `Int32 m_stage3EquipCount`

- `Int32 m_charHasModuleCount`

- `Int32 m_playerHasModuleCharCount`


## Properties

- `Int32 equipTotalCount`

- `Int32 equipGetCount`

- `Int32 stage3EquipCount`

- `Int32 charHasModuleCount`

- `Int32 playerHasModuleCharCount`


## Methods

- `Int32 get_equipTotalCount()`

- `Int32 get_equipGetCount()`

- `Int32 get_stage3EquipCount()`

- `Int32 get_charHasModuleCount()`

- `Int32 get_playerHasModuleCharCount()`

- `Void LoadData()`

- `Void _RefreshPlayerGetEquipCountInfo(UniEquipData, PlayerCharacter, ref, ref, ref, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveCollectionInfoViewModel : IHotfixable
{
	private Int32 m_equipTotalCount; // 0x10
	private Int32 m_equipGetCount; // 0x14
	private Int32 m_stage3EquipCount; // 0x18
	private Int32 m_charHasModuleCount; // 0x1c
	private Int32 m_playerHasModuleCharCount; // 0x20
	private Dictionary`2 m_equipInfoDict; // 0x28
	private static DelegateBridge __Hotfix0_get_equipTotalCount; // 0x0
	private static DelegateBridge __Hotfix0_get_equipGetCount; // 0x8
	private static DelegateBridge __Hotfix0_get_stage3EquipCount; // 0x10
	private static DelegateBridge __Hotfix0_get_charHasModuleCount; // 0x18
	private static DelegateBridge __Hotfix0_get_playerHasModuleCharCount; // 0x20
	private static DelegateBridge __Hotfix0_get_equipInfoDict; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0__RefreshPlayerGetEquipCountInfo; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 equipTotalCount { get; }
	public Int32 equipGetCount { get; }
	public Int32 stage3EquipCount { get; }
	public Int32 charHasModuleCount { get; }
	public Int32 playerHasModuleCharCount { get; }
	public Dictionary`2 equipInfoDict { get; }

	// RVA: 0x22f4cf4 VA: 0x759490ccf4
	public Int32 get_equipTotalCount() { }
	// RVA: 0x22f4c8c VA: 0x759490cc8c
	public Int32 get_equipGetCount() { }
	// RVA: 0x22f4d5c VA: 0x759490cd5c
	public Int32 get_stage3EquipCount() { }
	// RVA: 0x22f4e2c VA: 0x759490ce2c
	public Int32 get_charHasModuleCount() { }
	// RVA: 0x22f4dc4 VA: 0x759490cdc4
	public Int32 get_playerHasModuleCharCount() { }
	// RVA: 0x22f4f84 VA: 0x759490cf84
	public Dictionary`2 get_equipInfoDict() { }
	// RVA: 0x22f39f4 VA: 0x759490b9f4
	public Void LoadData() { }
	// RVA: 0x22f539c VA: 0x759490d39c
	private Void _RefreshPlayerGetEquipCountInfo(UniEquipData equipData, PlayerCharacter playerChar, ref UniEquipArchiveCollectionEquipInfoData infoData, ref Int32 equipGetCount, ref Int32 stage3EquipCount, ref PlayerCharEquipInfo equipInfo) { }
	// RVA: 0x22f5228 VA: 0x759490d228
	public Void .ctor() { }
}
```
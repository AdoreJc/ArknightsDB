# NameCardV2ViewModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `ShowType showType`

- `NameCardMiscModel miscModel`

- `String skinId`

- `Int32 skinTmpl`

- `Int32 editSeqNum`

- `Int32 resetSeqNum`

- `Int32 showDetailSeqNum`

- `Boolean skinChangeUnlocked`

- `Boolean hasNewSkinTrackPoint`

- `Boolean m_hasModuleListInited`


## Methods

- `Void LoadSelfData(String, ShowDetailOption)`

- `Void RefreshSelfData(String, ShowDetailOption)`

- `Void LoadFriendData(FriendDataWithNameCard)`

- `Boolean CanSelectModule()`

- `Void SelectModule(String)`

- `Void UnselectModule(String)`

- `Void SwitchOperatorStyle(String)`

- `Void SwitchAssistModuleStyle(String)`

- `Void SwitchEquipModuleStyle(String)`

- `Void SetNameCardShowType(ShowType)`

- `Void SetNameCardMisc(NameCardMiscModel, SetMiscOption)`

- `Boolean _ReloadFixedModuleIfNeed(String)`

- `Void _LoadFixedModuleModel(String, Int32, FriendDataWithNameCard)`

- `Void _RefreshFixedModuleModel(String, Int32)`

- `Void _InitRemovableModuleIfNot()`

- `Void _MoveRemovableModuleModels(PlayerNameCardStyle)`

- `Void _LoadRemovableModuleModel(ListDict`2, Boolean, String, Int32, FriendDataWithNameCard)`

- `Void _RefreshRemovableModuleModel(ListDict`2, Boolean, String, Int32)`

- `Void _LoadMiscData(PlayerNameCardStyle, ShowDetailOption)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2ViewModel : IHotfixable
{
	public ShowType showType; // 0x10
	public NameCardMiscModel miscModel; // 0x18
	public String skinId; // 0x20
	public Int32 skinTmpl; // 0x28
	public Int32 editSeqNum; // 0x2c
	public Int32 resetSeqNum; // 0x30
	public Int32 showDetailSeqNum; // 0x34
	public Dictionary`2 fixedModuleModelDict; // 0x38
	public ListDict`2 selectedModuleModelList; // 0x40
	public ListDict`2 unselectedModuleModelList; // 0x48
	public Boolean skinChangeUnlocked; // 0x50
	public Boolean hasNewSkinTrackPoint; // 0x51
	private Boolean m_hasModuleListInited; // 0x52
	private static DelegateBridge __Hotfix0_LoadSelfData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshSelfData; // 0x8
	private static DelegateBridge __Hotfix0_LoadFriendData; // 0x10
	private static DelegateBridge __Hotfix0_CanSelectModule; // 0x18
	private static DelegateBridge __Hotfix0_SelectModule; // 0x20
	private static DelegateBridge __Hotfix0_UnselectModule; // 0x28
	private static DelegateBridge __Hotfix0_SwitchOperatorStyle; // 0x30
	private static DelegateBridge __Hotfix0_SwitchAssistModuleStyle; // 0x38
	private static DelegateBridge __Hotfix0_SwitchEquipModuleStyle; // 0x40
	private static DelegateBridge __Hotfix0_SetNameCardShowType; // 0x48
	private static DelegateBridge __Hotfix0_SetNameCardMisc; // 0x50
	private static DelegateBridge __Hotfix0__ReloadFixedModuleIfNeed; // 0x58
	private static DelegateBridge __Hotfix0__LoadFixedModuleModel; // 0x60
	private static DelegateBridge __Hotfix0__RefreshFixedModuleModel; // 0x68
	private static DelegateBridge __Hotfix0__InitRemovableModuleIfNot; // 0x70
	private static DelegateBridge __Hotfix0__MoveRemovableModuleModels; // 0x78
	private static DelegateBridge __Hotfix0__LoadRemovableModuleModel; // 0x80
	private static DelegateBridge __Hotfix0__RefreshRemovableModuleModel; // 0x88
	private static DelegateBridge __Hotfix0__SortUnselectedModule; // 0x90
	private static DelegateBridge __Hotfix0__LoadMiscData; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x28b6a40 VA: 0x7594ecea40
	public Void LoadSelfData(String overrideSkinId, ShowDetailOption showDetailOpt) { }
	// RVA: 0x28bb8ac VA: 0x7594ed38ac
	public Void RefreshSelfData(String overrideSkinId, ShowDetailOption showDetailOpt) { }
	// RVA: 0x28c07d8 VA: 0x7594ed87d8
	public Void LoadFriendData(FriendDataWithNameCard data) { }
	// RVA: 0x28b788c VA: 0x7594ecf88c
	public Boolean CanSelectModule() { }
	// RVA: 0x28b7970 VA: 0x7594ecf970
	public Void SelectModule(String moduleId) { }
	// RVA: 0x28b7a90 VA: 0x7594ecfa90
	public Void UnselectModule(String moduleId) { }
	// RVA: 0x28bb430 VA: 0x7594ed3430
	public Void SwitchOperatorStyle(String moduleId) { }
	// RVA: 0x28bb53c VA: 0x7594ed353c
	public Void SwitchAssistModuleStyle(String moduleId) { }
	// RVA: 0x28bb650 VA: 0x7594ed3650
	public Void SwitchEquipModuleStyle(String moduleId) { }
	// RVA: 0x28b6c30 VA: 0x7594ecec30
	public Void SetNameCardShowType(ShowType type) { }
	// RVA: 0x28b8208 VA: 0x7594ed0208
	public Void SetNameCardMisc(NameCardMiscModel misc, SetMiscOption option) { }
	// RVA: 0x28bfdf0 VA: 0x7594ed7df0
	private Boolean _ReloadFixedModuleIfNeed(String skinId) { }
	// RVA: 0x28c0094 VA: 0x7594ed8094
	private Void _LoadFixedModuleModel(String skinId, Int32 skinTmpl, FriendDataWithNameCard data) { }
	// RVA: 0x28c04c4 VA: 0x7594ed84c4
	private Void _RefreshFixedModuleModel(String skinId, Int32 skinTmpl) { }
	// RVA: 0x28bf564 VA: 0x7594ed7564
	private Void _InitRemovableModuleIfNot() { }
	// RVA: 0x28bf8f8 VA: 0x7594ed78f8
	private Void _MoveRemovableModuleModels(PlayerNameCardStyle style) { }
	// RVA: 0x28bfb7c VA: 0x7594ed7b7c
	private Void _LoadRemovableModuleModel(ListDict`2 listDict, Boolean isSelect, String nameCardSkinId, Int32 nameCardSkinTmpl, FriendDataWithNameCard data) { }
	// RVA: 0x28c02ec VA: 0x7594ed82ec
	private Void _RefreshRemovableModuleModel(ListDict`2 listDict, Boolean isSelect, String nameCardSkinId, Int32 nameCardSkinTmpl) { }
	// RVA: 0x28c0e3c VA: 0x7594ed8e3c
	private static Int32 _SortUnselectedModule(KeyValuePair`2 a, KeyValuePair`2 b) { }
	// RVA: 0x28c0668 VA: 0x7594ed8668
	private Void _LoadMiscData(PlayerNameCardStyle style, ShowDetailOption showDetailOpt) { }
	// RVA: 0x28c0f20 VA: 0x7594ed8f20
	public Void .ctor() { }
}
```
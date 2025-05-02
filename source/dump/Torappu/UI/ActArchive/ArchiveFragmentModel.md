# ArchiveFragmentModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedItemId`

- `FragmentItemModel selectedItemModel`

- `Boolean showSwitchAnim`


## Properties

- `Int32 newItemCount`


## Methods

- `Int32 get_newItemCount()`

- `Void LoadData(String, RoguelikeArchiveComponentData)`

- `Void SetSelectedItem(String)`

- `String _GetDefaultItemId()`

- `Void _GenerateGroupModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveFragmentModel : IHotfixable
{
	public String selectedItemId; // 0x10
	public FragmentItemModel selectedItemModel; // 0x18
	public List`1 groupModelList; // 0x20
	public Boolean showSwitchAnim; // 0x28
	private ListDict`2 m_fragmentList; // 0x30
	private static DelegateBridge __Hotfix0_get_newItemCount; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedItem; // 0x10
	private static DelegateBridge __Hotfix0__GetDefaultItemId; // 0x18
	private static DelegateBridge __Hotfix0__GenerateGroupModel; // 0x20
	private static DelegateBridge __Hotfix0__GetStatusOfItem; // 0x28
	private static DelegateBridge __Hotfix0__GetLockedToastOfItem; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 newItemCount { get; }

	// RVA: 0x3055928 VA: 0x759566d928
	public Int32 get_newItemCount() { }
	// RVA: 0x3055a34 VA: 0x759566da34
	public Void LoadData(String archiveId, RoguelikeArchiveComponentData compData) { }
	// RVA: 0x3056944 VA: 0x759566e944
	public Void SetSelectedItem(String id) { }
	// RVA: 0x3056a68 VA: 0x759566ea68
	private String _GetDefaultItemId() { }
	// RVA: 0x3056598 VA: 0x759566e598
	private Void _GenerateGroupModel() { }
	// RVA: 0x305621c VA: 0x759566e21c
	private static RoguelikeArchiveItemUnlockStatus _GetStatusOfItem(OuterData outerData, String fragmentId) { }
	// RVA: 0x30562fc VA: 0x759566e2fc
	private static String _GetLockedToastOfItem(String archiveId, RoguelikeTopicDetail topicDetail, RoguelikeTopicItemModel itemInfo, RoguelikeArchiveItemUnlockStatus status) { }
	// RVA: 0x3056b50 VA: 0x759566eb50
	public Void .ctor() { }
}
```
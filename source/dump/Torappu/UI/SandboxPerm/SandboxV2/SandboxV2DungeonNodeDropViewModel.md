# SandboxV2DungeonNodeDropViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Properties

- `Boolean IsEmpty`


## Methods

- `Boolean get_IsEmpty()`

- `Void _MergeCollectDrop(SandboxV2Data, List`1)`

- `Void _MergeHuntDrop(SandboxV2Data, List`1)`

- `Void _MergeBaseDrop(SandboxV2Data, String)`

- `Void _MergeSingleEntityDrop(SandboxV2Data, EntityStatus)`

- `Void _MergeEntityDrop(SandboxV2Data, NodeStage)`

- `Void UpdateBasicData(UpdateParam)`

- `Void UpdateData(UpdateParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNodeDropViewModel : IHotfixable
{
	private ListDict`2 m_nodeDropList; // 0x10
	private HashSet`1 m_nodeDetailDropItems; // 0x18
	public List`1 mapPreviewDropList; // 0x20
	public List`1 detailPreviewDropList; // 0x28
	public List`1 regularDropList; // 0x30
	private static DelegateBridge __Hotfix0_get_IsEmpty; // 0x0
	private static DelegateBridge __Hotfix0__MergeCollectDrop; // 0x8
	private static DelegateBridge __Hotfix0__MergeHuntDrop; // 0x10
	private static DelegateBridge __Hotfix0__MergeBaseDrop; // 0x18
	private static DelegateBridge __Hotfix0__MergeSingleEntityDrop; // 0x20
	private static DelegateBridge __Hotfix0__MergeEntityDrop; // 0x28
	private static DelegateBridge __Hotfix0_UpdateBasicData; // 0x30
	private static DelegateBridge __Hotfix0_UpdateData; // 0x38
	private static DelegateBridge __Hotfix0_MergeDrop; // 0x40
	private static DelegateBridge __Hotfix0_MergeDropList; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Boolean IsEmpty { get; }

	// RVA: 0x25b5128 VA: 0x7594bcd128
	public Boolean get_IsEmpty() { }
	// RVA: 0x25b51cc VA: 0x7594bcd1cc
	private Void _MergeCollectDrop(SandboxV2Data topicData, List`1 playerCollectList) { }
	// RVA: 0x25b54ec VA: 0x7594bcd4ec
	private Void _MergeHuntDrop(SandboxV2Data topicData, List`1 playerHuntList) { }
	// RVA: 0x25b5704 VA: 0x7594bcd704
	private Void _MergeBaseDrop(SandboxV2Data topicData, String stageId) { }
	// RVA: 0x25b589c VA: 0x7594bcd89c
	private Void _MergeSingleEntityDrop(SandboxV2Data topicData, EntityStatus playerEntity) { }
	// RVA: 0x25b5a2c VA: 0x7594bcda2c
	private Void _MergeEntityDrop(SandboxV2Data topicData, NodeStage playerStageData) { }
	// RVA: 0x25b5cd4 VA: 0x7594bcdcd4
	public Void UpdateBasicData(UpdateParam updateParam) { }
	// RVA: 0x25b5ea0 VA: 0x7594bcdea0
	public Void UpdateData(UpdateParam updateParam) { }
	// RVA: 0x25b53cc VA: 0x7594bcd3cc
	public static Void MergeDrop(ListDict`2 targetDropList, SandboxV2DropDetail drop) { }
	// RVA: 0x25b6674 VA: 0x7594bce674
	public static Void MergeDropList(ListDict`2 targetDropList, ListDict`2 srcDropList) { }
	// RVA: 0x25b69cc VA: 0x7594bce9cc
	public Void .ctor() { }
}
```
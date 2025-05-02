# MissionArchiveViewModel

**Namespace:** `Torappu.UI.MissionArchive`


## Fields

- `String m_topicId`

- `MissionArchiveDataServiceProxy m_dataServiceProxy`

- `Boolean m_hiddenUnlokced`

- `MissionArchiveNodeViewModel <selectedNode>k__BackingField`

- `MissionArchiveVoicePlayState <playState>k__BackingField`


## Properties

- `String topicId`

- `Boolean hiddenUnlocked`

- `MissionArchiveNodeViewModel selectedNode`

- `MissionArchiveVoicePlayState playState`


## Methods

- `String get_topicId()`

- `Boolean get_hiddenUnlocked()`

- `MissionArchiveNodeViewModel get_selectedNode()`

- `Void set_selectedNode(MissionArchiveNodeViewModel)`

- `MissionArchiveVoicePlayState get_playState()`

- `Void set_playState(MissionArchiveVoicePlayState)`

- `Void LoadData(String, MissionArchiveDataServiceProxy)`

- `Void RefreshPlayerData()`

- `Boolean SelectNode(String, out)`

- `Void DeselectNode()`

- `MissionArchiveNodeViewModel _LoadNode(PlayerMissionArchive, MissionArchiveNodeData)`

- `MissionArchiveVoiceClipViewModel _LoadClip(MissionArchiveVoiceClipData)`

- `MissionArchiveNodeState _LoadNodeState(PlayerMissionArchive, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.MissionArchive
public class MissionArchiveViewModel : IHotfixable
{
	private readonly Dictionary`2 m_nodes; // 0x10
	private readonly List`1 m_hiddenClips; // 0x18
	private String m_topicId; // 0x20
	private MissionArchiveDataServiceProxy m_dataServiceProxy; // 0x28
	private Boolean m_hiddenUnlokced; // 0x30
	private MissionArchiveNodeViewModel <selectedNode>k__BackingField; // 0x38
	private MissionArchiveVoicePlayState <playState>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_hiddenUnlocked; // 0x8
	private static DelegateBridge __Hotfix0_get_nodes; // 0x10
	private static DelegateBridge __Hotfix0_get_hiddenClips; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedNode; // 0x20
	private static DelegateBridge __Hotfix0_set_selectedNode; // 0x28
	private static DelegateBridge __Hotfix0_get_playState; // 0x30
	private static DelegateBridge __Hotfix0_set_playState; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x48
	private static DelegateBridge __Hotfix0_SelectNode; // 0x50
	private static DelegateBridge __Hotfix0_DeselectNode; // 0x58
	private static DelegateBridge __Hotfix0__LoadNode; // 0x60
	private static DelegateBridge __Hotfix0__LoadClip; // 0x68
	private static DelegateBridge __Hotfix0__LoadNodeState; // 0x70
	private static DelegateBridge __Hotfix0__GetRealWordKey; // 0x78
	private static DelegateBridge __Hotfix0__ClipComparison; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public String topicId { get; }
	public Boolean hiddenUnlocked { get; }
	public Dictionary`2 nodes { get; }
	public List`1 hiddenClips { get; }
	public MissionArchiveNodeViewModel selectedNode { get; set; }
	public MissionArchiveVoicePlayState playState { get; set; }

	// RVA: 0x272fe50 VA: 0x7594d47e50
	public String get_topicId() { }
	// RVA: 0x272feb8 VA: 0x7594d47eb8
	public Boolean get_hiddenUnlocked() { }
	// RVA: 0x272ff20 VA: 0x7594d47f20
	public Dictionary`2 get_nodes() { }
	// RVA: 0x272ff88 VA: 0x7594d47f88
	public List`1 get_hiddenClips() { }
	// RVA: 0x272fff0 VA: 0x7594d47ff0
	public MissionArchiveNodeViewModel get_selectedNode() { }
	// RVA: 0x2730058 VA: 0x7594d48058
	private Void set_selectedNode(MissionArchiveNodeViewModel value) { }
	// RVA: 0x27300dc VA: 0x7594d480dc
	public MissionArchiveVoicePlayState get_playState() { }
	// RVA: 0x2730144 VA: 0x7594d48144
	public Void set_playState(MissionArchiveVoicePlayState value) { }
	// RVA: 0x27301c0 VA: 0x7594d481c0
	public Void LoadData(String topicId, MissionArchiveDataServiceProxy dataServiceProxy) { }
	// RVA: 0x27309e8 VA: 0x7594d489e8
	public Void RefreshPlayerData() { }
	// RVA: 0x2730d34 VA: 0x7594d48d34
	public Boolean SelectNode(String nodeId, out MissionArchiveNodeViewModel toSelect) { }
	// RVA: 0x2730e28 VA: 0x7594d48e28
	public Void DeselectNode() { }
	// RVA: 0x2730610 VA: 0x7594d48610
	private MissionArchiveNodeViewModel _LoadNode(PlayerMissionArchive playerData, MissionArchiveNodeData nodeData) { }
	// RVA: 0x27308d0 VA: 0x7594d488d0
	private MissionArchiveVoiceClipViewModel _LoadClip(MissionArchiveVoiceClipData clipData) { }
	// RVA: 0x2730c50 VA: 0x7594d48c50
	private MissionArchiveNodeState _LoadNodeState(PlayerMissionArchive playerData, String nodeId) { }
	// RVA: 0x2730ed4 VA: 0x7594d48ed4
	private static String _GetRealWordKey(String charId) { }
	// RVA: 0x2731020 VA: 0x7594d49020
	private static Int32 _ClipComparison(MissionArchiveVoiceClipViewModel x, MissionArchiveVoiceClipViewModel y) { }
	// RVA: 0x27310b0 VA: 0x7594d490b0
	public Void .ctor() { }
}
```
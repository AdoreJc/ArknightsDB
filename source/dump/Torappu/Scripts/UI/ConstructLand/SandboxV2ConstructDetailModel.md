# SandboxV2ConstructDetailModel

**Namespace:** `Torappu.Scripts.UI.ConstructLand`


## Fields

- `Int32 hideUI`

- `Boolean isDetailOn`

- `Int32 currentGoldCnt`

- `Int32 goldRequired`

- `SandboxV2NodeType nodeType`

- `String nodeTypeName`

- `String topicId`

- `String nodeId`


## Methods

- `Void SetUI(Boolean, HideUIReasonMask)`

- `Boolean IsConstructTipSelected(SandboxV2ConstructTipType)`

- `Int32 GetConstructTipCount(SandboxV2ConstructTipType)`

- `Boolean IsBuildingDetailEmpty()`

- `SandboxV2NodeType GetNodeType()`

- `String GetNodeTypeName()`

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Scripts.UI.ConstructLand
public class SandboxV2ConstructDetailModel : ISandboxV2BuildingDetail
{
	public Int32 hideUI; // 0x10
	public Int32[] tipsSum; // 0x18
	public Boolean isDetailOn; // 0x20
	public Boolean[] tipsOnClicked; // 0x28
	public Int32 currentGoldCnt; // 0x30
	public Int32 goldRequired; // 0x34
	public SandboxV2NodeType nodeType; // 0x38
	public String nodeTypeName; // 0x40
	public String topicId; // 0x48
	public String nodeId; // 0x50
	public ListDict`2 buildingDic; // 0x58
	private List`1 m_buildingTipCache; // 0x60
	private ListDict`2 m_upgradeCache; // 0x68


	// RVA: 0x3770678 VA: 0x7595d88678
	public Void SetUI(Boolean isHide, HideUIReasonMask reasonMask) { }
	// RVA: 0x377069c VA: 0x7595d8869c
	public Boolean IsConstructTipSelected(SandboxV2ConstructTipType tipType) { }
	// RVA: 0x37706cc VA: 0x7595d886cc
	public Int32 GetConstructTipCount(SandboxV2ConstructTipType tipType) { }
	// RVA: 0x37706fc VA: 0x7595d886fc
	public IEnumerable`1 IterBuildingTrapInfo() { }
	// RVA: 0x37707b4 VA: 0x7595d887b4
	public Boolean IsBuildingDetailEmpty() { }
	// RVA: 0x3770804 VA: 0x7595d88804
	public SandboxV2NodeType GetNodeType() { }
	// RVA: 0x377080c VA: 0x7595d8880c
	public String GetNodeTypeName() { }
	// RVA: 0x3770814 VA: 0x7595d88814
	public Void LoadData() { }
	// RVA: 0x3771554 VA: 0x7595d89554
	public Void .ctor() { }
}
```
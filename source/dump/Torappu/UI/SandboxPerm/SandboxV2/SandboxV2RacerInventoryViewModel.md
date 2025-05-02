# SandboxV2RacerInventoryViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String selectInstId`

- `String topicId`

- `String bagName`

- `String emptyLeftDesc`

- `String emptyRightDesc`

- `String tokenId`

- `Int32 tokenCount`

- `Int32 racerCount`

- `Int32 bagCapacity`

- `String tempBagName`

- `Int32 tempRacerCount`

- `Single tempBagRatio`

- `Boolean showTempBagFullIcon`

- `String nodeId`

- `String stageId`

- `Int32 apCost`

- `Type type`

- `Int32 focusSequenceNum`

- `Int32 learnTalentSequenceNum`

- `Int32 m_tempBagCapacity`


## Properties

- `Boolean isEmpty`


## Methods

- `Boolean get_isEmpty()`

- `Void LoadData(Input)`

- `Void RefreshData()`

- `Void RefreshInfo()`

- `Void _RefreshRacerBagData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerInventoryViewModel : IHotfixable
{
	public ListDict`2 racerList; // 0x10
	public List`1 itemModelList; // 0x18
	public String selectInstId; // 0x20
	public String topicId; // 0x28
	public String bagName; // 0x30
	public String emptyLeftDesc; // 0x38
	public String emptyRightDesc; // 0x40
	public String tokenId; // 0x48
	public Int32 tokenCount; // 0x50
	public Int32 racerCount; // 0x54
	public Int32 bagCapacity; // 0x58
	public String tempBagName; // 0x60
	public Int32 tempRacerCount; // 0x68
	public Single tempBagRatio; // 0x6c
	public Boolean showTempBagFullIcon; // 0x70
	public String nodeId; // 0x78
	public String stageId; // 0x80
	public Int32 apCost; // 0x88
	public Type type; // 0x8c
	public Int32 focusSequenceNum; // 0x90
	public Int32 learnTalentSequenceNum; // 0x94
	private Int32 m_tempBagCapacity; // 0x98
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_RefreshData; // 0x10
	private static DelegateBridge __Hotfix0_RefreshInfo; // 0x18
	private static DelegateBridge __Hotfix0__RefreshRacerBagData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isEmpty { get; }

	// RVA: 0x25e2010 VA: 0x7594bfa010
	public Boolean get_isEmpty() { }
	// RVA: 0x25e59e4 VA: 0x7594bfd9e4
	public Void LoadData(Input input) { }
	// RVA: 0x25e2c78 VA: 0x7594bfac78
	public Void RefreshData() { }
	// RVA: 0x25e52e0 VA: 0x7594bfd2e0
	public Void RefreshInfo() { }
	// RVA: 0x25e75c8 VA: 0x7594bff5c8
	private Void _RefreshRacerBagData() { }
	// RVA: 0x25e7bb4 VA: 0x7594bffbb4
	public Void .ctor() { }
}
```
# SandboxV2RacerTempInventoryViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String topicId`

- `String selectInstId`

- `String bagName`

- `String tempBagName`

- `String emptyLeftDesc`

- `String emptyRightDesc`

- `Int32 bagCapacity`

- `Int32 racerCount`

- `Int32 tempBagCapacity`

- `Int32 tempRacerCount`

- `Int32 focusSequenceNum`


## Properties

- `Boolean isEmpty`


## Methods

- `Boolean get_isEmpty()`

- `Void LoadData(String)`

- `Void RefreshData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerTempInventoryViewModel : IHotfixable
{
	public ListDict`2 racerList; // 0x10
	public String topicId; // 0x18
	public String selectInstId; // 0x20
	public String bagName; // 0x28
	public String tempBagName; // 0x30
	public String emptyLeftDesc; // 0x38
	public String emptyRightDesc; // 0x40
	public Int32 bagCapacity; // 0x48
	public Int32 racerCount; // 0x4c
	public Int32 tempBagCapacity; // 0x50
	public Int32 tempRacerCount; // 0x54
	public Int32 focusSequenceNum; // 0x58
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_RefreshData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isEmpty { get; }

	// RVA: 0x25f42b4 VA: 0x7594c0c2b4
	public Boolean get_isEmpty() { }
	// RVA: 0x25f61dc VA: 0x7594c0e1dc
	public Void LoadData(String topicId) { }
	// RVA: 0x25f4ad4 VA: 0x7594c0cad4
	public Void RefreshData() { }
	// RVA: 0x25f6ae4 VA: 0x7594c0eae4
	public Void .ctor() { }
}
```
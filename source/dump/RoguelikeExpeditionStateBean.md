# RoguelikeExpeditionStateBean

**Namespace:** ` `


## Fields

- `RoguelikeExpeditionModelProperty property`


## Properties

- `String selectingCharInstId`


## Methods

- `String get_selectingCharInstId()`

- `Void LoadData(String)`

- `Boolean UpdateSelectingChar(String)`

- `Void UpdateInitFlag(Boolean)`

- `Void SetCharListSort(RoguelikeExpeditionCharListSort)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RoguelikeExpeditionStateBean : IStateBean, IHotfixable
{
	public RoguelikeExpeditionModelProperty property; // 0x10
	private static DelegateBridge __Hotfix0_get_selectingCharInstId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateSelectingChar; // 0x10
	private static DelegateBridge __Hotfix0_UpdateInitFlag; // 0x18
	private static DelegateBridge __Hotfix0_SetCharListSort; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String selectingCharInstId { get; }

	// RVA: 0x2a34b4c VA: 0x759504cb4c
	public String get_selectingCharInstId() { }
	// RVA: 0x2a33c74 VA: 0x759504bc74
	public Void LoadData(String topicId) { }
	// RVA: 0x2a34270 VA: 0x759504c270
	public Boolean UpdateSelectingChar(String charId) { }
	// RVA: 0x2a33d1c VA: 0x759504bd1c
	public Void UpdateInitFlag(Boolean isInit) { }
	// RVA: 0x2a33f6c VA: 0x759504bf6c
	public Void SetCharListSort(RoguelikeExpeditionCharListSort overrideCharListSort) { }
	// RVA: 0x2a349a8 VA: 0x759504c9a8
	public Void .ctor() { }
}
```
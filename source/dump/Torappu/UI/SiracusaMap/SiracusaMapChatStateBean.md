# SiracusaMapChatStateBean

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `String charCardId`

- `String taskRingId`

- `String taskInfoId`

- `String groupId`

- `String pointName`

- `String pointDesc`

- `String lastSelectOptionId`

- `Boolean isChatComplete`

- `SiracusaMapChatProperty chatProperty`


## Properties

- `Boolean isReplay`


## Methods

- `Boolean get_isReplay()`

- `Void LoadData(SiracusaMapChatParam)`

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapChatStateBean : IStateBean, IHotfixable
{
	public String charCardId; // 0x10
	public String taskRingId; // 0x18
	public String taskInfoId; // 0x20
	public String groupId; // 0x28
	public String pointName; // 0x30
	public String pointDesc; // 0x38
	public String lastSelectOptionId; // 0x40
	public Boolean isChatComplete; // 0x48
	public SiracusaMapChatProperty chatProperty; // 0x50
	private static DelegateBridge __Hotfix0_get_isReplay; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isReplay { get; }

	// RVA: 0x24071d0 VA: 0x7594a1f1d0
	public Boolean get_isReplay() { }
	// RVA: 0x2406584 VA: 0x7594a1e584
	public Void LoadData(SiracusaMapChatParam param) { }
	// RVA: 0x24069c4 VA: 0x7594a1e9c4
	public Void RefreshPlayerData() { }
	// RVA: 0x240806c VA: 0x7594a2006c
	public Void .ctor() { }
}
```
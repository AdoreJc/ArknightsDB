# RL03TotemBuffBottomViewModel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `String topicId`

- `RL03TotemViewModel locationTotemViewModel`

- `RL03TotemViewModel effectTotemViewModel`

- `Boolean haveSelectNodes`

- `TotemViewShowType m_showType`


## Properties

- `Boolean showBottomView`

- `Boolean locationTotemValid`

- `Boolean effectTotemValid`

- `Boolean isSelectBossTotem`

- `RoguelikeTotemColorType locationTotemColorType`

- `RoguelikeTotemColorType effectTotemColorType`


## Methods

- `Boolean get_showBottomView()`

- `Boolean get_locationTotemValid()`

- `Boolean get_effectTotemValid()`

- `Boolean get_isSelectBossTotem()`

- `RoguelikeTotemColorType get_locationTotemColorType()`

- `RoguelikeTotemColorType get_effectTotemColorType()`

- `Void LoadData(String, TotemViewShowType)`

- `Void UpdateWholeBottomData(RL03TotemViewModel, RL03TotemViewModel, Boolean)`

- `Void UpdateMapNodeData(Boolean)`

- `Boolean CheckIfTotemResonance()`

- `Boolean CheckIfSelectTotemValid()`

- `Boolean CheckIfConfirmValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffBottomViewModel : IHotfixable
{
	public String topicId; // 0x10
	public RL03TotemViewModel locationTotemViewModel; // 0x18
	public RL03TotemViewModel effectTotemViewModel; // 0x20
	public Boolean haveSelectNodes; // 0x28
	private TotemViewShowType m_showType; // 0x2c
	private static DelegateBridge __Hotfix0_get_showBottomView; // 0x0
	private static DelegateBridge __Hotfix0_get_locationTotemValid; // 0x8
	private static DelegateBridge __Hotfix0_get_effectTotemValid; // 0x10
	private static DelegateBridge __Hotfix0_get_isSelectBossTotem; // 0x18
	private static DelegateBridge __Hotfix0_get_locationTotemColorType; // 0x20
	private static DelegateBridge __Hotfix0_get_effectTotemColorType; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_UpdateWholeBottomData; // 0x38
	private static DelegateBridge __Hotfix0_UpdateMapNodeData; // 0x40
	private static DelegateBridge __Hotfix0_CheckIfTotemResonance; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfSelectTotemValid; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfConfirmValid; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Boolean showBottomView { get; }
	public Boolean locationTotemValid { get; }
	public Boolean effectTotemValid { get; }
	public Boolean isSelectBossTotem { get; }
	public RoguelikeTotemColorType locationTotemColorType { get; }
	public RoguelikeTotemColorType effectTotemColorType { get; }

	// RVA: 0x2ba5d38 VA: 0x75951bdd38
	public Boolean get_showBottomView() { }
	// RVA: 0x2ba7198 VA: 0x75951bf198
	public Boolean get_locationTotemValid() { }
	// RVA: 0x2ba7224 VA: 0x75951bf224
	public Boolean get_effectTotemValid() { }
	// RVA: 0x2ba5f5c VA: 0x75951bdf5c
	public Boolean get_isSelectBossTotem() { }
	// RVA: 0x2ba7738 VA: 0x75951bf738
	public RoguelikeTotemColorType get_locationTotemColorType() { }
	// RVA: 0x2ba77c0 VA: 0x75951bf7c0
	public RoguelikeTotemColorType get_effectTotemColorType() { }
	// RVA: 0x2ba7848 VA: 0x75951bf848
	public Void LoadData(String topicId, TotemViewShowType showType) { }
	// RVA: 0x2ba78dc VA: 0x75951bf8dc
	public Void UpdateWholeBottomData(RL03TotemViewModel locationTotemViewModel, RL03TotemViewModel effectTotemViewModel, Boolean hasNodeSelected) { }
	// RVA: 0x2ba7998 VA: 0x75951bf998
	public Void UpdateMapNodeData(Boolean hasNodeSelected) { }
	// RVA: 0x2ba5ebc VA: 0x75951bdebc
	public Boolean CheckIfTotemResonance() { }
	// RVA: 0x2ba5e38 VA: 0x75951bde38
	public Boolean CheckIfSelectTotemValid() { }
	// RVA: 0x2ba5da8 VA: 0x75951bdda8
	public Boolean CheckIfConfirmValid() { }
	// RVA: 0x2ba7a18 VA: 0x75951bfa18
	public Void .ctor() { }
}
```
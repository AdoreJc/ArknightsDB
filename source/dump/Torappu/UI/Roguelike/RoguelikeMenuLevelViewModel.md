# RoguelikeMenuLevelViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Int32 maxLevel`

- `Int32 currLevel`

- `Int32 currExp`

- `Int32 nextExp`

- `PlayerLevelData nextLevelData`

- `Boolean isUseSpExpStyle`


## Methods

- `Void _LoadNormalNextLevelInfo(String)`

- `Void _LoadSpecialNextLevelInfo(String, RoguelikeTopicMode, String, Int32)`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuLevelViewModel : RoguelikeMenuCompViewModel
{
	public Int32 maxLevel; // 0x14
	public Int32 currLevel; // 0x18
	public Int32 currExp; // 0x1c
	public Int32 nextExp; // 0x20
	public PlayerLevelData nextLevelData; // 0x28
	public Boolean isUseSpExpStyle; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadNormalNextLevelInfo; // 0x8
	private static DelegateBridge __Hotfix0__LoadSpecialNextLevelInfo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2a7bfa0 VA: 0x7595093fa0
	public override Void LoadData(String topicId) { }
	// RVA: 0x2a7c224 VA: 0x7595094224
	private Void _LoadNormalNextLevelInfo(String theme) { }
	// RVA: 0x2a7c100 VA: 0x7595094100
	private Void _LoadSpecialNextLevelInfo(String theme, RoguelikeTopicMode mode, String predefinedId, Int32 modeGrade) { }
	// RVA: 0x2a7c318 VA: 0x7595094318
	public Void .ctor() { }
	// RVA: 0x2a7c388 VA: 0x7595094388
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```
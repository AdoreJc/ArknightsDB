# RoguelikeStatusBarHpWithMaxHpViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Int32 currHp`

- `Int32 currMaxHp`

- `Int32 currShield`

- `RewardHpShowStatus hpShowStatus`


## Properties

- `Boolean needHideHpStatus`


## Methods

- `Boolean get_needHideHpStatus()`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarHpWithMaxHpViewModel : RoguelikeMenuCompViewModel
{
	public Int32 currHp; // 0x14
	public Int32 currMaxHp; // 0x18
	public Int32 currShield; // 0x1c
	public RewardHpShowStatus hpShowStatus; // 0x20
	private static DelegateBridge __Hotfix0_get_needHideHpStatus; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean needHideHpStatus { get; }

	// RVA: 0x2a7e6ac VA: 0x75950966ac
	public Boolean get_needHideHpStatus() { }
	// RVA: 0x2a7e71c VA: 0x759509671c
	public override Void LoadData(String topicId) { }
	// RVA: 0x2a7e808 VA: 0x7595096808
	public Void .ctor() { }
	// RVA: 0x2a7e874 VA: 0x7595096874
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```
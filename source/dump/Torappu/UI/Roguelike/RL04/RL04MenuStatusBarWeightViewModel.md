# RL04MenuStatusBarWeightViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Int32 nextWeightUp`

- `RoguelikeFragmentLevelRelatedData m_nextFragmentLevelRelatedData`


## Properties

- `Boolean haveNextLevelRelatedData`


## Methods

- `Boolean get_haveNextLevelRelatedData()`

- `RoguelikeFragmentLevelRelatedData _GetTargetFragmentLevelData(String, Int32, Int32)`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04MenuStatusBarWeightViewModel : RoguelikeMenuCompViewModel
{
	public Int32 nextWeightUp; // 0x14
	private RoguelikeFragmentLevelRelatedData m_nextFragmentLevelRelatedData; // 0x18
	private static DelegateBridge __Hotfix0_get_haveNextLevelRelatedData; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__GetTargetFragmentLevelData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean haveNextLevelRelatedData { get; }

	// RVA: 0x2b2e458 VA: 0x7595146458
	public Boolean get_haveNextLevelRelatedData() { }
	// RVA: 0x2b2f4c8 VA: 0x75951474c8
	public override Void LoadData(String topicId) { }
	// RVA: 0x2b2f5d0 VA: 0x75951475d0
	private RoguelikeFragmentLevelRelatedData _GetTargetFragmentLevelData(String topicId, Int32 targetLevel, Int32 maxLevel) { }
	// RVA: 0x2b2f72c VA: 0x759514772c
	public Void .ctor() { }
	// RVA: 0x2b2f79c VA: 0x759514779c
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```
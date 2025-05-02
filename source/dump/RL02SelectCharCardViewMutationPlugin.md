# RL02SelectCharCardViewMutationPlugin

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RL02SelectCharCardViewMutationPlugin : RoguelikeCharCardPlugin`1
{
	private static readonly Color MUTATION_CHAR_NAME_COLOR; // 0x0
	private static readonly Color EVOLUTION_CHAR_NAME_COLOR; // 0x10
	private static DelegateBridge __Hotfix0_OverrideRaritySprite; // 0x20
	private static DelegateBridge __Hotfix0_OverrideCharNameColor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2b72518 VA: 0x759518a518
	public override Boolean OverrideRaritySprite(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig, Boolean isSelect, Int32 selectIndex, out Sprite sprite) { }
	// RVA: 0x2b72680 VA: 0x759518a680
	public override Boolean OverrideCharNameColor(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig, Boolean isSelect, Int32 selectIndex, out Color color) { }
	// RVA: 0x2b722b8 VA: 0x759518a2b8
	public Void .ctor() { }
	// RVA: 0x2b727bc VA: 0x759518a7bc
	private static Void .cctor() { }
}
```
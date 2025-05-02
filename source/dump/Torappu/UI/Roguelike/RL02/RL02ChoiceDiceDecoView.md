# RL02ChoiceDiceDecoView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `UIAtlasObject _atlas`

- `UIAtlasImage _imgIcon`

- `UIAtlasImage _imgNum`


## Methods

- `Boolean _LoadData(String, RoguelikeGameChoiceData, out, out)`

- `Void _Render(Int32, Int32)`

- `Void <>xLuaBaseProxy_Render(String, RoguelikeGameChoiceData, ChoiceAddition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ChoiceDiceDecoView : RoguelikeChoiceLeftDecoView
{
	private const String DICE_FACE_PREFIX; // 0x0
	private const String DICE_NUM_PREFIX; // 0x0
	private UIAtlasObject _atlas; // 0x18
	private UIAtlasImage _imgIcon; // 0x20
	private UIAtlasImage _imgNum; // 0x28
	private static DelegateBridge __Hotfix0__LoadData; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b5cb98 VA: 0x7595174b98
	private Boolean _LoadData(String topicId, RoguelikeGameChoiceData choiceData, out Int32 diceFaceNum, out Int32 minGoodNum) { }
	// RVA: 0x2b5cdf4 VA: 0x7595174df4
	private Void _Render(Int32 diceFaceNum, Int32 minGoodNum) { }
	// RVA: 0x2b5d030 VA: 0x7595175030
	public override Void Render(String topicId, RoguelikeGameChoiceData choiceData, ChoiceAddition playerAdditionData) { }
	// RVA: 0x2b5d0fc VA: 0x75951750fc
	public Void .ctor() { }
	// RVA: 0x2b5d16c VA: 0x759517516c
	private Void <>xLuaBaseProxy_Render(String P0, RoguelikeGameChoiceData P1, ChoiceAddition P2) { }
}
```
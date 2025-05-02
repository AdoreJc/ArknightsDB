# RL03VisionDecoView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `GameObject _pnlLower`

- `GameObject _pnlUpper`

- `Text _textVision`


## Methods

- `VisionChoiceConfig _LoadData(String, RoguelikeGameChoiceData)`

- `Void _Render(VisionChoiceConfig)`

- `Void <>xLuaBaseProxy_Render(String, RoguelikeGameChoiceData, ChoiceAddition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03VisionDecoView : RoguelikeChoiceLeftDecoView
{
	private GameObject _pnlLower; // 0x18
	private GameObject _pnlUpper; // 0x20
	private Text _textVision; // 0x28
	private static DelegateBridge __Hotfix0__LoadData; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b91954 VA: 0x75951a9954
	private VisionChoiceConfig _LoadData(String topicId, RoguelikeGameChoiceData choiceData) { }
	// RVA: 0x2b91a80 VA: 0x75951a9a80
	private Void _Render(VisionChoiceConfig visionChoiceConfig) { }
	// RVA: 0x2b91ba4 VA: 0x75951a9ba4
	public override Void Render(String topicId, RoguelikeGameChoiceData choiceData, ChoiceAddition playerAdditionData) { }
	// RVA: 0x2b91c68 VA: 0x75951a9c68
	public Void .ctor() { }
	// RVA: 0x2b91cd8 VA: 0x75951a9cd8
	private Void <>xLuaBaseProxy_Render(String P0, RoguelikeGameChoiceData P1, ChoiceAddition P2) { }
}
```
# RoguelikeTaskChoiceModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeTaskData m_taskData`


## Methods

- `Void <>xLuaBaseProxy_OnDataUpdated()`

- `String <>xLuaBaseProxy_get_choiceContent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeTaskChoiceModel : RoguelikeDefaultChoiceModel
{
	private RoguelikeTaskData m_taskData; // 0x50
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x0
	private static DelegateBridge __Hotfix0_get_choiceContent; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override String choiceContent { get; }

	// RVA: 0x29eb5b0 VA: 0x75950035b0
	protected override Void OnDataUpdated() { }
	// RVA: 0x29eb6c0 VA: 0x75950036c0
	public override String get_choiceContent() { }
	// RVA: 0x29eb200 VA: 0x7595003200
	public Void .ctor() { }
	// RVA: 0x29eb760 VA: 0x7595003760
	private Void <>xLuaBaseProxy_OnDataUpdated() { }
	// RVA: 0x29eb764 VA: 0x7595003764
	private String <>xLuaBaseProxy_get_choiceContent() { }
}
```
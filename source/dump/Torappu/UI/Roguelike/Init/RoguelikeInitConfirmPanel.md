# RoguelikeInitConfirmPanel

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `RectTransform _listRoot`


## Methods

- `Void _UpdateItems(ItemUpdatorImpl`1, Boolean)`

- `Void EventOnConfirm()`

- `RoguelikeInitChar <OnUpdateContext>b__3_0()`

- `Void <OnUpdateContext>b__3_1(Int32, RoguelikeInitChar)`

- `RoguelikeInitRelic <OnUpdateContext>b__3_2()`

- `Void <OnUpdateContext>b__3_3(Int32, RoguelikeInitRelic)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitConfirmPanel : RoguelikeInitStepPanel`1
{
	private RectTransform _listRoot; // 0x38
	private ItemUpdatorImpl`1 m_charCardImpl; // 0x40
	private ItemUpdatorImpl`1 m_relicCardImpl; // 0x48
	private static DelegateBridge __Hotfix0_OnUpdateContext; // 0x0
	private static DelegateBridge __Hotfix0__UpdateItems; // 0x8
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b85870 VA: 0x759519d870
	protected override Void OnUpdateContext(Boolean isNew) { }
	// RVA: 0x VA: 0x0
	private Void _UpdateItems(ItemUpdatorImpl`1 itemImpl, Boolean isNew) { }
	// RVA: 0x2b85bf8 VA: 0x759519dbf8
	public Void EventOnConfirm() { }
	// RVA: 0x2b85c84 VA: 0x759519dc84
	public Void .ctor() { }
	// RVA: 0x2b85d14 VA: 0x759519dd14
	private RoguelikeInitChar <OnUpdateContext>b__3_0() { }
	// RVA: 0x2b85e24 VA: 0x759519de24
	private Void <OnUpdateContext>b__3_1(Int32 idx, RoguelikeInitChar card) { }
	// RVA: 0x2b85ef8 VA: 0x759519def8
	private RoguelikeInitRelic <OnUpdateContext>b__3_2() { }
	// RVA: 0x2b86008 VA: 0x759519e008
	private Void <OnUpdateContext>b__3_3(Int32 idx, RoguelikeInitRelic card) { }
}
```
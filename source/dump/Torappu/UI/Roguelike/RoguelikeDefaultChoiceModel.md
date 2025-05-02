# RoguelikeDefaultChoiceModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeGameChoiceData m_data`

- `ChoiceAddition m_playerAdditionData`

- `Boolean m_selectable`

- `IRoguelikeChoiceHintModel m_choiceCostHintModel`

- `IRoguelikeChoiceHintModel m_choiceEffectHintModel`

- `String m_choiceHint`

- `String m_topicId`

- `RoguelikeChoiceDisplayData m_displayData`


## Properties

- `RoguelikeGameChoiceType m_choiceType`

- `RoguelikeGameChoiceData choiceData`

- `ChoiceAddition playerAdditionData`

- `RoguelikeChoiceLeftDecoType leftDecoType`

- `String choiceHint`


## Methods

- `RoguelikeGameChoiceType get_m_choiceType()`

- `Void UpdateData(String, RoguelikeGameChoiceData, RoguelikeChoiceDisplayData, ChoiceAddition, Boolean, RoguelikeChoiceHintFactory)`

- `Void _GenerateChoiceHint()`

- `RoguelikeGameChoiceData get_choiceData()`

- `ChoiceAddition get_playerAdditionData()`

- `RoguelikeChoiceLeftDecoType get_leftDecoType()`

- `String get_choiceHint()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDefaultChoiceModel : IRoguelikeGameChoice, IHotfixable
{
	private RoguelikeGameChoiceData m_data; // 0x10
	private ChoiceAddition m_playerAdditionData; // 0x18
	private Boolean m_selectable; // 0x20
	private IRoguelikeChoiceHintModel m_choiceCostHintModel; // 0x28
	private IRoguelikeChoiceHintModel m_choiceEffectHintModel; // 0x30
	private String m_choiceHint; // 0x38
	protected String m_topicId; // 0x40
	protected RoguelikeChoiceDisplayData m_displayData; // 0x48
	private static DelegateBridge __Hotfix0_get_m_choiceType; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0__GenerateChoiceHint; // 0x10
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x18
	private static DelegateBridge __Hotfix0_GetChoiceHintContext; // 0x20
	private static DelegateBridge __Hotfix0_get_choiceData; // 0x28
	private static DelegateBridge __Hotfix0_get_playerAdditionData; // 0x30
	private static DelegateBridge __Hotfix0_get_leftDecoType; // 0x38
	private static DelegateBridge __Hotfix0_get_choiceTitle; // 0x40
	private static DelegateBridge __Hotfix0_get_choiceContent; // 0x48
	private static DelegateBridge __Hotfix0_get_choiceHint; // 0x50
	private static DelegateBridge __Hotfix0_get_itemName; // 0x58
	private static DelegateBridge __Hotfix0_get_itemDesc; // 0x60
	private static DelegateBridge __Hotfix0_get_funcIconName; // 0x68
	private static DelegateBridge __Hotfix0_get_itemId; // 0x70
	private static DelegateBridge __Hotfix0_get_itemType; // 0x78
	private static DelegateBridge __Hotfix0_get_enabled; // 0x80
	private static DelegateBridge __Hotfix0_get_isLeave; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	protected RoguelikeGameChoiceType m_choiceType { get; }
	public RoguelikeGameChoiceData choiceData { get; }
	public ChoiceAddition playerAdditionData { get; }
	public RoguelikeChoiceLeftDecoType leftDecoType { get; }
	public virtual String choiceTitle { get; }
	public virtual String choiceContent { get; }
	public String choiceHint { get; }
	public virtual String itemName { get; }
	public virtual String itemDesc { get; }
	public virtual String funcIconName { get; }
	public virtual String itemId { get; }
	public virtual RoguelikeGameItemType itemType { get; }
	public virtual Boolean enabled { get; }
	public virtual Boolean isLeave { get; }

	// RVA: 0x29ec404 VA: 0x7595004404
	protected RoguelikeGameChoiceType get_m_choiceType() { }
	// RVA: 0x29eb2dc VA: 0x75950032dc
	public Void UpdateData(String topicId, RoguelikeGameChoiceData data, RoguelikeChoiceDisplayData displayData, ChoiceAddition additionData, Boolean selectable, RoguelikeChoiceHintFactory hintFactory) { }
	// RVA: 0x29ec478 VA: 0x7595004478
	private Void _GenerateChoiceHint() { }
	// RVA: 0x29eb65c VA: 0x759500365c
	protected virtual Void OnDataUpdated() { }
	// RVA: 0x29ec228 VA: 0x7595004228
	protected virtual IRoguelikeChoiceHintContext GetChoiceHintContext() { }
	// RVA: 0x29ec6cc VA: 0x75950046cc
	public RoguelikeGameChoiceData get_choiceData() { }
	// RVA: 0x29ec734 VA: 0x7595004734
	public ChoiceAddition get_playerAdditionData() { }
	// RVA: 0x29ec79c VA: 0x759500479c
	public RoguelikeChoiceLeftDecoType get_leftDecoType() { }
	// RVA: 0x29ec814 VA: 0x7595004814
	public virtual String get_choiceTitle() { }
	// RVA: 0x29eb768 VA: 0x7595003768
	public virtual String get_choiceContent() { }
	// RVA: 0x29ec8a8 VA: 0x75950048a8
	public String get_choiceHint() { }
	// RVA: 0x29ec048 VA: 0x7595004048
	public virtual String get_itemName() { }
	// RVA: 0x29ec0d0 VA: 0x75950040d0
	public virtual String get_itemDesc() { }
	// RVA: 0x29eb54c VA: 0x759500354c
	public virtual String get_funcIconName() { }
	// RVA: 0x29ec158 VA: 0x7595004158
	public virtual String get_itemId() { }
	// RVA: 0x29ec1c0 VA: 0x75950041c0
	public virtual RoguelikeGameItemType get_itemType() { }
	// RVA: 0x29ec910 VA: 0x7595004910
	public virtual Boolean get_enabled() { }
	// RVA: 0x29ec978 VA: 0x7595004978
	public virtual Boolean get_isLeave() { }
	// RVA: 0x29eb26c VA: 0x759500326c
	public Void .ctor() { }
}
```
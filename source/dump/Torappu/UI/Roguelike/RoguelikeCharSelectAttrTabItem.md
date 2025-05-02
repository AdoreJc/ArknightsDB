# RoguelikeCharSelectAttrTabItem

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CharAttrTabType _tabType`

- `RoguelikeCharAttrTabTypeMessage m_onSortTypeChanged`

- `Boolean m_isInited`

- `TwoStateToggle m_twoStateToggle`


## Properties

- `CharAttrTabType attrTabType`


## Methods

- `Void _InitIfNot(RoguelikeCharAttrTabTypeMessage)`

- `Void RenderType(RoguelikeCharCardViewModel, RoguelikeCharAttrTabTypeMessage)`

- `Void _OnToggle(State)`

- `CharAttrTabType get_attrTabType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectAttrTabItem : MonoBehaviour, IHotfixable
{
	private CharAttrTabType _tabType; // 0x18
	private RoguelikeCharAttrTabTypeMessage m_onSortTypeChanged; // 0x20
	private Boolean m_isInited; // 0x28
	private TwoStateToggle m_twoStateToggle; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderType; // 0x8
	private static DelegateBridge __Hotfix0__OnToggle; // 0x10
	private static DelegateBridge __Hotfix0_get_attrTabType; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public CharAttrTabType attrTabType { get; }

	// RVA: 0x2acce38 VA: 0x75950e4e38
	private Void _InitIfNot(RoguelikeCharAttrTabTypeMessage onTabClick) { }
	// RVA: 0x2acc4d0 VA: 0x75950e44d0
	public Void RenderType(RoguelikeCharCardViewModel viewModel, RoguelikeCharAttrTabTypeMessage onTabClick) { }
	// RVA: 0x2accf74 VA: 0x75950e4f74
	private Void _OnToggle(State state) { }
	// RVA: 0x2acd020 VA: 0x75950e5020
	public CharAttrTabType get_attrTabType() { }
	// RVA: 0x2acd088 VA: 0x75950e5088
	public Void .ctor() { }
}
```
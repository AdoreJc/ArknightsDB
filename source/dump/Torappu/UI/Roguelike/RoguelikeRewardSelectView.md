# RoguelikeRewardSelectView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `SimpleLayoutContent _content`

- `SimpleLayoutContent _constContent`

- `UIIntEvent _onClick`

- `Adapter m_adapter`

- `ConstAdapter m_constAdapter`

- `RoguelikeRewardStyle <uiStyle>k__BackingField`

- `Boolean m_isInited`


## Properties

- `RoguelikeRewardStyle uiStyle`


## Methods

- `RoguelikeRewardStyle get_uiStyle()`

- `Void set_uiStyle(RoguelikeRewardStyle)`

- `Void _InitIfNot()`

- `Void OnRender(List`1, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardSelectView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private SimpleLayoutContent _constContent; // 0x20
	private UIIntEvent _onClick; // 0x28
	private Adapter m_adapter; // 0x30
	private ConstAdapter m_constAdapter; // 0x38
	private RoguelikeRewardStyle <uiStyle>k__BackingField; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0_get_uiStyle; // 0x0
	private static DelegateBridge __Hotfix0_set_uiStyle; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnRender; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public RoguelikeRewardStyle uiStyle { get; set; }

	// RVA: 0x2aa1580 VA: 0x75950b9580
	public RoguelikeRewardStyle get_uiStyle() { }
	// RVA: 0x2aa15e8 VA: 0x75950b95e8
	public Void set_uiStyle(RoguelikeRewardStyle value) { }
	// RVA: 0x2aa166c VA: 0x75950b966c
	private Void _InitIfNot() { }
	// RVA: 0x2aa19f4 VA: 0x75950b99f4
	public Void OnRender(List`1 itemList, Boolean showSeparator) { }
	// RVA: 0x2aa1af8 VA: 0x75950b9af8
	public Void .ctor() { }
}
```
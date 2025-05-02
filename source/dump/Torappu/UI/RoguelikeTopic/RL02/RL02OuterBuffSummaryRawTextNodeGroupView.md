# RL02OuterBuffSummaryRawTextNodeGroupView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `SimpleLayoutContent _groupContent`

- `UIPage <page>k__BackingField`

- `String m_topicId`

- `Boolean m_hasInited`

- `Adapter m_adapter`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void Render(RL02OuterBuffListModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffSummaryRawTextNodeGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _groupContent; // 0x18
	private UIPage <page>k__BackingField; // 0x20
	private List`1 m_groupModelList; // 0x28
	private String m_topicId; // 0x30
	private Boolean m_hasInited; // 0x38
	private Adapter m_adapter; // 0x40
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private UIPage page { get; set; }

	// RVA: 0x26c4934 VA: 0x7594cdc934
	private UIPage get_page() { }
	// RVA: 0x26c499c VA: 0x7594cdc99c
	public Void set_page(UIPage value) { }
	// RVA: 0x26c4a20 VA: 0x7594cdca20
	public Void Render(RL02OuterBuffListModel viewModel) { }
	// RVA: 0x26c4ae8 VA: 0x7594cdcae8
	private Void _InitIfNot() { }
	// RVA: 0x26c4c4c VA: 0x7594cdcc4c
	public Void .ctor() { }
}
```
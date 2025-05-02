# RL02OuterBuffSummaryMergedGroupView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `SimpleLayoutContent _itemContent`

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
public class RL02OuterBuffSummaryMergedGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _itemContent; // 0x18
	private UIPage <page>k__BackingField; // 0x20
	private List`1 m_cachedModel; // 0x28
	private String m_topicId; // 0x30
	private Boolean m_hasInited; // 0x38
	private Adapter m_adapter; // 0x40
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected UIPage page { get; set; }

	// RVA: 0x26c3f68 VA: 0x7594cdbf68
	protected UIPage get_page() { }
	// RVA: 0x26c3fd0 VA: 0x7594cdbfd0
	public Void set_page(UIPage value) { }
	// RVA: 0x26c4054 VA: 0x7594cdc054
	public Void Render(RL02OuterBuffListModel viewModel) { }
	// RVA: 0x26c411c VA: 0x7594cdc11c
	private Void _InitIfNot() { }
	// RVA: 0x26c4280 VA: 0x7594cdc280
	public Void .ctor() { }
}
```
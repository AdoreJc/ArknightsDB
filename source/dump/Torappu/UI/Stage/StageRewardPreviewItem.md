# StageRewardPreviewItem

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Transform _itemCardContainer`

- `Single _cardScaleFactor`

- `GameObject _onceTag`

- `GameObject _completeTag`

- `GameObject _overrideDropTag`

- `Text _overrideDropText`

- `Boolean _showItemNum`

- `Transform _timelyDropContainer`

- `GameObject m_timelyDropItem`

- `String m_cacheDropId`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_viewModel`

- `Boolean m_isInited`


## Methods

- `Void Render(StageRewardViewModel)`

- `Void _RenderOverrideDropTag(StageRewardViewModel)`

- `Void _RenderTimelyDrop(StageRewardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageRewardPreviewItem : MonoBehaviour, IHotfixable
{
	protected Transform _itemCardContainer; // 0x18
	protected Single _cardScaleFactor; // 0x20
	protected GameObject _onceTag; // 0x28
	protected GameObject _completeTag; // 0x30
	private GameObject _overrideDropTag; // 0x38
	private Text _overrideDropText; // 0x40
	protected Boolean _showItemNum; // 0x48
	protected Transform _timelyDropContainer; // 0x50
	protected GameObject m_timelyDropItem; // 0x58
	private String m_cacheDropId; // 0x60
	protected UIItemCard m_itemCard; // 0x68
	protected UIItemViewModel m_viewModel; // 0x70
	protected Boolean m_isInited; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNeeded; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderOverrideDropTag; // 0x10
	private static DelegateBridge __Hotfix0__RenderTimelyDrop; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2faca3c VA: 0x75955c4a3c
	protected virtual Void _InitIfNeeded() { }
	// RVA: 0x2fabb08 VA: 0x75955c3b08
	public Void Render(StageRewardViewModel viewModel) { }
	// RVA: 0x2facc04 VA: 0x75955c4c04
	private Void _RenderOverrideDropTag(StageRewardViewModel viewModel) { }
	// RVA: 0x2facdb4 VA: 0x75955c4db4
	private Void _RenderTimelyDrop(StageRewardViewModel viewModel) { }
	// RVA: 0x2fad01c VA: 0x75955c501c
	public Void .ctor() { }
}
```
# ClimbTowerRewardPreviewItem

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Transform _itemCardContainer`

- `Transform _timelyDropContainer`

- `String m_cacheDropId`

- `GameObject m_timelyDropItem`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_viewModel`

- `Single m_scaleFactor`

- `Boolean m_isInited`


## Properties

- `Single scaleFactor`


## Methods

- `Void set_scaleFactor(Single)`

- `Void _InitIfNot()`

- `Void Render(StageRewardViewModel)`

- `Void _RenderTimelyDrop(StageRewardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRewardPreviewItem : MonoBehaviour, IHotfixable
{
	private Transform _itemCardContainer; // 0x18
	private Transform _timelyDropContainer; // 0x20
	private String m_cacheDropId; // 0x28
	private GameObject m_timelyDropItem; // 0x30
	private UIItemCard m_itemCard; // 0x38
	private UIItemViewModel m_viewModel; // 0x40
	private Single m_scaleFactor; // 0x48
	private Boolean m_isInited; // 0x4c
	private static DelegateBridge __Hotfix0_set_scaleFactor; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderTimelyDrop; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Single scaleFactor { set; }

	// RVA: 0x2c757d4 VA: 0x759528d7d4
	public Void set_scaleFactor(Single value) { }
	// RVA: 0x2c76708 VA: 0x759528e708
	private Void _InitIfNot() { }
	// RVA: 0x2c75850 VA: 0x759528d850
	public Void Render(StageRewardViewModel viewModel) { }
	// RVA: 0x2c768d0 VA: 0x759528e8d0
	private Void _RenderTimelyDrop(StageRewardViewModel viewModel) { }
	// RVA: 0x2c76b38 VA: 0x759528eb38
	public Void .ctor() { }
}
```
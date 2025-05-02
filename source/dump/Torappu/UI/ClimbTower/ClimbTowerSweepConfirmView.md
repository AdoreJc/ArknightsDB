# ClimbTowerSweepConfirmView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `CanvasGroup _floatGroup`

- `Text _textLayerCount`

- `RectTransform _lowItemIconContainer`

- `Text _textLowItemName`

- `Slider _slideLowItemFrom`

- `Slider _slideLowItemTo`

- `Text _textLowItemFrom`

- `Text _textLowItemTo`

- `Text _textLowItemAdd`

- `RectTransform _highItemIconContainer`

- `Text _textHighItemName`

- `Slider _slideHighItemFrom`

- `Slider _slideHighItemTo`

- `Text _textHighItemFrom`

- `Text _textHighItemTo`

- `Text _textHighItemAdd`

- `Text _textConfirm`

- `SimpleLayoutContent _layoutCostTkt`

- `Single _itemCardScaleFactor`

- `ClimbTowerViewModel m_viewModel`

- `TktAdapter m_tktAdapter`

- `UIItemCard m_lowItemCard`

- `UIItemCard m_highItemCard`

- `UIStateFinder m_stateFinder`

- `Int32 m_resetSweepConfirmSeqNum`

- `FadeSwitchTween m_fadeSwitchTween`

- `Boolean m_isInited`


## Methods

- `Void Render(ClimbTowerViewModel)`

- `Void _RenderItemIcon(ItemData, ItemData)`

- `Void _InitIfNot()`

- `Void OnClickStartSweep()`

- `Void OnClickCancelSweep()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSweepConfirmView : MonoBehaviour, IHotfixable
{
	private const String TARGET_ITEM_FMT; // 0x0
	private CanvasGroup _floatGroup; // 0x18
	private Text _textLayerCount; // 0x20
	private RectTransform _lowItemIconContainer; // 0x28
	private Text _textLowItemName; // 0x30
	private Slider _slideLowItemFrom; // 0x38
	private Slider _slideLowItemTo; // 0x40
	private Text _textLowItemFrom; // 0x48
	private Text _textLowItemTo; // 0x50
	private Text _textLowItemAdd; // 0x58
	private RectTransform _highItemIconContainer; // 0x60
	private Text _textHighItemName; // 0x68
	private Slider _slideHighItemFrom; // 0x70
	private Slider _slideHighItemTo; // 0x78
	private Text _textHighItemFrom; // 0x80
	private Text _textHighItemTo; // 0x88
	private Text _textHighItemAdd; // 0x90
	private Text _textConfirm; // 0x98
	private SimpleLayoutContent _layoutCostTkt; // 0xa0
	private Single _itemCardScaleFactor; // 0xa8
	private ClimbTowerViewModel m_viewModel; // 0xb0
	private TktAdapter m_tktAdapter; // 0xb8
	private UIItemCard m_lowItemCard; // 0xc0
	private UIItemCard m_highItemCard; // 0xc8
	private UIStateFinder m_stateFinder; // 0xd0
	private Int32 m_resetSweepConfirmSeqNum; // 0xe0
	private FadeSwitchTween m_fadeSwitchTween; // 0xe8
	private Boolean m_isInited; // 0xf0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderItemIcon; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnClickStartSweep; // 0x18
	private static DelegateBridge __Hotfix0_OnClickCancelSweep; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2c77418 VA: 0x759528f418
	public Void Render(ClimbTowerViewModel viewModel) { }
	// RVA: 0x2c77c68 VA: 0x759528fc68
	private Void _RenderItemIcon(ItemData lowData, ItemData highData) { }
	// RVA: 0x2c7791c VA: 0x759528f91c
	private Void _InitIfNot() { }
	// RVA: 0x2c77e20 VA: 0x759528fe20
	public Void OnClickStartSweep() { }
	// RVA: 0x2c77ec4 VA: 0x759528fec4
	public Void OnClickCancelSweep() { }
	// RVA: 0x2c77f68 VA: 0x759528ff68
	public Void .ctor() { }
}
```
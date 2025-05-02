# MainStageSpecialStoryButtonPlugin

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _spstReward`

- `Single _itemScaler`

- `RectTransform _itemCardContainer`

- `GameObject _spstObj`

- `CanvasGroup _spstAniamtionGroup`

- `Color _lockedColor`

- `Color _unlockedColor`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`

- `Tween m_lineTween`


## Methods

- `Void OnSpecialRewardClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class MainStageSpecialStoryButtonPlugin : StageButtonHolderPlugin
{
	private Image[] _decoSquares; // 0x28
	private GameObject _spstReward; // 0x30
	private Single _itemScaler; // 0x38
	private RectTransform _itemCardContainer; // 0x40
	private GameObject _spstObj; // 0x48
	private CanvasGroup _spstAniamtionGroup; // 0x50
	private Color _lockedColor; // 0x58
	private Color _unlockedColor; // 0x68
	private const Single ANIMATION_ORIGIN_ALPHA; // 0x0
	private const Single ANIMATION_TARGET_ALPHA; // 0x0
	private const Single ANIMATION_DURATION; // 0x0
	private UIItemCard m_itemCard; // 0x78
	private UIItemViewModel m_itemModel; // 0x80
	private Tween m_lineTween; // 0x88
	private static DelegateBridge __Hotfix0_OnSpecialRewardClick; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRenderStage; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f90c7c VA: 0x75955a8c7c
	public Void OnSpecialRewardClick() { }
	// RVA: 0x2f90d3c VA: 0x75955a8d3c
	protected override Void OnInit() { }
	// RVA: 0x2f90e10 VA: 0x75955a8e10
	protected override Void OnRenderStage(StageViewModel viewModel) { }
	// RVA: 0x2f914c8 VA: 0x75955a94c8
	public Void .ctor() { }
}
```
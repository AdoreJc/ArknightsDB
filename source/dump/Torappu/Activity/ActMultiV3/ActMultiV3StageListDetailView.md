# ActMultiV3StageListDetailView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `SimpleLayoutContent _layoutDots`

- `RectTransform _viewHolder`

- `ActMultiV3StageDetailView _viewPrefab`

- `GameObject _pnlEnemyHandbook`

- `Boolean m_inited`

- `ActMultiV3MapDiffType m_cachedDiffType`

- `Adapter m_adapter`

- `ActMultiV3StageDetailView m_view`

- `ActMultiV3StageListDetailStateViewModel m_cachedViewModel`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void OnBtnLeftClicked()`

- `Void OnBtnRightClicked()`

- `Void OnBtnEnemyHandbookClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListDetailView : DataBinder`1
{
	private AnimConfig[] _animConfigs; // 0x20
	private SimpleLayoutContent _layoutDots; // 0x28
	private RectTransform _viewHolder; // 0x30
	private ActMultiV3StageDetailView _viewPrefab; // 0x38
	private GameObject _pnlEnemyHandbook; // 0x40
	private EnemyItemView[] _enemyItems; // 0x48
	private Boolean m_inited; // 0x50
	private ActMultiV3MapDiffType m_cachedDiffType; // 0x54
	private Adapter m_adapter; // 0x58
	private ActMultiV3StageDetailView m_view; // 0x60
	private ActMultiV3StageListDetailStateViewModel m_cachedViewModel; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnBtnLeftClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnBtnRightClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnBtnEnemyHandbookClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3149598 VA: 0x7595761598
	private Void _InitIfNot() { }
	// RVA: 0x314976c VA: 0x759576176c
	public override Void OnValueChanged(ActMultiV3StageDetailStateProperty property) { }
	// RVA: 0x3149c20 VA: 0x7595761c20
	public Void OnBtnLeftClicked() { }
	// RVA: 0x3149cd4 VA: 0x7595761cd4
	public Void OnBtnRightClicked() { }
	// RVA: 0x3149d88 VA: 0x7595761d88
	public Void OnBtnEnemyHandbookClicked() { }
	// RVA: 0x3149e2c VA: 0x7595761e2c
	public Void .ctor() { }
}
```
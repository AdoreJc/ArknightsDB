# RecruitBuildFastBuyView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Text _buyText`

- `UIRenderTextureImage _backImage`

- `GameObject _obj`

- `UIItemCard _itemPrefab`

- `Single _itemScale`

- `RectTransform _costItemHolder`

- `RectTransform _targetItemHolder`

- `Int32 m_cost`

- `Int32 m_slotId`

- `UIItemCard m_costItem`

- `UIItemCard m_targetItem`

- `UIItemViewModel m_costModel`

- `UIItemViewModel m_targetModel`

- `Boolean m_isInited`

- `Boolean m_cacheFlag`

- `UIIntEvent _onClickFast`

- `UIIntEvent _onClickFastNotEnough`


## Methods

- `Void Dismiss()`

- `Void OnClick()`

- `Void OnEnterNotEnough(Int32)`

- `Void OnEnter(Int32)`

- `Void _InitIfNot(Boolean)`

- `Void _InitItemCard(ref, Transform, Action`1)`

- `Void <_InitIfNot>b__24_0(Int32)`

- `Void <_InitIfNot>b__24_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildFastBuyView : PageSingleComponent
{
	private Text _buyText; // 0x20
	private UIRenderTextureImage _backImage; // 0x28
	private GameObject _obj; // 0x30
	private UIItemCard _itemPrefab; // 0x38
	private Single _itemScale; // 0x40
	private RectTransform _costItemHolder; // 0x48
	private RectTransform _targetItemHolder; // 0x50
	private Int32 m_cost; // 0x58
	private Int32 m_slotId; // 0x5c
	private UIItemCard m_costItem; // 0x60
	private UIItemCard m_targetItem; // 0x68
	private UIItemViewModel m_costModel; // 0x70
	private UIItemViewModel m_targetModel; // 0x78
	private Boolean m_isInited; // 0x80
	private Boolean m_cacheFlag; // 0x81
	private UIIntEvent _onClickFast; // 0x88
	private UIIntEvent _onClickFastNotEnough; // 0x90
	private static DelegateBridge __Hotfix0_Dismiss; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_OnDismissStatic; // 0x10
	private static DelegateBridge __Hotfix0_OnEnterNotEnoughStatic; // 0x18
	private static DelegateBridge __Hotfix0_OnEnterStatic; // 0x20
	private static DelegateBridge __Hotfix0_OnEnterNotEnough; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__InitItemCard; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2704ce4 VA: 0x7594d1cce4
	public Void Dismiss() { }
	// RVA: 0x2704d6c VA: 0x7594d1cd6c
	public Void OnClick() { }
	// RVA: 0x26fb030 VA: 0x7594d13030
	public static Void OnDismissStatic() { }
	// RVA: 0x2704e10 VA: 0x7594d1ce10
	public static Void OnEnterNotEnoughStatic(Int32 slotId) { }
	// RVA: 0x27051e0 VA: 0x7594d1d1e0
	public static Void OnEnterStatic(Int32 slotId) { }
	// RVA: 0x2704eec VA: 0x7594d1ceec
	public Void OnEnterNotEnough(Int32 slotId) { }
	// RVA: 0x27052bc VA: 0x7594d1d2bc
	public Void OnEnter(Int32 slotId) { }
	// RVA: 0x27054b8 VA: 0x7594d1d4b8
	private Void _InitIfNot(Boolean diamondFlag) { }
	// RVA: 0x2705688 VA: 0x7594d1d688
	private Void _InitItemCard(ref UIItemCard itemCard, Transform parent, Action`1 onClick) { }
	// RVA: 0x2705818 VA: 0x7594d1d818
	public Void .ctor() { }
	// RVA: 0x27058f0 VA: 0x7594d1d8f0
	private Void <_InitIfNot>b__24_0(Int32 _) { }
	// RVA: 0x2705928 VA: 0x7594d1d928
	private Void <_InitIfNot>b__24_1(Int32 _) { }
}
```
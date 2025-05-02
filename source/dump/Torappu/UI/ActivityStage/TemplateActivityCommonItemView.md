# TemplateActivityCommonItemView

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `Transform _itemCont`

- `Transform _itemRepCont`

- `GameObject _panelRepIcon`

- `AnimationWrapper _repAnim`

- `GameObject _noItemPart`

- `Single scaler`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `UIItemCard m_repItemCard`

- `RepTweenController m_repTween`

- `UIItemViewModel m_itemModel`

- `UIItemViewModel m_repItemModel`

- `Boolean m_isReplicate`


## Methods

- `Void _InitIfNot()`

- `UIItemCard _EnsureRepItemCard()`

- `Void Render(BasicActivityItemViewModel)`

- `Void _UpdateReplicateInfo(BasicActivityItemViewModel)`

- `Void _OnRepItemCardClicked(Int32)`

- `Void _OnItemCardClicked(Int32)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityCommonItemView : MonoBehaviour, IHotfixable
{
	private const String ANIM_PARAM; // 0x0
	private Transform _itemCont; // 0x18
	private Transform _itemRepCont; // 0x20
	private GameObject _panelRepIcon; // 0x28
	private AnimationWrapper _repAnim; // 0x30
	private GameObject _noItemPart; // 0x38
	public Single scaler; // 0x40
	private Boolean m_isInited; // 0x44
	private UIItemCard m_itemCard; // 0x48
	private UIItemCard m_repItemCard; // 0x50
	private RepTweenController m_repTween; // 0x58
	private UIItemViewModel m_itemModel; // 0x60
	private UIItemViewModel m_repItemModel; // 0x68
	private Boolean m_isReplicate; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__EnsureRepItemCard; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__UpdateReplicateInfo; // 0x18
	private static DelegateBridge __Hotfix0__OnRepItemCardClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x30a985c VA: 0x75956c185c
	private Void _InitIfNot() { }
	// RVA: 0x30a9a50 VA: 0x75956c1a50
	private UIItemCard _EnsureRepItemCard() { }
	// RVA: 0x30a726c VA: 0x75956bf26c
	public Void Render(BasicActivityItemViewModel viewModel) { }
	// RVA: 0x30a9c58 VA: 0x75956c1c58
	private Void _UpdateReplicateInfo(BasicActivityItemViewModel actItemModel) { }
	// RVA: 0x30aa10c VA: 0x75956c210c
	private Void _OnRepItemCardClicked(Int32 unusedIndex) { }
	// RVA: 0x30aa208 VA: 0x75956c2208
	private Void _OnItemCardClicked(Int32 unusedIndex) { }
	// RVA: 0x30aa2fc VA: 0x75956c22fc
	private Void OnDestroy() { }
	// RVA: 0x30aa414 VA: 0x75956c2414
	public Void .ctor() { }
}
```
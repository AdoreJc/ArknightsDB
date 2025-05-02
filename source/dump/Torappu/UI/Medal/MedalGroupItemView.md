# MedalGroupItemView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Image _groupImage`

- `Image _groupBackImage`

- `GameObject _panelStyledTitle`

- `SimpleLayoutContent _content`

- `GameObject _jumpBtn`

- `GameObject _typeSplit`

- `VerticalLayoutGroup _selfLayout`

- `GridLayoutGroup _childLayout`

- `LayoutElement _layoutTypeSplit`

- `LayoutElement _layoutStyleTitle`

- `UIMedalEvent clickEvent`

- `UIStringEvent clickToGroupEvent`

- `Boolean ableToGetFlag`

- `String pageName`

- `ItemAdapter m_itemAdapter`

- `Boolean m_isInited`

- `MedalGroupViewModel m_cachedGroupModel`


## Methods

- `Void _InitIfNot()`

- `Void RenderData(Param)`

- `Void _UpdateMedalItems(Int32, IList`1, AsyncGameObjectLoader)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalGroupItemView : MonoBehaviour, IHotfixable
{
	private Image _groupImage; // 0x18
	private Image _groupBackImage; // 0x20
	private GameObject _panelStyledTitle; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private GameObject _jumpBtn; // 0x38
	private GameObject _typeSplit; // 0x40
	private VerticalLayoutGroup _selfLayout; // 0x48
	private GridLayoutGroup _childLayout; // 0x50
	private LayoutElement _layoutTypeSplit; // 0x58
	private LayoutElement _layoutStyleTitle; // 0x60
	public UIMedalEvent clickEvent; // 0x68
	public UIStringEvent clickToGroupEvent; // 0x70
	public Boolean ableToGetFlag; // 0x78
	public String pageName; // 0x80
	private ItemAdapter m_itemAdapter; // 0x88
	private List`1 m_paramList; // 0x90
	private Boolean m_isInited; // 0x98
	private MedalGroupViewModel m_cachedGroupModel; // 0xa0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderData; // 0x8
	private static DelegateBridge __Hotfix0__CheckIfShowTypeSplit; // 0x10
	private static DelegateBridge __Hotfix0__CalcSelfHeightLogicly; // 0x18
	private static DelegateBridge __Hotfix0__UpdateMedalItems; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x279a720 VA: 0x7594db2720
	private Void _InitIfNot() { }
	// RVA: 0x279a898 VA: 0x7594db2898
	protected Void RenderData(Param param) { }
	// RVA: 0x279ad64 VA: 0x7594db2d64
	private static Boolean _CheckIfShowTypeSplit(MedalGroupListItemModel prevModel, Boolean isStyledGroup) { }
	// RVA: 0x279ae00 VA: 0x7594db2e00
	private static Single _CalcSelfHeightLogicly(MedalGroupItemView prefab, MedalGroupListItemModel curModel, MedalGroupListItemModel prevModel) { }
	// RVA: 0x279aab4 VA: 0x7594db2ab4
	private Void _UpdateMedalItems(Int32 groupIndex, IList`1 viewModelList, AsyncGameObjectLoader asyncLoader) { }
	// RVA: 0x279b080 VA: 0x7594db3080
	public Void OnClick() { }
	// RVA: 0x279b128 VA: 0x7594db3128
	public Void .ctor() { }
}
```
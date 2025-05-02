# Act24sideBattleFinishMeldingDropInfoItemView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `SimpleLayoutContent _itemGridFirst`

- `SimpleLayoutContent _itemGridMeal`

- `SimpleLayoutContent _itemGridNormal`

- `CanvasGroup _lineFirst`

- `CanvasGroup _lineMeal`

- `Single _delayPerItem`

- `Single _lineFadeDuration`

- `ItemAdapter m_itemAdapterFirst`

- `ItemAdapter m_itemAdapterMeal`

- `ItemAdapter m_itemAdapterNormal`

- `Animator m_itemAnimatorFirst`

- `Animator m_itemAnimatorMeal`

- `Animator m_itemAnimatorNormal`

- `Boolean m_isInited`

- `String m_cachedActId`

- `Boolean <rendering>k__BackingField`


## Properties

- `Boolean rendering`


## Methods

- `Boolean get_rendering()`

- `Void set_rendering(Boolean)`

- `Void _InitIfNot()`

- `Void Render(Act24sideBattleFinishMeldingDropViewModel)`

- `IEnumerator _RenderViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleFinishMeldingDropInfoItemView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _itemGridFirst; // 0x18
	private SimpleLayoutContent _itemGridMeal; // 0x20
	private SimpleLayoutContent _itemGridNormal; // 0x28
	private CanvasGroup _lineFirst; // 0x30
	private CanvasGroup _lineMeal; // 0x38
	private Single _delayPerItem; // 0x40
	private Single _lineFadeDuration; // 0x44
	private List`1 m_dropItemsFirst; // 0x48
	private List`1 m_dropItemsMeal; // 0x50
	private List`1 m_dropItemsNormal; // 0x58
	private ItemAdapter m_itemAdapterFirst; // 0x60
	private ItemAdapter m_itemAdapterMeal; // 0x68
	private ItemAdapter m_itemAdapterNormal; // 0x70
	private Animator m_itemAnimatorFirst; // 0x78
	private Animator m_itemAnimatorMeal; // 0x80
	private Animator m_itemAnimatorNormal; // 0x88
	private Boolean m_isInited; // 0x90
	private String m_cachedActId; // 0x98
	private Boolean <rendering>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_rendering; // 0x0
	private static DelegateBridge __Hotfix0_set_rendering; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__RenderViewModel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean rendering { get; set; }

	// RVA: 0x3290738 VA: 0x75958a8738
	public Boolean get_rendering() { }
	// RVA: 0x32907a0 VA: 0x75958a87a0
	private Void set_rendering(Boolean value) { }
	// RVA: 0x3290820 VA: 0x75958a8820
	private Void _InitIfNot() { }
	// RVA: 0x3290bcc VA: 0x75958a8bcc
	public Void Render(Act24sideBattleFinishMeldingDropViewModel viewModel) { }
	// RVA: 0x3290d78 VA: 0x75958a8d78
	private IEnumerator _RenderViewModel() { }
	// RVA: 0x3290e4c VA: 0x75958a8e4c
	public Void .ctor() { }
}
```
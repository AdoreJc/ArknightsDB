# BattleFinishDropInfoView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `SimpleLayoutContent _itemGridFirst`

- `SimpleLayoutContent _itemGridMulti`

- `SimpleLayoutContent _itemGridNormal`

- `SimpleLayoutContent _itemGridUnusual`

- `SimpleLayoutContent _itemGridAdditional`

- `SimpleLayoutContent _itemGridAP`

- `SimpleLayoutContent _itemGridItemReturn`

- `SimpleLayoutContent _itemGridDiamondMaterial`

- `SimpleLayoutContent _itemGridFurniture`

- `SimpleLayoutContent _itemGridOverride`

- `Text _percentText`

- `Text _percentTextWhite`

- `Single _delayPerItem`

- `ItemAdapter m_itemAdapterFirst`

- `ItemAdapter m_itemAdapterMulti`

- `ItemAdapter m_itemAdapterAP`

- `ItemAdapter m_itemAdapterNormal`

- `ItemAdapter m_itemAdapterUnusual`

- `ItemAdapter m_itemAdapterAdditional`

- `ItemAdapter m_itemAdapterDiamondMaterial`

- `ItemAdapter m_itemAdapterFurniture`

- `ItemAdapter m_itemAdapterOverride`

- `ItemAdapter m_itemAdapterReturn`

- `Animator m_itemAnimatorFirst`

- `Animator m_itemAnimatorMulti`

- `Animator m_itemAnimatorAP`

- `Animator m_itemAnimatorNormal`

- `Animator m_itemAnimatorUnusual`

- `Animator m_itemAnimatorAdditional`

- `Animator m_itemAnimatorDiamondMaterial`

- `Animator m_itemAnimatorFurniture`

- `Animator m_itemAnimatorOverride`

- `Animator m_itemAnimatorReturn`

- `Boolean m_isInited`

- `Boolean <rendering>k__BackingField`


## Properties

- `Boolean rendering`


## Methods

- `Boolean get_rendering()`

- `Void set_rendering(Boolean)`

- `Void _InitIfNot()`

- `IEnumerator _RenderViewModel()`

- `Void Render(DropInfoGroupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishDropInfoView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _itemGridFirst; // 0x18
	private SimpleLayoutContent _itemGridMulti; // 0x20
	private SimpleLayoutContent _itemGridNormal; // 0x28
	private SimpleLayoutContent _itemGridUnusual; // 0x30
	private SimpleLayoutContent _itemGridAdditional; // 0x38
	private SimpleLayoutContent _itemGridAP; // 0x40
	private SimpleLayoutContent _itemGridItemReturn; // 0x48
	private SimpleLayoutContent _itemGridDiamondMaterial; // 0x50
	private SimpleLayoutContent _itemGridFurniture; // 0x58
	private SimpleLayoutContent _itemGridOverride; // 0x60
	private Text _percentText; // 0x68
	private Text _percentTextWhite; // 0x70
	private Single _delayPerItem; // 0x78
	private List`1 m_dropItemsFirst; // 0x80
	private List`1 m_dropItemsMulti; // 0x88
	private List`1 m_dropItemsAP; // 0x90
	private List`1 m_dropItemsNormal; // 0x98
	private List`1 m_dropItemsUnusual; // 0xa0
	private List`1 m_dropItemsAdditional; // 0xa8
	private List`1 m_dropItemsDiamondMaterial; // 0xb0
	private List`1 m_dropItemsFurniture; // 0xb8
	private List`1 m_dropItemsOverride; // 0xc0
	private List`1 m_dropItemsReturn; // 0xc8
	private ItemAdapter m_itemAdapterFirst; // 0xd0
	private ItemAdapter m_itemAdapterMulti; // 0xd8
	private ItemAdapter m_itemAdapterAP; // 0xe0
	private ItemAdapter m_itemAdapterNormal; // 0xe8
	private ItemAdapter m_itemAdapterUnusual; // 0xf0
	private ItemAdapter m_itemAdapterAdditional; // 0xf8
	private ItemAdapter m_itemAdapterDiamondMaterial; // 0x100
	private ItemAdapter m_itemAdapterFurniture; // 0x108
	private ItemAdapter m_itemAdapterOverride; // 0x110
	private ItemAdapter m_itemAdapterReturn; // 0x118
	private Animator m_itemAnimatorFirst; // 0x120
	private Animator m_itemAnimatorMulti; // 0x128
	private Animator m_itemAnimatorAP; // 0x130
	private Animator m_itemAnimatorNormal; // 0x138
	private Animator m_itemAnimatorUnusual; // 0x140
	private Animator m_itemAnimatorAdditional; // 0x148
	private Animator m_itemAnimatorDiamondMaterial; // 0x150
	private Animator m_itemAnimatorFurniture; // 0x158
	private Animator m_itemAnimatorOverride; // 0x160
	private Animator m_itemAnimatorReturn; // 0x168
	private Boolean m_isInited; // 0x170
	private Boolean <rendering>k__BackingField; // 0x171
	private static DelegateBridge __Hotfix0_get_rendering; // 0x0
	private static DelegateBridge __Hotfix0_set_rendering; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__RenderViewModel; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean rendering { get; set; }

	// RVA: 0x2e8bd10 VA: 0x75954a3d10
	public Boolean get_rendering() { }
	// RVA: 0x2e8bd78 VA: 0x75954a3d78
	private Void set_rendering(Boolean value) { }
	// RVA: 0x2e8bdf8 VA: 0x75954a3df8
	private Void _InitIfNot() { }
	// RVA: 0x2e8c5cc VA: 0x75954a45cc
	private IEnumerator _RenderViewModel() { }
	// RVA: 0x2e8c6a0 VA: 0x75954a46a0
	public Void Render(DropInfoGroupViewModel viewModel) { }
	// RVA: 0x2e8ce68 VA: 0x75954a4e68
	public Void .ctor() { }
}
```
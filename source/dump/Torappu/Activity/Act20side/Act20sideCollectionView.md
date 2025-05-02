# Act20sideCollectionView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Text _partNameText`

- `Text _descriptionText`

- `Text _recommendText`

- `Text _obtainMethodText`

- `Text _collectionProgressText`

- `Text _totalCollectCount`

- `UIAtlasImage _selectItemBg`

- `UIAtlasObject _itemBgAtlas`

- `Act20sideCollectionItemAdapter _adapter`

- `UIAtlasImage _unobtainedMask`

- `UIAtlasImage _itemImgHeadstock`

- `UIAtlasImage _itemImgRoof`

- `UIAtlasImage _itemImgTrunk`

- `Image _itemIconImg`

- `String m_selectedItemId`

- `Boolean m_hasInited`

- `SpriteRenderData _selectRenderData`

- `UIAtlasObject m_atlasObject`


## Methods

- `UIAtlasObject _EnsureAtlasObject()`

- `Void OnDestroy()`

- `Void _UnloadCart()`

- `SpriteRenderData _GetSpriteCart(String, CartAccessoryPos)`

- `Void set_onItemClicked(Action`1)`

- `Void _RenderSelectItem()`

- `Void _SetItemImg(SpriteRenderData, CartAccessoryType)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCollectionView : DataBinder`1, IHotfixable
{
	private static readonly String COLLECT_PROGRESS_FORMAT; // 0x0
	private Text _partNameText; // 0x20
	private Text _descriptionText; // 0x28
	private Text _recommendText; // 0x30
	private Text _obtainMethodText; // 0x38
	private Text _collectionProgressText; // 0x40
	private Text _totalCollectCount; // 0x48
	private UIAtlasImage _selectItemBg; // 0x50
	private UIAtlasObject _itemBgAtlas; // 0x58
	private Act20sideCollectionItemAdapter _adapter; // 0x60
	private UIAtlasImage _unobtainedMask; // 0x68
	private UIAtlasImage _itemImgHeadstock; // 0x70
	private UIAtlasImage _itemImgRoof; // 0x78
	private UIAtlasImage _itemImgTrunk; // 0x80
	private Image _itemIconImg; // 0x88
	private List`1 m_cachedItemModelList; // 0x90
	private String m_selectedItemId; // 0x98
	private Boolean m_hasInited; // 0xa0
	private SpriteRenderData _selectRenderData; // 0xa8
	private UIAtlasObject m_atlasObject; // 0xd0
	private Action`1 <onItemClicked>k__BackingField; // 0xd8
	private static DelegateBridge __Hotfix0__EnsureAtlasObject; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0__UnloadCart; // 0x18
	private static DelegateBridge __Hotfix0__GetSpriteCart; // 0x20
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x28
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge __Hotfix0__RenderSelectItem; // 0x40
	private static DelegateBridge __Hotfix0__SetItemImg; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private Action`1 onItemClicked { get; set; }

	// RVA: 0x32fe8c4 VA: 0x75959168c4
	private UIAtlasObject _EnsureAtlasObject() { }
	// RVA: 0x32fe9fc VA: 0x75959169fc
	private Void OnDestroy() { }
	// RVA: 0x32fea74 VA: 0x7595916a74
	private Void _UnloadCart() { }
	// RVA: 0x32febc4 VA: 0x7595916bc4
	private SpriteRenderData _GetSpriteCart(String compId, CartAccessoryPos pos) { }
	// RVA: 0x32fed30 VA: 0x7595916d30
	private Action`1 get_onItemClicked() { }
	// RVA: 0x32f6ad4 VA: 0x759590ead4
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x32feda8 VA: 0x7595916da8
	public override Void OnValueChanged(Act20sideCollectionProperty property) { }
	// RVA: 0x32ff0c0 VA: 0x75959170c0
	private Void _RenderSelectItem() { }
	// RVA: 0x32ff37c VA: 0x759591737c
	private Void _SetItemImg(SpriteRenderData spriteData, CartAccessoryType type) { }
	// RVA: 0x32fef9c VA: 0x7595916f9c
	private Void _InitIfNot() { }
	// RVA: 0x32ff520 VA: 0x7595917520
	public Void .ctor() { }
	// RVA: 0x32ff5c0 VA: 0x75959175c0
	private static Void .cctor() { }
}
```
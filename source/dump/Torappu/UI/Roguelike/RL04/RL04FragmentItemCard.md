# RL04FragmentItemCard

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Image _imgIcon`

- `Text _textName`

- `Text _textUsage`

- `Text _textDesc`

- `Text _textWeight`

- `SimpleLayoutContent _content`

- `GameObject _panelSelected`

- `UIColorGraphic _graphic`

- `UIScaler _scaler`

- `ILoadAsset <loader>k__BackingField`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `Int32 m_cachedValue`

- `String m_cachedInstId`


## Properties

- `ILoadAsset loader`

- `Graphic graphic`

- `Boolean interactable`

- `UIScaler scaler`


## Methods

- `ILoadAsset get_loader()`

- `Void set_loader(ILoadAsset)`

- `Void set_onItemClicked(Action`1)`

- `Graphic get_graphic()`

- `Boolean get_interactable()`

- `Void set_interactable(Boolean)`

- `UIScaler get_scaler()`

- `Void Render(IRoguelikeFragmentItemModel)`

- `Void EventOnItemClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentItemCard : MonoBehaviour, IHotfixable
{
	private Image _imgIcon; // 0x18
	private Text _textName; // 0x20
	private Text _textUsage; // 0x28
	private Text _textDesc; // 0x30
	private Text _textWeight; // 0x38
	private SimpleLayoutContent _content; // 0x40
	private GameObject _panelSelected; // 0x48
	private UIColorGraphic _graphic; // 0x50
	private UIScaler _scaler; // 0x58
	private ILoadAsset <loader>k__BackingField; // 0x60
	private Action`1 <onItemClicked>k__BackingField; // 0x68
	private Boolean m_hasInited; // 0x70
	private Adapter m_adapter; // 0x78
	private Int32 m_cachedValue; // 0x80
	private String m_cachedInstId; // 0x88
	private static DelegateBridge __Hotfix0_get_loader; // 0x0
	private static DelegateBridge __Hotfix0_set_loader; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_graphic; // 0x20
	private static DelegateBridge __Hotfix0_get_interactable; // 0x28
	private static DelegateBridge __Hotfix0_set_interactable; // 0x30
	private static DelegateBridge __Hotfix0_get_scaler; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge __Hotfix0_EventOnItemClicked; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private ILoadAsset loader { get; set; }
	private Action`1 onItemClicked { get; set; }
	public Graphic graphic { get; }
	public Boolean interactable { get; set; }
	public UIScaler scaler { get; }

	// RVA: 0x2b1ca8c VA: 0x7595134a8c
	private ILoadAsset get_loader() { }
	// RVA: 0x2b12f20 VA: 0x759512af20
	public Void set_loader(ILoadAsset value) { }
	// RVA: 0x2b1caf4 VA: 0x7595134af4
	private Action`1 get_onItemClicked() { }
	// RVA: 0x2b1cb5c VA: 0x7595134b5c
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x2b12fa4 VA: 0x759512afa4
	public Graphic get_graphic() { }
	// RVA: 0x2b1cbe0 VA: 0x7595134be0
	public Boolean get_interactable() { }
	// RVA: 0x2b12e40 VA: 0x759512ae40
	public Void set_interactable(Boolean value) { }
	// RVA: 0x2b1cca8 VA: 0x7595134ca8
	public UIScaler get_scaler() { }
	// RVA: 0x2b1332c VA: 0x759512b32c
	public Void Render(IRoguelikeFragmentItemModel viewModel) { }
	// RVA: 0x2b1cde0 VA: 0x7595134de0
	public Void EventOnItemClicked() { }
	// RVA: 0x2b1cd10 VA: 0x7595134d10
	private Void _InitIfNot() { }
	// RVA: 0x2b1cf14 VA: 0x7595134f14
	public Void .ctor() { }
}
```
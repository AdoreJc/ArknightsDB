# Act20sideCommonCarCompItemView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Text _itemNum`

- `GameObject _panelNum`

- `Text _itemName`

- `Image _itemIcon`

- `UIAtlasImage _rarityFrameImg`

- `UIAtlasObject _rarityFrameHolder`

- `GameObject _selectFrameImg`

- `UIAtlasImage _unobtainedMask`

- `UICommonTrackPoint _trackPoint`

- `String m_cachedId`

- `Boolean m_isInited`

- `TrackPointViewProperty m_itemNewProperty`


## Methods

- `Void set_onItemClicked(Action`1)`

- `Void _InitIfNot()`

- `Void Render(Act20sideCollectionItemViewModel, String)`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCommonCarCompItemView : MonoBehaviour, IHotfixable
{
	private const String RARITY_FRAME_NAME_FORMAT; // 0x0
	private Text _itemNum; // 0x18
	private GameObject _panelNum; // 0x20
	private Text _itemName; // 0x28
	private Image _itemIcon; // 0x30
	private UIAtlasImage _rarityFrameImg; // 0x38
	private UIAtlasObject _rarityFrameHolder; // 0x40
	private GameObject _selectFrameImg; // 0x48
	private UIAtlasImage _unobtainedMask; // 0x50
	private UICommonTrackPoint _trackPoint; // 0x58
	private String m_cachedId; // 0x60
	private Boolean m_isInited; // 0x68
	private TrackPointViewProperty m_itemNewProperty; // 0x70
	private Action`1 <onItemClicked>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onItemClicked { get; set; }

	// RVA: 0x32ff62c VA: 0x759591762c
	private Action`1 get_onItemClicked() { }
	// RVA: 0x32fe7a8 VA: 0x75959167a8
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x32ff694 VA: 0x7595917694
	private Void _InitIfNot() { }
	// RVA: 0x32fe3fc VA: 0x75959163fc
	public Void Render(Act20sideCollectionItemViewModel model, String selectItemId) { }
	// RVA: 0x32ff734 VA: 0x7595917734
	public Void OnItemClick() { }
	// RVA: 0x32ff7d4 VA: 0x75959177d4
	public Void .ctor() { }
}
```
# FunLiveUIBattlePhotoLibraryPanel

**Namespace:** `Torappu.Battle.FunLive`


## Fields

- `Text _photoCnt`

- `SimpleLayoutContent _photoList`

- `RectTransform _photoListScrollView`

- `ContentSizeFitter _contentFitter`

- `RectTransform _grid`

- `GameObject _nodataImage`

- `FunLiveUIPlugin m_plugin`

- `FunLiveUIPhotoLibraryState m_state`

- `CardListAdapter m_photoListAdapter`

- `CanvasGroup m_svCanScroll`


## Methods

- `Void Init(FunLiveUIPhotoLibraryState, List`1)`

- `Void Show()`

- `Void ClosePhotoLibraryPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.FunLive
public class FunLiveUIBattlePhotoLibraryPanel : MonoBehaviour, IHotfixable
{
	private Text _photoCnt; // 0x18
	private SimpleLayoutContent _photoList; // 0x20
	private RectTransform _photoListScrollView; // 0x28
	private ContentSizeFitter _contentFitter; // 0x30
	private RectTransform _grid; // 0x38
	private GameObject _nodataImage; // 0x40
	private FunLiveUIPlugin m_plugin; // 0x48
	private FunLiveUIPhotoLibraryState m_state; // 0x50
	private CardListAdapter m_photoListAdapter; // 0x58
	private List`1 m_photoList; // 0x60
	private CanvasGroup m_svCanScroll; // 0x68
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_ClosePhotoLibraryPanel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1c5bc20 VA: 0x7594273c20
	public Void Init(FunLiveUIPhotoLibraryState state, List`1 eventList) { }
	// RVA: 0x1c5c028 VA: 0x7594274028
	public Void Show() { }
	// RVA: 0x1c5c230 VA: 0x7594274230
	public Void ClosePhotoLibraryPanel() { }
	// RVA: 0x1c5c310 VA: 0x7594274310
	public Void .ctor() { }
}
```
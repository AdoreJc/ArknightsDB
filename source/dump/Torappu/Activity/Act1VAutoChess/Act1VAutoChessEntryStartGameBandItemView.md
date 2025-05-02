# Act1VAutoChessEntryStartGameBandItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `GameObject _normalPanel`

- `GameObject _lockedPanel`

- `Image _iconImage`

- `Image _charImage`

- `CanvasGroup _selectGroup`

- `Single _selectDuration`

- `UICommonTrackPoint _trackPoint`

- `GameObject _tutorialOnly_selectButton`

- `Boolean m_hasInited`

- `UIPageFinder m_finder`

- `ILoadAsset m_iLoadAsset`

- `FadeSwitchTween m_selectTween`

- `TrackPointViewProperty m_trackPointProperty`

- `String m_cachedId`

- `String m_cachedIconId`

- `String m_cachedCharId`


## Methods

- `Void OnSelectBandEvent()`

- `Void Render(BandViewModel, Boolean)`

- `GameObject Tutorial_GetButtonGO()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryStartGameBandItemView : MonoBehaviour, IHotfixable
{
	private GameObject _normalPanel; // 0x18
	private GameObject _lockedPanel; // 0x20
	private Image _iconImage; // 0x28
	private Image _charImage; // 0x30
	private CanvasGroup _selectGroup; // 0x38
	private Single _selectDuration; // 0x40
	private UICommonTrackPoint _trackPoint; // 0x48
	private GameObject _tutorialOnly_selectButton; // 0x50
	private Boolean m_hasInited; // 0x58
	private UIPageFinder m_finder; // 0x60
	private ILoadAsset m_iLoadAsset; // 0x70
	private FadeSwitchTween m_selectTween; // 0x78
	private TrackPointViewProperty m_trackPointProperty; // 0x80
	private String m_cachedId; // 0x88
	private String m_cachedIconId; // 0x90
	private String m_cachedCharId; // 0x98
	private static DelegateBridge __Hotfix0_OnSelectBandEvent; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_Tutorial_GetButtonGO; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x334b40c VA: 0x759596340c
	public Void OnSelectBandEvent() { }
	// RVA: 0x334af44 VA: 0x7595962f44
	public Void Render(BandViewModel model, Boolean selected) { }
	// RVA: 0x334b30c VA: 0x759596330c
	public GameObject Tutorial_GetButtonGO() { }
	// RVA: 0x334b500 VA: 0x7595963500
	private Void _InitIfNot() { }
	// RVA: 0x334b67c VA: 0x759596367c
	public Void .ctor() { }
}
```
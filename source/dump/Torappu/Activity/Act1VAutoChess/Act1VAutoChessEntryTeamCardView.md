# Act1VAutoChessEntryTeamCardView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _teamLeadAvatar`

- `Image _charTeamLogo`

- `Image _enemyTeamLogo`

- `GameObject _lockMask`

- `GameObject _selectFrame`

- `GameObject _charTeamBg`

- `GameObject _enemyTeamBg`

- `UICommonTrackPoint _trackPoint`

- `Boolean m_hasInited`

- `TrackPointViewProperty m_trackPointProperty`

- `UIPageFinder m_finder`

- `Act1VAutoChessEntryTeamCardViewModel _cachedViewModel`


## Methods

- `Void Render(String, Act1VAutoChessEntryTeamCardViewModel)`

- `Void OnTeamCardClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryTeamCardView : MonoBehaviour, IHotfixable
{
	private Image _teamLeadAvatar; // 0x18
	private Image _charTeamLogo; // 0x20
	private Image _enemyTeamLogo; // 0x28
	private GameObject _lockMask; // 0x30
	private GameObject _selectFrame; // 0x38
	private GameObject _charTeamBg; // 0x40
	private GameObject _enemyTeamBg; // 0x48
	private UICommonTrackPoint _trackPoint; // 0x50
	private Boolean m_hasInited; // 0x58
	private TrackPointViewProperty m_trackPointProperty; // 0x60
	private UIPageFinder m_finder; // 0x68
	private Act1VAutoChessEntryTeamCardViewModel _cachedViewModel; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnTeamCardClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x333ce78 VA: 0x7595954e78
	public Void Render(String actId, Act1VAutoChessEntryTeamCardViewModel teamCardViewModel) { }
	// RVA: 0x333d1ec VA: 0x75959551ec
	public Void OnTeamCardClick() { }
	// RVA: 0x333d104 VA: 0x7595955104
	private Void _InitIfNot() { }
	// RVA: 0x333d334 VA: 0x7595955334
	public Void .ctor() { }
}
```
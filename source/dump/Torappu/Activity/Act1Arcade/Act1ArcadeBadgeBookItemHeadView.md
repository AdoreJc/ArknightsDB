# Act1ArcadeBadgeBookItemHeadView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `GameObject _normalPanel`

- `Image _iconImage`

- `Image _tierIconImage`

- `Transform _effectHolder`

- `Text _scoreText`

- `Int32 _scoreMaximum`

- `String _scoreFormat`

- `UICommonTrackPoint _trackPoint`

- `UIStateFinder m_stateFinder`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`

- `TrackPointViewProperty m_trackPointProperty`

- `String m_cachedActId`

- `String m_cachedBadgeId`

- `String m_cachedTierId`

- `Int32 m_cachedTier`

- `String m_cachedShareIconId`

- `String m_cachedEffectId`

- `GameObject m_loadedEffect`


## Methods

- `Void OnClickEvent()`

- `Void Render(String, Act1ArcadeBadgeBookItemViewModel)`

- `String GetActId()`

- `Boolean GetUnlocked()`

- `String GetIconId()`

- `CrossAppShareImageModel GenerateIconImageModel()`

- `CrossAppShareImageModel GenerateTierImageModel()`

- `CrossAppShareTextModel GenerateScoreTextModel()`

- `Void _InitIfNot()`

- `Void _RenderLocked(String, String)`

- `Void _RenderUnlockedTier(String, Act1ArcadeBadgeBookItemTierViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookItemHeadView : MonoBehaviour, IHotfixable
{
	private List`1 _lockedPanels; // 0x18
	private GameObject _normalPanel; // 0x20
	private Image _iconImage; // 0x28
	private Image _tierIconImage; // 0x30
	private Transform _effectHolder; // 0x38
	private Text _scoreText; // 0x40
	private Int32 _scoreMaximum; // 0x48
	private String _scoreFormat; // 0x50
	private UICommonTrackPoint _trackPoint; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	private readonly UpdateParam m_updateParam; // 0x70
	private Boolean m_hasInited; // 0x78
	private ILoadAsset m_iLoadAsset; // 0x80
	private TrackPointViewProperty m_trackPointProperty; // 0x88
	private String m_cachedActId; // 0x90
	private String m_cachedBadgeId; // 0x98
	private String m_cachedTierId; // 0xa0
	private Int32 m_cachedTier; // 0xa8
	private String m_cachedShareIconId; // 0xb0
	private String m_cachedEffectId; // 0xb8
	private GameObject m_loadedEffect; // 0xc0
	private static DelegateBridge __Hotfix0_OnClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_GetActId; // 0x10
	private static DelegateBridge __Hotfix0_GetUnlocked; // 0x18
	private static DelegateBridge __Hotfix0_GetIconId; // 0x20
	private static DelegateBridge __Hotfix0_GenerateIconImageModel; // 0x28
	private static DelegateBridge __Hotfix0_GenerateTierImageModel; // 0x30
	private static DelegateBridge __Hotfix0_GenerateScoreTextModel; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__RenderLocked; // 0x48
	private static DelegateBridge __Hotfix0__RenderUnlockedTier; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x33f5ed0 VA: 0x7595a0ded0
	public Void OnClickEvent() { }
	// RVA: 0x33f5fd8 VA: 0x7595a0dfd8
	public Void Render(String actId, Act1ArcadeBadgeBookItemViewModel model) { }
	// RVA: 0x33f6810 VA: 0x7595a0e810
	public String GetActId() { }
	// RVA: 0x33f6878 VA: 0x7595a0e878
	public Boolean GetUnlocked() { }
	// RVA: 0x33f68e8 VA: 0x7595a0e8e8
	public String GetIconId() { }
	// RVA: 0x33f6950 VA: 0x7595a0e950
	public CrossAppShareImageModel GenerateIconImageModel() { }
	// RVA: 0x33f6a38 VA: 0x7595a0ea38
	public CrossAppShareImageModel GenerateTierImageModel() { }
	// RVA: 0x33f6b20 VA: 0x7595a0eb20
	public CrossAppShareTextModel GenerateScoreTextModel() { }
	// RVA: 0x33f6254 VA: 0x7595a0e254
	private Void _InitIfNot() { }
	// RVA: 0x33f6620 VA: 0x7595a0e620
	private Void _RenderLocked(String actId, String badgeId) { }
	// RVA: 0x33f63ac VA: 0x7595a0e3ac
	private Void _RenderUnlockedTier(String actId, Act1ArcadeBadgeBookItemTierViewModel model) { }
	// RVA: 0x33f6c08 VA: 0x7595a0ec08
	public Void .ctor() { }
}
```
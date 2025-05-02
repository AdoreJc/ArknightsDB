# StageMixStoryRetroSSView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `StageMixStoryRetroSSTagView _tagView`

- `Text _blockCountText`

- `Text _descText`

- `ScrollRect _descScrollRect`

- `GameObject _beforeReopenPart`

- `GameObject _storyPart`

- `GameObject _reopeningPart`

- `GameObject _retroPart`

- `GameObject _retroLockedPart`

- `Text _retroUnlockDescText`

- `GameObject _retroUnlockedPart`

- `GameObject _retroTrailPart`

- `Text _stageProgressText`

- `GameObject _retroTrailIncompletePart`

- `UIAtlasImage _retroTrailColorImage`

- `GameObject _trackPointPrefab`

- `Transform _trackPointHolder`

- `GameObject _retroTrailCompletePart`

- `UIStateFinder m_finder`

- `GameObject m_trackPointInstance`

- `StageStorylineSSViewModel m_cachedModel`


## Methods

- `Void ToStoriesEvent()`

- `Void ToReopenActEvent()`

- `Void ToRetroTrailEvent()`

- `Void ToZoneMapEvent()`

- `Void UnlockRetroEvent()`

- `Void ToCoinDetailEvent()`

- `Void ClearCache()`

- `Void Render(StageStorylineSSViewModel)`

- `Void _RenderRetro(StageStorylineSSViewModel)`

- `Void _RenderTrail(StageStorylineSSViewModel)`

- `Void _RenderTrackPoint(StageStorylineSSViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryRetroSSView : MonoBehaviour, IHotfixable
{
	private StageMixStoryRetroSSTagView _tagView; // 0x18
	private Text _blockCountText; // 0x20
	private Text _descText; // 0x28
	private ScrollRect _descScrollRect; // 0x30
	private GameObject _beforeReopenPart; // 0x38
	private GameObject _storyPart; // 0x40
	private GameObject _reopeningPart; // 0x48
	private GameObject _retroPart; // 0x50
	private GameObject _retroLockedPart; // 0x58
	private Text _retroUnlockDescText; // 0x60
	private GameObject _retroUnlockedPart; // 0x68
	private GameObject _retroTrailPart; // 0x70
	private Text _stageProgressText; // 0x78
	private GameObject _retroTrailIncompletePart; // 0x80
	private UIAtlasImage _retroTrailColorImage; // 0x88
	private GameObject _trackPointPrefab; // 0x90
	private Transform _trackPointHolder; // 0x98
	private GameObject _retroTrailCompletePart; // 0xa0
	private UIStateFinder m_finder; // 0xa8
	private GameObject m_trackPointInstance; // 0xb8
	private StageStorylineSSViewModel m_cachedModel; // 0xc0
	private static DelegateBridge __Hotfix0_ToStoriesEvent; // 0x0
	private static DelegateBridge __Hotfix0_ToReopenActEvent; // 0x8
	private static DelegateBridge __Hotfix0_ToRetroTrailEvent; // 0x10
	private static DelegateBridge __Hotfix0_ToZoneMapEvent; // 0x18
	private static DelegateBridge __Hotfix0_UnlockRetroEvent; // 0x20
	private static DelegateBridge __Hotfix0_ToCoinDetailEvent; // 0x28
	private static DelegateBridge __Hotfix0_ClearCache; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x38
	private static DelegateBridge __Hotfix0__RenderRetro; // 0x40
	private static DelegateBridge __Hotfix0__RenderTrail; // 0x48
	private static DelegateBridge __Hotfix0__RenderTrackPoint; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3001158 VA: 0x7595619158
	public Void ToStoriesEvent() { }
	// RVA: 0x300120c VA: 0x759561920c
	public Void ToReopenActEvent() { }
	// RVA: 0x30012c0 VA: 0x75956192c0
	public Void ToRetroTrailEvent() { }
	// RVA: 0x3001374 VA: 0x7595619374
	public Void ToZoneMapEvent() { }
	// RVA: 0x3001428 VA: 0x7595619428
	public Void UnlockRetroEvent() { }
	// RVA: 0x30014dc VA: 0x75956194dc
	public Void ToCoinDetailEvent() { }
	// RVA: 0x3001590 VA: 0x7595619590
	public Void ClearCache() { }
	// RVA: 0x3001600 VA: 0x7595619600
	public Void Render(StageStorylineSSViewModel model) { }
	// RVA: 0x30018a8 VA: 0x75956198a8
	private Void _RenderRetro(StageStorylineSSViewModel model) { }
	// RVA: 0x3001b74 VA: 0x7595619b74
	private Void _RenderTrail(StageStorylineSSViewModel model) { }
	// RVA: 0x3001a48 VA: 0x7595619a48
	private Void _RenderTrackPoint(StageStorylineSSViewModel model) { }
	// RVA: 0x3001d48 VA: 0x7595619d48
	public Void .ctor() { }
}
```
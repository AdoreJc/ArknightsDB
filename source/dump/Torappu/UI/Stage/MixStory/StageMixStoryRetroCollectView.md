# StageMixStoryRetroCollectView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `Text _descText`

- `ScrollRect _descScrollRect`

- `GameObject _retroTrailPart`

- `Transform _trackPointHolder`

- `UIStateFinder m_finder`

- `StageStorylineCollectViewModel m_cachedModel`

- `GameObject m_trackPointInstance`


## Methods

- `Void ToStoriesEvent()`

- `Void ToRetroTrailEvent()`

- `Void ClearCache()`

- `Void Render(StageStorylineCollectViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryRetroCollectView : MonoBehaviour, IHotfixable
{
	private Text _descText; // 0x18
	private ScrollRect _descScrollRect; // 0x20
	private GameObject _retroTrailPart; // 0x28
	private Transform _trackPointHolder; // 0x30
	private UIStateFinder m_finder; // 0x38
	private StageStorylineCollectViewModel m_cachedModel; // 0x48
	private GameObject m_trackPointInstance; // 0x50
	private static DelegateBridge __Hotfix0_ToStoriesEvent; // 0x0
	private static DelegateBridge __Hotfix0_ToRetroTrailEvent; // 0x8
	private static DelegateBridge __Hotfix0_ClearCache; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2ffe988 VA: 0x7595616988
	public Void ToStoriesEvent() { }
	// RVA: 0x2ffea3c VA: 0x7595616a3c
	public Void ToRetroTrailEvent() { }
	// RVA: 0x2ffeaf0 VA: 0x7595616af0
	public Void ClearCache() { }
	// RVA: 0x2ffeb60 VA: 0x7595616b60
	public Void Render(StageStorylineCollectViewModel model) { }
	// RVA: 0x2ffed4c VA: 0x7595616d4c
	public Void .ctor() { }
}
```
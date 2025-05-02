# StageMixStoryBackgroundView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `UIDynImage _backgroundImage`

- `GameObject _continuousPanel`

- `GameObject _discretePanel`

- `UIAnimationLocation _switchAnimation`

- `Ease _switchEase`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`

- `AnimationWrapper m_wrapper`

- `Single m_switchDuration`

- `String m_cachedId`

- `StorylineType m_lineType`

- `String m_displayingId`

- `Tween m_switchTween`

- `Single m_time`

- `Single m_lastPos`


## Methods

- `Void ResetView()`

- `Void Render(MixStoryZoneGroupViewModel, Boolean)`

- `Void _InitIfNot()`

- `String _GetTargetBackgroundId(MixStoryZoneGroupViewModel)`

- `StorylineType _GetLineType(MixStoryZoneGroupViewModel)`

- `Void _RenderBackground()`

- `Tween _GenerateSwitchTween()`

- `Single _GetTime()`

- `Void _SetTime(Single)`

- `Single _EvaluatePosition(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryBackgroundView : MonoBehaviour, IHotfixable
{
	private UIDynImage _backgroundImage; // 0x18
	private GameObject _continuousPanel; // 0x20
	private GameObject _discretePanel; // 0x28
	private UIAnimationLocation _switchAnimation; // 0x30
	private Ease _switchEase; // 0x40
	private Boolean m_hasInited; // 0x44
	private ILoadAsset m_iLoadAsset; // 0x48
	private AnimationWrapper m_wrapper; // 0x50
	private Single m_switchDuration; // 0x58
	private String m_cachedId; // 0x60
	private StorylineType m_lineType; // 0x68
	private String m_displayingId; // 0x70
	private Tween m_switchTween; // 0x78
	private Single m_time; // 0x80
	private Single m_lastPos; // 0x84
	private static DelegateBridge __Hotfix0_ResetView; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__GetTargetBackgroundId; // 0x18
	private static DelegateBridge __Hotfix0__GetLineType; // 0x20
	private static DelegateBridge __Hotfix0__RenderBackground; // 0x28
	private static DelegateBridge __Hotfix0__GenerateSwitchTween; // 0x30
	private static DelegateBridge __Hotfix0__GetTime; // 0x38
	private static DelegateBridge __Hotfix0__SetTime; // 0x40
	private static DelegateBridge __Hotfix0__EvaluatePosition; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2fe6654 VA: 0x75955fe654
	public Void ResetView() { }
	// RVA: 0x2fe671c VA: 0x75955fe71c
	public Void Render(MixStoryZoneGroupViewModel model, Boolean fastMode) { }
	// RVA: 0x2fe68a8 VA: 0x75955fe8a8
	private Void _InitIfNot() { }
	// RVA: 0x2fe69a8 VA: 0x75955fe9a8
	private String _GetTargetBackgroundId(MixStoryZoneGroupViewModel model) { }
	// RVA: 0x2fe6a9c VA: 0x75955fea9c
	private StorylineType _GetLineType(MixStoryZoneGroupViewModel model) { }
	// RVA: 0x2fe6b3c VA: 0x75955feb3c
	private Void _RenderBackground() { }
	// RVA: 0x2fe6c2c VA: 0x75955fec2c
	private Tween _GenerateSwitchTween() { }
	// RVA: 0x2fe6eb4 VA: 0x75955feeb4
	private Single _GetTime() { }
	// RVA: 0x2fe6f1c VA: 0x75955fef1c
	private Void _SetTime(Single time) { }
	// RVA: 0x2fe7048 VA: 0x75955ff048
	private Single _EvaluatePosition(Single time) { }
	// RVA: 0x2fe70dc VA: 0x75955ff0dc
	public Void .ctor() { }
}
```
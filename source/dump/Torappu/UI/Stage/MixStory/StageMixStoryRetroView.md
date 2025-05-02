# StageMixStoryRetroView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `StageMixStoryRetroLineView _lineView`

- `UIAnimationLocation _switchAnimation`

- `Image _bkgImage`

- `Image _titleImage`

- `GameObject _ssPart`

- `StageMixStoryRetroSSView _ssView`

- `GameObject _collectPart`

- `StageMixStoryRetroCollectView _collectView`

- `Boolean m_hasInited`

- `UIStateFinder m_finder`

- `ILoadAsset m_iLoadAsset`

- `AnimationSwitchTween m_switchTween`

- `StageStorylineStorySetViewModel m_cachedSelectedRetro`


## Methods

- `Void ResetViews()`

- `Void _InitIfNot()`

- `Void _RenderRetro()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryRetroView : DataBinder`1
{
	private StageMixStoryRetroLineView _lineView; // 0x20
	private UIAnimationLocation _switchAnimation; // 0x28
	private Image _bkgImage; // 0x38
	private Image _titleImage; // 0x40
	private GameObject _ssPart; // 0x48
	private StageMixStoryRetroSSView _ssView; // 0x50
	private GameObject _collectPart; // 0x58
	private StageMixStoryRetroCollectView _collectView; // 0x60
	private Boolean m_hasInited; // 0x68
	private UIStateFinder m_finder; // 0x70
	private ILoadAsset m_iLoadAsset; // 0x80
	private AnimationSwitchTween m_switchTween; // 0x88
	private StageStorylineStorySetViewModel m_cachedSelectedRetro; // 0x90
	private static DelegateBridge __Hotfix0_ResetViews; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__RenderRetro; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3001db8 VA: 0x7595619db8
	public Void ResetViews() { }
	// RVA: 0x3001f40 VA: 0x7595619f40
	public override Void OnValueChanged(ZoneGroupViewProperty property) { }
	// RVA: 0x3001e40 VA: 0x7595619e40
	private Void _InitIfNot() { }
	// RVA: 0x30020c0 VA: 0x759561a0c0
	private Void _RenderRetro() { }
	// RVA: 0x3002318 VA: 0x759561a318
	public Void .ctor() { }
}
```
# HandBookV2MapForceCardView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `GameObject _clickAreaGo`

- `Text _textForceName`

- `Text _textForceCode`

- `Image _imgCollect`

- `Image _imgCharCount`

- `Text _textCharCount`

- `UICommonTrackPoint _updatedTrackPoint`

- `AnimationWrapper _animWrapper`

- `TrackPointViewProperty m_updatedTrackPointProperty`

- `HandBookV2ForceViewModel m_forceViewModel`

- `HandbookTeamData m_forceData`

- `UIStringEvent <onCardClick>k__BackingField`


## Properties

- `UIStringEvent onCardClick`


## Methods

- `UIStringEvent get_onCardClick()`

- `Void set_onCardClick(UIStringEvent)`

- `Void OnCardClick()`

- `Void PlayFadeOut(Boolean)`

- `Void Render(HandBookV2ForceViewModel)`

- `Void _UpdateTrackPoint(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapForceCardView : MonoBehaviour, IHotfixable
{
	private GameObject _clickAreaGo; // 0x18
	private Text _textForceName; // 0x20
	private Text _textForceCode; // 0x28
	private Image _imgCollect; // 0x30
	private Image _imgCharCount; // 0x38
	private Text _textCharCount; // 0x40
	private UICommonTrackPoint _updatedTrackPoint; // 0x48
	private AnimationWrapper _animWrapper; // 0x50
	private const String CARD_FADE_OUT; // 0x0
	private TrackPointViewProperty m_updatedTrackPointProperty; // 0x58
	private HandBookV2ForceViewModel m_forceViewModel; // 0x60
	private HandbookTeamData m_forceData; // 0x68
	private UIStringEvent <onCardClick>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onCardClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onCardClick; // 0x8
	private static DelegateBridge __Hotfix0_OnCardClick; // 0x10
	private static DelegateBridge __Hotfix0_PlayFadeOut; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__UpdateTrackPoint; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private UIStringEvent onCardClick { get; set; }

	// RVA: 0x2ed14c0 VA: 0x75954e94c0
	private UIStringEvent get_onCardClick() { }
	// RVA: 0x2ed1528 VA: 0x75954e9528
	public Void set_onCardClick(UIStringEvent value) { }
	// RVA: 0x2ed15ac VA: 0x75954e95ac
	public Void OnCardClick() { }
	// RVA: 0x2ed16c8 VA: 0x75954e96c8
	public Void PlayFadeOut(Boolean isFadeOut) { }
	// RVA: 0x2ed1818 VA: 0x75954e9818
	public Void Render(HandBookV2ForceViewModel viewModel) { }
	// RVA: 0x2ed1ca0 VA: 0x75954e9ca0
	private Void _UpdateTrackPoint(List`1 charIdList) { }
	// RVA: 0x2ed1d68 VA: 0x75954e9d68
	public Void .ctor() { }
}
```
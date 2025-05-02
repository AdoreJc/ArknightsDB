# ActMultiV3TrainingRoomModeItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _pnlLocked`

- `Image _imgModeIconLocked`

- `Text _textLockedDesc`

- `UIAnimationLocation _animSelected`

- `Image _imgModeIcon`

- `Text _textModeName`

- `UIAtlasImage _imgSelected`

- `UIAtlasImage _imgSelectedGlow`

- `Image _imgModeIconSelected`

- `CanvasGroup _canvasGroup`

- `Boolean m_inited`

- `UISwitchTween m_selectedTween`

- `Int32 m_cachedInitSeq`

- `ActMultiV3MapModeType m_cachedModeType`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void Render(ActMultiV3TrainingRoomModeViewModel, ActMultiV3TrainingRoomViewModel)`

- `Void OnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3TrainingRoomModeItemView : MonoBehaviour, IHotfixable
{
	private GameObject _pnlLocked; // 0x18
	private Image _imgModeIconLocked; // 0x20
	private Text _textLockedDesc; // 0x28
	private UIAnimationLocation _animSelected; // 0x30
	private Image _imgModeIcon; // 0x40
	private Text _textModeName; // 0x48
	private UIAtlasImage _imgSelected; // 0x50
	private UIAtlasImage _imgSelectedGlow; // 0x58
	private Image _imgModeIconSelected; // 0x60
	private CanvasGroup _canvasGroup; // 0x68
	private Boolean m_inited; // 0x70
	private UISwitchTween m_selectedTween; // 0x78
	private Int32 m_cachedInitSeq; // 0x80
	private ActMultiV3MapModeType m_cachedModeType; // 0x84
	private UIStateFinder m_stateFinder; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnBtnClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3152884 VA: 0x759576a884
	private Void _InitIfNot() { }
	// RVA: 0x3152974 VA: 0x759576a974
	public Void Render(ActMultiV3TrainingRoomModeViewModel viewModel, ActMultiV3TrainingRoomViewModel roomViewModel) { }
	// RVA: 0x3152d50 VA: 0x759576ad50
	public Void OnBtnClicked() { }
	// RVA: 0x3152e58 VA: 0x759576ae58
	public Void .ctor() { }
}
```
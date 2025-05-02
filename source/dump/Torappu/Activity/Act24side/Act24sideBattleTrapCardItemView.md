# Act24sideBattleTrapCardItemView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Image _imgCardBg`

- `UIAnimationLocation _newUnlockAnim`

- `GameObject _objLockPart`

- `Text _txtLockDesc`

- `GameObject _objUnlockPart`

- `Image _imgIconDec`

- `GameObject _objNewUnlockTag`

- `Image _imgIcon`

- `Text _txtToolTitle`

- `Image _imgIconSmall`

- `Text _txtToolDesc`

- `UIAnimationLocation _selectAnim`

- `AnimationSwitchTween m_selectSwitchTween`

- `Boolean m_hasInited`

- `Boolean m_isSelectAnimFastMode`

- `Boolean m_isNewUnlockAnimPlayed`

- `String m_cachedTrapId`

- `UnlockState m_cachedUnlockState`

- `UIStateFinder m_finder`

- `Tween m_cachedNewUnlockTween`


## Methods

- `Void Render(Act24sideBattleTrapItemViewModel)`

- `Void OnDestroy()`

- `Void _InitIfNot()`

- `Void _PlaySelectAnim(Boolean, Boolean)`

- `Void _ResetNewUnlockTween()`

- `Void _PlayNewUnlockAnim()`

- `Void OnCardClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleTrapCardItemView : MonoBehaviour, IHotfixable
{
	private Image _imgCardBg; // 0x18
	private UIAnimationLocation _newUnlockAnim; // 0x20
	private GameObject _objLockPart; // 0x30
	private Text _txtLockDesc; // 0x38
	private GameObject _objUnlockPart; // 0x40
	private Image _imgIconDec; // 0x48
	private GameObject _objNewUnlockTag; // 0x50
	private Image _imgIcon; // 0x58
	private Text _txtToolTitle; // 0x60
	private Image _imgIconSmall; // 0x68
	private Text _txtToolDesc; // 0x70
	private UIAnimationLocation _selectAnim; // 0x78
	private AnimationSwitchTween m_selectSwitchTween; // 0x88
	private Boolean m_hasInited; // 0x90
	private Boolean m_isSelectAnimFastMode; // 0x91
	private Boolean m_isNewUnlockAnimPlayed; // 0x92
	private String m_cachedTrapId; // 0x98
	private UnlockState m_cachedUnlockState; // 0xa0
	private UIStateFinder m_finder; // 0xa8
	private Tween m_cachedNewUnlockTween; // 0xb8
	private const Single NEW_UNLOCK_ANIM_DELAY; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__PlaySelectAnim; // 0x18
	private static DelegateBridge __Hotfix0__ResetNewUnlockTween; // 0x20
	private static DelegateBridge __Hotfix0__PlayNewUnlockAnim; // 0x28
	private static DelegateBridge __Hotfix0_OnCardClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3293464 VA: 0x75958ab464
	public Void Render(Act24sideBattleTrapItemViewModel model) { }
	// RVA: 0x3293c9c VA: 0x75958abc9c
	public Void OnDestroy() { }
	// RVA: 0x32937fc VA: 0x75958ab7fc
	private Void _InitIfNot() { }
	// RVA: 0x3293bf4 VA: 0x75958abbf4
	private Void _PlaySelectAnim(Boolean isSelect, Boolean isFastMode) { }
	// RVA: 0x3293d04 VA: 0x75958abd04
	private Void _ResetNewUnlockTween() { }
	// RVA: 0x3293a90 VA: 0x75958aba90
	private Void _PlayNewUnlockAnim() { }
	// RVA: 0x3293da4 VA: 0x75958abda4
	public Void OnCardClick() { }
	// RVA: 0x3293ebc VA: 0x75958abebc
	public Void .ctor() { }
}
```
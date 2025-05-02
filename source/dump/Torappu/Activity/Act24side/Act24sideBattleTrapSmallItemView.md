# Act24sideBattleTrapSmallItemView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Image _imgSelectIcon`

- `Image _imgUnselectIcon`

- `GameObject _objLock`

- `UIAnimationLocation _selectAnim`

- `AnimationSwitchTween m_selectSwitchTween`

- `Boolean m_hasInited`

- `Boolean m_isSelectAnimFastMode`

- `String m_cachedTrapId`

- `UIStateFinder m_finder`

- `UnlockState m_cachedUnlockState`


## Methods

- `Void Render(Act24sideBattleTrapItemViewModel)`

- `Void _InitIfNot()`

- `Void _PlaySelectAnim(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleTrapSmallItemView : MonoBehaviour, IHotfixable
{
	private Image _imgSelectIcon; // 0x18
	private Image _imgUnselectIcon; // 0x20
	private GameObject _objLock; // 0x28
	private UIAnimationLocation _selectAnim; // 0x30
	private AnimationSwitchTween m_selectSwitchTween; // 0x40
	private Boolean m_hasInited; // 0x48
	private Boolean m_isSelectAnimFastMode; // 0x49
	private String m_cachedTrapId; // 0x50
	private UIStateFinder m_finder; // 0x58
	private UnlockState m_cachedUnlockState; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__PlaySelectAnim; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3293f9c VA: 0x75958abf9c
	public Void Render(Act24sideBattleTrapItemViewModel model) { }
	// RVA: 0x3294188 VA: 0x75958ac188
	private Void _InitIfNot() { }
	// RVA: 0x329427c VA: 0x75958ac27c
	private Void _PlaySelectAnim(Boolean isSelect, Boolean isFastMode) { }
	// RVA: 0x3294324 VA: 0x75958ac324
	public Void .ctor() { }
}
```
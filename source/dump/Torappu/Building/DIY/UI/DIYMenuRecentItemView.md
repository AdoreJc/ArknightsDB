# DIYMenuRecentItemView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Text _textCount`

- `Text _textOldCount`

- `GameObject _pnlNone`

- `GameObject _pnlRecent`

- `GameObject _pnlTrackpoint`

- `UIAnimationLocation _animSwitch`

- `Boolean m_cachedEmpty`


## Methods

- `Void Setup(List`1, Int32, String, Boolean, Boolean)`

- `Tween GenerateShowTween()`

- `Tween GenerateHideTween()`

- `Void ShowImmediately()`

- `Void HideImmediately()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYMenuRecentItemView : MonoBehaviour, IHotfixable
{
	private const Single ANIM_DURATION; // 0x0
	private const Single ANIM_SIZE_DELTA_DURATION; // 0x0
	private const Int32 WIDTH_EMPTY; // 0x0
	private const Int32 WIDTH_NORMAL; // 0x0
	private const Single HEIGHT_NORMAL; // 0x0
	private DIYMenuRecentItem[] _showIcons; // 0x18
	private Text _textCount; // 0x20
	private Text _textOldCount; // 0x28
	private GameObject _pnlNone; // 0x30
	private GameObject _pnlRecent; // 0x38
	private GameObject _pnlTrackpoint; // 0x40
	private UIAnimationLocation _animSwitch; // 0x48
	private Boolean m_cachedEmpty; // 0x58
	private static DelegateBridge __Hotfix0_Setup; // 0x0
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x8
	private static DelegateBridge __Hotfix0_GenerateHideTween; // 0x10
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x18
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3822378 VA: 0x7595e3a378
	public Void Setup(List`1 itemDatas, Int32 count, String oldText, Boolean showTrackpoint, Boolean isFurniture) { }
	// RVA: 0x38226c4 VA: 0x7595e3a6c4
	public Tween GenerateShowTween() { }
	// RVA: 0x3822874 VA: 0x7595e3a874
	public Tween GenerateHideTween() { }
	// RVA: 0x3822a14 VA: 0x7595e3aa14
	public Void ShowImmediately() { }
	// RVA: 0x3822ac8 VA: 0x7595e3aac8
	public Void HideImmediately() { }
	// RVA: 0x3822b68 VA: 0x7595e3ab68
	public Void .ctor() { }
}
```
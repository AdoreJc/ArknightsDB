# Act1VAutoChessHUDHpItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `UIAnimationLocation _emptyAnim`

- `Image _dangerFill`

- `Image _emptyFill`

- `GameObject _panelEnable`

- `GameObject _panelDisable`

- `Boolean m_isInited`

- `Single m_cachedPercent`

- `AnimationSwitchTween m_emptyTween`


## Methods

- `Void Render(Single, Boolean, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDHpItemView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _emptyAnim; // 0x18
	private Image _dangerFill; // 0x28
	private Image _emptyFill; // 0x30
	private GameObject _panelEnable; // 0x38
	private GameObject _panelDisable; // 0x40
	private Boolean m_isInited; // 0x48
	private Single m_cachedPercent; // 0x4c
	private AnimationSwitchTween m_emptyTween; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3378a98 VA: 0x7595990a98
	public Void Render(Single percent, Boolean isDisable, Boolean isFastMode) { }
	// RVA: 0x3378c54 VA: 0x7595990c54
	private Void _InitIfNot() { }
	// RVA: 0x3378d44 VA: 0x7595990d44
	public Void .ctor() { }
}
```
# Act25sideResearchMissionCompleteState

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Image _icon`

- `Text _areaName`

- `Text _progress`

- `GameObject _max`

- `UIAnimationLocation _enterAnim`

- `Boolean m_isInited`

- `Act25sideResearchMissionCompleteStateBean m_stateBean`

- `String m_cachedAudSig`

- `Tween m_cachedTween`


## Methods

- `Void _InitIfNot()`

- `Void _PlayAnim()`

- `Void _Render()`

- `Sprite _LoadIcon(String)`

- `Void OnDismiss()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchMissionCompleteState : PopupFloatState, IHotfixable
{
	private Image _icon; // 0x70
	private Text _areaName; // 0x78
	private Text _progress; // 0x80
	private GameObject _max; // 0x88
	private UIAnimationLocation _enterAnim; // 0x90
	private Boolean m_isInited; // 0xa0
	private Act25sideResearchMissionCompleteStateBean m_stateBean; // 0xa8
	private String m_cachedAudSig; // 0xb0
	private Tween m_cachedTween; // 0xb8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge __Hotfix0__LoadIcon; // 0x28
	private static DelegateBridge __Hotfix0_OnDismiss; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3279e74 VA: 0x7595891e74
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3279edc VA: 0x7595891edc
	protected override Void OnEnter() { }
	// RVA: 0x3279f60 VA: 0x7595891f60
	private Void _InitIfNot() { }
	// RVA: 0x327a2ec VA: 0x75958922ec
	private Void _PlayAnim() { }
	// RVA: 0x327a058 VA: 0x7595892058
	private Void _Render() { }
	// RVA: 0x327a4ac VA: 0x75958924ac
	private Sprite _LoadIcon(String iconId) { }
	// RVA: 0x327a584 VA: 0x7595892584
	public Void OnDismiss() { }
	// RVA: 0x327a6e4 VA: 0x75958926e4
	public Void .ctor() { }
	// RVA: 0x327a800 VA: 0x7595892800
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```
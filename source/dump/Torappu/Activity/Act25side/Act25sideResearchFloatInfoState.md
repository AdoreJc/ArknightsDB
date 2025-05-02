# Act25sideResearchFloatInfoState

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `GameObject _panelToken`

- `GameObject _panelRule`

- `Text _ruleTitle`

- `Text _ruleDesc`

- `Text _tokenTitle`

- `Text _tokenDesc`

- `Boolean m_isInited`

- `Act25sideResearchFloatInfoStateBean m_cachedBean`


## Methods

- `Void _RenderInfo()`

- `Void _RenderHarvestRule(Act25SideData)`

- `Void _RenderTokenInfo(Act25SideData)`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchFloatInfoState : PopupFloatState
{
	private GameObject _panelToken; // 0x70
	private GameObject _panelRule; // 0x78
	private Text _ruleTitle; // 0x80
	private Text _ruleDesc; // 0x88
	private Text _tokenTitle; // 0x90
	private Text _tokenDesc; // 0x98
	private Boolean m_isInited; // 0xa0
	private Act25sideResearchFloatInfoStateBean m_cachedBean; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__RenderInfo; // 0x8
	private static DelegateBridge __Hotfix0__RenderHarvestRule; // 0x10
	private static DelegateBridge __Hotfix0__RenderTokenInfo; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x32798c0 VA: 0x75958918c0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3279928 VA: 0x7595891928
	private Void _RenderInfo() { }
	// RVA: 0x3279a04 VA: 0x7595891a04
	private Void _RenderHarvestRule(Act25SideData actData) { }
	// RVA: 0x3279af0 VA: 0x7595891af0
	private Void _RenderTokenInfo(Act25SideData actData) { }
	// RVA: 0x3279bdc VA: 0x7595891bdc
	private Void _InitIfNot() { }
	// RVA: 0x3279cd4 VA: 0x7595891cd4
	protected override Void OnEnter() { }
	// RVA: 0x3279d50 VA: 0x7595891d50
	public Void .ctor() { }
	// RVA: 0x3279e6c VA: 0x7595891e6c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```
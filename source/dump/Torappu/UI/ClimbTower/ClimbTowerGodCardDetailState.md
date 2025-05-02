# ClimbTowerGodCardDetailState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerEntryGodCardDetailView _detailView`

- `ClimbTowerEntryGodCardDetailButtonGroupView _buttonGroupView`

- `UIAnimationLocation _entryAnim`

- `UIAnimationLocation _refreshAnim`

- `RectTransform _topContainer`

- `Tween m_cachedEntryTween`

- `Tween m_cachedRefreshTween`

- `ClimbTowerGodCardDetailStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnCardClicked(String)`

- `Void <_InitIfNot>b__13_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerGodCardDetailState : PopupFadeState, IHotfixable
{
	private ClimbTowerEntryGodCardDetailView _detailView; // 0x70
	private ClimbTowerEntryGodCardDetailButtonGroupView _buttonGroupView; // 0x78
	private UIAnimationLocation _entryAnim; // 0x80
	private UIAnimationLocation _refreshAnim; // 0x90
	private RectTransform _topContainer; // 0xa0
	private Tween m_cachedEntryTween; // 0xa8
	private Tween m_cachedRefreshTween; // 0xb0
	private ClimbTowerGodCardDetailStateBean m_stateBean; // 0xb8
	private Boolean m_hasInited; // 0xc0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnCardClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2ca2668 VA: 0x75952ba668
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ca26d0 VA: 0x75952ba6d0
	protected override Void OnEnter() { }
	// RVA: 0x2ca29c0 VA: 0x75952ba9c0
	protected override Void OnResume() { }
	// RVA: 0x2ca2800 VA: 0x75952ba800
	private Void _InitIfNot() { }
	// RVA: 0x2ca2ae4 VA: 0x75952baae4
	private Void _OnCardClicked(String cardId) { }
	// RVA: 0x2ca2c94 VA: 0x75952bac94
	public Void .ctor() { }
	// RVA: 0x2ca2df0 VA: 0x75952badf0
	private Void <_InitIfNot>b__13_0() { }
	// RVA: 0x2ca2ed0 VA: 0x75952baed0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ca2ed8 VA: 0x75952baed8
	private Void <>xLuaBaseProxy_OnResume() { }
}
```
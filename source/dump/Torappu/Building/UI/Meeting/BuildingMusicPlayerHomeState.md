# BuildingMusicPlayerHomeState

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `BuildingUIRoomTitle _roomTitle`

- `BuildingMusicPlayerView _view`

- `UIAnimationLocation _animEntry`

- `UIAnimationLocation _animOut`

- `BuildingMusicPlayerPage m_page`

- `BuildingMusicPlayerStateBean m_stateBean`

- `Tween m_entryTween`

- `Tween m_outTween`

- `Boolean m_firstResume`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnChangeSortOrder()`

- `Void _OnSetBgmBtnClicked()`

- `Void _OnMusicItemClicked(MusicPlayInfo)`

- `Void _InitTopMenu()`

- `Void _InitRoomTitle()`

- `Void _OnClickClose()`

- `IEnumerator _PlayEntryAnim()`

- `Void <_InitTopMenu>b__19_0(GameObject)`

- `Void <_OnClickClose>b__21_0()`

- `Boolean <_PlayEntryAnim>b__22_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMusicPlayerHomeState : State, IValueMsgReceiver
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x50
	private BuildingUIRoomTitle _roomTitle; // 0x58
	private BuildingMusicPlayerView _view; // 0x60
	private UIAnimationLocation _animEntry; // 0x68
	private UIAnimationLocation _animOut; // 0x78
	public const Int32 MSG_MUSIC_ITEM_CLICK; // 0x0
	public const Int32 MSG_SET_MUSIC_CLICK; // 0x0
	private BuildingMusicPlayerPage m_page; // 0x88
	private BuildingMusicPlayerStateBean m_stateBean; // 0x90
	private Tween m_entryTween; // 0x98
	private Tween m_outTween; // 0xa0
	private Boolean m_firstResume; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__OnChangeSortOrder; // 0x20
	private static DelegateBridge __Hotfix0__OnSetBgmBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnMusicItemClicked; // 0x30
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x38
	private static DelegateBridge __Hotfix0__InitRoomTitle; // 0x40
	private static DelegateBridge __Hotfix0__OnClickClose; // 0x48
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3de9ca8 VA: 0x7596401ca8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3de9d10 VA: 0x7596401d10
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3dea284 VA: 0x7596402284
	protected override Void OnEnter() { }
	// RVA: 0x3dea874 VA: 0x7596402874
	protected override Void OnResume() { }
	// RVA: 0x3deaa24 VA: 0x7596402a24
	private Void _OnChangeSortOrder() { }
	// RVA: 0x3de9fa0 VA: 0x7596401fa0
	private Void _OnSetBgmBtnClicked() { }
	// RVA: 0x3de9e14 VA: 0x7596401e14
	private Void _OnMusicItemClicked(MusicPlayInfo musicPlayInfo) { }
	// RVA: 0x3dea614 VA: 0x7596402614
	private Void _InitTopMenu() { }
	// RVA: 0x3dea6d8 VA: 0x75964026d8
	private Void _InitRoomTitle() { }
	// RVA: 0x3deab68 VA: 0x7596402b68
	private Void _OnClickClose() { }
	// RVA: 0x3dea568 VA: 0x7596402568
	private IEnumerator _PlayEntryAnim() { }
	// RVA: 0x3deaf58 VA: 0x7596402f58
	public Void .ctor() { }
	// RVA: 0x3deb0b0 VA: 0x75964030b0
	private Void <_InitTopMenu>b__19_0(GameObject obj) { }
	// RVA: 0x3deb174 VA: 0x7596403174
	private Void <_OnClickClose>b__21_0() { }
	// RVA: 0x3deb1e8 VA: 0x75964031e8
	private Boolean <_PlayEntryAnim>b__22_0() { }
	// RVA: 0x3deb1fc VA: 0x75964031fc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3deb204 VA: 0x7596403204
	private Void <>xLuaBaseProxy_OnResume() { }
}
```
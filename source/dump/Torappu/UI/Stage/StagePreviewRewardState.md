# StagePreviewRewardState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageRewardStateBean _stateBean`

- `StagePreviewRewardView _view`

- `TopMenuDynamicPrefabInstHolder _topMenuContainer`

- `StageRewardDetailPluginHandler _pluginHandler`

- `RectTransform _pluginContainer`

- `Image _imgBgTint`

- `Color _defaultBgTint`

- `Boolean m_isInited`

- `GameObject _globalEventMask`


## Methods

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__8_0(GameObject)`

- `Void <_InitIfNot>b__8_1()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewRewardState : PopupFloatState
{
	private StageRewardStateBean _stateBean; // 0x70
	private StagePreviewRewardView _view; // 0x78
	private TopMenuDynamicPrefabInstHolder _topMenuContainer; // 0x80
	private StageRewardDetailPluginHandler _pluginHandler; // 0x88
	private RectTransform _pluginContainer; // 0x90
	private Image _imgBgTint; // 0x98
	private Color _defaultBgTint; // 0xa0
	private Boolean m_isInited; // 0xb0
	protected GameObject _globalEventMask; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnPause; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2f6a6e0 VA: 0x75955826e0
	private Void _InitIfNot() { }
	// RVA: 0x2f6a7c0 VA: 0x75955827c0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f6a828 VA: 0x7595582828
	protected override Void OnPause() { }
	// RVA: 0x2f6a8f4 VA: 0x75955828f4
	protected override Void OnResume() { }
	// RVA: 0x2f6a9c0 VA: 0x75955829c0
	protected override Void OnEnter() { }
	// RVA: 0x2f6acf4 VA: 0x7595582cf4
	public Void .ctor() { }
	// RVA: 0x2f6ad64 VA: 0x7595582d64
	private Void <_InitIfNot>b__8_0(GameObject gameObj) { }
	// RVA: 0x2f6ae60 VA: 0x7595582e60
	private Void <_InitIfNot>b__8_1() { }
	// RVA: 0x2f6ae70 VA: 0x7595582e70
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x2f6ae78 VA: 0x7595582e78
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2f6ae80 VA: 0x7595582e80
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```
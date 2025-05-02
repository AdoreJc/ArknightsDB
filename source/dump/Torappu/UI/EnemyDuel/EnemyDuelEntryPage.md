# EnemyDuelEntryPage

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `CanvasGroup _root`

- `PageCameraRenderTextureHolder _rtHolder`

- `RectTransform _dialogContainer`

- `RectTransform _spineContainer`

- `UICompDialogMgr m_diaglogMgr`

- `ActHandler m_actHandler`


## Properties

- `UICompDialogMgr dialogMgr`

- `RectTransform spineContainer`

- `PageCameraRenderTextureHolder rtHolder`


## Methods

- `UICompDialogMgr get_dialogMgr()`

- `RectTransform get_spineContainer()`

- `PageCameraRenderTextureHolder get_rtHolder()`

- `ActHandler _EnsureActHandler()`

- `Void <>xLuaBaseProxy_SetPageShow(Boolean)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEntryPage : ActivityEntryPage
{
	private CanvasGroup _root; // 0x100
	private PageCameraRenderTextureHolder _rtHolder; // 0x108
	private RectTransform _dialogContainer; // 0x110
	private RectTransform _spineContainer; // 0x118
	private UICompDialogMgr m_diaglogMgr; // 0x120
	private ActHandler m_actHandler; // 0x128
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x0
	private static DelegateBridge __Hotfix0_get_spineContainer; // 0x8
	private static DelegateBridge __Hotfix0_get_rtHolder; // 0x10
	private static DelegateBridge __Hotfix0__EnsureActHandler; // 0x18
	private static DelegateBridge __Hotfix0_GetActivityHandler; // 0x20
	private static DelegateBridge __Hotfix0_SetPageShow; // 0x28
	private static DelegateBridge __Hotfix0_OnCreate; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public UICompDialogMgr dialogMgr { get; }
	public RectTransform spineContainer { get; }
	public PageCameraRenderTextureHolder rtHolder { get; }

	// RVA: 0x2945ef8 VA: 0x7594f5def8
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x2945f60 VA: 0x7594f5df60
	public RectTransform get_spineContainer() { }
	// RVA: 0x2945fc8 VA: 0x7594f5dfc8
	public PageCameraRenderTextureHolder get_rtHolder() { }
	// RVA: 0x2946030 VA: 0x7594f5e030
	private ActHandler _EnsureActHandler() { }
	// RVA: 0x2946178 VA: 0x7594f5e178
	public override IPageActHandler GetActivityHandler() { }
	// RVA: 0x29461e0 VA: 0x7594f5e1e0
	protected override Void SetPageShow(Boolean isShow) { }
	// RVA: 0x2946278 VA: 0x7594f5e278
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2946334 VA: 0x7594f5e334
	public Void .ctor() { }
	// RVA: 0x29463a4 VA: 0x7594f5e3a4
	private Void <>xLuaBaseProxy_SetPageShow(Boolean P0) { }
	// RVA: 0x29463b0 VA: 0x7594f5e3b0
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```
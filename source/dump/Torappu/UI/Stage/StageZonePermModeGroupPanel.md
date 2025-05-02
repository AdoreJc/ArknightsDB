# StageZonePermModeGroupPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _panelRoguelike`

- `Image _imgRoguelike`

- `GameObject _panelOnBattle`

- `Text _textOnBattleName`

- `GameObject _panelRoguelikeDLCUpdate`

- `GameObject _panelRoguelikeReviewUpdate`

- `GameObject _panelSandboxClosed`

- `GameObject _panelSandbox`

- `GameObject _panelSandboxUpdate`

- `Image _imgSandbox`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`


## Methods

- `Void EventOnRoguelikeClicked()`

- `Void EventOnRoguelikeEntryClicked()`

- `Void EventOnSandboxHomeClicked()`

- `Void _InitIfNot()`

- `Void _RenderRoguelike(PermModeZoneGroupViewModel, ILoadAsset)`

- `Void _RenderSandbox(PermModeZoneGroupViewModel, ILoadAsset)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnDataUpdated(ZoneGroupViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZonePermModeGroupPanel : StageZoneGroupPanel, IHotfixable
{
	private GameObject _panelRoguelike; // 0x60
	private Image _imgRoguelike; // 0x68
	private GameObject _panelOnBattle; // 0x70
	private Text _textOnBattleName; // 0x78
	private MaskableGraphic[] _imgOnBattle; // 0x80
	private GameObject _panelRoguelikeDLCUpdate; // 0x88
	private GameObject _panelRoguelikeReviewUpdate; // 0x90
	private GameObject _panelSandboxClosed; // 0x98
	private GameObject _panelSandbox; // 0xa0
	private GameObject _panelSandboxUpdate; // 0xa8
	private Image _imgSandbox; // 0xb0
	private Boolean m_hasInited; // 0xb8
	private UIStateFinder m_stateFinder; // 0xc0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x8
	private static DelegateBridge __Hotfix0_EventOnRoguelikeClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnRoguelikeEntryClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnSandboxHomeClicked; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__RenderRoguelike; // 0x30
	private static DelegateBridge __Hotfix0__RenderSandbox; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2fbbb8c VA: 0x75955d3b8c
	protected override Void OnEnter() { }
	// RVA: 0x2fbbbfc VA: 0x75955d3bfc
	protected override Void OnDataUpdated(ZoneGroupViewProperty prop) { }
	// RVA: 0x2fbc1b4 VA: 0x75955d41b4
	public Void EventOnRoguelikeClicked() { }
	// RVA: 0x2fbc258 VA: 0x75955d4258
	public Void EventOnRoguelikeEntryClicked() { }
	// RVA: 0x2fbc2fc VA: 0x75955d42fc
	public Void EventOnSandboxHomeClicked() { }
	// RVA: 0x2fbbd28 VA: 0x75955d3d28
	private Void _InitIfNot() { }
	// RVA: 0x2fbbd9c VA: 0x75955d3d9c
	private Void _RenderRoguelike(PermModeZoneGroupViewModel model, ILoadAsset loader) { }
	// RVA: 0x2fbc030 VA: 0x75955d4030
	private Void _RenderSandbox(PermModeZoneGroupViewModel model, ILoadAsset loader) { }
	// RVA: 0x2fbc3a0 VA: 0x75955d43a0
	public Void .ctor() { }
	// RVA: 0x2fbc40c VA: 0x75955d440c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2fbc410 VA: 0x75955d4410
	private Void <>xLuaBaseProxy_OnDataUpdated(ZoneGroupViewProperty P0) { }
}
```
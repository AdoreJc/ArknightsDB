# BuildingStationSelectBuffUnlockFloat

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `CanvasGroup _alphaHandler`

- `RectTransform _panelContent`

- `Text _textUnlockCond`

- `FadeSwitchTween m_fadeTween`


## Properties

- `FadeSwitchTween fadeTween`


## Methods

- `FadeSwitchTween get_fadeTween()`

- `Void _Show(BuildingBuffDescStruct, RectTransform)`

- `Void EventOnBlankClicked()`

- `Void <>xLuaBaseProxy_OnStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectBuffUnlockFloat : PageSingleComponent
{
	private CanvasGroup _alphaHandler; // 0x20
	private RectTransform _panelContent; // 0x28
	private Text _textUnlockCond; // 0x30
	private FadeSwitchTween m_fadeTween; // 0x38
	private static DelegateBridge __Hotfix0_get_fadeTween; // 0x0
	private static DelegateBridge __Hotfix0_OnStart; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0__Show; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBlankClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected FadeSwitchTween fadeTween { get; }

	// RVA: 0x3d991b8 VA: 0x75963b11b8
	protected FadeSwitchTween get_fadeTween() { }
	// RVA: 0x3d99280 VA: 0x75963b1280
	protected override Void OnStart() { }
	// RVA: 0x3d98868 VA: 0x75963b0868
	public static Void Show(Interface pageInterface, BuildingBuffDescStruct buffStruct, RectTransform buttonAnchor) { }
	// RVA: 0x3d99308 VA: 0x75963b1308
	private Void _Show(BuildingBuffDescStruct buffStruct, RectTransform buttonAnchor) { }
	// RVA: 0x3d994b8 VA: 0x75963b14b8
	public Void EventOnBlankClicked() { }
	// RVA: 0x3d99530 VA: 0x75963b1530
	public Void .ctor() { }
	// RVA: 0x3d995a0 VA: 0x75963b15a0
	private Void <>xLuaBaseProxy_OnStart() { }
}
```
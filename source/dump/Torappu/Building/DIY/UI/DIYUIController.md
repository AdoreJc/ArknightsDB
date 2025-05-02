# DIYUIController

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `GameObject _comfortPanel`

- `BuildingUIRoomTitle _roomTitle`

- `DIYComfortDetailView _comfortDetailView`

- `GameObject _shopBtnPanel`

- `PrefabInstHolder _shopPanelHolder`

- `DIYFurnitureDetailPanel _furnitureDetailPanel`

- `DIYCameraSwitchToggle _cameraSwitchToggle`

- `Int32 _viewportBottomMargin`

- `StateEngine _bottomStateEngine`

- `DIYListViewStateBean _stateBean`

- `GameObject _backButton`

- `UIHandler m_pageHandler`

- `StateBeanHandler m_stateBeanHandler`

- `DIYShopPanel m_shopPanel`

- `Boolean m_isInited`

- `Boolean m_furnitureChanged`

- `Boolean m_modifierChanged`


## Properties

- `StateEngine bottomStateEngine`

- `GameObject backButton`


## Methods

- `StateEngine get_bottomStateEngine()`

- `GameObject get_backButton()`

- `Void Setup(UIHandler)`

- `Void NotifyFurnitureUnequiped(Furniture)`

- `Void NotifyFurnitureRegistered(IFurnitureController)`

- `Void NotifyFurnitureUnregistered(IFurnitureController)`

- `Void NotifyModifierChanged(DIYRoomModifier, DIYRoomModifier)`

- `Void NotifyResetAllChanges()`

- `Void NotifyClearAllFurnitures()`

- `Void NotifyThemeApplied()`

- `Void NotifyPresetApplied()`

- `Void NotifyFurnitureSaved()`

- `Void NotifyCameraChanged(CameraStateType)`

- `Void MarkFurnitureChanged()`

- `Void MarkModifierChanged()`

- `Void _InitIfNot(UIHandler)`

- `Void _InitRoomTitle()`

- `Void _OnBackPressAction()`

- `Void _ShowJudgeDialog(String, Action)`

- `Void OnTopMenuBackButtonPressed()`

- `Void OnSaveButtonPressed()`

- `Void OnClearButtonPressed()`

- `Void OnResetButtonPressed()`

- `Void OnShopPressed()`

- `Void OnComfortPressed()`

- `Void OnManifestBGPressed()`

- `Void OnCeilDirectlyButtonPressed()`

- `Void OnFloorDirectlyButtonPressed()`

- `Void OnWallButtonPressed()`

- `Void OnCameraResetButtonPressed()`

- `Void <_InitIfNot>b__36_0(GameObject)`

- `Void <OnTopMenuBackButtonPressed>b__40_0()`

- `Void <OnClearButtonPressed>b__42_0()`

- `Void <OnResetButtonPressed>b__43_0()`

- `Void <OnShopPressed>b__44_0(Int32)`

- `Void <OnShopPressed>b__44_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYUIController : PageSingleComponent, IHotfixable
{
	private const Int32 VIEWPORT_BOTTOM_MARGIN; // 0x0
	private GameObject _comfortPanel; // 0x20
	private BuildingUIRoomTitle _roomTitle; // 0x28
	private DIYComfortDetailView _comfortDetailView; // 0x30
	private GameObject _shopBtnPanel; // 0x38
	private PrefabInstHolder _shopPanelHolder; // 0x40
	private DIYFurnitureDetailPanel _furnitureDetailPanel; // 0x48
	private DIYCameraSwitchToggle _cameraSwitchToggle; // 0x50
	private Int32 _viewportBottomMargin; // 0x58
	private StateEngine _bottomStateEngine; // 0x60
	private DIYListViewStateBean _stateBean; // 0x68
	private GameObject _backButton; // 0x70
	private UIHandler m_pageHandler; // 0x78
	private StateBeanHandler m_stateBeanHandler; // 0x80
	private DIYShopPanel m_shopPanel; // 0x88
	private Boolean m_isInited; // 0x90
	private Boolean m_furnitureChanged; // 0x91
	private Boolean m_modifierChanged; // 0x92
	private static DelegateBridge __Hotfix0_get_bottomStateEngine; // 0x0
	private static DelegateBridge __Hotfix0_get_backButton; // 0x8
	private static DelegateBridge __Hotfix0_Setup; // 0x10
	private static DelegateBridge __Hotfix0_NotifyFurnitureUnequiped; // 0x18
	private static DelegateBridge __Hotfix0_NotifyFurnitureRegistered; // 0x20
	private static DelegateBridge __Hotfix0_NotifyFurnitureUnregistered; // 0x28
	private static DelegateBridge __Hotfix0_NotifyModifierChanged; // 0x30
	private static DelegateBridge __Hotfix0_NotifyResetAllChanges; // 0x38
	private static DelegateBridge __Hotfix0_NotifyClearAllFurnitures; // 0x40
	private static DelegateBridge __Hotfix0_NotifyThemeApplied; // 0x48
	private static DelegateBridge __Hotfix0_NotifyPresetApplied; // 0x50
	private static DelegateBridge __Hotfix0_NotifyFurnitureSaved; // 0x58
	private static DelegateBridge __Hotfix0_NotifyCameraChanged; // 0x60
	private static DelegateBridge __Hotfix0_MarkFurnitureChanged; // 0x68
	private static DelegateBridge __Hotfix0_MarkModifierChanged; // 0x70
	private static DelegateBridge __Hotfix0_GetUIBottomMargin; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x80
	private static DelegateBridge __Hotfix0__InitRoomTitle; // 0x88
	private static DelegateBridge __Hotfix0__OnBackPressAction; // 0x90
	private static DelegateBridge __Hotfix0__ShowJudgeDialog; // 0x98
	private static DelegateBridge __Hotfix0_OnTopMenuBackButtonPressed; // 0xa0
	private static DelegateBridge __Hotfix0_OnSaveButtonPressed; // 0xa8
	private static DelegateBridge __Hotfix0_OnClearButtonPressed; // 0xb0
	private static DelegateBridge __Hotfix0_OnResetButtonPressed; // 0xb8
	private static DelegateBridge __Hotfix0_OnShopPressed; // 0xc0
	private static DelegateBridge __Hotfix0_OnComfortPressed; // 0xc8
	private static DelegateBridge __Hotfix0_OnManifestBGPressed; // 0xd0
	private static DelegateBridge __Hotfix0_OnCeilDirectlyButtonPressed; // 0xd8
	private static DelegateBridge __Hotfix0_OnFloorDirectlyButtonPressed; // 0xe0
	private static DelegateBridge __Hotfix0_OnWallButtonPressed; // 0xe8
	private static DelegateBridge __Hotfix0_OnCameraResetButtonPressed; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8

	public StateEngine bottomStateEngine { get; }
	public GameObject backButton { get; }

	// RVA: 0x38271c4 VA: 0x7595e3f1c4
	public StateEngine get_bottomStateEngine() { }
	// RVA: 0x382722c VA: 0x7595e3f22c
	public GameObject get_backButton() { }
	// RVA: 0x3827294 VA: 0x7595e3f294
	public Void Setup(UIHandler pageHandler) { }
	// RVA: 0x3827700 VA: 0x7595e3f700
	public Void NotifyFurnitureUnequiped(Furniture furniture) { }
	// RVA: 0x38277b8 VA: 0x7595e3f7b8
	public Void NotifyFurnitureRegistered(IFurnitureController controller) { }
	// RVA: 0x3827870 VA: 0x7595e3f870
	public Void NotifyFurnitureUnregistered(IFurnitureController controller) { }
	// RVA: 0x3827928 VA: 0x7595e3f928
	public Void NotifyModifierChanged(DIYRoomModifier pre, DIYRoomModifier post) { }
	// RVA: 0x38279e8 VA: 0x7595e3f9e8
	public Void NotifyResetAllChanges() { }
	// RVA: 0x3827a84 VA: 0x7595e3fa84
	public Void NotifyClearAllFurnitures() { }
	// RVA: 0x3827b24 VA: 0x7595e3fb24
	public Void NotifyThemeApplied() { }
	// RVA: 0x3827bd8 VA: 0x7595e3fbd8
	public Void NotifyPresetApplied() { }
	// RVA: 0x3827c64 VA: 0x7595e3fc64
	public Void NotifyFurnitureSaved() { }
	// RVA: 0x3827cd4 VA: 0x7595e3fcd4
	public Void NotifyCameraChanged(CameraStateType cameraStateType) { }
	// RVA: 0x3827da8 VA: 0x7595e3fda8
	public Void MarkFurnitureChanged() { }
	// RVA: 0x3827e1c VA: 0x7595e3fe1c
	public Void MarkModifierChanged() { }
	// RVA: 0x3827e90 VA: 0x7595e3fe90
	public static Int32 GetUIBottomMargin() { }
	// RVA: 0x3827388 VA: 0x7595e3f388
	private Void _InitIfNot(UIHandler pageHandler) { }
	// RVA: 0x3827ef0 VA: 0x7595e3fef0
	private Void _InitRoomTitle() { }
	// RVA: 0x38281f4 VA: 0x7595e401f4
	private Void _OnBackPressAction() { }
	// RVA: 0x38284e8 VA: 0x7595e404e8
	private Void _ShowJudgeDialog(String content, Action positiveAction) { }
	// RVA: 0x3828644 VA: 0x7595e40644
	public Void OnTopMenuBackButtonPressed() { }
	// RVA: 0x38287cc VA: 0x7595e407cc
	public Void OnSaveButtonPressed() { }
	// RVA: 0x3828898 VA: 0x7595e40898
	public Void OnClearButtonPressed() { }
	// RVA: 0x3828988 VA: 0x7595e40988
	public Void OnResetButtonPressed() { }
	// RVA: 0x3828a78 VA: 0x7595e40a78
	public Void OnShopPressed() { }
	// RVA: 0x3828c54 VA: 0x7595e40c54
	public Void OnComfortPressed() { }
	// RVA: 0x3828d88 VA: 0x7595e40d88
	public Void OnManifestBGPressed() { }
	// RVA: 0x3828dfc VA: 0x7595e40dfc
	public Void OnCeilDirectlyButtonPressed() { }
	// RVA: 0x3828e70 VA: 0x7595e40e70
	public Void OnFloorDirectlyButtonPressed() { }
	// RVA: 0x3828ee4 VA: 0x7595e40ee4
	public Void OnWallButtonPressed() { }
	// RVA: 0x3828f58 VA: 0x7595e40f58
	public Void OnCameraResetButtonPressed() { }
	// RVA: 0x3828fcc VA: 0x7595e40fcc
	public Void .ctor() { }
	// RVA: 0x382903c VA: 0x7595e4103c
	private Void <_InitIfNot>b__36_0(GameObject inst) { }
	// RVA: 0x3829138 VA: 0x7595e41138
	private Void <OnTopMenuBackButtonPressed>b__40_0() { }
	// RVA: 0x3829158 VA: 0x7595e41158
	private Void <OnClearButtonPressed>b__42_0() { }
	// RVA: 0x3829188 VA: 0x7595e41188
	private Void <OnResetButtonPressed>b__43_0() { }
	// RVA: 0x38291b8 VA: 0x7595e411b8
	private Void <OnShopPressed>b__44_0(Int32 result) { }
	// RVA: 0x382928c VA: 0x7595e4128c
	private Void <OnShopPressed>b__44_1() { }
}
```
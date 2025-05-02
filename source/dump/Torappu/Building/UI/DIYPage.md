# DIYPage

**Namespace:** `Torappu.Building.UI`


## Fields

- `DIYRoom _diyRoom`

- `FurnitureGenreConfig _groundFurnitureGenre`

- `DIYTouchHandler _touchHandler`

- `DIYRoomIndicator _indicator`

- `Single _cameraDragSpeed`

- `GameObject _cameraLockIcon`

- `GameObject _cameraUnlockIcon`

- `String _presetImagePath`

- `Int32 _presetThumbsnailsWidth`

- `Int32 _presetThumbsnailsHeight`

- `Camera _presetShotCamera`

- `GameObject _intersectHint`

- `Single _bottomMarginLinearWeight`

- `Single _bottomMarginLinearBias`

- `ReflectCamera _reflectCamera`

- `Single _reflectFadeHeight`

- `Camera _roomCamera`

- `DIYUIController _uiControllerPrefab`

- `RectTransform _uiContainer`

- `Sprite _unequipIcon`

- `UICanvasScalerHelper _scaler`

- `DIYUIController m_uiController`

- `IFurnitureTypeDB m_furnitureTypeDB`

- `FurnitureMemento m_furnitureMemento`

- `DIYRoomModifierMemento m_modifierMemento`

- `IFurnitureController m_selectFurnitureController`

- `Boolean m_lockCamera`

- `CameraState m_currentCameraState`

- `CameraStateConfigs m_currentCameraStateConfigs`

- `Single m_cameraHorizontalOffset`

- `Single m_cameraVerticleOffset`

- `Boolean m_cameraTweening`

- `Boolean m_processingPresetApplying`

- `PersistentImageProxy m_imageProxy`

- `Matrix4x4 m_orthoMatrix`

- `Matrix4x4 m_persMatrix`

- `Boolean m_cachedMatrix`

- `DIYPageSwitchTween m_pageSwitchTween`

- `ReflectCameraHolder m_reflectCameraHolder`

- `Boolean m_isCeilingDir`

- `UnequipModifierViewData m_unequipModifierViewData`


## Properties

- `ReflectCameraHolder reflectCameraHolder`

- `Single minCameraOffset`

- `Single maxCameraOffset`

- `Single minCameraVerticleOffset`

- `Single maxCameraVerticleOffset`

- `Boolean furnitureEnableRotate`

- `GameObject uiControllerBackButton`


## Methods

- `ReflectCameraHolder get_reflectCameraHolder()`

- `Single get_minCameraOffset()`

- `Single get_maxCameraOffset()`

- `Single get_minCameraVerticleOffset()`

- `Single get_maxCameraVerticleOffset()`

- `Boolean get_furnitureEnableRotate()`

- `GameObject get_uiControllerBackButton()`

- `Void _AdjustReflectCameraIndexUsage(Boolean)`

- `Void _ForceRefreshFurniturePositionRecord()`

- `Void _GetAddFurnitureInitialPosition(IFurnitureData, out, out)`

- `Void _AddDIYItemToDIYRoom(IDIYItem)`

- `Void _SelectSameDIYItem(IDIYItem)`

- `Void _UnequipModifierFromRoom(DIYRoomPart)`

- `Void _SetCameraState(CameraStateType, Boolean)`

- `Void _SetupFurnitureCameraState(RoomSlotModel)`

- `Void _ResetFurnitureCameraState(Boolean)`

- `Void _ResetFurnitureSelect()`

- `Void _SetIndicator(ISpaceOccupation, FurnitureLocationType, Boolean)`

- `Void _OnTweeningOffset(Vector3, CameraState, Single, Boolean)`

- `Void _OnCameraStateChange(CameraState)`

- `Void _SetCeilingMatRenderQueue(Boolean)`

- `Void _CacheOrthoPersMatrix(Boolean)`

- `Void _DoCameraPerspectiveTransIfNeeded(Single, Boolean)`

- `Matrix4x4 MatrixLerp(Matrix4x4, Matrix4x4, Single)`

- `Void _OnFurniturePointEmpty()`

- `Void _OnDragEmpty(Vector2)`

- `Boolean _CanDragVerticle()`

- `Void _FurnitureBeginDrag(IFurnitureController, Boolean)`

- `Void _OnFurnitureBeginDrag(IFurnitureController, Boolean)`

- `Void _FurnitureEndDrag(IFurnitureController)`

- `Void _OnFurnitureEndDrag(IFurnitureController)`

- `Void _FurnitureStartDrag(IFurnitureController)`

- `Void _OnFurnitureStartDrag(IFurnitureController)`

- `Void _OnFurnitureDragged(IFurnitureController, Int32, Int32)`

- `Void _OnIndicatorButtonPressed(DIYRoomIndicatorButton)`

- `Void _UpdateCameraViewport(CanvasScaler)`

- `Void _Setup()`

- `Int32 _GetRoomComfortLimit()`

- `Void _ResetAllChanges()`

- `Void _ClearAllFurnitures()`

- `Void _IndicatorMuteAction(Action)`

- `Void _SaveAllChanges(Action`1)`

- `Void _ShowOKDialog(String, Action)`

- `Void _SetCameraLock(Boolean)`

- `Boolean _TrySaveDIY()`

- `Void _TrySavePreset(Int32, Action`1)`

- `Void _TrySavePreset(Int32, Texture2D, Action`1)`

- `Void _LoadDIYPreset(Int32, IDIYPreset)`

- `Void _TrySavePreset(Int32, String, Texture2D, Action`1)`

- `Texture2D _GetPresetPreviewTexture()`

- `Void _ApplyThemePresetToCurRoom(String)`

- `Void OnSetup()`

- `Void OnFurnitureRegistered(IFurnitureController)`

- `Void OnFurnitureUnregistered(IFurnitureController)`

- `Void OnFloorModifierChanged(DIYRoomModifier, DIYRoomModifier)`

- `Void OnWallModifierChanged(DIYRoomModifier, DIYRoomModifier)`

- `Void OnIntersectionStateChanged(Boolean)`

- `Void OnCameraLockPressed()`

- `Void <_ForceRefreshFurniturePositionRecord>b__77_0(IFurnitureController)`

- `Void <_ResetFurnitureSelect>b__85_0(IFurnitureController)`

- `Boolean <_OnIndicatorButtonPressed>b__103_0(Furniture)`

- `Void <_OnIndicatorButtonPressed>b__103_1(Furniture)`

- `Void <_Setup>b__105_0(IFurnitureController)`

- `Boolean <EffectsOnShow>b__106_0()`

- `IEnumerator <>n__0(Boolean)`

- `Boolean <EffectsOnHide>b__107_0()`

- `IEnumerator <>n__1(Boolean)`

- `Void <_ResetAllChanges>b__110_0(IFurnitureController)`

- `Boolean <_ClearAllFurnitures>b__111_0(Furniture)`

- `Void <_TrySaveDIY>b__116_0(Int32)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnStop()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class DIYPage : BuildingCommonPage, IListener
{
	private const Single IN_OUT_ANIM_DURATION; // 0x0
	private const Single FIELD_OF_VIEW_OFFSET; // 0x0
	private const Int32 JPEG_ENCODE_QUALITY; // 0x0
	private const Int32 PRESET_THUMBNAIL_CACHE_SIZE_THRESHOLD_KB; // 0x0
	private DIYRoom _diyRoom; // 0x110
	private FurnitureGenreConfig _groundFurnitureGenre; // 0x118
	private DIYTouchHandler _touchHandler; // 0x120
	private List`1 _cameraConfigs; // 0x128
	private DIYRoomIndicator _indicator; // 0x130
	private Single _cameraDragSpeed; // 0x138
	private GameObject _cameraLockIcon; // 0x140
	private GameObject _cameraUnlockIcon; // 0x148
	private String _presetImagePath; // 0x150
	private Int32 _presetThumbsnailsWidth; // 0x158
	private Int32 _presetThumbsnailsHeight; // 0x15c
	private Camera _presetShotCamera; // 0x160
	private GameObject _intersectHint; // 0x168
	private Single _bottomMarginLinearWeight; // 0x170
	private Single _bottomMarginLinearBias; // 0x174
	private ReflectCamera _reflectCamera; // 0x178
	private Single _reflectFadeHeight; // 0x180
	private Camera _roomCamera; // 0x188
	private DIYUIController _uiControllerPrefab; // 0x190
	private RectTransform _uiContainer; // 0x198
	private Sprite _unequipIcon; // 0x1a0
	private UICanvasScalerHelper _scaler; // 0x1a8
	private DIYUIController m_uiController; // 0x1b0
	private IFurnitureTypeDB m_furnitureTypeDB; // 0x1b8
	private FurnitureMemento m_furnitureMemento; // 0x1c0
	private DIYRoomModifierMemento m_modifierMemento; // 0x1c8
	private IFurnitureController m_selectFurnitureController; // 0x1d0
	private Boolean m_lockCamera; // 0x1d8
	private CameraState m_currentCameraState; // 0x1e0
	private CameraStateConfigs m_currentCameraStateConfigs; // 0x1e8
	private Single m_cameraHorizontalOffset; // 0x1f0
	private Single m_cameraVerticleOffset; // 0x1f4
	private Boolean m_cameraTweening; // 0x1f8
	private Boolean m_processingPresetApplying; // 0x1f9
	private PersistentImageProxy m_imageProxy; // 0x200
	private Matrix4x4 m_orthoMatrix; // 0x208
	private Matrix4x4 m_persMatrix; // 0x248
	private Boolean m_cachedMatrix; // 0x288
	private DIYPageSwitchTween m_pageSwitchTween; // 0x290
	private TweenerCore`3 m_tweenOffset; // 0x298
	private TweenerCore`3 m_tweenLookOffset; // 0x2a0
	private ReflectCameraHolder m_reflectCameraHolder; // 0x2a8
	private Boolean m_isCeilingDir; // 0x2b0
	private UnequipModifierViewData m_unequipModifierViewData; // 0x2b8
	private List`1 m_furniturePositionRecordList; // 0x2c0
	private static DelegateBridge __Hotfix0_get_reflectCameraHolder; // 0x0
	private static DelegateBridge __Hotfix0_get_minCameraOffset; // 0x8
	private static DelegateBridge __Hotfix0_get_maxCameraOffset; // 0x10
	private static DelegateBridge __Hotfix0_get_minCameraVerticleOffset; // 0x18
	private static DelegateBridge __Hotfix0_get_maxCameraVerticleOffset; // 0x20
	private static DelegateBridge __Hotfix0_get_furnitureEnableRotate; // 0x28
	private static DelegateBridge __Hotfix0_get_uiControllerBackButton; // 0x30
	private static DelegateBridge __Hotfix0_OnCreate; // 0x38
	private static DelegateBridge __Hotfix0_OnStart; // 0x40
	private static DelegateBridge __Hotfix0_OnStop; // 0x48
	private static DelegateBridge __Hotfix0__AdjustReflectCameraIndexUsage; // 0x50
	private static DelegateBridge __Hotfix0__ForceRefreshFurniturePositionRecord; // 0x58
	private static DelegateBridge __Hotfix0__GetAddFurnitureInitialPosition; // 0x60
	private static DelegateBridge __Hotfix0__AddDIYItemToDIYRoom; // 0x68
	private static DelegateBridge __Hotfix0__SelectSameDIYItem; // 0x70
	private static DelegateBridge __Hotfix0__UnequipModifierFromRoom; // 0x78
	private static DelegateBridge __Hotfix0__SetCameraState; // 0x80
	private static DelegateBridge __Hotfix0__SetupFurnitureCameraState; // 0x88
	private static DelegateBridge __Hotfix0__ResetFurnitureCameraState; // 0x90
	private static DelegateBridge __Hotfix0__ResetFurnitureSelect; // 0x98
	private static DelegateBridge __Hotfix0__SetIndicator; // 0xa0
	private static DelegateBridge __Hotfix0__OnTweeningOffset; // 0xa8
	private static DelegateBridge __Hotfix0__OnCameraStateChange; // 0xb0
	private static DelegateBridge __Hotfix0__SetCeilingMatRenderQueue; // 0xb8
	private static DelegateBridge __Hotfix0__CacheOrthoPersMatrix; // 0xc0
	private static DelegateBridge __Hotfix0__DoCameraPerspectiveTransIfNeeded; // 0xc8
	private static DelegateBridge __Hotfix0_MatrixLerp; // 0xd0
	private static DelegateBridge __Hotfix0__OnFurniturePointEmpty; // 0xd8
	private static DelegateBridge __Hotfix0__OnDragEmpty; // 0xe0
	private static DelegateBridge __Hotfix0__CanDragVerticle; // 0xe8
	private static DelegateBridge __Hotfix0__FurnitureBeginDrag; // 0xf0
	private static DelegateBridge __Hotfix0__OnFurnitureBeginDrag; // 0xf8
	private static DelegateBridge __Hotfix0__FurnitureEndDrag; // 0x100
	private static DelegateBridge __Hotfix0__OnFurnitureEndDrag; // 0x108
	private static DelegateBridge __Hotfix0__FurnitureStartDrag; // 0x110
	private static DelegateBridge __Hotfix0__OnFurnitureStartDrag; // 0x118
	private static DelegateBridge __Hotfix0__OnFurnitureDragged; // 0x120
	private static DelegateBridge __Hotfix0__OnIndicatorButtonPressed; // 0x128
	private static DelegateBridge __Hotfix0__UpdateCameraViewport; // 0x130
	private static DelegateBridge __Hotfix0__Setup; // 0x138
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x140
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x148
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x150
	private static DelegateBridge __Hotfix0__GetRoomComfortLimit; // 0x158
	private static DelegateBridge __Hotfix0__ResetAllChanges; // 0x160
	private static DelegateBridge __Hotfix0__ClearAllFurnitures; // 0x168
	private static DelegateBridge __Hotfix0__IndicatorMuteAction; // 0x170
	private static DelegateBridge __Hotfix0__SaveAllChanges; // 0x178
	private static DelegateBridge __Hotfix0__ShowOKDialog; // 0x180
	private static DelegateBridge __Hotfix0__SetCameraLock; // 0x188
	private static DelegateBridge __Hotfix0__TrySaveDIY; // 0x190
	private static DelegateBridge __Hotfix0__TrySavePreset; // 0x198
	private static DelegateBridge __Hotfix1__TrySavePreset; // 0x1a0
	private static DelegateBridge __Hotfix0__LoadDIYPreset; // 0x1a8
	private static DelegateBridge __Hotfix2__TrySavePreset; // 0x1b0
	private static DelegateBridge __Hotfix0__GetPresetPreviewTexture; // 0x1b8
	private static DelegateBridge __Hotfix0__ApplyThemePresetToCurRoom; // 0x1c0
	private static DelegateBridge __Hotfix0_OnSetup; // 0x1c8
	private static DelegateBridge __Hotfix0_OnFurnitureRegistered; // 0x1d0
	private static DelegateBridge __Hotfix0_OnFurnitureUnregistered; // 0x1d8
	private static DelegateBridge __Hotfix0_OnFloorModifierChanged; // 0x1e0
	private static DelegateBridge __Hotfix0_OnWallModifierChanged; // 0x1e8
	private static DelegateBridge __Hotfix0_OnIntersectionStateChanged; // 0x1f0
	private static DelegateBridge __Hotfix0_OnCameraLockPressed; // 0x1f8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x200

	private ReflectCameraHolder reflectCameraHolder { get; }
	private Single minCameraOffset { get; }
	private Single maxCameraOffset { get; }
	private Single minCameraVerticleOffset { get; }
	private Single maxCameraVerticleOffset { get; }
	private Boolean furnitureEnableRotate { get; }
	public GameObject uiControllerBackButton { get; }

	// RVA: 0x3d21fc4 VA: 0x7596339fc4
	private ReflectCameraHolder get_reflectCameraHolder() { }
	// RVA: 0x3d220ac VA: 0x759633a0ac
	private Single get_minCameraOffset() { }
	// RVA: 0x3d22148 VA: 0x759633a148
	private Single get_maxCameraOffset() { }
	// RVA: 0x3d221e4 VA: 0x759633a1e4
	private Single get_minCameraVerticleOffset() { }
	// RVA: 0x3d22258 VA: 0x759633a258
	private Single get_maxCameraVerticleOffset() { }
	// RVA: 0x3d222cc VA: 0x759633a2cc
	private Boolean get_furnitureEnableRotate() { }
	// RVA: 0x3d223b4 VA: 0x759633a3b4
	public GameObject get_uiControllerBackButton() { }
	// RVA: 0x3d22428 VA: 0x759633a428
	protected override Void OnCreate(DataBundle savedInstance) { }
	// RVA: 0x3d22634 VA: 0x759633a634
	protected override Void OnStart() { }
	// RVA: 0x3d22838 VA: 0x759633a838
	protected override Void OnStop() { }
	// RVA: 0x3d226f4 VA: 0x759633a6f4
	private Void _AdjustReflectCameraIndexUsage(Boolean isPageEnable) { }
	// RVA: 0x3d22910 VA: 0x759633a910
	private Void _ForceRefreshFurniturePositionRecord() { }
	// RVA: 0x3d22a0c VA: 0x759633aa0c
	public Void _GetAddFurnitureInitialPosition(IFurnitureData furniture, out Int32 x, out Int32 y) { }
	// RVA: 0x3d22e60 VA: 0x759633ae60
	private Void _AddDIYItemToDIYRoom(IDIYItem diyItem) { }
	// RVA: 0x3d23434 VA: 0x759633b434
	private Void _SelectSameDIYItem(IDIYItem diyItem) { }
	// RVA: 0x3d238d4 VA: 0x759633b8d4
	private Void _UnequipModifierFromRoom(DIYRoomPart roomPart) { }
	// RVA: 0x3d23aa4 VA: 0x759633baa4
	private Void _SetCameraState(CameraStateType stateType, Boolean force) { }
	// RVA: 0x3d24184 VA: 0x759633c184
	private Void _SetupFurnitureCameraState(RoomSlotModel roomSlotModel) { }
	// RVA: 0x3d244fc VA: 0x759633c4fc
	private Void _ResetFurnitureCameraState(Boolean force) { }
	// RVA: 0x3d23760 VA: 0x759633b760
	private Void _ResetFurnitureSelect() { }
	// RVA: 0x3d24588 VA: 0x759633c588
	private Void _SetIndicator(ISpaceOccupation occupation, FurnitureLocationType locationType, Boolean isShow) { }
	// RVA: 0x3d246d4 VA: 0x759633c6d4
	private Void _OnTweeningOffset(Vector3 currentCameraOffset, CameraState state, Single val, Boolean isCeilingDir) { }
	// RVA: 0x3d23c78 VA: 0x759633bc78
	private Void _OnCameraStateChange(CameraState state) { }
	// RVA: 0x3d24a48 VA: 0x759633ca48
	private Void _SetCeilingMatRenderQueue(Boolean needSet) { }
	// RVA: 0x3d24b28 VA: 0x759633cb28
	private Void _CacheOrthoPersMatrix(Boolean curIsOrtho) { }
	// RVA: 0x3d247f0 VA: 0x759633c7f0
	private Void _DoCameraPerspectiveTransIfNeeded(Single progress, Boolean isCeilingDir) { }
	// RVA: 0x3d24cf4 VA: 0x759633ccf4
	private Matrix4x4 MatrixLerp(Matrix4x4 from, Matrix4x4 to, Single t) { }
	// RVA: 0x3d25020 VA: 0x759633d020
	private Void _OnFurniturePointEmpty() { }
	// RVA: 0x3d25094 VA: 0x759633d094
	private Void _OnDragEmpty(Vector2 vec) { }
	// RVA: 0x3d2535c VA: 0x759633d35c
	private Boolean _CanDragVerticle() { }
	// RVA: 0x3d253fc VA: 0x759633d3fc
	private Void _FurnitureBeginDrag(IFurnitureController controller, Boolean isFirstAdd) { }
	// RVA: 0x3d23848 VA: 0x759633b848
	private Void _OnFurnitureBeginDrag(IFurnitureController controller, Boolean isFirstAdd) { }
	// RVA: 0x3d2592c VA: 0x759633d92c
	private Void _FurnitureEndDrag(IFurnitureController controller) { }
	// RVA: 0x3d25ac8 VA: 0x759633dac8
	private Void _OnFurnitureEndDrag(IFurnitureController controller) { }
	// RVA: 0x3d25b48 VA: 0x759633db48
	private Void _FurnitureStartDrag(IFurnitureController controller) { }
	// RVA: 0x3d25ce4 VA: 0x759633dce4
	private Void _OnFurnitureStartDrag(IFurnitureController controller) { }
	// RVA: 0x3d25d64 VA: 0x759633dd64
	private Void _OnFurnitureDragged(IFurnitureController controller, Int32 pos0, Int32 pos1) { }
	// RVA: 0x3d25e08 VA: 0x759633de08
	private Void _OnIndicatorButtonPressed(DIYRoomIndicatorButton button) { }
	// RVA: 0x3d26320 VA: 0x759633e320
	private Void _UpdateCameraViewport(CanvasScaler scaler) { }
	// RVA: 0x3d26488 VA: 0x759633e488
	private Void _Setup() { }
	// RVA: 0x3d26eb4 VA: 0x759633eeb4
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x3d26fa4 VA: 0x759633efa4
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x3d27094 VA: 0x759633f094
	protected override Void OnDestroy() { }
	// RVA: 0x3d271a8 VA: 0x759633f1a8
	private Int32 _GetRoomComfortLimit() { }
	// RVA: 0x3d27388 VA: 0x759633f388
	private Void _ResetAllChanges() { }
	// RVA: 0x3d27694 VA: 0x759633f694
	private Void _ClearAllFurnitures() { }
	// RVA: 0x3d2782c VA: 0x759633f82c
	private Void _IndicatorMuteAction(Action action) { }
	// RVA: 0x3d278cc VA: 0x759633f8cc
	private Void _SaveAllChanges(Action`1 resultHandler) { }
	// RVA: 0x3d27a58 VA: 0x759633fa58
	private Void _ShowOKDialog(String content, Action okAction) { }
	// RVA: 0x3d27bb8 VA: 0x759633fbb8
	private Void _SetCameraLock(Boolean lockCamera) { }
	// RVA: 0x3d27d44 VA: 0x759633fd44
	private Boolean _TrySaveDIY() { }
	// RVA: 0x3d27e5c VA: 0x759633fe5c
	private Void _TrySavePreset(Int32 index, Action`1 resultHandler) { }
	// RVA: 0x3d28430 VA: 0x7596340430
	private Void _TrySavePreset(Int32 index, Texture2D tex, Action`1 resultHandler) { }
	// RVA: 0x3d2858c VA: 0x759634058c
	private Void _LoadDIYPreset(Int32 index, IDIYPreset preset) { }
	// RVA: 0x3d28160 VA: 0x7596340160
	private Void _TrySavePreset(Int32 index, String presetName, Texture2D tex, Action`1 resultHandler) { }
	// RVA: 0x3d27f90 VA: 0x759633ff90
	private Texture2D _GetPresetPreviewTexture() { }
	// RVA: 0x3d28ab4 VA: 0x7596340ab4
	private Void _ApplyThemePresetToCurRoom(String themeId) { }
	// RVA: 0x3d2980c VA: 0x759634180c
	public Void OnSetup() { }
	// RVA: 0x3d29870 VA: 0x7596341870
	public Void OnFurnitureRegistered(IFurnitureController controller) { }
	// RVA: 0x3d29c34 VA: 0x7596341c34
	public Void OnFurnitureUnregistered(IFurnitureController controller) { }
	// RVA: 0x3d29dbc VA: 0x7596341dbc
	public Void OnFloorModifierChanged(DIYRoomModifier pre, DIYRoomModifier post) { }
	// RVA: 0x3d29e54 VA: 0x7596341e54
	public Void OnWallModifierChanged(DIYRoomModifier pre, DIYRoomModifier post) { }
	// RVA: 0x3d29eec VA: 0x7596341eec
	public Void OnIntersectionStateChanged(Boolean intersect) { }
	// RVA: 0x3d29f70 VA: 0x7596341f70
	public Void OnCameraLockPressed() { }
	// RVA: 0x3d29fe4 VA: 0x7596341fe4
	public Void .ctor() { }
	// RVA: 0x3d2a358 VA: 0x7596342358
	private Void <_ForceRefreshFurniturePositionRecord>b__77_0(IFurnitureController furnitureController) { }
	// RVA: 0x3d2a5a0 VA: 0x75963425a0
	private Void <_ResetFurnitureSelect>b__85_0(IFurnitureController x) { }
	// RVA: 0x3d2a798 VA: 0x7596342798
	private Boolean <_OnIndicatorButtonPressed>b__103_0(Furniture x) { }
	// RVA: 0x3d2a874 VA: 0x7596342874
	private Void <_OnIndicatorButtonPressed>b__103_1(Furniture x) { }
	// RVA: 0x3d2a8d0 VA: 0x75963428d0
	private Void <_Setup>b__105_0(IFurnitureController x) { }
	// RVA: 0x3d2ab88 VA: 0x7596342b88
	private Boolean <EffectsOnShow>b__106_0() { }
	// RVA: 0x3d2aba4 VA: 0x7596342ba4
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x3d2abb0 VA: 0x7596342bb0
	private Boolean <EffectsOnHide>b__107_0() { }
	// RVA: 0x3d2abcc VA: 0x7596342bcc
	private IEnumerator <>n__1(Boolean isIntoStack) { }
	// RVA: 0x3d2abd8 VA: 0x7596342bd8
	private Void <_ResetAllChanges>b__110_0(IFurnitureController x) { }
	// RVA: 0x3d2ae20 VA: 0x7596342e20
	private Boolean <_ClearAllFurnitures>b__111_0(Furniture x) { }
	// RVA: 0x3d2ae50 VA: 0x7596342e50
	private Void <_TrySaveDIY>b__116_0(Int32 result) { }
	// RVA: 0x3d2af70 VA: 0x7596342f70
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x3d2af78 VA: 0x7596342f78
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x3d2af80 VA: 0x7596342f80
	private Void <>xLuaBaseProxy_OnStop() { }
	// RVA: 0x3d2af88 VA: 0x7596342f88
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x3d2af94 VA: 0x7596342f94
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
	// RVA: 0x3d2afa0 VA: 0x7596342fa0
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```
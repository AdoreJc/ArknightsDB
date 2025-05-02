# VCharacter

**Namespace:** `Torappu.Building.Vault`


## Fields

- `Transform _centerTransform`

- `Transform _shadowTransform`

- `Boolean _isShadowFollowBone`

- `String _followBoneName`

- `SkeletonAnimation _skeleton`

- `Options _options`

- `Single _spineScale`

- `Int32 m_faceSign`

- `StateMachine m_stateMachine`

- `VMoveController m_moveController`

- `SpineOutline m_outline`

- `Transform m_headAnchor`

- `Tween m_startTween`

- `InteractSlot m_interactingSlot`

- `Vector3 m_headOffset`

- `Boolean m_isSleep`

- `Boolean m_isMovable`

- `Boolean m_isInteractable`

- `Boolean m_hasSpecialAnim`

- `Boolean m_isSelected`

- `Boolean m_hideOutline`

- `Bone m_shadowFollowBone`

- `Boolean <inControl>k__BackingField`

- `InteractSlot <interactingSlot>k__BackingField`

- `ILODHolder m_lodHolder`

- `BuildingCharModel <charModel>k__BackingField`

- `Boolean <isStarted>k__BackingField`

- `ExclusiveCoroutineHost m_stateTransCoroHost`


## Properties

- `Bone shadowFollowBone`

- `Boolean inControl`

- `InteractSlot interactingSlot`

- `Boolean interactingSlotValid`

- `VMoveController moveController`

- `Boolean hideOutline`

- `Boolean isInCFurnitureState`

- `Boolean isInCSpecialState`

- `Boolean isInCNormalState`

- `ILODHolder lodHolder`

- `Int32 faceSign`

- `BuildingCharModel charModel`

- `Options options`

- `Single moveSpeed`

- `Single alpha`

- `Boolean isSleep`

- `Boolean isSelected`

- `Boolean isStarted`

- `Boolean isMovable`

- `Boolean isInteractable`

- `Boolean hasSpecialAnim`

- `String stateDebugStr`

- `SkeletonAnimation skeleton`

- `Single spineScale`


## Methods

- `Bone get_shadowFollowBone()`

- `Boolean get_inControl()`

- `Void set_inControl(Boolean)`

- `InteractSlot get_interactingSlot()`

- `Void set_interactingSlot(InteractSlot)`

- `Boolean get_interactingSlotValid()`

- `VMoveController get_moveController()`

- `Boolean get_hideOutline()`

- `Void set_hideOutline(Boolean)`

- `Boolean get_isInCFurnitureState()`

- `Boolean get_isInCSpecialState()`

- `Boolean get_isInCNormalState()`

- `ILODHolder get_lodHolder()`

- `Int32 get_faceSign()`

- `Void set_faceSign(Int32)`

- `BuildingCharModel get_charModel()`

- `Void set_charModel(BuildingCharModel)`

- `Options get_options()`

- `Single get_moveSpeed()`

- `Single get_alpha()`

- `Void set_alpha(Single)`

- `Boolean get_isSleep()`

- `Void set_isSleep(Boolean)`

- `Boolean get_isSelected()`

- `Boolean get_isStarted()`

- `Void set_isStarted(Boolean)`

- `Void AddListener(IListener)`

- `Void RemoveListener(IListener)`

- `Boolean get_isMovable()`

- `Boolean get_isInteractable()`

- `Boolean get_hasSpecialAnim()`

- `String get_stateDebugStr()`

- `SkeletonAnimation get_skeleton()`

- `Single get_spineScale()`

- `Void _OnInteractFinish(Int32, Int32)`

- `Void SetInControl(Boolean)`

- `Void InteractInControl(InteractSlot)`

- `Void SpecialInteractInControl()`

- `Void MoveToNextRoom(VRoom)`

- `Void ControlMove(Boolean)`

- `Void EnableOutline(Boolean)`

- `Void TriggerInteractState()`

- `Boolean TryGetHeadPosWithOffset(out)`

- `Void OnFixedUpdate(Single)`

- `Void OnSleepChanged(Boolean)`

- `Boolean PlayAnimation(String, Boolean, Single, Single)`

- `Boolean PlayAnimation(String, Boolean, Single, out, Single)`

- `Void ResumeAnimation(String, Boolean)`

- `Boolean ContainsAnimation(String)`

- `String GetCurrentAnimation()`

- `Void _InitLocationAndPose()`

- `Void _SetFaceInternal(Int32, Boolean)`

- `Boolean _TryPickRandomStandGrid(out)`

- `Void _SetSleepInternal(Boolean, Boolean)`

- `Boolean _CheckStayAwake()`

- `Void _ResetHeight(Single)`

- `Void _SetShadowActive(Boolean)`

- `Void _SetSpineAlpha(Single)`

- `Void _DoShadowFollowBone()`

- `Void UpdateHeadOffset(InteractSlot)`

- `Void Awake()`

- `Void Start()`

- `Void OnDestroy()`

- `Void <OnInit>b__98_1()`

- `Boolean <>xLuaBaseProxy_OnInteract()`

- `Void <>xLuaBaseProxy_OnSelect()`

- `Void <>xLuaBaseProxy_OnDeselect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VCharacter : Object, IMovable
{
	private const String HEAD_ANCHOR_NAME; // 0x0
	private const String SHADOW_OBJ_NAME; // 0x0
	private const Single INIT_FADEIN_DURATION; // 0x0
	private const String SIT_ANIM_NAME; // 0x0
	private const String SLEEP_ANIM_NAME; // 0x0
	private const Single OFFSET_HEAD_Y_SIT; // 0x0
	private const Single OFFSET_HEAD_Y_SLEEP; // 0x0
	private Transform _centerTransform; // 0x30
	private Transform _shadowTransform; // 0x38
	private Boolean _isShadowFollowBone; // 0x40
	private String _followBoneName; // 0x48
	private SkeletonAnimation _skeleton; // 0x50
	private Options _options; // 0x58
	private Single _spineScale; // 0x60
	private Int32 m_faceSign; // 0x64
	private StateMachine m_stateMachine; // 0x68
	private VMoveController m_moveController; // 0x70
	private SpineOutline m_outline; // 0x78
	private Transform m_headAnchor; // 0x80
	private List`1 m_listeners; // 0x88
	private Tween m_startTween; // 0x90
	private InteractSlot m_interactingSlot; // 0x98
	private Vector3 m_headOffset; // 0xa0
	private Boolean m_isSleep; // 0xac
	private Boolean m_isMovable; // 0xad
	private Boolean m_isInteractable; // 0xae
	private Boolean m_hasSpecialAnim; // 0xaf
	private Boolean m_isSelected; // 0xb0
	private Boolean m_hideOutline; // 0xb1
	private Bone m_shadowFollowBone; // 0xb8
	private Boolean <inControl>k__BackingField; // 0xc0
	private InteractSlot <interactingSlot>k__BackingField; // 0xc8
	private ILODHolder m_lodHolder; // 0xd0
	private BuildingCharModel <charModel>k__BackingField; // 0xd8
	private Boolean <isStarted>k__BackingField; // 0x148
	private ExclusiveCoroutineHost m_stateTransCoroHost; // 0x150
	private static DelegateBridge __Hotfix0_get_shadowFollowBone; // 0x0
	private static DelegateBridge __Hotfix0_get_inControl; // 0x8
	private static DelegateBridge __Hotfix0_set_inControl; // 0x10
	private static DelegateBridge __Hotfix0_get_interactingSlot; // 0x18
	private static DelegateBridge __Hotfix0_set_interactingSlot; // 0x20
	private static DelegateBridge __Hotfix0_get_interactingSlotValid; // 0x28
	private static DelegateBridge __Hotfix0_get_moveController; // 0x30
	private static DelegateBridge __Hotfix0_get_hideOutline; // 0x38
	private static DelegateBridge __Hotfix0_set_hideOutline; // 0x40
	private static DelegateBridge __Hotfix0_get_isInCFurnitureState; // 0x48
	private static DelegateBridge __Hotfix0_get_isInCSpecialState; // 0x50
	private static DelegateBridge __Hotfix0_get_isInCNormalState; // 0x58
	private static DelegateBridge __Hotfix0_get_lodHolder; // 0x60
	private static DelegateBridge __Hotfix0_get_faceSign; // 0x68
	private static DelegateBridge __Hotfix0_set_faceSign; // 0x70
	private static DelegateBridge __Hotfix0_get_worldCenter; // 0x78
	private static DelegateBridge __Hotfix0_get_charModel; // 0x80
	private static DelegateBridge __Hotfix0_set_charModel; // 0x88
	private static DelegateBridge __Hotfix0_get_options; // 0x90
	private static DelegateBridge __Hotfix0_get_moveSpeed; // 0x98
	private static DelegateBridge __Hotfix0_get_alpha; // 0xa0
	private static DelegateBridge __Hotfix0_set_alpha; // 0xa8
	private static DelegateBridge __Hotfix0_get_isSleep; // 0xb0
	private static DelegateBridge __Hotfix0_set_isSleep; // 0xb8
	private static DelegateBridge __Hotfix0_get_isSelected; // 0xc0
	private static DelegateBridge __Hotfix0_get_isStarted; // 0xc8
	private static DelegateBridge __Hotfix0_set_isStarted; // 0xd0
	private static DelegateBridge __Hotfix0_AddListener; // 0xd8
	private static DelegateBridge __Hotfix0_RemoveListener; // 0xe0
	private static DelegateBridge __Hotfix0_get_isMovable; // 0xe8
	private static DelegateBridge __Hotfix0_get_isInteractable; // 0xf0
	private static DelegateBridge __Hotfix0_get_hasSpecialAnim; // 0xf8
	private static DelegateBridge __Hotfix0_get_stateDebugStr; // 0x100
	private static DelegateBridge __Hotfix0_get_skeleton; // 0x108
	private static DelegateBridge __Hotfix0_get_spineScale; // 0x110
	private static DelegateBridge __Hotfix0_OnInit; // 0x118
	private static DelegateBridge __Hotfix0_OnEnter; // 0x120
	private static DelegateBridge __Hotfix0_OnExit; // 0x128
	private static DelegateBridge __Hotfix0_OnInteract; // 0x130
	private static DelegateBridge __Hotfix0__OnInteractFinish; // 0x138
	private static DelegateBridge __Hotfix0_SetInControl; // 0x140
	private static DelegateBridge __Hotfix0_InteractInControl; // 0x148
	private static DelegateBridge __Hotfix0_SpecialInteractInControl; // 0x150
	private static DelegateBridge __Hotfix0_MoveToNextRoom; // 0x158
	private static DelegateBridge __Hotfix0_ControlMove; // 0x160
	private static DelegateBridge __Hotfix0_EnableOutline; // 0x168
	private static DelegateBridge __Hotfix0_TriggerInteractState; // 0x170
	private static DelegateBridge __Hotfix0_TryGetHeadPosWithOffset; // 0x178
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x180
	private static DelegateBridge __Hotfix0_OnSelect; // 0x188
	private static DelegateBridge __Hotfix0_OnDeselect; // 0x190
	private static DelegateBridge __Hotfix0_OnSleepChanged; // 0x198
	private static DelegateBridge __Hotfix0_PlayAnimation; // 0x1a0
	private static DelegateBridge __Hotfix1_PlayAnimation; // 0x1a8
	private static DelegateBridge __Hotfix0_ResumeAnimation; // 0x1b0
	private static DelegateBridge __Hotfix0_ContainsAnimation; // 0x1b8
	private static DelegateBridge __Hotfix0_GetCurrentAnimation; // 0x1c0
	private static DelegateBridge __Hotfix0_ConstructStateMachine; // 0x1c8
	private static DelegateBridge __Hotfix0__InitLocationAndPose; // 0x1d0
	private static DelegateBridge __Hotfix0__SetFaceInternal; // 0x1d8
	private static DelegateBridge __Hotfix0__TryPickRandomStandGrid; // 0x1e0
	private static DelegateBridge __Hotfix0__SetSleepInternal; // 0x1e8
	private static DelegateBridge __Hotfix0__CheckStayAwake; // 0x1f0
	private static DelegateBridge __Hotfix0__ResetHeight; // 0x1f8
	private static DelegateBridge __Hotfix0__SetShadowActive; // 0x200
	private static DelegateBridge __Hotfix0__SetSpineAlpha; // 0x208
	private static DelegateBridge __Hotfix0__DoShadowFollowBone; // 0x210
	private static DelegateBridge __Hotfix0_UpdateHeadOffset; // 0x218
	private static DelegateBridge __Hotfix0_Awake; // 0x220
	private static DelegateBridge __Hotfix0_Start; // 0x228
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x230
	private static DelegateBridge _c__Hotfix0_ctor; // 0x238

	protected Bone shadowFollowBone { get; }
	public Boolean inControl { get; set; }
	public InteractSlot interactingSlot { get; set; }
	public Boolean interactingSlotValid { get; }
	public VMoveController moveController { get; }
	public Boolean hideOutline { get; set; }
	public Boolean isInCFurnitureState { get; }
	public Boolean isInCSpecialState { get; }
	public Boolean isInCNormalState { get; }
	private ILODHolder lodHolder { get; }
	public Int32 faceSign { get; set; }
	public override Vector3 worldCenter { get; }
	public BuildingCharModel charModel { get; set; }
	public Options options { get; }
	public Single moveSpeed { get; }
	public Single alpha { get; set; }
	public Boolean isSleep { get; set; }
	public Boolean isSelected { get; }
	public Boolean isStarted { get; set; }
	public Boolean isMovable { get; }
	public Boolean isInteractable { get; }
	public Boolean hasSpecialAnim { get; }
	public String stateDebugStr { get; }
	protected SkeletonAnimation skeleton { get; }
	public Single spineScale { get; }

	// RVA: 0x38488ac VA: 0x7595e608ac
	protected Bone get_shadowFollowBone() { }
	// RVA: 0x3848960 VA: 0x7595e60960
	public Boolean get_inControl() { }
	// RVA: 0x38489c8 VA: 0x7595e609c8
	public Void set_inControl(Boolean value) { }
	// RVA: 0x3848a48 VA: 0x7595e60a48
	public InteractSlot get_interactingSlot() { }
	// RVA: 0x3848ab0 VA: 0x7595e60ab0
	public Void set_interactingSlot(InteractSlot value) { }
	// RVA: 0x3848b34 VA: 0x7595e60b34
	public Boolean get_interactingSlotValid() { }
	// RVA: 0x3848c70 VA: 0x7595e60c70
	public VMoveController get_moveController() { }
	// RVA: 0x3848cd8 VA: 0x7595e60cd8
	public Boolean get_hideOutline() { }
	// RVA: 0x3848d40 VA: 0x7595e60d40
	public Void set_hideOutline(Boolean value) { }
	// RVA: 0x3848dc0 VA: 0x7595e60dc0
	public Boolean get_isInCFurnitureState() { }
	// RVA: 0x3848e3c VA: 0x7595e60e3c
	public Boolean get_isInCSpecialState() { }
	// RVA: 0x3848eb8 VA: 0x7595e60eb8
	public Boolean get_isInCNormalState() { }
	// RVA: 0x3848f38 VA: 0x7595e60f38
	private ILODHolder get_lodHolder() { }
	// RVA: 0x3848fd4 VA: 0x7595e60fd4
	public Int32 get_faceSign() { }
	// RVA: 0x384903c VA: 0x7595e6103c
	public Void set_faceSign(Int32 value) { }
	// RVA: 0x38491ec VA: 0x7595e611ec
	public override Vector3 get_worldCenter() { }
	// RVA: 0x3848040 VA: 0x7595e60040
	public BuildingCharModel get_charModel() { }
	// RVA: 0x3849260 VA: 0x7595e61260
	public Void set_charModel(BuildingCharModel value) { }
	// RVA: 0x3849314 VA: 0x7595e61314
	public Options get_options() { }
	// RVA: 0x384937c VA: 0x7595e6137c
	public Single get_moveSpeed() { }
	// RVA: 0x384942c VA: 0x7595e6142c
	public Single get_alpha() { }
	// RVA: 0x38494b8 VA: 0x7595e614b8
	public Void set_alpha(Single value) { }
	// RVA: 0x3849570 VA: 0x7595e61570
	public Boolean get_isSleep() { }
	// RVA: 0x38495d8 VA: 0x7595e615d8
	public Void set_isSleep(Boolean value) { }
	// RVA: 0x3849710 VA: 0x7595e61710
	public Boolean get_isSelected() { }
	// RVA: 0x3848844 VA: 0x7595e60844
	public Boolean get_isStarted() { }
	// RVA: 0x3849778 VA: 0x7595e61778
	private Void set_isStarted(Boolean value) { }
	// RVA: 0x38497f8 VA: 0x7595e617f8
	public Void AddListener(IListener listener) { }
	// RVA: 0x3849930 VA: 0x7595e61930
	public Void RemoveListener(IListener listener) { }
	// RVA: 0x3849a44 VA: 0x7595e61a44
	public Boolean get_isMovable() { }
	// RVA: 0x3849af4 VA: 0x7595e61af4
	public Boolean get_isInteractable() { }
	// RVA: 0x3849b5c VA: 0x7595e61b5c
	public Boolean get_hasSpecialAnim() { }
	// RVA: 0x3849bc4 VA: 0x7595e61bc4
	public String get_stateDebugStr() { }
	// RVA: 0x3849c64 VA: 0x7595e61c64
	protected SkeletonAnimation get_skeleton() { }
	// RVA: 0x3849ccc VA: 0x7595e61ccc
	public Single get_spineScale() { }
	// RVA: 0x3849d34 VA: 0x7595e61d34
	public override Void OnInit() { }
	// RVA: 0x384a238 VA: 0x7595e62238
	public override Void OnEnter() { }
	// RVA: 0x384a4b8 VA: 0x7595e624b8
	public override Void OnExit() { }
	// RVA: 0x384a5f4 VA: 0x7595e625f4
	public override Boolean OnInteract() { }
	// RVA: 0x384a9dc VA: 0x7595e629dc
	private Void _OnInteractFinish(Int32 stateId, Int32 targetStateId) { }
	// RVA: 0x384ab20 VA: 0x7595e62b20
	public Void SetInControl(Boolean enable) { }
	// RVA: 0x384ac10 VA: 0x7595e62c10
	public Void InteractInControl(InteractSlot slot) { }
	// RVA: 0x384acc4 VA: 0x7595e62cc4
	public Void SpecialInteractInControl() { }
	// RVA: 0x384ad54 VA: 0x7595e62d54
	public Void MoveToNextRoom(VRoom newRoom) { }
	// RVA: 0x384af50 VA: 0x7595e62f50
	public Void ControlMove(Boolean isMove) { }
	// RVA: 0x384b014 VA: 0x7595e63014
	public Void EnableOutline(Boolean enable) { }
	// RVA: 0x384b098 VA: 0x7595e63098
	public Void TriggerInteractState() { }
	// RVA: 0x384b124 VA: 0x7595e63124
	public Boolean TryGetHeadPosWithOffset(out Vector3 position) { }
	// RVA: 0x384b254 VA: 0x7595e63254
	public Void OnFixedUpdate(Single deltaTime) { }
	// RVA: 0x384b664 VA: 0x7595e63664
	protected override Void OnSelect() { }
	// RVA: 0x384b6f0 VA: 0x7595e636f0
	protected override Void OnDeselect() { }
	// RVA: 0x384b780 VA: 0x7595e63780
	protected Void OnSleepChanged(Boolean value) { }
	// RVA: 0x384b92c VA: 0x7595e6392c
	protected Boolean PlayAnimation(String animKey, Boolean loop, Single animScale, Single crossfade) { }
	// RVA: 0x384b9e8 VA: 0x7595e639e8
	protected Boolean PlayAnimation(String animKey, Boolean loop, Single animScale, out Single time, Single crossfade) { }
	// RVA: 0x384bc4c VA: 0x7595e63c4c
	protected Void ResumeAnimation(String animationName, Boolean loop) { }
	// RVA: 0x384bd74 VA: 0x7595e63d74
	public Boolean ContainsAnimation(String animKey) { }
	// RVA: 0x384beb8 VA: 0x7595e63eb8
	public String GetCurrentAnimation() { }
	// RVA: 0x384bfac VA: 0x7595e63fac
	protected virtual StateMachine ConstructStateMachine() { }
	// RVA: 0x384a2e4 VA: 0x7595e622e4
	private Void _InitLocationAndPose() { }
	// RVA: 0x38490c0 VA: 0x7595e610c0
	private Void _SetFaceInternal(Int32 faceSign, Boolean force) { }
	// RVA: 0x384c340 VA: 0x7595e64340
	private Boolean _TryPickRandomStandGrid(out GridPosition pos) { }
	// RVA: 0x384965c VA: 0x7595e6165c
	private Void _SetSleepInternal(Boolean value, Boolean force) { }
	// RVA: 0x384b3a4 VA: 0x7595e633a4
	private Boolean _CheckStayAwake() { }
	// RVA: 0x384c5b8 VA: 0x7595e645b8
	private Void _ResetHeight(Single height) { }
	// RVA: 0x384c4d8 VA: 0x7595e644d8
	private Void _SetShadowActive(Boolean isActive) { }
	// RVA: 0x384a0d0 VA: 0x7595e620d0
	private Void _SetSpineAlpha(Single alpha) { }
	// RVA: 0x384b528 VA: 0x7595e63528
	private Void _DoShadowFollowBone() { }
	// RVA: 0x384c680 VA: 0x7595e64680
	protected Void UpdateHeadOffset(InteractSlot interactSlot) { }
	// RVA: 0x384c864 VA: 0x7595e64864
	private Void Awake() { }
	// RVA: 0x384ca18 VA: 0x7595e64a18
	private Void Start() { }
	// RVA: 0x384cb94 VA: 0x7595e64b94
	private Void OnDestroy() { }
	// RVA: 0x384cc08 VA: 0x7595e64c08
	public Void .ctor() { }
	// RVA: 0x384ce9c VA: 0x7595e64e9c
	private Void <OnInit>b__98_1() { }
	// RVA: 0x384cea4 VA: 0x7595e64ea4
	private Boolean <>xLuaBaseProxy_OnInteract() { }
	// RVA: 0x384ceac VA: 0x7595e64eac
	private Void <>xLuaBaseProxy_OnSelect() { }
	// RVA: 0x384ceb4 VA: 0x7595e64eb4
	private Void <>xLuaBaseProxy_OnDeselect() { }
}
```
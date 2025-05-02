# GachaPhase0

**Namespace:** `Torappu.Gacha`


## Fields

- `Options _options`

- `Camera _camera`

- `Animation _bagAnimation`

- `Animation _camAnimation`

- `Animation _folderAnimation`

- `StateMachine m_stateMachine`


## Properties

- `Options options`

- `String stateDebugStr`


## Methods

- `Options get_options()`

- `String get_stateDebugStr()`

- `Void OnBeginDrag(BaseEventData)`

- `Void OnDrag(BaseEventData)`

- `Void OnEndDrag(BaseEventData)`

- `Void OnSkipAllBtnClicked()`

- `Void _ResetAllAnimations()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void Update()`

- `Boolean <>xLuaBaseProxy_get_hasOwnCamera()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Boolean <>xLuaBaseProxy_TryFetchAndAddCameras(List`1)`

- `Void <>xLuaBaseProxy_OnDisposeForReuse()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class GachaPhase0 : GachaPhase
{
	private const Single CAMERA_ANIMATION_CROSSFADE; // 0x0
	private const String BAG_ANIMATION_START; // 0x0
	private const String BAG_ANIMATION_OPEN; // 0x0
	private const String CAMERA_ANIMATION_START; // 0x0
	private const String CAMERA_ANIMATION_HOLD; // 0x0
	private const String CAMERA_ANIMATION_SHAKE; // 0x0
	private const String SPINE_ANIMATION_DEFAULT; // 0x0
	private const String SPINE_ANIMATION_ONE; // 0x0
	private const String SPINE_ANIMATION_TEN; // 0x0
	private const String FOLDER_ANIMATION_START; // 0x0
	private Options _options; // 0x18
	private Camera _camera; // 0x20
	private Animation _bagAnimation; // 0x28
	private Animation _camAnimation; // 0x30
	private Animation _folderAnimation; // 0x38
	private StateMachine m_stateMachine; // 0x40
	private static DelegateBridge __Hotfix0_get_options; // 0x0
	private static DelegateBridge __Hotfix0_get_canSkip; // 0x8
	private static DelegateBridge __Hotfix0_get_hasOwnCamera; // 0x10
	private static DelegateBridge __Hotfix0_get_stateDebugStr; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0__ResetAnimationState; // 0x28
	private static DelegateBridge __Hotfix0_Play; // 0x30
	private static DelegateBridge __Hotfix0_SkipToEnd; // 0x38
	private static DelegateBridge __Hotfix0_PreloadSounds; // 0x40
	private static DelegateBridge __Hotfix0_TryFetchAndAddCameras; // 0x48
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x50
	private static DelegateBridge __Hotfix0_OnDrag; // 0x58
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x60
	private static DelegateBridge __Hotfix0_OnSkipAllBtnClicked; // 0x68
	private static DelegateBridge __Hotfix0_OnDisposeForReuse; // 0x70
	private static DelegateBridge __Hotfix0__ResetAllAnimations; // 0x78
	private static DelegateBridge __Hotfix0_OnEnable; // 0x80
	private static DelegateBridge __Hotfix0_OnDisable; // 0x88
	private static DelegateBridge __Hotfix0_Update; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public Options options { get; }
	public override Boolean canSkip { get; }
	public override Boolean hasOwnCamera { get; }
	public String stateDebugStr { get; }

	// RVA: 0x36fc30c VA: 0x7595d1430c
	public Options get_options() { }
	// RVA: 0x36fc374 VA: 0x7595d14374
	public override Boolean get_canSkip() { }
	// RVA: 0x36fc3dc VA: 0x7595d143dc
	public override Boolean get_hasOwnCamera() { }
	// RVA: 0x36fc444 VA: 0x7595d14444
	public String get_stateDebugStr() { }
	// RVA: 0x36fc4dc VA: 0x7595d144dc
	public override Void OnInit() { }
	// RVA: 0x36fc6cc VA: 0x7595d146cc
	private static Void _ResetAnimationState(Animation animation) { }
	// RVA: 0x36fc9f4 VA: 0x7595d149f4
	public override IEnumerator Play(GachaController controller, PlayMode playMode) { }
	// RVA: 0x36fcaf4 VA: 0x7595d14af4
	public override Void SkipToEnd(GachaController controller, PlayMode playMode) { }
	// RVA: 0x36fcb88 VA: 0x7595d14b88
	public override Void PreloadSounds(PlayMode playMode, RarityRank rarity, Boolean isMultipleGacha) { }
	// RVA: 0x36fcd78 VA: 0x7595d14d78
	public override Boolean TryFetchAndAddCameras(List`1 cameras) { }
	// RVA: 0x36fceb0 VA: 0x7595d14eb0
	public Void OnBeginDrag(BaseEventData evData) { }
	// RVA: 0x36fcfbc VA: 0x7595d14fbc
	public Void OnDrag(BaseEventData evData) { }
	// RVA: 0x36fd0c8 VA: 0x7595d150c8
	public Void OnEndDrag(BaseEventData evData) { }
	// RVA: 0x36fd1d4 VA: 0x7595d151d4
	public Void OnSkipAllBtnClicked() { }
	// RVA: 0x36fd238 VA: 0x7595d15238
	protected override Void OnDisposeForReuse() { }
	// RVA: 0x36fd2ac VA: 0x7595d152ac
	private Void _ResetAllAnimations() { }
	// RVA: 0x36fd34c VA: 0x7595d1534c
	private Void OnEnable() { }
	// RVA: 0x36fd3c4 VA: 0x7595d153c4
	private Void OnDisable() { }
	// RVA: 0x36fd470 VA: 0x7595d15470
	private Void Update() { }
	// RVA: 0x36fd558 VA: 0x7595d15558
	public Void .ctor() { }
	// RVA: 0x36fd5c8 VA: 0x7595d155c8
	private Boolean <>xLuaBaseProxy_get_hasOwnCamera() { }
	// RVA: 0x36fd5d0 VA: 0x7595d155d0
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x36fd5d8 VA: 0x7595d155d8
	private Boolean <>xLuaBaseProxy_TryFetchAndAddCameras(List`1 P0) { }
	// RVA: 0x36fd5e0 VA: 0x7595d155e0
	private Void <>xLuaBaseProxy_OnDisposeForReuse() { }
}
```
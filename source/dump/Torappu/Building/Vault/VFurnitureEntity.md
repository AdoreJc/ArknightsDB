# VFurnitureEntity

**Namespace:** `Torappu.Building.Vault`


## Fields

- `Transform _focusCenter`

- `Animator _animPlayer`

- `FurnitureEntity _furnitureEntity`

- `String m_musicId`

- `String m_id`

- `Boolean m_isInteractable`

- `Vector3 m_worldCenter`

- `Coroutine m_coroutine`

- `VFurnitureOutline m_vFurnitureOutline`

- `Boolean m_isInited`

- `Boolean m_isPlaying`

- `Boolean m_isMusicPlaying`

- `FurnitureInteractType m_furnitureInteractType`

- `FurnitureType m_furniType`

- `VFuncFurniture m_funcFurniture`

- `IFurnitureController m_controller`


## Properties

- `Transform focusCenter`

- `String id`

- `String musicId`

- `Boolean isMusicFurniture`

- `Boolean isPlaying`

- `Boolean isFunctional`

- `Boolean isOutlineOn`

- `FurnitureSubType subType`

- `Bounds bounds`

- `VFurnitureOutline vFurnitureOutline`


## Methods

- `Transform get_focusCenter()`

- `Void _OnAnimatorStateChange(String, AnimatorStateEvent)`

- `String get_id()`

- `String get_musicId()`

- `Boolean get_isMusicFurniture()`

- `Boolean get_isPlaying()`

- `Boolean get_isFunctional()`

- `Boolean get_isOutlineOn()`

- `FurnitureSubType get_subType()`

- `Bounds get_bounds()`

- `VFurnitureOutline get_vFurnitureOutline()`

- `Void SetData(IFurnitureController)`

- `Void _DoInteract()`

- `Void StoppedByOthers()`

- `Void EnableOutline(Boolean)`

- `Void ResetOutline()`

- `Transform GetFuncFurnitureBtnPos()`

- `Void OpenFunctionPage()`

- `Void _InteractAnimation(String)`

- `Void _InteractAnimation(String, Boolean)`

- `IEnumerator _WaitInteractCooldown()`

- `Void _PlayMusic()`

- `Void _StopMusic()`

- `Boolean IsVCharInteractable(VCharacter)`

- `Void OnVCharInteract(VCharacter)`

- `Void OnInteractableChanged(Boolean)`

- `Void OnDisable()`

- `Void OnEnable()`

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_Init(VRoom, VGridPlane)`

- `Boolean <>xLuaBaseProxy_OnInteract()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VFurnitureEntity : Object, IHotfixable, IVCharInteractable
{
	private Transform _focusCenter; // 0x30
	protected Animator _animPlayer; // 0x38
	private FurnitureEntity _furnitureEntity; // 0x40
	private List`1 _animatorEventControllers; // 0x48
	private String m_musicId; // 0x50
	private String m_id; // 0x58
	protected Boolean m_isInteractable; // 0x60
	private Vector3 m_worldCenter; // 0x64
	protected Coroutine m_coroutine; // 0x70
	private VFurnitureOutline m_vFurnitureOutline; // 0x78
	private Boolean m_isInited; // 0x80
	private FurnitureAnimatorBehaviour[] m_behaviours; // 0x88
	private List`1 m_animatorEventControllers; // 0x90
	private Boolean m_isPlaying; // 0x98
	private Boolean m_isMusicPlaying; // 0x99
	private FurnitureInteractType m_furnitureInteractType; // 0x9c
	private FurnitureType m_furniType; // 0xa0
	private VFuncFurniture m_funcFurniture; // 0xa8
	private IFurnitureController m_controller; // 0xb0
	private static DelegateBridge __Hotfix0_get_focusCenter; // 0x0
	private static DelegateBridge __Hotfix0__OnAnimatorStateChange; // 0x8
	private static DelegateBridge __Hotfix0_get_interactAnimation; // 0x10
	private static DelegateBridge __Hotfix0_get_id; // 0x18
	private static DelegateBridge __Hotfix0_get_musicId; // 0x20
	private static DelegateBridge __Hotfix0_get_worldCenter; // 0x28
	private static DelegateBridge __Hotfix0_get_isMusicFurniture; // 0x30
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x38
	private static DelegateBridge __Hotfix0_get_isFunctional; // 0x40
	private static DelegateBridge __Hotfix0_get_isOutlineOn; // 0x48
	private static DelegateBridge __Hotfix0_get_subType; // 0x50
	private static DelegateBridge __Hotfix0_get_bounds; // 0x58
	private static DelegateBridge __Hotfix0_get_vFurnitureOutline; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x68
	private static DelegateBridge __Hotfix0_OnInit; // 0x70
	private static DelegateBridge __Hotfix0_SetData; // 0x78
	private static DelegateBridge __Hotfix0_OnEnter; // 0x80
	private static DelegateBridge __Hotfix0_OnExit; // 0x88
	private static DelegateBridge __Hotfix0_OnInteract; // 0x90
	private static DelegateBridge __Hotfix0__DoInteract; // 0x98
	private static DelegateBridge __Hotfix0_StoppedByOthers; // 0xa0
	private static DelegateBridge __Hotfix0_EnableOutline; // 0xa8
	private static DelegateBridge __Hotfix0_ResetOutline; // 0xb0
	private static DelegateBridge __Hotfix0_GetFuncFurnitureBtnPos; // 0xb8
	private static DelegateBridge __Hotfix0_OpenFunctionPage; // 0xc0
	private static DelegateBridge __Hotfix0__InteractAnimation; // 0xc8
	private static DelegateBridge __Hotfix1__InteractAnimation; // 0xd0
	private static DelegateBridge __Hotfix0__WaitInteractCooldown; // 0xd8
	private static DelegateBridge __Hotfix0__PlayMusic; // 0xe0
	private static DelegateBridge __Hotfix0__StopMusic; // 0xe8
	private static DelegateBridge __Hotfix0_IsVCharInteractable; // 0xf0
	private static DelegateBridge __Hotfix0_OnVCharInteract; // 0xf8
	private static DelegateBridge __Hotfix0_OnInteractableChanged; // 0x100
	private static DelegateBridge __Hotfix0_OnDisable; // 0x108
	private static DelegateBridge __Hotfix0_OnEnable; // 0x110
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x118
	private static DelegateBridge _c__Hotfix0_ctor; // 0x120

	public Transform focusCenter { get; }
	protected virtual String interactAnimation { get; }
	public String id { get; }
	public String musicId { get; }
	public override Vector3 worldCenter { get; }
	public Boolean isMusicFurniture { get; }
	public Boolean isPlaying { get; }
	public Boolean isFunctional { get; }
	public Boolean isOutlineOn { get; }
	public FurnitureSubType subType { get; }
	public Bounds bounds { get; }
	public VFurnitureOutline vFurnitureOutline { get; }

	// RVA: 0x3d0588c VA: 0x759631d88c
	public Transform get_focusCenter() { }
	// RVA: 0x3d058f4 VA: 0x759631d8f4
	private Void _OnAnimatorStateChange(String stateName, AnimatorStateEvent stateEvent) { }
	// RVA: 0x3d063c4 VA: 0x759631e3c4
	protected virtual String get_interactAnimation() { }
	// RVA: 0x3d06440 VA: 0x759631e440
	public String get_id() { }
	// RVA: 0x3d05cd0 VA: 0x759631dcd0
	public String get_musicId() { }
	// RVA: 0x3d064a8 VA: 0x759631e4a8
	public override Vector3 get_worldCenter() { }
	// RVA: 0x3d05c60 VA: 0x759631dc60
	public Boolean get_isMusicFurniture() { }
	// RVA: 0x3d06510 VA: 0x759631e510
	public Boolean get_isPlaying() { }
	// RVA: 0x3d06578 VA: 0x759631e578
	public Boolean get_isFunctional() { }
	// RVA: 0x3d065e8 VA: 0x759631e5e8
	public Boolean get_isOutlineOn() { }
	// RVA: 0x3d06730 VA: 0x759631e730
	public FurnitureSubType get_subType() { }
	// RVA: 0x3d067f0 VA: 0x759631e7f0
	public Bounds get_bounds() { }
	// RVA: 0x3d06660 VA: 0x759631e660
	public VFurnitureOutline get_vFurnitureOutline() { }
	// RVA: 0x3d06900 VA: 0x759631e900
	public override Void Init(VRoom room, VGridPlane plane) { }
	// RVA: 0x3d069a0 VA: 0x759631e9a0
	public override Void OnInit() { }
	// RVA: 0x3d0700c VA: 0x759631f00c
	public Void SetData(IFurnitureController controller) { }
	// RVA: 0x3d07360 VA: 0x759631f360
	public override Void OnEnter() { }
	// RVA: 0x3d07574 VA: 0x759631f574
	public override Void OnExit() { }
	// RVA: 0x3d079c8 VA: 0x759631f9c8
	public override Boolean OnInteract() { }
	// RVA: 0x3d07be0 VA: 0x759631fbe0
	private Void _DoInteract() { }
	// RVA: 0x3d07eb8 VA: 0x759631feb8
	public Void StoppedByOthers() { }
	// RVA: 0x3d07f70 VA: 0x759631ff70
	public Void EnableOutline(Boolean value) { }
	// RVA: 0x3d07804 VA: 0x759631f804
	public Void ResetOutline() { }
	// RVA: 0x3d08000 VA: 0x7596320000
	public Transform GetFuncFurnitureBtnPos() { }
	// RVA: 0x3d07b24 VA: 0x759631fb24
	public Void OpenFunctionPage() { }
	// RVA: 0x3d07d34 VA: 0x759631fd34
	protected Void _InteractAnimation(String triggerName) { }
	// RVA: 0x3d05e98 VA: 0x759631de98
	private Void _InteractAnimation(String triggerName, Boolean value) { }
	// RVA: 0x3d07e0c VA: 0x759631fe0c
	protected IEnumerator _WaitInteractCooldown() { }
	// RVA: 0x3d05d38 VA: 0x759631dd38
	private Void _PlayMusic() { }
	// RVA: 0x3d05df4 VA: 0x759631ddf4
	private Void _StopMusic() { }
	// RVA: 0x3d080b8 VA: 0x75963200b8
	public Boolean IsVCharInteractable(VCharacter character) { }
	// RVA: 0x3d08140 VA: 0x7596320140
	public Void OnVCharInteract(VCharacter character) { }
	// RVA: 0x3d081bc VA: 0x75963201bc
	public Void OnInteractableChanged(Boolean interactable) { }
	// RVA: 0x3d0823c VA: 0x759632023c
	private Void OnDisable() { }
	// RVA: 0x3d082b0 VA: 0x75963202b0
	private Void OnEnable() { }
	// RVA: 0x3d08338 VA: 0x7596320338
	private Void OnDestroy() { }
	// RVA: 0x3d08610 VA: 0x7596320610
	public Void .ctor() { }
	// RVA: 0x3d0871c VA: 0x759632071c
	private Void <>xLuaBaseProxy_Init(VRoom P0, VGridPlane P1) { }
	// RVA: 0x3d08724 VA: 0x7596320724
	private Boolean <>xLuaBaseProxy_OnInteract() { }
}
```
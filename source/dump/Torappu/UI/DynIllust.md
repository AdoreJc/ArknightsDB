# DynIllust

**Namespace:** `Torappu.UI`


## Fields

- `SkeletonAnimation _skeleton`

- `Single _cameraSize`

- `Vector2 _maxSize`

- `Boolean _fixFxDelay`

- `DynIllustAction m_action`

- `Single m_loop`

- `DynIllustAction m_playingAction`

- `Animation m_playingAnim`

- `Single m_playEnd`

- `Boolean <started>k__BackingField`

- `Int64 m_lastEnableTick`


## Properties

- `SkeletonAnimation skeleton`

- `Vector2 maxSize`

- `Single cameraSize`

- `Boolean started`

- `DynIllustAction action`

- `DynIllustAction playingAction`

- `Single playingActionDur`

- `Single playingTime`

- `Single playingLoop`

- `Single activeTime`

- `Boolean _actionDataInitialized`


## Methods

- `Void add_eActionChanged(Action`1)`

- `Void remove_eActionChanged(Action`1)`

- `Void add_ePlayingActionChanged(Action`1)`

- `Void remove_ePlayingActionChanged(Action`1)`

- `SkeletonAnimation get_skeleton()`

- `Vector2 get_maxSize()`

- `Single get_cameraSize()`

- `Boolean get_started()`

- `Void set_started(Boolean)`

- `Void Awake()`

- `Void Start()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void Update()`

- `Void RebindAnimation()`

- `DynIllustAdjust GetAdjustParam(DynIllustAdjustType)`

- `Void set_action(DynIllustAction)`

- `DynIllustAction get_action()`

- `DynIllustAction get_playingAction()`

- `Single get_playingActionDur()`

- `Single get_playingTime()`

- `Single get_playingLoop()`

- `Single get_activeTime()`

- `Void ChangeAction(DynIllustAction, Single)`

- `Single GetActionDur(DynIllustAction)`

- `Void _ApplyAnimation()`

- `Boolean get__actionDataInitialized()`

- `Void CopyManualParam(DynIllust)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class DynIllust : MonoBehaviour, IHotfixable
{
	private SkeletonAnimation _skeleton; // 0x18
	private ActionParticle[] _particles; // 0x20
	private Animator[] _animators; // 0x28
	private Single _cameraSize; // 0x30
	private Vector2 _maxSize; // 0x34
	private DynIllustAdjust[] _adjustes; // 0x40
	private Boolean _fixFxDelay; // 0x48
	private DynIllustAction m_action; // 0x4c
	private Single m_loop; // 0x50
	private DynIllustAction m_playingAction; // 0x54
	private Animation m_playingAnim; // 0x58
	private Single m_playEnd; // 0x60
	private Action`1 eActionChanged; // 0x68
	private Action`1 ePlayingActionChanged; // 0x70
	private Boolean <started>k__BackingField; // 0x78
	private Int64 m_lastEnableTick; // 0x80
	private static Dictionary`2 s_animatorTriggerDict; // 0x0
	private static DelegateBridge __Hotfix0_add_eActionChanged; // 0x8
	private static DelegateBridge __Hotfix0_remove_eActionChanged; // 0x10
	private static DelegateBridge __Hotfix0_add_ePlayingActionChanged; // 0x18
	private static DelegateBridge __Hotfix0_remove_ePlayingActionChanged; // 0x20
	private static DelegateBridge __Hotfix0_get_skeleton; // 0x28
	private static DelegateBridge __Hotfix0_get_maxSize; // 0x30
	private static DelegateBridge __Hotfix0_get_cameraSize; // 0x38
	private static DelegateBridge __Hotfix0_get_started; // 0x40
	private static DelegateBridge __Hotfix0_set_started; // 0x48
	private static DelegateBridge __Hotfix0_Awake; // 0x50
	private static DelegateBridge __Hotfix0_Start; // 0x58
	private static DelegateBridge __Hotfix0_OnEnable; // 0x60
	private static DelegateBridge __Hotfix0_OnDisable; // 0x68
	private static DelegateBridge __Hotfix0_Update; // 0x70
	private static DelegateBridge __Hotfix0_RebindAnimation; // 0x78
	private static DelegateBridge __Hotfix0_GetAdjustParam; // 0x80
	private static DelegateBridge __Hotfix0_set_action; // 0x88
	private static DelegateBridge __Hotfix0_get_action; // 0x90
	private static DelegateBridge __Hotfix0_get_playingAction; // 0x98
	private static DelegateBridge __Hotfix0_get_playingActionDur; // 0xa0
	private static DelegateBridge __Hotfix0_get_playingTime; // 0xa8
	private static DelegateBridge __Hotfix0_get_playingLoop; // 0xb0
	private static DelegateBridge __Hotfix0_get_activeTime; // 0xb8
	private static DelegateBridge __Hotfix0_ChangeAction; // 0xc0
	private static DelegateBridge __Hotfix0_GetActionDur; // 0xc8
	private static DelegateBridge __Hotfix0__ApplyAnimation; // 0xd0
	private static DelegateBridge __Hotfix0_get__actionDataInitialized; // 0xd8
	private static DelegateBridge __Hotfix0_CopyManualParam; // 0xe0
	private static DelegateBridge __Hotfix0_GetAnimationName; // 0xe8
	private static DelegateBridge __Hotfix0_GetActionType; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8

	public SkeletonAnimation skeleton { get; }
	public Vector2 maxSize { get; }
	public Single cameraSize { get; }
	public Boolean started { get; set; }
	public DynIllustAction action { get; set; }
	public DynIllustAction playingAction { get; }
	public Single playingActionDur { get; }
	public Single playingTime { get; }
	public Single playingLoop { get; }
	public Single activeTime { get; }
	private Boolean _actionDataInitialized { get; }

	// RVA: 0x210ffa4 VA: 0x7594727fa4
	public Void add_eActionChanged(Action`1 value) { }
	// RVA: 0x21100a8 VA: 0x75947280a8
	public Void remove_eActionChanged(Action`1 value) { }
	// RVA: 0x21101ac VA: 0x75947281ac
	public Void add_ePlayingActionChanged(Action`1 value) { }
	// RVA: 0x21102b0 VA: 0x75947282b0
	public Void remove_ePlayingActionChanged(Action`1 value) { }
	// RVA: 0x21103b4 VA: 0x75947283b4
	public SkeletonAnimation get_skeleton() { }
	// RVA: 0x211042c VA: 0x759472842c
	public Vector2 get_maxSize() { }
	// RVA: 0x21104a0 VA: 0x75947284a0
	public Single get_cameraSize() { }
	// RVA: 0x2110518 VA: 0x7594728518
	public Boolean get_started() { }
	// RVA: 0x2110590 VA: 0x7594728590
	private Void set_started(Boolean value) { }
	// RVA: 0x2110620 VA: 0x7594728620
	private Void Awake() { }
	// RVA: 0x211079c VA: 0x759472879c
	private Void Start() { }
	// RVA: 0x2110818 VA: 0x7594728818
	private Void OnEnable() { }
	// RVA: 0x21109bc VA: 0x75947289bc
	private Void OnDisable() { }
	// RVA: 0x2110a38 VA: 0x7594728a38
	private Void Update() { }
	// RVA: 0x2110ad4 VA: 0x7594728ad4
	public Void RebindAnimation() { }
	// RVA: 0x2110b94 VA: 0x7594728b94
	public DynIllustAdjust GetAdjustParam(DynIllustAdjustType type) { }
	// RVA: 0x2110cb8 VA: 0x7594728cb8
	public Void set_action(DynIllustAction value) { }
	// RVA: 0x2110d68 VA: 0x7594728d68
	public DynIllustAction get_action() { }
	// RVA: 0x2110de0 VA: 0x7594728de0
	public DynIllustAction get_playingAction() { }
	// RVA: 0x2110e58 VA: 0x7594728e58
	public Single get_playingActionDur() { }
	// RVA: 0x2110ee0 VA: 0x7594728ee0
	public Single get_playingTime() { }
	// RVA: 0x2110f8c VA: 0x7594728f8c
	public Single get_playingLoop() { }
	// RVA: 0x2111048 VA: 0x7594729048
	public Single get_activeTime() { }
	// RVA: 0x21108ec VA: 0x75947288ec
	public Void ChangeAction(DynIllustAction action, Single loop) { }
	// RVA: 0x21115b0 VA: 0x75947295b0
	public Single GetActionDur(DynIllustAction action) { }
	// RVA: 0x2111148 VA: 0x7594729148
	private Void _ApplyAnimation() { }
	// RVA: 0x21116b8 VA: 0x75947296b8
	private Boolean get__actionDataInitialized() { }
	// RVA: 0x2111898 VA: 0x7594729898
	public Void CopyManualParam(DynIllust src) { }
	// RVA: 0x2111798 VA: 0x7594729798
	public static String GetAnimationName(DynIllustAction action) { }
	// RVA: 0x2111944 VA: 0x7594729944
	public static DynIllustAction GetActionType(String name) { }
	// RVA: 0x2111a78 VA: 0x7594729a78
	public Void .ctor() { }
	// RVA: 0x2111b2c VA: 0x7594729b2c
	private static Void .cctor() { }
}
```
# AVGEffectItem

**Namespace:** `Torappu.AVG`


## Fields

- `Single _effectDuration`

- `FadeType _fadeType`

- `Animation _fadeAnimation`

- `Animator _effectAnimator`

- `FxUVTweenerAdvance _tweenController`

- `SmoothStep m_particleFadeTween`

- `State m_state`

- `Boolean m_animatorEnd`


## Properties

- `Single duration`

- `FadeType fadeType`

- `Animator animator`


## Methods

- `Single get_duration()`

- `Void set_duration(Single)`

- `FadeType get_fadeType()`

- `Animator get_animator()`

- `Void set_animator(Animator)`

- `Void OnEnable()`

- `Void OnDestroy()`

- `Void _CacheParam()`

- `Void InitEffectShow(Single)`

- `Void _ProcessAnimation(Single)`

- `Void _ProcessAnimatorHide(Single)`

- `Void _ProcessAnimatorShow(Single)`

- `Void _OnAnimatorDestroy()`

- `IEnumerator _CheckAnimatorState(Animator, String, Action)`

- `Boolean _CheckAnimatorState(Animator, String)`

- `Void _ProcessTween(Single)`

- `Void _ProcessEmission(Single)`

- `Void HideEffect(Single)`

- `Void _ProcessEmissionState(Boolean, Single)`

- `Void _ProcessParticleEmissions(Boolean)`

- `Void _ProcessTwHide(Single)`

- `Void Update()`

- `Void _OnStateChage(State, State)`

- `Void _UpdateParticleCount(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGEffectItem : MonoBehaviour, IHotfixable
{
	private Single _effectDuration; // 0x18
	private FadeType _fadeType; // 0x1c
	private ParticleSystem[] _particleSystemList; // 0x20
	private Animation _fadeAnimation; // 0x28
	private Animator _effectAnimator; // 0x30
	private MeshRenderer[] _meshRenderers; // 0x38
	private FxUVTweenerAdvance _tweenController; // 0x40
	private SmoothStep m_particleFadeTween; // 0x48
	private Int32[] maxParticleTarget; // 0x80
	private State m_state; // 0x88
	private Boolean m_animatorEnd; // 0x8c
	private const String ANIMATOR_CONDITION_END; // 0x0
	private const String ANIMATOR_DESTORY_STATE_NAME; // 0x0
	private static DelegateBridge __Hotfix0_get_duration; // 0x0
	private static DelegateBridge __Hotfix0_set_duration; // 0x8
	private static DelegateBridge __Hotfix0_get_fadeType; // 0x10
	private static DelegateBridge __Hotfix0_get_animator; // 0x18
	private static DelegateBridge __Hotfix0_set_animator; // 0x20
	private static DelegateBridge __Hotfix0_get_imageEffectMeshRenderers; // 0x28
	private static DelegateBridge __Hotfix0_OnEnable; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0__CacheParam; // 0x40
	private static DelegateBridge __Hotfix0_InitEffectShow; // 0x48
	private static DelegateBridge __Hotfix0__ProcessAnimation; // 0x50
	private static DelegateBridge __Hotfix0__ProcessAnimatorHide; // 0x58
	private static DelegateBridge __Hotfix0__ProcessAnimatorShow; // 0x60
	private static DelegateBridge __Hotfix0__OnAnimatorDestroy; // 0x68
	private static DelegateBridge __Hotfix0__CheckAnimatorState; // 0x70
	private static DelegateBridge __Hotfix1__CheckAnimatorState; // 0x78
	private static DelegateBridge __Hotfix0__ProcessTween; // 0x80
	private static DelegateBridge __Hotfix0__ProcessEmission; // 0x88
	private static DelegateBridge __Hotfix0_HideEffect; // 0x90
	private static DelegateBridge __Hotfix0__ProcessEmissionState; // 0x98
	private static DelegateBridge __Hotfix0__ProcessParticleEmissions; // 0xa0
	private static DelegateBridge __Hotfix0__ProcessTwHide; // 0xa8
	private static DelegateBridge __Hotfix0_Update; // 0xb0
	private static DelegateBridge __Hotfix0__OnStateChage; // 0xb8
	private static DelegateBridge __Hotfix0__UpdateParticleCount; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public Single duration { get; set; }
	public FadeType fadeType { get; }
	public Animator animator { get; set; }
	public MeshRenderer[] imageEffectMeshRenderers { get; }

	// RVA: 0x3ea5a68 VA: 0x75964bda68
	public Single get_duration() { }
	// RVA: 0x3ea5ad0 VA: 0x75964bdad0
	public Void set_duration(Single value) { }
	// RVA: 0x3ea5b4c VA: 0x75964bdb4c
	public FadeType get_fadeType() { }
	// RVA: 0x3ea5bb4 VA: 0x75964bdbb4
	public Animator get_animator() { }
	// RVA: 0x3ea5c1c VA: 0x75964bdc1c
	public Void set_animator(Animator value) { }
	// RVA: 0x3ea5ca0 VA: 0x75964bdca0
	public MeshRenderer[] get_imageEffectMeshRenderers() { }
	// RVA: 0x3ea5d08 VA: 0x75964bdd08
	private Void OnEnable() { }
	// RVA: 0x3ea5d6c VA: 0x75964bdd6c
	private Void OnDestroy() { }
	// RVA: 0x3ea5e50 VA: 0x75964bde50
	private Void _CacheParam() { }
	// RVA: 0x3ea5fb0 VA: 0x75964bdfb0
	public Void InitEffectShow(Single duration) { }
	// RVA: 0x3ea60b0 VA: 0x75964be0b0
	private Void _ProcessAnimation(Single duration) { }
	// RVA: 0x3ea654c VA: 0x75964be54c
	private Void _ProcessAnimatorHide(Single duration) { }
	// RVA: 0x3ea63b8 VA: 0x75964be3b8
	private Void _ProcessAnimatorShow(Single duration) { }
	// RVA: 0x3ea68ac VA: 0x75964be8ac
	private Void _OnAnimatorDestroy() { }
	// RVA: 0x3ea67a0 VA: 0x75964be7a0
	private IEnumerator _CheckAnimatorState(Animator animator, String stateName, Action callback) { }
	// RVA: 0x3ea6940 VA: 0x75964be940
	private Boolean _CheckAnimatorState(Animator animator, String stateName) { }
	// RVA: 0x3ea61a4 VA: 0x75964be1a4
	private Void _ProcessTween(Single duration) { }
	// RVA: 0x3ea62dc VA: 0x75964be2dc
	private Void _ProcessEmission(Single duration) { }
	// RVA: 0x3ea6e20 VA: 0x75964bee20
	public Void HideEffect(Single duration) { }
	// RVA: 0x3ea6cac VA: 0x75964becac
	private Void _ProcessEmissionState(Boolean isShow, Single duration) { }
	// RVA: 0x3ea6bac VA: 0x75964bebac
	private Void _ProcessParticleEmissions(Boolean active) { }
	// RVA: 0x3ea6f04 VA: 0x75964bef04
	private Void _ProcessTwHide(Single duration) { }
	// RVA: 0x3ea6ff0 VA: 0x75964beff0
	private Void Update() { }
	// RVA: 0x3ea7110 VA: 0x75964bf110
	private Void _OnStateChage(State from, State to) { }
	// RVA: 0x3ea6a10 VA: 0x75964bea10
	private Void _UpdateParticleCount(Single multiplior) { }
	// RVA: 0x3ea71ec VA: 0x75964bf1ec
	public Void .ctor() { }
}
```
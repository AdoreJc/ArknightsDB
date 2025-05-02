# BuildingEffect

**Namespace:** `Torappu.Building.Vault`


## Fields

- `Single _predelay`

- `Single _delayToFinish`

- `FP _playProbability`

- `ParticleSystem m_particleSystem`

- `Animator m_animator`

- `Boolean m_isPlaying`

- `Boolean m_isPreDelay`

- `Boolean m_isDelayToFinish`

- `Single m_delayToFinishTime`

- `Single m_predelay`

- `String m_triggerkey`


## Properties

- `ParticleSystem particleSystem`

- `Boolean isValid`


## Methods

- `ParticleSystem get_particleSystem()`

- `Boolean get_isValid()`

- `Void Awake()`

- `Void Init()`

- `Void Reset()`

- `Void LateUpdate()`

- `Void Play()`

- `Void _PlayInternal()`

- `Void Stop()`

- `Void SetTrigger(String)`

- `Void FinishMe()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class BuildingEffect : MonoBehaviour
{
	private const String EFFECT_TRIGGER_KEY; // 0x0
	private Single _predelay; // 0x18
	private Single _delayToFinish; // 0x1c
	private FP _playProbability; // 0x20
	private ParticleSystem m_particleSystem; // 0x28
	private Animator m_animator; // 0x30
	private Boolean m_isPlaying; // 0x38
	private Boolean m_isPreDelay; // 0x39
	private Boolean m_isDelayToFinish; // 0x3a
	private Single m_delayToFinishTime; // 0x3c
	private Single m_predelay; // 0x40
	private String m_triggerkey; // 0x48

	protected ParticleSystem particleSystem { get; }
	private Boolean isValid { get; }

	// RVA: 0x3845d80 VA: 0x7595e5dd80
	protected ParticleSystem get_particleSystem() { }
	// RVA: 0x3845d88 VA: 0x7595e5dd88
	private Boolean get_isValid() { }
	// RVA: 0x3845db0 VA: 0x7595e5ddb0
	public Void Awake() { }
	// RVA: 0x3845df4 VA: 0x7595e5ddf4
	public Void Init() { }
	// RVA: 0x3845ecc VA: 0x7595e5decc
	public Void Reset() { }
	// RVA: 0x3846024 VA: 0x7595e5e024
	private Void LateUpdate() { }
	// RVA: 0x3846174 VA: 0x7595e5e174
	public Void Play() { }
	// RVA: 0x38460c4 VA: 0x7595e5e0c4
	private Void _PlayInternal() { }
	// RVA: 0x3846258 VA: 0x7595e5e258
	public Void Stop() { }
	// RVA: 0x3846278 VA: 0x7595e5e278
	public Void SetTrigger(String triggerKey) { }
	// RVA: 0x3846170 VA: 0x7595e5e170
	public Void FinishMe() { }
	// RVA: 0x384633c VA: 0x7595e5e33c
	public Void .ctor() { }
}
```
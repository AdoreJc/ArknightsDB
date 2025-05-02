# EffectOptions

**Namespace:** ` `


## Fields

- `DirectionType _directionType`

- `UberEffectEmitter m_holder`


## Properties

- `String effect`

- `Boolean isSingle`

- `Single playbackSpeed`

- `Entity owner`

- `Boolean isFirstAttack`


## Methods

- `String get_effect()`

- `Void set_effect(String)`

- `Void set_effects(String[])`

- `Boolean get_isSingle()`

- `Single get_playbackSpeed()`

- `Entity get_owner()`

- `Boolean get_isFirstAttack()`

- `Boolean TryGetEffect(out)`

- `Entity GetInputTargetAsEntity()`

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EffectOptions
{
	public DirectionType _directionType; // 0x10
	private String[] _effects; // 0x18
	protected UberEffectEmitter m_holder; // 0x20

	public String effect { get; set; }
	public String[] effects { get; set; }
	public Boolean isSingle { get; }
	protected Single playbackSpeed { get; }
	protected Entity owner { get; }
	protected KeyValuePair`2 inputTarget { get; }
	protected Boolean isFirstAttack { get; }
	protected List`1 castTargets { get; }

	// RVA: 0x1ecb648 VA: 0x75944e3648
	public String get_effect() { }
	// RVA: 0x1ecb670 VA: 0x75944e3670
	public Void set_effect(String value) { }
	// RVA: 0x1ecb6d0 VA: 0x75944e36d0
	public String[] get_effects() { }
	// RVA: 0x1ecb6d8 VA: 0x75944e36d8
	public Void set_effects(String[] value) { }
	// RVA: 0x1ecb6e0 VA: 0x75944e36e0
	public Boolean get_isSingle() { }
	// RVA: 0x1ecb6f0 VA: 0x75944e36f0
	protected Single get_playbackSpeed() { }
	// RVA: 0x1ecb710 VA: 0x75944e3710
	protected Entity get_owner() { }
	// RVA: 0x1ecb72c VA: 0x75944e372c
	protected KeyValuePair`2 get_inputTarget() { }
	// RVA: 0x1ecb76c VA: 0x75944e376c
	protected Boolean get_isFirstAttack() { }
	// RVA: 0x1ecb788 VA: 0x75944e3788
	protected List`1 get_castTargets() { }
	// RVA: 0x1ecb7a4 VA: 0x75944e37a4
	public virtual Void Init(UberEffectEmitter holder) { }
	// RVA: 0x1ecb7ac VA: 0x75944e37ac
	public virtual Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1ecb7b0 VA: 0x75944e37b0
	public virtual Void OnCastStart() { }
	// RVA: 0x1ecb7b4 VA: 0x75944e37b4
	public virtual Void OnCastFinish() { }
	// RVA: 0x1ecb7b8 VA: 0x75944e37b8
	public virtual Void OnEvent(Event ev) { }
	// RVA: 0x1ecb7bc VA: 0x75944e37bc
	protected Boolean TryGetEffect(out String effect) { }
	// RVA: 0x1ecbb54 VA: 0x75944e3b54
	protected Entity GetInputTargetAsEntity() { }
	// RVA: 0x1ec84a8 VA: 0x75944e04a8
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ecbc1c VA: 0x75944e3c1c
	public override String ToString() { }
	// RVA: 0x1ecbcb0 VA: 0x75944e3cb0
	public Void .ctor() { }
}
```
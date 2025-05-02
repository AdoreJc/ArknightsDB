# CastEffectOptions

**Namespace:** ` `


## Fields

- `Boolean _oneshot`

- `Event _startEvent`

- `Event _endEvent`

- `Boolean _onlyOnce`

- `Boolean _useFourDirectionalFace`

- `Single _delayIfFirstAttack`

- `String _hookEffectAfterFirstAttack`

- `Boolean m_casted`


## Properties

- `Boolean oneshot`


## Methods

- `Boolean get_oneshot()`

- `Void _ClearEffects()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CastEffectOptions : EffectOptions
{
	private Boolean _oneshot; // 0x28
	private Event _startEvent; // 0x2c
	private Event _endEvent; // 0x30
	private Boolean _onlyOnce; // 0x34
	private Boolean _useFourDirectionalFace; // 0x35
	private Single _delayIfFirstAttack; // 0x38
	private String _hookEffectAfterFirstAttack; // 0x40
	private Boolean m_casted; // 0x48
	protected List`1 m_effects; // 0x50

	public Boolean oneshot { get; }

	// RVA: 0x1ecc52c VA: 0x75944e452c
	public Boolean get_oneshot() { }
	// RVA: 0x1ecc534 VA: 0x75944e4534
	public override Void Init(UberEffectEmitter holder) { }
	// RVA: 0x1ecc5dc VA: 0x75944e45dc
	public override Void OnCastStart() { }
	// RVA: 0x1ecc658 VA: 0x75944e4658
	public override Void OnCastFinish() { }
	// RVA: 0x1ecc7a4 VA: 0x75944e47a4
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ecc924 VA: 0x75944e4924
	public override String ToString() { }
	// RVA: 0x1ec7a4c VA: 0x75944dfa4c
	protected virtual Effect CreateEffect(String effect) { }
	// RVA: 0x1eccc04 VA: 0x75944e4c04
	protected virtual Void PlayEffect() { }
	// RVA: 0x1ecc668 VA: 0x75944e4668
	private Void _ClearEffects() { }
	// RVA: 0x1ec7bfc VA: 0x75944dfbfc
	public Void .ctor() { }
}
```
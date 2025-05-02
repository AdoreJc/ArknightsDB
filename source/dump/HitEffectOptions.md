# HitEffectOptions

**Namespace:** ` `


## Fields

- `Boolean _oneshot`

- `Event _endEvent`

- `Boolean _onlyOnce`

- `Boolean _useFourDirectionalFace`

- `Boolean _useOwnerToTargetDirection`

- `Boolean _playIfNotInputTarget`

- `Boolean _playOnlyIfInputTarget`

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
public class HitEffectOptions : EffectOptions
{
	private Boolean _oneshot; // 0x28
	private Event _endEvent; // 0x2c
	private Boolean _onlyOnce; // 0x30
	private Boolean _useFourDirectionalFace; // 0x31
	private Boolean _useOwnerToTargetDirection; // 0x32
	private Boolean _playIfNotInputTarget; // 0x33
	private Boolean _playOnlyIfInputTarget; // 0x34
	private Boolean m_casted; // 0x35
	private List`1 m_effects; // 0x38

	public Boolean oneshot { get; }

	// RVA: 0x1ecbd14 VA: 0x75944e3d14
	public Boolean get_oneshot() { }
	// RVA: 0x1ecbd1c VA: 0x75944e3d1c
	public override Void Init(UberEffectEmitter holder) { }
	// RVA: 0x1ecbdc4 VA: 0x75944e3dc4
	public override Void OnCastStart() { }
	// RVA: 0x1ecbe40 VA: 0x75944e3e40
	public override Void OnCastFinish() { }
	// RVA: 0x1ecbf8c VA: 0x75944e3f8c
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1ecc430 VA: 0x75944e4430
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ecc44c VA: 0x75944e444c
	public override String ToString() { }
	// RVA: 0x1ecbe50 VA: 0x75944e3e50
	private Void _ClearEffects() { }
	// RVA: 0x1ecc518 VA: 0x75944e4518
	public Void .ctor() { }
}
```
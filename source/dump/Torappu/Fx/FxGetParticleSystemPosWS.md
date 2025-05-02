# FxGetParticleSystemPosWS

**Namespace:** `Torappu.Fx`


## Fields

- `Boolean _needUpdate`

- `Material m_activeMaterial`

- `ParticleSystemRenderer m_renderer`


## Properties

- `Material activeMaterial`


## Methods

- `Material get_activeMaterial()`

- `Void Awake()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Fx
public class FxGetParticleSystemPosWS : MonoBehaviour, IHotfixable
{
	private static readonly Int32 PARTICLE_POSITION_WS_ID; // 0x0
	private Boolean _needUpdate; // 0x18
	private Material m_activeMaterial; // 0x20
	private ParticleSystemRenderer m_renderer; // 0x28
	private static DelegateBridge __Hotfix0_get_activeMaterial; // 0x8
	private static DelegateBridge __Hotfix0_Awake; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Material activeMaterial { get; }

	// RVA: 0x3efcb34 VA: 0x7596514b34
	private Material get_activeMaterial() { }
	// RVA: 0x3efcc20 VA: 0x7596514c20
	private Void Awake() { }
	// RVA: 0x3efcd80 VA: 0x7596514d80
	private Void Update() { }
	// RVA: 0x3efceac VA: 0x7596514eac
	public Void .ctor() { }
	// RVA: 0x3efcf2c VA: 0x7596514f2c
	private static Void .cctor() { }
}
```
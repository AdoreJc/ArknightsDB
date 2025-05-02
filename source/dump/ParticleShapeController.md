# ParticleShapeController

**Namespace:** ` `


## Fields

- `RectTransform m_target`

- `ScreenEffectHolder m_effectHolder`

- `ParticleSystem m_particle`

- `Vector3 m_rawShapeSize`


## Methods

- `Void NotifyLayoutReady()`

- `Void Tick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ParticleShapeController : IHotfixable
{
	private RectTransform m_target; // 0x10
	private ScreenEffectHolder m_effectHolder; // 0x18
	private ParticleSystem m_particle; // 0x20
	private Vector3 m_rawShapeSize; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_NotifyLayoutReady; // 0x8
	private static DelegateBridge __Hotfix0_Tick; // 0x10


	// RVA: 0x2412574 VA: 0x7594a2a574
	public Void .ctor(SiracusaMapBigMapView closure) { }
	// RVA: 0x2412620 VA: 0x7594a2a620
	public Void NotifyLayoutReady() { }
	// RVA: 0x2412768 VA: 0x7594a2a768
	public Void Tick() { }
}
```
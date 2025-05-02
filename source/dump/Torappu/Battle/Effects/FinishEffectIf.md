# FinishEffectIf

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _finishIfOwnerInvalid`

- `Boolean _finishIfCurrentAnimFinish`

- `Boolean _finishIfNotDummy`

- `Animator m_animator`


## Methods

- `Void Update()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class FinishEffectIf : Behaviour, IHotfixable
{
	private Boolean _finishIfOwnerInvalid; // 0x20
	private Boolean _finishIfCurrentAnimFinish; // 0x21
	private Boolean _finishIfNotDummy; // 0x22
	private Animator m_animator; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_Awake; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1ffac2c VA: 0x7594612c2c
	private Void Update() { }
	// RVA: 0x1ffaea0 VA: 0x7594612ea0
	private Void Awake() { }
	// RVA: 0x1ffaf44 VA: 0x7594612f44
	public Void .ctor() { }
}
```
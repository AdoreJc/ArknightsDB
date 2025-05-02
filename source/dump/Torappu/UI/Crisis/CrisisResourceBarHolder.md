# CrisisResourceBarHolder

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `Transform _container`

- `CrisisResourceBar _resourceBar`

- `Option _option`

- `CrisisResourceBar m_resourceBar`


## Methods

- `Void InitAndBind()`

- `Void UnBind()`

- `Void OnEnable()`

- `Void OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisResourceBarHolder : MonoBehaviour, IHotfixable
{
	private Transform _container; // 0x18
	private CrisisResourceBar _resourceBar; // 0x20
	private Option _option; // 0x28
	private CrisisResourceBar m_resourceBar; // 0x30
	private static DelegateBridge __Hotfix0_InitAndBind; // 0x0
	private static DelegateBridge __Hotfix0_UnBind; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0_OnDisable; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2c37404 VA: 0x759524f404
	public Void InitAndBind() { }
	// RVA: 0x2c3750c VA: 0x759524f50c
	public Void UnBind() { }
	// RVA: 0x2c3757c VA: 0x759524f57c
	private Void OnEnable() { }
	// RVA: 0x2c375e4 VA: 0x759524f5e4
	private Void OnDisable() { }
	// RVA: 0x2c3764c VA: 0x759524f64c
	public Void .ctor() { }
}
```
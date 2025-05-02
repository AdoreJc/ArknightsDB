# FxAnimationEvent

**Namespace:** `Torappu.Fx`


## Fields

- `Boolean _disableAllOnEnable`


## Methods

- `Void OnEnable()`

- `Void EnableObject(String)`

- `Void DisbaleObject(String)`

- `Void DisableAndEnableObject(String)`

- `Void DisableAll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Fx
public class FxAnimationEvent : MonoBehaviour, IHotfixable
{
	private List`1 _objects; // 0x18
	private Boolean _disableAllOnEnable; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_EnableObject; // 0x8
	private static DelegateBridge __Hotfix0_DisbaleObject; // 0x10
	private static DelegateBridge __Hotfix0_DisableAndEnableObject; // 0x18
	private static DelegateBridge __Hotfix0_DisableAll; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3efbf2c VA: 0x7596513f2c
	private Void OnEnable() { }
	// RVA: 0x3efc12c VA: 0x759651412c
	public Void EnableObject(String name) { }
	// RVA: 0x3efc2f4 VA: 0x75965142f4
	public Void DisbaleObject(String name) { }
	// RVA: 0x3efc4bc VA: 0x75965144bc
	public Void DisableAndEnableObject(String name) { }
	// RVA: 0x3efbfa8 VA: 0x7596513fa8
	public Void DisableAll() { }
	// RVA: 0x3efc698 VA: 0x7596514698
	public Void .ctor() { }
}
```
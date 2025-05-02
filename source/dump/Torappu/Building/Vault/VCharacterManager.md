# VCharacterManager

**Namespace:** `Torappu.Building.Vault`


## Methods

- `Boolean Register(VCharacter)`

- `Boolean Unregister(VCharacter)`

- `Void ClearAll()`

- `Void OnFixedUpdate(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VCharacterManager : Singleton`1
{
	private List`1 m_list; // 0x10
	private static DelegateBridge __Hotfix0_Register; // 0x0
	private static DelegateBridge __Hotfix0_Unregister; // 0x8
	private static DelegateBridge __Hotfix0_ClearAll; // 0x10
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3cf8820 VA: 0x7596310820
	public Boolean Register(VCharacter character) { }
	// RVA: 0x3cf89d8 VA: 0x75963109d8
	public Boolean Unregister(VCharacter character) { }
	// RVA: 0x3cf7978 VA: 0x759630f978
	public Void ClearAll() { }
	// RVA: 0x3cf84b4 VA: 0x75963104b4
	public Void OnFixedUpdate(Single deltaTime) { }
	// RVA: 0x3cf966c VA: 0x759631166c
	public Void .ctor() { }
}
```
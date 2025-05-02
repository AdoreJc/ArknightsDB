# VOUIOrthoPrefabConfig

**Namespace:** `Torappu.Building.Vault.UI`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault.UI
public class VOUIOrthoPrefabConfig : ScriptableObject, IHotfixable
{
	private VOUIPanel[] _orthoCharUIPrefs; // 0x18
	private VOUIPanel[] _orthoFurniUIPrefs; // 0x20
	private static DelegateBridge __Hotfix0_GetOrthoCharPrefabs; // 0x0
	private static DelegateBridge __Hotfix0_GetOrthoFurniPrefabs; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3d09a00 VA: 0x7596321a00
	public IEnumerator`1 GetOrthoCharPrefabs(BuildingEvent evt, Object roomObject) { }
	// RVA: 0x3d09b04 VA: 0x7596321b04
	public IEnumerator`1 GetOrthoFurniPrefabs(BuildingEvent evt, Object roomObject) { }
	// RVA: 0x3d09c08 VA: 0x7596321c08
	public Void .ctor() { }
}
```
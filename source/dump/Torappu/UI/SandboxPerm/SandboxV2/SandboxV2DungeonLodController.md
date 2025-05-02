# SandboxV2DungeonLodController

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Single m_lod`

- `SandboxV2DungeonLodRank m_lodRank`


## Methods

- `Void Watch(ISandboxV2DungeonLodElement)`

- `Void Unwatch(ISandboxV2DungeonLodElement)`

- `Void UpdateLod(Single, SandboxV2DungeonLodRank)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonLodController : MonoBehaviour, IHotfixable
{
	private HashSet`1 m_lodElements; // 0x18
	private Single m_lod; // 0x20
	private SandboxV2DungeonLodRank m_lodRank; // 0x24
	private static DelegateBridge __Hotfix0_Watch; // 0x0
	private static DelegateBridge __Hotfix0_Unwatch; // 0x8
	private static DelegateBridge __Hotfix0_UpdateLod; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2512ea0 VA: 0x7594b2aea0
	public Void Watch(ISandboxV2DungeonLodElement element) { }
	// RVA: 0x2513010 VA: 0x7594b2b010
	public Void Unwatch(ISandboxV2DungeonLodElement element) { }
	// RVA: 0x25130ec VA: 0x7594b2b0ec
	public Void UpdateLod(Single normalizedLod, SandboxV2DungeonLodRank lodRank) { }
	// RVA: 0x25132fc VA: 0x7594b2b2fc
	public Void .ctor() { }
}
```
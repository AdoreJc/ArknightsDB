# SandboxV2DungeonFloatGroupViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean isEnemyRush`

- `Int32 stackCount`

- `Single hpRatio`


## Methods

- `Boolean IsEmpty()`

- `Void Clear()`

- `Void AddFloat(SandboxV2DungeonFloatViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonFloatGroupViewModel : IHotfixable
{
	public List`1 floatList; // 0x10
	public List`1 floatKeys; // 0x18
	public Boolean isEnemyRush; // 0x20
	public Int32 stackCount; // 0x24
	public Single hpRatio; // 0x28
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x0
	private static DelegateBridge __Hotfix0_Clear; // 0x8
	private static DelegateBridge __Hotfix0_AddFloat; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25bf3f8 VA: 0x7594bd73f8
	public Boolean IsEmpty() { }
	// RVA: 0x25babec VA: 0x7594bd2bec
	public Void Clear() { }
	// RVA: 0x25ba810 VA: 0x7594bd2810
	public Void AddFloat(SandboxV2DungeonFloatViewModel floatViewModel) { }
	// RVA: 0x25bbc38 VA: 0x7594bd3c38
	public Void .ctor() { }
}
```
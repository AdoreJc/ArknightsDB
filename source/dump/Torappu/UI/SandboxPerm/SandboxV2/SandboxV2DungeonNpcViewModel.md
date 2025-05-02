# SandboxV2DungeonNpcViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String npcId`

- `Int32 instId`

- `Boolean isBlackMarketNpc`

- `String npcTrapId`

- `Boolean enabled`

- `SandboxV2NpcType npcType`


## Methods

- `Void UpdateData(UpdateParam)`

- `Int32 <>xLuaBaseProxy_CompareDungeonFloat(SandboxV2DungeonFloatViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNpcViewModel : SandboxV2DungeonFloatViewModel
{
	private const String UNIQUE_ID_FORMAT; // 0x0
	public String npcId; // 0x60
	public Int32 instId; // 0x68
	public Boolean isBlackMarketNpc; // 0x6c
	public String npcTrapId; // 0x70
	public Boolean enabled; // 0x78
	public SandboxV2NpcType npcType; // 0x7c
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge __Hotfix0_CompareDungeonFloat; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x25b9e9c VA: 0x7594bd1e9c
	public Void UpdateData(UpdateParam updateParam) { }
	// RVA: 0x25c0a38 VA: 0x7594bd8a38
	public override Int32 CompareDungeonFloat(SandboxV2DungeonFloatViewModel other) { }
	// RVA: 0x25b9e30 VA: 0x7594bd1e30
	public Void .ctor() { }
	// RVA: 0x25c0b08 VA: 0x7594bd8b08
	private Int32 <>xLuaBaseProxy_CompareDungeonFloat(SandboxV2DungeonFloatViewModel P0) { }
}
```
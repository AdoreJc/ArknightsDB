# SandboxV2DungeonEventViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String eventId`

- `Int32 instId`

- `SandboxV2EventType eventType`

- `String sceneId`

- `Boolean finished`

- `Boolean isOriginal`


## Methods

- `Void UpdateData(UpdateParam)`

- `Int32 <>xLuaBaseProxy_CompareDungeonFloat(SandboxV2DungeonFloatViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonEventViewModel : SandboxV2DungeonFloatViewModel
{
	private const String FLOAT_ICON_ID_ENCOUNTER; // 0x0
	private const String FLOAT_ICON_ID_EXPEDITION; // 0x0
	private const String UNIQUE_ID_FORMAT; // 0x0
	public String eventId; // 0x60
	public Int32 instId; // 0x68
	public SandboxV2EventType eventType; // 0x6c
	public String sceneId; // 0x70
	public Boolean finished; // 0x78
	public Boolean isOriginal; // 0x79
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge __Hotfix0_CompareDungeonFloat; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x25ba344 VA: 0x7594bd2344
	public Void UpdateData(UpdateParam updateParam) { }
	// RVA: 0x25c0154 VA: 0x7594bd8154
	public override Int32 CompareDungeonFloat(SandboxV2DungeonFloatViewModel other) { }
	// RVA: 0x25ba2d8 VA: 0x7594bd22d8
	public Void .ctor() { }
	// RVA: 0x25c0224 VA: 0x7594bd8224
	private Int32 <>xLuaBaseProxy_CompareDungeonFloat(SandboxV2DungeonFloatViewModel P0) { }
}
```
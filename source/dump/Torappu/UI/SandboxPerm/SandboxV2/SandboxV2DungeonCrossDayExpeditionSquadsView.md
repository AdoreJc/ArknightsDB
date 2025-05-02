# SandboxV2DungeonCrossDayExpeditionSquadsView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _expeditionsListContent`

- `Boolean m_isInited`

- `SquadItemListAdapter m_adapter`


## Methods

- `Void Render(List`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCrossDayExpeditionSquadsView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _expeditionsListContent; // 0x18
	private Boolean m_isInited; // 0x20
	private SquadItemListAdapter m_adapter; // 0x28
	private List`1 m_squadsList; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2520808 VA: 0x7594b38808
	public Void Render(List`1 squadsList) { }
	// RVA: 0x25208ac VA: 0x7594b388ac
	private Void _InitIfNot() { }
	// RVA: 0x2520a60 VA: 0x7594b38a60
	public Void .ctor() { }
}
```
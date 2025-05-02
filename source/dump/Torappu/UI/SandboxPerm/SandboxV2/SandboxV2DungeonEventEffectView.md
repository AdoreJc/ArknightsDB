# SandboxV2DungeonEventEffectView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _content`

- `Text _title`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `SandboxV2DungeonMiscEventEffectViewModel m_cachedViewModel`


## Methods

- `Void Render(SandboxV2DungeonMiscEventEffectViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonEventEffectView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Text _title; // 0x20
	private Boolean m_isInited; // 0x28
	private Adapter m_adapter; // 0x30
	private SandboxV2DungeonMiscEventEffectViewModel m_cachedViewModel; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2549f68 VA: 0x7594b61f68
	public Void Render(SandboxV2DungeonMiscEventEffectViewModel viewModel) { }
	// RVA: 0x254a2c0 VA: 0x7594b622c0
	private Void _InitIfNot() { }
	// RVA: 0x254a424 VA: 0x7594b62424
	public Void .ctor() { }
}
```
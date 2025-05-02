# SandboxV2DungeonExpeditionEffectGroupView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _content`

- `Text _statusDesc`

- `Text _effectDesc`

- `GameObject _panelLine`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `SandboxV2DungeonMiscExpeditionItemViewModel m_cachedViewModel`


## Methods

- `Void Render(SandboxV2DungeonMiscExpeditionItemViewModel, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonExpeditionEffectGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Text _statusDesc; // 0x20
	private Text _effectDesc; // 0x28
	private GameObject _panelLine; // 0x30
	private Boolean m_isInited; // 0x38
	private Adapter m_adapter; // 0x40
	private SandboxV2DungeonMiscExpeditionItemViewModel m_cachedViewModel; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x254aba4 VA: 0x7594b62ba4
	public Void Render(SandboxV2DungeonMiscExpeditionItemViewModel groupViewModel, Boolean showLine) { }
	// RVA: 0x254ad00 VA: 0x7594b62d00
	private Void _InitIfNot() { }
	// RVA: 0x254ae64 VA: 0x7594b62e64
	public Void .ctor() { }
}
```
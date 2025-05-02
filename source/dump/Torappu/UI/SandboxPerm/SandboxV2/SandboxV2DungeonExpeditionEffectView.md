# SandboxV2DungeonExpeditionEffectView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _content`

- `Text _title`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `SandboxV2DungeonMiscExpeditionViewModel m_cachedViewModel`


## Methods

- `Void Render(SandboxV2DungeonMiscExpeditionViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonExpeditionEffectView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Text _title; // 0x20
	private Boolean m_isInited; // 0x28
	private Adapter m_adapter; // 0x30
	private SandboxV2DungeonMiscExpeditionViewModel m_cachedViewModel; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x254aa38 VA: 0x7594b62a38
	public Void Render(SandboxV2DungeonMiscExpeditionViewModel expeditionViewModel) { }
	// RVA: 0x254b2ac VA: 0x7594b632ac
	private Void _InitIfNot() { }
	// RVA: 0x254b410 VA: 0x7594b63410
	public Void .ctor() { }
}
```
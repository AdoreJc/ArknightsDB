# ClimbTowerEntryFloatSeasonProgressView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _content`

- `Boolean m_hasInited`

- `Int32 m_periodSum`

- `Int32 m_periodCurr`

- `Adapter m_adapter`

- `String m_seasonId`


## Methods

- `Void Render(ClimbTowerEntryFloatPanelViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryFloatSeasonProgressView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Boolean m_hasInited; // 0x20
	private Int32 m_periodSum; // 0x24
	private Int32 m_periodCurr; // 0x28
	private Adapter m_adapter; // 0x30
	private String m_seasonId; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c6437c VA: 0x759527c37c
	public Void Render(ClimbTowerEntryFloatPanelViewModel viewModel) { }
	// RVA: 0x2c64420 VA: 0x759527c420
	private Void _InitIfNot() { }
	// RVA: 0x2c64584 VA: 0x759527c584
	public Void .ctor() { }
}
```
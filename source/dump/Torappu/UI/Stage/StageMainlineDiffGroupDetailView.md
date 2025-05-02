# StageMainlineDiffGroupDetailView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `SimpleLayoutContent _content`

- `SimpleLayoutContent _splitContent`

- `GameObject _unlockedPart`

- `GameObject _lockedPart`

- `Adapter m_adatper`

- `SplitLineAdapter m_splitAdapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(ZoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageMainlineDiffGroupDetailView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private SimpleLayoutContent _splitContent; // 0x20
	private GameObject _unlockedPart; // 0x28
	private GameObject _lockedPart; // 0x30
	public Action`1 diffGroupEvent; // 0x38
	private Adapter m_adatper; // 0x40
	private SplitLineAdapter m_splitAdapter; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2f8d8b0 VA: 0x75955a58b0
	private Void _InitIfNot() { }
	// RVA: 0x2f8dac0 VA: 0x75955a5ac0
	public Void Render(ZoneViewModel viewModel) { }
	// RVA: 0x2f8dc30 VA: 0x75955a5c30
	public Void .ctor() { }
}
```
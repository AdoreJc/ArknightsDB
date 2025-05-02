# ActMultiV3StageListRowView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `SimpleLayoutContent _titleLayout`

- `GameObject _pnlTitle`

- `SimpleLayoutContent _stageLayout`

- `VirtualView m_cachedData`

- `Boolean m_inited`

- `Adapter m_titleAdapter`

- `StageAdapter m_stageAdapter`


## Methods

- `Void _InitIfNot()`

- `Void Render(VirtualView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListRowView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _titleLayout; // 0x18
	private GameObject _pnlTitle; // 0x20
	private SimpleLayoutContent _stageLayout; // 0x28
	private VirtualView m_cachedData; // 0x30
	private Boolean m_inited; // 0x38
	private Adapter m_titleAdapter; // 0x40
	private StageAdapter m_stageAdapter; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x314cec4 VA: 0x7595764ec4
	private Void _InitIfNot() { }
	// RVA: 0x314d110 VA: 0x7595765110
	public Void Render(VirtualView data) { }
	// RVA: 0x314d1e0 VA: 0x75957651e0
	public Void .ctor() { }
}
```
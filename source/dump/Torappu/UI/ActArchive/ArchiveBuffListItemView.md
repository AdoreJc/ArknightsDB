# ArchiveBuffListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _icon`

- `GameObject _panelSelect`

- `GameObject _panelNew`

- `GameObject _panelLocked`

- `Color _selectColor`

- `Color _unselectColor`

- `Color _lockedColor`

- `BuffItemViewModel m_cachedViewModel`


## Methods

- `Void Render(BuffItemViewModel)`

- `Void OnItemClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveBuffListItemView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private GameObject _panelSelect; // 0x20
	private GameObject _panelNew; // 0x28
	private GameObject _panelLocked; // 0x30
	private Color _selectColor; // 0x38
	private Color _unselectColor; // 0x48
	private Color _lockedColor; // 0x58
	public Action`1 onItemClick; // 0x68
	private BuffItemViewModel m_cachedViewModel; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnItemClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3039008 VA: 0x7595651008
	public Void Render(BuffItemViewModel viewModel) { }
	// RVA: 0x303921c VA: 0x759565121c
	public Void OnItemClicked() { }
	// RVA: 0x3039314 VA: 0x7595651314
	public Void .ctor() { }
}
```
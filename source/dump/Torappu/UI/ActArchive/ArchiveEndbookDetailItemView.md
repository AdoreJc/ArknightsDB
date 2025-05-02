# ArchiveEndbookDetailItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `UIAnimationLocation _switchAnim`

- `Text _textTitle`

- `GameObject _panelNew`

- `GameObject _panelSelect`

- `EndbookDetailSwitchTween m_swietchTween`

- `Boolean m_isInited`

- `Int32 m_cachedIndex`


## Methods

- `Void _InitIfNot()`

- `Void Render(ArchiveEndbookItemModel, Int32, Boolean)`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveEndbookDetailItemView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _switchAnim; // 0x18
	private Text _textTitle; // 0x28
	private GameObject _panelNew; // 0x30
	private GameObject _panelSelect; // 0x38
	public Action`1 onItemClicked; // 0x40
	private EndbookDetailSwitchTween m_swietchTween; // 0x48
	private Boolean m_isInited; // 0x50
	private Int32 m_cachedIndex; // 0x54
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x304dda0 VA: 0x7595665da0
	private Void _InitIfNot() { }
	// RVA: 0x304dc34 VA: 0x7595665c34
	public Void Render(ArchiveEndbookItemModel viewModel, Int32 index, Boolean isSelected) { }
	// RVA: 0x304def0 VA: 0x7595665ef0
	public Void OnItemClick() { }
	// RVA: 0x304df78 VA: 0x7595665f78
	public Void .ctor() { }
}
```
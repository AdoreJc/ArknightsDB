# ArchiveChatRecordItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _panelUnlock`

- `GameObject _panelLock`

- `Text _textContent`

- `Text _lockContent`

- `LayoutElement _layoutElement`

- `TextGenerator m_textGenerator`

- `Boolean m_isInited`


## Methods

- `Void Render(ArchiveChatRecordItemViewStruct)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChatRecordItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelUnlock; // 0x18
	private GameObject _panelLock; // 0x20
	private Text _textContent; // 0x28
	private Text _lockContent; // 0x30
	private LayoutElement _layoutElement; // 0x38
	private GameObject[] _titleImages; // 0x40
	private TextGenerator m_textGenerator; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3046544 VA: 0x759565e544
	public Void Render(ArchiveChatRecordItemViewStruct viewModel) { }
	// RVA: 0x304673c VA: 0x759565e73c
	private Void _InitIfNot() { }
	// RVA: 0x30467f8 VA: 0x759565e7f8
	public Void .ctor() { }
}
```
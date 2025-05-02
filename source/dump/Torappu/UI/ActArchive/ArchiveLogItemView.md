# ArchiveLogItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _panelChapterData`

- `GameObject _panelItemData`

- `Text _textTitle`

- `Text _textContent`

- `Text _textDisplayId`


## Methods

- `Void Render(LogArchiveResItemData, LogTitleParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveLogItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelChapterData; // 0x18
	private GameObject _panelItemData; // 0x20
	private Text _textTitle; // 0x28
	private Text _textContent; // 0x30
	private Text _textDisplayId; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x305b1a4 VA: 0x75956731a4
	public Void Render(LogArchiveResItemData logItem, LogTitleParam title) { }
	// RVA: 0x305b2dc VA: 0x75956732dc
	public Void .ctor() { }
}
```
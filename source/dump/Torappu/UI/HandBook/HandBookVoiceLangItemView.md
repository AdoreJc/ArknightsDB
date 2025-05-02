# HandBookVoiceLangItemView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `GameObject _selectObj`

- `GameObject _unSelectObj`

- `Text _voiceLangText`

- `Text _cvText`

- `GameObject _hotspotObj`

- `GameObject _unselectTagObj`

- `GameObject _selectTagObj`

- `VoiceLangType m_voiceLangType`

- `Boolean m_hasNoResource`


## Methods

- `Void Render(HandBookVoiceLangViewModel, Int32)`

- `Void OnVoiceLangItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookVoiceLangItemView : MonoBehaviour, IHotfixable
{
	private GameObject _selectObj; // 0x18
	private GameObject _unSelectObj; // 0x20
	private Text _voiceLangText; // 0x28
	private Text _cvText; // 0x30
	private GameObject _hotspotObj; // 0x38
	private GameObject _unselectTagObj; // 0x40
	private GameObject _selectTagObj; // 0x48
	public Action`1 onItemClick; // 0x50
	private VoiceLangType m_voiceLangType; // 0x58
	private Boolean m_hasNoResource; // 0x5c
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnVoiceLangItemClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2eb7248 VA: 0x75954cf248
	public Void Render(HandBookVoiceLangViewModel viewModel, Int32 position) { }
	// RVA: 0x2eb7494 VA: 0x75954cf494
	public Void OnVoiceLangItemClick() { }
	// RVA: 0x2eb7574 VA: 0x75954cf574
	public Void .ctor() { }
}
```
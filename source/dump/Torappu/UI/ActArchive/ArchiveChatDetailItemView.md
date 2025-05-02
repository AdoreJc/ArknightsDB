# ArchiveChatDetailItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Text _unlockStatus`

- `Text _textYear`

- `Text _textMonth`

- `Text _textTitle`

- `Text _textDesc`

- `SimpleLayoutContent _unlockProgressContent`

- `GameObject _panelBtn`

- `Adapter m_adapter`

- `Int32 m_chatSum`

- `Int32 m_chatUnlockNum`

- `Boolean m_hasInit`

- `Color m_teamColor`


## Methods

- `Void Render(ChatItemModel, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChatDetailItemView : MonoBehaviour, IHotfixable
{
	private Text _unlockStatus; // 0x18
	private Text _textYear; // 0x20
	private Text _textMonth; // 0x28
	private Text _textTitle; // 0x30
	private Text _textDesc; // 0x38
	private SimpleLayoutContent _unlockProgressContent; // 0x40
	private GameObject _panelBtn; // 0x48
	private Adapter m_adapter; // 0x50
	private Int32 m_chatSum; // 0x58
	private Int32 m_chatUnlockNum; // 0x5c
	private Boolean m_hasInit; // 0x60
	private Color m_teamColor; // 0x64
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30434dc VA: 0x759565b4dc
	public Void Render(ChatItemModel item, Boolean showButton) { }
	// RVA: 0x3043708 VA: 0x759565b708
	private Void _InitIfNot() { }
	// RVA: 0x304386c VA: 0x759565b86c
	public Void .ctor() { }
}
```
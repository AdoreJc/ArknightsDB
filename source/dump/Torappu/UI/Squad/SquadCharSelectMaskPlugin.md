# SquadCharSelectMaskPlugin

**Namespace:** `Torappu.UI.Squad`


## Fields

- `GameObject _panelBlock`

- `Text _textForbid`

- `GameObject _panelExclusiveInfo`

- `Text _textName`

- `CharSelectStateBean m_charSelectBean`

- `ISquadCharSelectContext m_context`


## Methods

- `String _GetMutuallyExclusiveInfo(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadCharSelectMaskPlugin : CharSelectCardMaskPlugin
{
	private GameObject _panelBlock; // 0x18
	private Text _textForbid; // 0x20
	private GameObject _panelExclusiveInfo; // 0x28
	private Text _textName; // 0x30
	private CharSelectStateBean m_charSelectBean; // 0x38
	private ISquadCharSelectContext m_context; // 0x40
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__GetMutuallyExclusiveInfo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23c5230 VA: 0x75949dd230
	public override Void Init(CharSelectCardView cardView, CharSelectStateBean stateBean, Object context) { }
	// RVA: 0x23c5394 VA: 0x75949dd394
	public override Void Render(CharacterCardViewModel cardModel) { }
	// RVA: 0x23c55a4 VA: 0x75949dd5a4
	private String _GetMutuallyExclusiveInfo(Int32 instId) { }
	// RVA: 0x23c5b14 VA: 0x75949ddb14
	public Void .ctor() { }
}
```
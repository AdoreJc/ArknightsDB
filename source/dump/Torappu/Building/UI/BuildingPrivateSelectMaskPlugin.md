# BuildingPrivateSelectMaskPlugin

**Namespace:** `Torappu.Building.UI`


## Fields

- `GameObject _panelPrivateTag`

- `Text _txtRoomCode`

- `CharSelectStateBean m_stateBean`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingPrivateSelectMaskPlugin : CharSelectCardMaskPlugin
{
	private GameObject _panelPrivateTag; // 0x18
	private Text _txtRoomCode; // 0x20
	private CharSelectStateBean m_stateBean; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3d54100 VA: 0x759636c100
	public override Void Init(CharSelectCardView cardView, CharSelectStateBean stateBean, Object context) { }
	// RVA: 0x3d541a0 VA: 0x759636c1a0
	public override Void Render(CharacterCardViewModel cardModel) { }
	// RVA: 0x3d54484 VA: 0x759636c484
	public Void .ctor() { }
}
```
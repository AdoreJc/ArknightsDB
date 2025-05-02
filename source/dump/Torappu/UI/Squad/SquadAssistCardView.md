# SquadAssistCardView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `GameObject _panelEmpty`

- `Transform _cardContainer`

- `GameObject _cleanButton`

- `Single _charCardScaler`

- `GameObject _activePart`

- `GameObject _unactivePart`

- `GameObject _panelLocked`

- `UICharacterCardPanel m_characterCard`


## Methods

- `Void _RenderCard(SharedCharData, EvolvePhaseAndLevel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadAssistCardView : DataBinder`1
{
	private GameObject _panelEmpty; // 0x20
	private Transform _cardContainer; // 0x28
	private GameObject _cleanButton; // 0x30
	private Single _charCardScaler; // 0x38
	private GameObject _activePart; // 0x40
	private GameObject _unactivePart; // 0x48
	private GameObject _panelLocked; // 0x50
	private UICharacterCardPanel m_characterCard; // 0x58
	private static DelegateBridge __Hotfix0__RenderCard; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x23c3ff4 VA: 0x75949dbff4
	private Void _RenderCard(SharedCharData inputSharedCharacter, EvolvePhaseAndLevel maxEvolvePhaseAndLevel, Boolean isFriend) { }
	// RVA: 0x23c4264 VA: 0x75949dc264
	public override Void OnValueChanged(SquadGroupViewProperty property) { }
	// RVA: 0x23c4400 VA: 0x75949dc400
	public Void .ctor() { }
}
```
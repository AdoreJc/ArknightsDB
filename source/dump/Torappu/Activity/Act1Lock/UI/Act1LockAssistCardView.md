# Act1LockAssistCardView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `GameObject _panelEmpty`

- `UIAtlasImage _portraitImg`

- `Transform _cardContainer`

- `GameObject _cleanButton`

- `Single _charCardScaler`

- `GameObject _activePart`

- `GameObject _unactivePart`

- `GameObject _lockedPart`

- `UICharacterCardPanel m_characterCard`

- `String m_portrait`


## Methods

- `Void _RenderCard(SharedCharData, EvolvePhaseAndLevel)`

- `Void _RenderEmptyPanel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockAssistCardView : DataBinder`1
{
	private GameObject _panelEmpty; // 0x20
	private UIAtlasImage _portraitImg; // 0x28
	private Transform _cardContainer; // 0x30
	private GameObject _cleanButton; // 0x38
	private Single _charCardScaler; // 0x40
	private GameObject _activePart; // 0x48
	private GameObject _unactivePart; // 0x50
	private GameObject _lockedPart; // 0x58
	private UICharacterCardPanel m_characterCard; // 0x60
	private String m_portrait; // 0x68
	private static DelegateBridge __Hotfix0__RenderCard; // 0x0
	private static DelegateBridge __Hotfix0__RenderEmptyPanel; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x33a75dc VA: 0x75959bf5dc
	private Void _RenderCard(SharedCharData inputSharedCharacter, EvolvePhaseAndLevel maxEvolvePhaseAndLevel) { }
	// RVA: 0x33a77f4 VA: 0x75959bf7f4
	private Void _RenderEmptyPanel(String portraitId) { }
	// RVA: 0x33a7918 VA: 0x75959bf918
	public override Void OnValueChanged(SquadGroupViewProperty property) { }
	// RVA: 0x33a7bfc VA: 0x75959bfbfc
	public Void .ctor() { }
}
```
# CharSelectCardGroup

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `CharSelectCardListAdapter _dataTargetAdapter`

- `GameObject _panelNoCard`

- `Text _textNoCard`

- `String pageName`

- `IPlugin m_statePlugin`


## Methods

- `Void InjectPlugin(IPlugin)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectCardGroup : DataBinder`1
{
	private CharSelectCardListAdapter _dataTargetAdapter; // 0x20
	private GameObject _panelNoCard; // 0x28
	private Text _textNoCard; // 0x30
	public String pageName; // 0x38
	private IPlugin m_statePlugin; // 0x40
	private static DelegateBridge __Hotfix0_InjectPlugin; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2cf52d4 VA: 0x759530d2d4
	public Void InjectPlugin(IPlugin statePlugin) { }
	// RVA: 0x2cf5358 VA: 0x759530d358
	public override Void OnValueChanged(CardGroupViewProperty property) { }
	// RVA: 0x2cf55c8 VA: 0x759530d5c8
	public Void .ctor() { }
}
```